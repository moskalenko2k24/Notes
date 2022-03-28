# Два указателя

Здесь должно быть описание алгоритма,
но для себя я оставляю пример простой реализации. <br>
Проще всего использовать полуинтервал, т.е поддерживать [left; right)
вместо [left, right]. `right` увеличивается только при успешном добавлении.
Длина полуинтервала -- разность правого и левого индекса.

[ссылка](https://leetcode.com/problems/longest-substring-without-repeating-characters/)

Условие задачи
> Given a string s, find the length of
the longest substring without repeating characters.

>**Constraints:** <br>
>0 <= s.length <= 5 * 10<sup>4</sup> <br>
>s consists of English letters, digits, symbols and spaces.

Мой код на JavaScript
```js

/**
 * @param {string} s
 * @return {number}
 */
var lengthOfLongestSubstring = function(s) {
    const set = new Set();
    // [left; right)
    let right = 0;
    let longest = 0;
    for (let left = 0; left < s.length; left++) {
        while (right < s.length) {
            if (!set.has(s[right])) {
                set.add(s[right]);
                ++right;
            }
            else break;
        }
        longest = Math.max(longest, right - left);
        set.delete(s[left]);
    }
    return longest;
};

```

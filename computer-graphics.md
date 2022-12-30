# Компьютерная графика. Полезные ссылки

Здесь ссылки на полезные материалы по изучению компьютерной графики и OpenGL.

## 1. Алгоритмы и математика

Материалы по алгоритмам, но не про OpenGL. <br>
Т.е о том как это работает всё изнутри. <br>
Как это всё сделать без готовых функций, как выводятся формулы и.т.д и.т.п.

### 1. 1 Краткий курс КГ: пишем упрощенный OpenGL своими руками

https://habr.com/ru/post/248153/ <br>
Реализация всего с 0. От функций setPixel / getPixel, до рисования отрезков, треугольников, а потом и 3D-объектов...

### 1.2 Tiny renderer or how OpenGL works: software rendering in 500 lines of code

(то что выше, но на английском) <br>
https://github.com/ssloy/tinyrenderer/wiki

### 1.3 256 строчек голого C++: пишем трассировщик лучей с нуля за несколько часов

https://habr.com/ru/post/436790/ <br>
Статья того же автора, опять же про то как оно работает внутри.

### 1.4 Understandable RayTracing in 256 lines of bare C++

(то что выше, но на английском) <br>
https://github.com/ssloy/tinyraytracer <br>

### 1.5 Трёхмерная компьютерная графика (осень 2017)

Курс от Computer Science Center. <br>
https://www.youtube.com/playlist?list=PLlb7e2G7aSpRhAzyVXo7HYyS3QLxvNaa6 <br>
Курс про DirectX, но и про матчасть в том числе.

https://www.youtube.com/watch?v=7tLavP0SIe4 <br>
Первая лекция курса от Computer Science Center. <br>
Вывод формул для матрицы камеры и матрицы проекции.

### 1.6 Виталий Галинский. Компьютерная графика 2018

Старый курс, 2011 год <br>
https://www.lektorium.tv/course/22834 <br>
https://www.youtube.com/playlist?list=PL-_cKNuVAYAX-pXo6-CV21Z6e1_i_PTUu

Новый курс, 2018 год <br>
https://www.lektorium.tv/node/33155 <br>
https://www.youtube.com/playlist?list=PL-_cKNuVAYAVK2E--20nqggd57jcipCk6 <br>

Рассматриваются общие принципы и задачи компьютерной графики, алгоритмы построения и визуализации плоских и объемных изображений, сплайны, алгоритмы удаления невидимых поверхностей, работа с цветом, полутонирование, алгоритмы закраски, построение реалистичных изображений.

### 1.7 Основы линейной алгебры для 3D приложений

Внутренняя лекция UNIGINE <br>
https://www.youtube.com/watch?v=FSTxFlgmb9Q

### 1.8 Ray Tracing in One Weekend Series

https://raytracing.github.io <br>
https://github.com/RayTracing/raytracing.github.io

### 1.9 Rasterization in One Weekend

https://tayfunkayhan.wordpress.com/2018/11/24/rasterization-in-one-weekend/

### 1.10 Shading a Triangle in Software

https://habr.com/ru/post/526340/ (перевод) <br>
https://austinmorlan.com/posts/drawing_a_triangle/

### 1.11 Computer Graphics and Imaging

Berkley cs184/284a <br>
https://cs184.eecs.berkeley.edu/sp22 <br>
https://cs184.eecs.berkeley.edu/sp19 <br>

### 1.12 Rasterization: a Practical Implementation

https://www.scratchapixel.com/lessons/3d-basic-rendering/rasterization-practical-implementation

### 1.13 Introduction to Ray Tracing

https://www.scratchapixel.com/lessons/3d-basic-rendering/introduction-to-ray-tracing

### 1.14 CS 1230

https://cs1230.graphics/

### 1.15 Introduction to Computer Graphics

Legacy OpenGL + WebGL + Three.js <br>

https://math.hws.edu/graphicsbook/

### 1.16 Code-It-Yourself! 3D Graphics Engine

[Part 1. Triangles & Projection](https://www.youtube.com/watch?v=ih20l3pJoeU) <br>
[Part 2. Normals, Culling, Lighting & Object Files](https://www.youtube.com/watch?v=XgMWc6LumG4) <br>
[Part 3. Cameras & Clipping](https://www.youtube.com/watch?v=HXSuNxpCzdM) <br>
[Part 4. Texturing & Depth Buffers](https://www.youtube.com/watch?v=nBzCS-Y0FcY)

## 2 OpenGL

Материалы по современному OpenGL с шейдерами.

### 2.1 Learn OpenGL

https://learnopengl.com <br>
Самый популярный сайт по современному OpenGL. <br>
С самого нуля про шейдеры и.т.д. <br>
Но на самом деле там и про математику с формулами тоже рассказывается.

### 2.2 Learn OpenGL (перевод)

https://habr.com/ru/post/310790/ <br>
Серия статей на Хабре, переводы туториалов с Learn OpenGL.

### 2.3 Уроки по OpenGL 3

https://code.google.com/archive/p/gl33lessons

### 2.4 OpenGL Tutorial

http://www.opengl-tutorial.org

### 2.5 lisyarus / graphics-course-slides

https://github.com/lisyarus/graphics-course-slides <br>
Курс про OpenGL на гитхабе, на русском, с теорией и задачами для практики.

### 2.6 WebGL Fundamentals

https://webglfundamentals.org <br>
Туторы про WebGL - OpenGL внутри браузера.
Огромный плюс WebGL в том, что браузеры везде одинаковые,
а значит не нужно думать о том как скомпилировать / собрать приложение, в отличии от C / C++(где на разных ОС подключение нужных библиотек делается по разному). WebGL удобен для изучения самого OpenGL, так как API там практически 1 в 1. На сайте есть переводы на другие языки, в том числе на русский.

### 2.7 WebGL2 Fundamentals

https://webgl2fundamentals.org <br>
Туторы по WebGL 2. WebGL 2 имеет чуть более сложный API, но это как раз ближе к обычному OpenGL.

### 2.8 The Book of Shaders

https://thebookofshaders.com <br>
Онлайн-книга про шейдеры и GLSL, используется WebGL
Есть перевод на русский.

### 2.9 Примеры кода на WebGL (из книги)

https://vk.com/wall-85029013_531 <br>
Примеры из книги "WebGL Programming Guide",
выложенные в песочницу JSFiddle.

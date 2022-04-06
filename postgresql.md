# PostgreSQL. Установка и базовые команды

Только самые базовые вещи. <br>
Здесь только о том как поставить PostgreSQL и начать с ним работать.

Видео [Тимура Шемсединова](https://www.youtube.com/watch?v=Fm6yLb8qCh4)

Нужно зайти на [официальный сайт](https://www.postgresql.org/download/)
и выбрать семейство ОС (Linux), ОС (Fedora), версию PostgreSQL (14),
архитектуру (x86_64). И затем появится нужный набор команд для установки.
Например,
```shell
sudo dnf install -y https://download.postgresql.org/pub/repos/yum/reporpms/F-35-x86_64/pgdg-fedora-repo-latest.noarch.rpm
sudo dnf install -y postgresql14-server
sudo /usr/pgsql-14/bin/postgresql-14-setup initdb
sudo systemctl enable postgresql-14
sudo systemctl start postgresql-14
```

Чтобы начать пользоваться PostgreSQL, <br>
нужно сначала сменить пользователя командой `sudo su - postgres`, <br>
затем можно запустить консольный клиент `psql`.

Базовые операции в psql.

| Команда      | Действие          |
| :-------:    | :---------------- |
| \q           | выйти             |
| \h           | справка           |
| \l           | список баз данных |
| \d           | список таблиц     |
| \c [db-name] | подключиться к БД |


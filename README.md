## Проект Yatube

Расширирен проект Yatube. Настроен эмулятор отправки писем; отправленные письма должны сохраняться в виде текстовых файлов в директорию /sent_emails. Настроена отправка письма при восстановлении пароля. Создана страница для публикации постов и страница редактирования постов.

Проект реализован на Django Framework.

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/Marikalis/hw03_forms
```

```
cd hw03_forms
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```

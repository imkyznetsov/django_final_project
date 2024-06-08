# Создание заметок

## Начало работы

1. Настройки для локального запуска проекта:
> [!IMPORTANT]
> *Перед началом работы создайте папку на вашем компьютере под управлением `ОС Linux`, которая будет содержать проект. Для этого выполните следующие команды в Вашем терминале:*
- `$ mkdir folder_name`  *создайте папку в которую вы поместите проект*
- `$ cd folder_name` *перейдите в нее*
- `$ sudo apt-get update` *проверьте наличие обновлений*
- `$ sudo apt install python3-venv` *установите пакет для работы с виртуальным окружением*
- `$ python3 -m venv venv_name` *создайте новое окружение*
- `$ source venv_name/bin/activate` *активируйте новое окружение*

> [!NOTE]
> *Для работы в `Windows` выполните следующие действия:*
- `$ mkdir folder_name`  *создайте папку в которую вы поместите проект*
- `$ cd folder_name` *перейдите в нее*
- `$ pip install virtualenv`  *установите пакет для работы с виртуальным окружением (при условии, что `pip` уже установлен в `Windows`*
- `$ py -m venv venv_name` *создайте новое окружение*
- `$ venv_name\Scripts\activate` *активируйте новое окружение*

2. Загрузка и запуск проекта:
> [!NOTE]
> *Для успешного запуска приложения, пожалуйста, проделайте следующие шаги:*
- `$ git clone git@github.com:imkyznetsov/django_final_project.git` *(создайте клон проекта `Linux`)/скачайте (`Windows`)* [Download](https://github.com/imkyznetsov/django_final_project/archive/refs/heads/main.zip) *из репозитория и распакуйте*
- `$ pip install -r requirements.txt` *(установите все необходимые библиотеки из файла)*
- `$ python manage.py runserver` *(запустите приложение `Linux`)* `$ py manage.py runserver` *(запустите приложение `Windows`)*
 ```
На новой вкладке введите последовательно:
  curl -X 'POST' \
  'http://127.0.0.1:8000/predict/' \
  -H 'Content-Type: application/json' \
  -d '{
  "text": "Only this evening, and only now you can hear this bell"
}'
 ```

## Выполнил

```
Менеджер проекта, Full Stack-разработчик, аналитик данных, тестировщик и документалист – Кузнецов Иван

```

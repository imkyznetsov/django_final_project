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
- `$ git clone git@github.com:imkyznetsov/django_final_project.git` *(создайте клон проекта `Linux`)/скачайте (`Windows`)* >>> [Download](https://github.com/imkyznetsov/django_final_project/archive/refs/heads/main.zip) <<< *из репозитория и распакуйте*
- `$ cd django_final_project-main\django_final_project-main` *перейдите в распакованный рабочий каталог*
- `$ pip install -r requirements.txt` *(установите все необходимые библиотеки из файла)*
- `$ python manage.py runserver` *(запустите приложение `Linux`)* `$ py manage.py runserver` *(запустите приложение `Windows`)*
 
 ```
Если страница не открылась автоматически, то на новой вкладке Вашего браузера введите адрес:
  http://127.0.0.1:8000
  
 ```

## Выполнил

```
Full Stack-разработчик, тестировщик и документалист – Кузнецов Иван

```

## Примеры работы

![image](https://github.com/imkyznetsov/django_final_project/assets/149815971/f85093d8-528a-4c99-8b8a-19f5beae6ca2)

![image](https://github.com/imkyznetsov/django_final_project/assets/149815971/6c66b403-21a2-4d69-b8d5-73c00654c657)

![image](https://github.com/imkyznetsov/django_final_project/assets/149815971/f35123b1-2bd0-4368-af48-e67d45128558)





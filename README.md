  1.Для начала создайте в  папке lab1 файл под названием groupmates.py. 
  2.Написание первой функции - форматированный вывод списка студентов в виде таблицы. Функция будет называться print_students
  3.В папке с проектом django необходимо выполнить команду: python setup.py install
C:\work>python
>>>
>>> import django
>>> django.get_version()
django-admin.py startproject admin_learning
  4.В файле settings.py настройте два параметра для базы данных. В переменной-словаре DATABASES есть ключ default, по которому
содержится ещё один внутренний словарь с ключами ENGINE и NAME.
Установите следующие значения этим параметрам:
◦ ENGINE: 'django.db.backends.sqlite3'
◦ NAME: 'db_admin_learning
  5.python manage.py syncdb
  6.Нобходимо запустить сервер, если он не был запущен до этого, командой:python manage.py runserver

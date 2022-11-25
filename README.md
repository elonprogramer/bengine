Як встановити скрипт?
створіть папку в якій буде сайт
увійдіть в неї через консоль
введіть команду  django-admin startproject {name}
Замість {name} введіть вашу назву
Зайдіть в папку та розмістіть папку main Біля папки проєкту 
Зайдіть у папку проєкту
у файлі settings.py Знайдіть INSTALLED_APPS
Додайте в кінці списку
 'main',
Введіть у консоль python3 manage.py makemigrations
та введіть python3 manage.py migrate
Зрібіть свій акаунт
команда python3 manage.py createsuperuser
Введіть Логін . емейл та пароль . пароль має бути надійний
Відкрийте папку проєкту та відкрийте файл urls.py
Знайдіть “from django.urls import path”
Замініть на “from django.urls import path , include”
Знайдіть “urlpatterns”
І в список додайте “    path('', include('main.urls')),”
Насолоджуйтеся роботою BEngine!


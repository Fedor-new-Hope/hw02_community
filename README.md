# yatube_project
Social network of bloggers

### *Описание*
Yatube - это социальная сеть с авторизацией, персональными лентами, комментариями и подписками на авторов статей.

### *Функционал*
- Создано и зарегистрировано приложение Posts
- Подключена база данных
- Десять последних записей выводятся на главную страницу
- В админ-зоне доступно управление объектами модели Post. Можно публиковать новые записи, редактировать и удалять существующие
- Пользователь может перейти на страницу любого сообщества, где отображаются десять последних публикаций из этой группы.


### *Технологии*
- Python 3.7
- Django 2.2.19
- pytest 6.2.5
- HTML

### *Установка*
- Клонировать репозитарий 
```
git clone git@github.com:Fedor-new-Hope/hw02_community.git
```
- Установить виртуальное окружение для проекта, выполнить миграции:
```
cd hw02_community/
python -m venv venv
source venv/Scripts/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
cd yatube/
python manage.py migrate
python manage.py runserver
# адрес запущенного проекта
# http://127.0.0.1:8000
```
- Регистрация  суперпользователя
```
python3 manage.py createsuperuser

# адрес панели администратора
# http://127.0.0.1:8000/admin
```

### **Авторы**
![Fedor_Mihailovich](https://upload.wikimedia.org/wikipedia/commons/thumb/7/78/Vasily_Perov_-_%D0%9F%D0%BE%D1%80%D1%82%D1%80%D0%B5%D1%82_%D0%A4.%D0%9C.%D0%94%D0%BE%D1%81%D1%82%D0%BE%D0%B5%D0%B2%D1%81%D0%BA%D0%BE%D0%B3%D0%BE_-_Google_Art_Project.jpg/274px-Vasily_Perov_-_%D0%9F%D0%BE%D1%80%D1%82%D1%80%D0%B5%D1%82_%D0%A4.%D0%9C.%D0%94%D0%BE%D1%81%D1%82%D0%BE%D0%B5%D0%B2%D1%81%D0%BA%D0%BE%D0%B3%D0%BE_-_Google_Art_Project.jpg)



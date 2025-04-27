# پروژه جنگو

یک پروژه ساده با فریم‌ورک جنگو (Django)

## نصب و راه‌اندازی

### پیش‌نیازها
- Python 3.13 یا بالاتر
- pip (ابزار مدیریت بسته‌های پایتون)

### گام‌های نصب

1. دریافت کدهای برنامه:
```
git clone <repository-url>
cd my-django-project
```

2. ایجاد محیط مجازی:
```
python -m venv venv
```

3. فعال‌سازی محیط مجازی:

در ویندوز:
```
venv\Scripts\activate
```

در لینوکس یا مک:
```
source venv/bin/activate
```

4. نصب وابستگی‌ها:
```
pip install -r requirements.txt
```

5. اجرای مهاجرت‌های پایگاه داده:
```
python manage.py migrate
```

6. اجرای سرور توسعه:
```
python manage.py runserver
```

7. مشاهده برنامه در مرورگر:
برنامه در آدرس `http://127.0.0.1:8000` قابل دسترسی خواهد بود.

## ویژگی‌ها

- مدل ساده Task برای مدیریت کارها
- رابط کاربری به زبان فارسی
- طراحی واکنش‌گرا (Responsive Design)

## فناوری‌های مورد استفاده

- Django 5.2
- HTML/CSS
- SQLite (پایگاه داده پیش‌فرض) 
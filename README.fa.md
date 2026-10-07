<div align="center">

<img src="assets/readme/hero.gif" width="1200" alt="SQLALCHEMY CRUD — rotating 3D geometry" />

**[English](README.md) · [فارسی](README.fa.md)**

<img src="assets/readme/identity.svg" width="1200" alt="learning / English and Persian documentation" />

</div>

# SQLALCHEMY CRUD

چهار تمرین Python ORM، درج، خواندن، تغییر و حذف ردیف در جدول MySQL را نشان می‌دهند.

[GitHub](https://github.com/MOHAMMADREZAABEDINPOOR/sqlalchemy) · [PIMX / Profile](https://github.com/MOHAMMADREZAABEDINPOOR) · [بنر ثابت](assets/readme/hero.png)

## امکانات

- نگاشت جدول pr1
- فایل درج، خواندن، تغییر و حذف
- عملیات ORM با Session

## پشته فنی

| ابزار | نسخه یا منبع |
|---|---|
| Python | `standard library / source imports` |

## شروع کار

Python 3 و محیط دسکتاپ برای پروژه‌های Tkinter/Turtle؛ Tkinter از اجزای نصب Python است و با pip نصب نمی‌شود. برای وابستگی‌های قدیمی از نسخه Python سازگار استفاده کنید.

```bash
git clone https://github.com/MOHAMMADREZAABEDINPOOR/sqlalchemy.git
cd sqlalchemy

python -m pip install "SQLAlchemy<2" mysql-connector-python
python "sql insert.py"
python "sql1 select.py"
```

## تنظیمات

فایل محیط استاندارد تعریف نشده است. برای تمرین‌های مستقل تنظیم خارجی لازم نیست؛ اگر در کد ثابت‌های سرویس یا مسیر وجود دارد، آن‌ها را پیش از اجرا بررسی کنید.

## استفاده

دیتابیس آزمایشی MySQL بسازید، رشته اتصال توسعه را در همه فایل‌ها تغییر دهید و ابتدا درج و خواندن را بررسی کنید.

## ساختار پروژه

| مسیر | نقش |
|---|---|
| [`assets/`](assets/) | فایل برند، رسانه و README |
| [`sql insert.py`](sql%20insert.py) | فایل ورودی یا تنظیم پروژه |
| [`sql1 select.py`](sql1%20select.py) | فایل ورودی یا تنظیم پروژه |
| [`sql2 update.py`](sql2%20update.py) | فایل ورودی یا تنظیم پروژه |
| [`sql3 delete.py`](sql3%20delete.py) | فایل ورودی یا تنظیم پروژه |

## فرمان‌ها و بررسی

فرمان آزمون خودکار در manifest تعریف نشده است. اجرای محلی و بررسی رفتار نمونه را انجام دهید.

## استقرار

این تمرین محلی است و سرویس عمومی ندارد. برای تمرین وب میزبانی استاتیک کافی است.

## محدودیت‌ها

رشته اتصال در کد قدیمی ثابت است. تغییر و حذف به ردیف مطابق نیاز دارند و در نبود آن خطا می‌دهند؛ دیتابیس آزمایشی استفاده کنید.

## رفع مشکل

- خطای اتصال: MySQL آزمایشی آماده و رشته اتصال منبع را تغییر دهید.
- خطای تغییر و حذف: ردیف مورد انتظار را پیش از اجرای مثال بسازید.

## مشارکت

برای تغییر، شاخه مستقل بسازید، رفتار فعلی را بررسی کنید و توضیح روشن همراه تغییر بفرستید. اطلاعات خصوصی، خروجی build و دیتابیس محلی را commit نکنید.

## مجوز

فایل مجوز در این نسخه موجود نیست. نمایش عمومی کد به‌تنهایی مجوز استفاده مجدد نیست؛ برای شرایط استفاده با مالک مخزن هماهنگ کنید.

---

ساخته‌شده در مجموعه **PIMX** · مستندات فارسی و انگلیسی.

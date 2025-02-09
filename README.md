# Anonymous-Telegram-Bot

ابتدا یک Worker در Cloudflare ایجاد کنید. تمام کدهای موجود را پاک کنید و کدی که از لینک بالا دریافت کرده‌اید را در آن جای‌گذاری کنید.

سپس در بخش Storage & Databases یک پایگاه داده ایجاد کنید (نام آن مهم نیست).

وارد پایگاه داده شوید و در Console فرمان زیر را اجرا کنید:



CREATE TABLE users ("id" integer PRIMARY KEY, "telegram_user_id" text, "rkey" text, "target_user" text)

بعد به Worker برگردید و در بخش settings و قسمت bindings پایگاه داده‌ای که ساخته‌اید را با نام db بایند کنید.

یک ربات در تلگرام با استفاده از @botfather بسازید.

برای BOT_TOKEN توکن ربات خود را قرار دهید.

برای BOT_ID نیز آی‌دی ربات را بدون @ وارد کنید.

بر روی گزینه visit کلیک کنید تا Worker در مرورگر باز شود و در انتهای آدرس /init را اضافه کنید. به عنوان مثال: https://yourworker.username.workers.dev/init

سپس Enter را بزنید تا وب‌هوک تنظیم شود.

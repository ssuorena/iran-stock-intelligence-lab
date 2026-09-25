# انتشار در GitHub / Publish on GitHub

This directory is a complete Git repository after extraction. The online GitHub repository is currently **private**.

این بسته پس از استخراج، یک ریپوی Git آماده است. نسخه آنلاین در حساب `ssuorena` ساخته شده و در حال حاضر خصوصی است.

برای اتصال پوشه محلی به ریپوی آنلاین، وارد پوشه استخراج‌شده شوید:

```bash
cd /path/to/iran-stock-intelligence-launch
git remote add origin https://github.com/ssuorena/iran-stock-intelligence-lab.git
git fetch origin
git status
```

تاریخچه Git نسخه آنلاین به‌دلیل بارگذاری از مرورگر با فایل ZIP محلی متفاوت است؛ پیش از `git push`، تاریخچه‌ها را با آگاهی از این تفاوت هماهنگ کنید. ساده‌ترین روش برای کار آینده، `git clone` کردن ریپوی آنلاین پس از اتمام بارگذاری فایل‌هاست. GitHub ممکن است هنگام clone یا push ورود از طریق مرورگر یا credential manager بخواهد؛ رمز حساب را در دستور ترمینال یا در فایل‌های پروژه قرار ندهید.

تصاویر در `assets/` و فایل قابل‌ایمپورت در `workflows/` هستند. لینک خصوصی برای خوانندگان پست لینکدین باز نمی‌شود؛ عمومی‌کردن ریپو نیاز به تصمیم جداگانه صاحب حساب دارد.

The project has no license yet. Choose one explicitly if you intend to grant others reuse rights.

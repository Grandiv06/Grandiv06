# 🚀 راهنمای نصب پروفایل GitHub

## مرحله ۱: ساخت ریپازیتوری پروفایل

1. یک ریپازیتوری **جدید** در GitHub بساز
2. نام ریپازیتوری باید **دقیقاً** برابر با یوزرنیم GitHub تو باشه
   - مثال: اگه یوزرنیمت `soroush-dev` هست، ریپو هم باید `soroush-dev` باشه
3. ریپو رو **Public** بذار
4. گزینه "Add a README file" رو **تیک نزن** (خودمون README داریم)

## مرحله ۲: شخصی‌سازی README

فایل `README.md` رو باز کن و این موارد رو جایگزین کن:

| Placeholder | جایگزین با |
|-------------|-----------|
| `YOUR_USERNAME` | یوزرنیم GitHub تو |
| `YOUR_LINKEDIN` | لینک LinkedIn |
| `YOUR_TWITTER` | یوزرنیم Twitter/X |
| `YOUR_TELEGRAM` | یوزرنیم تلگرام |
| `your.email@example.com` | ایمیل واقعی |
| `your-portfolio.com` | آدرس سایت شخصی |
| `Soroush` | اسم خودت |
| پروژه‌ها | پروژه‌های واقعی خودت |

## مرحله ۳: آپلود فایل‌ها

```bash
# کلون کردن ریپازیتوری پروفایل
git clone https://github.com/YOUR_USERNAME/YOUR_USERNAME.git
cd YOUR_USERNAME

# کپی فایل‌ها
cp /path/to/gitreadme/README.md .
cp -r /path/to/gitreadme/.github .

# پوش کردن
git add .
git commit -m "feat: add awesome profile README"
git push origin main
```

## مرحله ۴: فعال‌سازی Snake Animation (اختیاری)

فولدر `.github/workflows/snake.yml` رو push کن.
بعد از اولین اجرای workflow، مار contribution graph نمایش داده می‌شه.

> **نکته:** برای snake animation، در README مسیر تصویر رو به
> `YOUR_USERNAME/YOUR_USERNAME` تغییر بده (همون ریپوی پروفایل).

## مرحله ۵: تست

برو به `https://github.com/YOUR_USERNAME` و پروفایل جدیدت رو ببین! 🎉

---

## 💡 نکات حرفه‌ای

- **پین کردن ریپو:** رروژه‌های مهم رو در پروفایل پین کن
- **Bio:** در تنظیمات GitHub یک bio کوتاه و جذاب بنویس
- **Pinned Repos:** حداکثر ۶ ریپو پین کن
- **Custom Social Preview:** در Settings → Profile → Edit profile یک تصویر کاور بذار

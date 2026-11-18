# آخرین قطرات هایپ ارز دیجیتال | AFTER THE HYPE

کارگاه فارسی و پروژه‌محور درباره بلاکچین، DeFi و تحلیل داده‌های آن‌چین؛ با تمرکز بر فهم زیرساخت به‌جای هیجان قیمت.

**وب‌سایت:** https://shaiinarab.github.io/crypto-hype-last-drops/

## انتشار در GitHub Pages

**تنظیم یک‌باره الزامی است:** GitHub Pages هنوز برای این مخزن فعال نشده است. دسترسی GitHub Actions متصل به این مخزن اجازه ایجاد اولیه Pages site را ندارد.

1. وارد [Settings → Pages](https://github.com/Shaiinarab/crypto-hype-last-drops/settings/pages) شو.
2. در بخش **Build and deployment**، گزینه **GitHub Actions** را به‌عنوان Source انتخاب و Save کن.
3. به زبانه [Actions](https://github.com/Shaiinarab/crypto-hype-last-drops/actions/workflows/pages.yml) برو و اجرای ناموفق فعلی را باز کن.
4. **Re-run all jobs** را بزن. پس از اولین انتشار موفق، هر push به `main` به‌صورت خودکار سایت را منتشر می‌کند.

Workflow در `.github/workflows/pages.yml` قرار دارد. فایل سایت مستقل از فریم‌ورک است و به نصب پکیج یا کلید API نیاز ندارد.

## بخش‌های سایت

- بررسی اینکه یک مسئله واقعاً به بلاکچین نیاز دارد یا نه
- بازکردن هش تراکنش اتریوم در Etherscan
- شبیه‌ساز AMM با مدل ساده `x × y = k`
- محاسبه‌گر Impermanent Loss
- راهنمای شاخص‌های TVL، Fees، Revenue، Exchange Flows، Open Interest، MVRV و SOPR
- مسیر آموزشی و جعبه‌ابزار منابع

## اجرای محلی

فایل `index.html` را باز کن، یا اجرا کن:

```bash
python3 -m http.server 8080
```

سپس به `http://localhost:8080` برو.

## مرزبندی

این پروژه آموزشی است، نه توصیه سرمایه‌گذاری. هیچ کیف پولی وصل نمی‌شود و شبیه‌سازها داده زنده یا سیگنال معاملاتی تولید نمی‌کنند. هر شاخص باید همراه با تعریف و محدودیت داده بررسی شود.

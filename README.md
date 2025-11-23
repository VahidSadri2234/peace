# Viewing the Assignment Strategy Settings page

This repository includes standalone HTML pages for configuring ticket flow settings.

## Flow Builder (سا۲)
1. فایل `flow_builder.html` را در پوشه‌ی اصلی مخزن پیدا کنید.
2. روی آن دوبار کلیک کنید یا در مرورگر بکشید و رها کنید تا مستقیماً باز شود (کاملاً ایستا است).
3. در صفحه می‌توانید:
   - نام فلو را وارد کنید و یکی از مرحله‌های نمونه را انتخاب کنید.
   - تنظیمات استراتژی ارجاع تیکت هر مرحله را تغییر دهید.
   - پیش‌نمایش JSON را در پایین صفحه ببینید.
4. برای اجرای محلی (اختیاری):
   ```bash
   python -m http.server 8000
   ```
   سپس به آدرس http://localhost:8000/flow_builder.html بروید.

## راهنمای سریع (فارسی)
1. فایل `assignment_strategy.html` را در پوشه‌ی اصلی مخزن پیدا کنید.
2. روی فایل دوبار کلیک کنید یا آن را به داخل مرورگر بکشید و رها کنید تا مستقیم باز شود.
   - صفحه کاملاً ایستا است و به هیچ پیش‌نیازی احتیاج ندارد.
3. اگر ترجیح می‌دهید از سرور محلی استفاده کنید، مراحل بخش بعد را انجام دهید.

## Quick view
1. Locate `assignment_strategy.html` in the repository root.
2. Open the file directly in a modern web browser (double-click or drag-and-drop). The page is fully static and requires no build step.

## View via local server (optional)
If you prefer to serve the file locally:
1. From the repository root, start a simple HTTP server:
   ```bash
   python -m http.server 8000
   ```
2. Open http://localhost:8000/assignment_strategy.html in your browser.

Either approach will display the RTL Persian UI for the assignment strategy form.

راهنمای انتشار نرم افزار مدیریت مالی دادیلانه

1) تمام فایل‌های این پوشه باید مستقیماً در ریشه Repository گیت‌هاب قرار بگیرند.
2) index.html و config.js باید کنار هم و در ریشه Repository باشند.
3) در GitHub: Settings > Pages > Deploy from a branch > main > /(root) را انتخاب کنید.
4) در Supabase ابتدا supabase_schema.sql را در SQL Editor اجرا کنید.
5) فایل config.js از قبل با Project URL و Publishable/Anon Key تنظیم شده است.
6) هرگز Service Role/Secret Key را در GitHub قرار ندهید.

ساختار صحیح:
index.html
config.js
supabase_schema.sql
seed.sql
favicon.svg
.nojekyll
README_GITHUB_راه‌اندازی.txt

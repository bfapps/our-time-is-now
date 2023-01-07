# V2Ray (vmess , vless)
ابزار ها و سرویس دهنده های مربوط به این پروتکل در این قسمت قرار می گیرند. 

## ابزار ها 
برای استفاده از این سرویس نیاز به برنامه هایی دارید که از پروتکل های vmess و vless پشتیبانی بکنه . 

کلاینت های زیر از این پروتکل ها پشتیبانی  می کنن و بنابر تجربه خودم کلاینت Trojan بهترین عملکرد رو داره . 

- [Trojan for Android](/trojan/app)
- [V2rayNG for Android](/v2ray/app)
- [Matsouri for android](v2ray/app)
- [Onclick for IOS](https://apps.apple.com/us/app/oneclick-safe-easy-fast/id1545555197)
- [QV2ray for Desktop](/v2ray/app)
  - [Download for Windows](https://github.com/Qv2ray/Qv2ray/releases/download/v2.7.0/Qv2ray-v2.7.0-Windows-Installer.exe) 
  - [Download for Mac](https://github.com/Qv2ray/Qv2ray/releases/download/v2.7.0/Qv2ray-v2.7.0-macOS-x64.dmg)
  - [Downlaod for Linux](https://github.com/Qv2ray/Qv2ray/releases/download/v2.7.0/Qv2ray-v2.7.0-linux-x64.AppImage)
- [Nekoray for Desktop](https://github.com/MatsuriDayo/nekoray)
  - [Download for Windows](https://github.com/MatsuriDayo/nekoray/releases/download/2.3/nekoray-2.3-2022-11-09-windows64.zip)
  - [Download for Mac](https://github.com/MatsuriDayo/nekoray/releases/download/2.3/nekoray-2.3-2022-11-09-macos-amd64.dmg)
  - [Download for Linux](https://github.com/MatsuriDayo/nekoray/releases/download/2.3/nekoray-2.3-2022-11-09-linux64.zip)

# آموزش نصب 
اگر برای نصب Qv2ray نیاز به کمک دارید از این لینک استفاده کنید 

[V2ray Installation](/v2ray/guide/)


## سرویس دهنده ها 
سرویس هایی که در این قسمت قرار می گیره روزانه آپدیت میشن  اونایی که  توسط خود تیم منتشر میشن محدودیت اتصال ۲۴ ساعته دارن و بعد از اون غیر فعال میشن. یک مشکل عمده ای که وجود داره اینه که با بالا رفتن تعداد یوزر ها احتمال اینکه آی پی سرور بلاک بشه هست و میشه گفت این مهم ترین مشکل پیش رویه هر سرویسی هست ولی ما نا امید نمی شیم و تا جایی که لازم باشه هزینه شو پرداخت می کنیم. 

| expire | provider | location | url |
| ----- | ----- | ---- | ----- |
| 2023-10-05 23:00 | ⚡OurTimeisNow | US | vmess://ewogICJ2IjogIjIiLAogICJwcyI6ICLimqFBbm9ueW1vdXNlIzAxMC1PdXJUaW1lSXNOb3fimqEiLAogICJhZGQiOiAiMy4xMzMuMTMuMjQ3IiwKICAicG9ydCI6IDgwLAogICJpZCI6ICJhNDlmZWM3MS00YjgxLTQzNDYtYjc4My1hZTE4YWJjY2Q3NTEiLAogICJhaWQiOiAwLAogICJuZXQiOiAidGNwIiwKICAidHlwZSI6ICJodHRwIiwKICAiaG9zdCI6ICIiLAogICJwYXRoIjogIi8iLAogICJ0bHMiOiAibm9uZSIKfQ== | 
| 2023-01-07 23:00 | ⚡OurTimeisNow | DE | vmess://eyJhZGQiOiJkaXNjb3JkLmNvbSIsImFpZCI6IjAiLCJhbHBuIjoiIiwiaG9zdCI6IiIsImlkIjoiYzRkNDgyZTQtOGRhZi00ZDMzLWVkMWQtMDhhNDJlODA5ZDU0IiwibmV0IjoiZ3JwYyIsInBhdGgiOiJhbWluIiwicG9ydCI6IjIwNTMiLCJwcyI6IuKaoUFub255bW91c2UjMTAyLU91clRpbWVJc05vd+KaoSIsInNjeSI6ImF1dG8iLCJzbmkiOiJvdXRsYXdhbm9ueW1vdXNlLm1sIiwidGxzIjoidGxzIiwidHlwZSI6Imd1biIsInYiOiIyIn0= | 
| 2023-01-07 23:00 | ⚡OurTimeisNow | DE | vmess://eyJhZGQiOiJkaXNjb3JkLmNvbSIsImFpZCI6IjAiLCJhbHBuIjoiIiwiaG9zdCI6IiIsImlkIjoiNWMzNzNmNTMtZTEwNy00NDEyLWNkMjAtZWI1MzI5NzM3MGNhIiwibmV0IjoiZ3JwYyIsInBhdGgiOiJhbWluIiwicG9ydCI6IjIwNTMiLCJwcyI6IuKaoUFub255bW91c2UjMTAyLU91clRpbWVJc05vd+KaoSIsInNjeSI6ImF1dG8iLCJzbmkiOiJvdXRsYXdhbm9ueW1vdXNlLm1sIiwidGxzIjoidGxzIiwidHlwZSI6Imd1biIsInYiOiIyIn0= | 
| 2023-01-07 23:00 | ⚡OurTimeisNow | DE | vmess://eyJhZGQiOiJibG9nLm91dGxhd2Fub255bW91c2UubWwiLCJhaWQiOiIwIiwiYWxwbiI6IiIsImhvc3QiOiIiLCJpZCI6IjhmNzFjODc5LTcyMDQtNDYwYy1mNjNhLTZlZDI3MjU2OTUwZCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJwb3J0IjoiODA4MCIsInBzIjoi4pqhQW5vbnltb3VzZSMxMDEtT3VyVGltZUlzTm934pqhIiwic2N5IjoiYXV0byIsInNuaSI6IiIsInRscyI6IiIsInR5cGUiOiIiLCJ2IjoiMiJ9 |
| 2023-01-07 23:00 | ⚡OurTimeisNow | DE | vmess://eyJhZGQiOiJibG9nLm91dGxhd2Fub255bW91c2UubWwiLCJhaWQiOiIwIiwiYWxwbiI6IiIsImhvc3QiOiIiLCJpZCI6IjMwMjYwZGE4LTgwNmUtNGY1Ny1hY2I1LWJlNzg0Yzc5MmY1MSIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJwb3J0IjoiODA4MCIsInBzIjoi4pqhQW5vbnltb3VzZSMxMDEtT3VyVGltZUlzTm934pqhIiwic2N5IjoiYXV0byIsInNuaSI6IiIsInRscyI6IiIsInR5cGUiOiIiLCJ2IjoiMiJ9 | 
| 2023-01-08 23:00 | ⚡OurTimeisNow | SG | vmess://eyJhZGQiOiJwb3J0Zm9saW8ub3V0bGF3YW5vbnltb3VzZS5tbCIsImFpZCI6MCwiaWQiOiIzNGUxNDUzMC04MzA5LTQxNWItZWY0YS03Yzg3ODlkOWY2NGQiLCJuZXQiOiJncnBjIiwicGF0aCI6ImFub255bW91ZSIsInBvcnQiOjIwNTMsInBzIjoi4pqhQW5vbnltb3VzZSMyMDAtT3VyVGltZUlzTm934pqhIiwic2N5IjoiYWVzLTEyOC1nY20iLCJzbmkiOiIiLCJ0bHMiOiJ0bHMiLCJ0eXBlIjoibm9uZSIsInYiOjJ9 |
| 2023-01-08 23:00 | ⚡OurTimeisNow | SG | vmess://eyJhZGQiOiJwb3J0Zm9saW8ub3V0bGF3YW5vbnltb3VzZS5tbCIsImFpZCI6MCwiaWQiOiI0OTk5NjAzYy04YWM1LTRlOWQtYmVjNi1hYzIzNjcyNmRkMTIiLCJuZXQiOiJncnBjIiwicGF0aCI6ImFub255bW91ZSIsInBvcnQiOjIwNTMsInBzIjoi4pqhQW5vbnltb3VzZSMyMDAtT3VyVGltZUlzTm934pqhIiwic2N5IjoiYWVzLTEyOC1nY20iLCJzbmkiOiIiLCJ0bHMiOiJ0bHMiLCJ0eXBlIjoibm9uZSIsInYiOjJ9 |
| 2023-01-08 23:00 | ⚡OurTimeisNow | SG | vmess://eyJhZGQiOiIxNDYuMTkwLjIwMC4yMzMiLCJhaWQiOjAsImlkIjoiYjQxMjdkNGUtODY2ZC00YzhmLWU5NmItYmRlMjUzOTNmMTgyIiwibmV0IjoidGNwIiwicG9ydCI6NjAsInBzIjoi4pqhQW5vbnltb3VzZSMyMDEtT3VyVGltZUlzTm934pqhIiwic2N5IjoiYWVzLTEyOC1nY20iLCJ0bHMiOiJub25lIiwidHlwZSI6Imh0dHAiLCJ2IjoyfQ== |
| 2023-01-08 23:00 | ⚡OurTimeisNow | SG | vmess://eyJhZGQiOiIxNDYuMTkwLjIwMC4yMzMiLCJhaWQiOjAsImlkIjoiYTJkZGZkNDEtN2ZhNi00M2YzLWJlYTUtNzFmOTdkYzFlYmRlIiwibmV0IjoidGNwIiwicG9ydCI6NjAsInBzIjoi4pqhQW5vbnltb3VzZSMyMDEtT3VyVGltZUlzTm934pqhIiwic2N5IjoiYWVzLTEyOC1nY20iLCJ0bHMiOiJub25lIiwidHlwZSI6Imh0dHAiLCJ2IjoyfQ== |
| 2023-01-08 23:00 | ⚡OurTimeisNow | SG | vmess://eyJhZGQiOiI2Ni4yMzUuMjAwLjE0OCIsImFpZCI6MCwiaWQiOiIzNGUxNDUzMC04MzA5LTQxNWItZWY0YS03Yzg3ODlkOWY2NGQiLCJuZXQiOiJncnBjIiwicGF0aCI6ImFub255bW91ZSIsInBvcnQiOjIwNTMsInBzIjoi4pqhQW5vbnltb3VzZSMyMDAtT3VyVGltZUlzTm934pqhIiwic2N5IjoiYWVzLTEyOC1nY20iLCJzbmkiOiJwb3J0Zm9saW8ub3V0bGF3YW5vbnltb3VzZS5tbCIsInRscyI6InRscyIsInR5cGUiOiJub25lIiwidiI6Mn0= |
| 2023-01-08 23:00 | ⚡OurTimeisNow | SG | vmess://eyJhZGQiOiI2Ni4yMzUuMjAwLjE0OCIsImFpZCI6MCwiaWQiOiI0OTk5NjAzYy04YWM1LTRlOWQtYmVjNi1hYzIzNjcyNmRkMTIiLCJuZXQiOiJncnBjIiwicGF0aCI6ImFub255bW91ZSIsInBvcnQiOjIwNTMsInBzIjoi4pqhQW5vbnltb3VzZSMyMDAtT3VyVGltZUlzTm934pqhIiwic2N5IjoiYWVzLTEyOC1nY20iLCJzbmkiOiJwb3J0Zm9saW8ub3V0bGF3YW5vbnltb3VzZS5tbCIsInRscyI6InRscyIsInR5cGUiOiJub25lIiwidiI6Mn0= |
| 2023-01-08 23:00 | ⚡OurTimeisNow | SG | vmess://eyJhZGQiOiJkaXNjb3JkLmNvbSIsImFpZCI6MCwiaWQiOiIzNGUxNDUzMC04MzA5LTQxNWItZWY0YS03Yzg3ODlkOWY2NGQiLCJuZXQiOiJncnBjIiwicGF0aCI6ImFub255bW91ZSIsInBvcnQiOjIwNTMsInBzIjoi4pqhQW5vbnltb3VzZSMyMDAtT3VyVGltZUlzTm934pqhIiwic2N5IjoiYWVzLTEyOC1nY20iLCJzbmkiOiJwb3J0Zm9saW8ub3V0bGF3YW5vbnltb3VzZS5tbCIsInRscyI6InRscyIsInR5cGUiOiJub25lIiwidiI6Mn0= |
| 2023-01-08 23:00 | ⚡OurTimeisNow | SG | vmess://eyJhZGQiOiJkaXNjb3JkLmNvbSIsImFpZCI6MCwiaWQiOiI0OTk5NjAzYy04YWM1LTRlOWQtYmVjNi1hYzIzNjcyNmRkMTIiLCJuZXQiOiJncnBjIiwicGF0aCI6ImFub255bW91ZSIsInBvcnQiOjIwNTMsInBzIjoi4pqhQW5vbnltb3VzZSMyMDAtT3VyVGltZUlzTm934pqhIiwic2N5IjoiYWVzLTEyOC1nY20iLCJzbmkiOiJwb3J0Zm9saW8ub3V0bGF3YW5vbnltb3VzZS5tbCIsInRscyI6InRscyIsInR5cGUiOiJub25lIiwidiI6Mn0= |
| unknown | SSR | - | [click to open file](/v2ray/config/ssr-1401-10-02txt) |
| unknown | SSR | - | [click to open file](/v2ray/config/ssr-1401-10-09txt) |
| unknown | SSR | - | [click to open file](/v2ray/config/ssr-1401-10-16txt) |

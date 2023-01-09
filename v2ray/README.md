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
| 2023-01-10 23:00 | ⚡OurTimeisNow | NE | vmess://ewogICJ2IjogIjIiLAogICJwcyI6ICLimqFBbm9ueW1vdXNlIzMwMC1PdXJUaW1lSXNOb3fimqEiLAogICJhZGQiOiAicHJvZmlsZS5vdXRsYXdhbm9ueW1vdXNlLm1sIiwKICAicG9ydCI6IDIwOTYsCiAgImlkIjogIjI4MGZkMTI0LWNkZDQtNGU1YS04YjJhLTc4ZDAwOTg3YTkxNSIsCiAgImFpZCI6IDAsCiAgIm5ldCI6ICJncnBjIiwKICAidHlwZSI6ICJub25lIiwKICAiaG9zdCI6ICIiLAogICJwYXRoIjogInByb2ZpbGUiLAogICJ0bHMiOiAidGxzIgp9 |
| 2023-01-10 23:00 | ⚡OurTimeisNow | NE | vmess://ewogICJ2IjogIjIiLAogICJwcyI6ICLimqFBbm9ueW1vdXNlIzMwMC1PdXJUaW1lSXNOb3fimqEiLAogICJhZGQiOiAicHJvZmlsZS5vdXRsYXdhbm9ueW1vdXNlLm1sIiwKICAicG9ydCI6IDIwOTYsCiAgImlkIjogIjQ2ZjAwZDU1LTE4NjUtNGQ4YS1jMmU5LTkyNTRlNzVlMjlhZSIsCiAgImFpZCI6IDAsCiAgIm5ldCI6ICJncnBjIiwKICAidHlwZSI6ICJub25lIiwKICAiaG9zdCI6ICIiLAogICJwYXRoIjogInByb2ZpbGUiLAogICJ0bHMiOiAidGxzIgp9 |
| 2023-01-10 23:00 | ⚡OurTimeisNow | NE | vmess://eyJhZGQiOiI2Ni4yMzUuMjAwLjE0OCIsImFpZCI6IjAiLCJhbHBuIjoiIiwiaG9zdCI6IiIsImlkIjoiMjgwZmQxMjQtY2RkNC00ZTVhLThiMmEtNzhkMDA5ODdhOTE1IiwibmV0IjoiZ3JwYyIsInBhdGgiOiJwcm9maWxlIiwicG9ydCI6IjIwOTYiLCJwcyI6IuKaoUFub255bW91c2UjMzAwLU91clRpbWVJc05vd+KaoSIsInNjeSI6ImF1dG8iLCJzbmkiOiJwcm9maWxlLm91dGxhd2Fub255bW91c2UubWwiLCJ0bHMiOiJ0bHMiLCJ0eXBlIjoiZ3VuIiwidiI6IjIifQ==
| 2023-01-10 23:00 | ⚡OurTimeisNow | NE | vmess://eyJhZGQiOiI2Ni4yMzUuMjAwLjE0OCIsImFpZCI6IjAiLCJhbHBuIjoiIiwiaG9zdCI6IiIsImlkIjoiN2Y1NzI2ZTEtYWFhZi00N2Q4LWFkZGItNzdhODY1ZjVhZjQxIiwibmV0IjoiZ3JwYyIsInBhdGgiOiJvdXRsYXdhbm9ueW1vdXNlIiwicG9ydCI6IjIwOTYiLCJwcyI6IuKaoUFub255bW91c2UjMjAwLU91clRpbWVJc05vd+KaoSIsInNjeSI6ImF1dG8iLCJzbmkiOiJwb3J0Zm9saW8ub3V0bGF3YW5vbnltb3VzZS5tbCIsInRscyI6InRscyIsInR5cGUiOiJndW4iLCJ2IjoiMiJ9 |
| 2023-01-10 23:00 | ⚡OurTimeisNow | NE | vmess://eyJhZGQiOiJkaXNjb3JkLmNvbSIsImFpZCI6IjAiLCJhbHBuIjoiIiwiaG9zdCI6IiIsImlkIjoiNDZmMDBkNTUtMTg2NS00ZDhhLWMyZTktOTI1NGU3NWUyOWFlIiwibmV0IjoiZ3JwYyIsInBhdGgiOiJwcm9maWxlIiwicG9ydCI6IjIwOTYiLCJwcyI6IuKaoUFub255bW91c2UjMzAwLU91clRpbWVJc05vd+KaoSIsInNjeSI6ImF1dG8iLCJzbmkiOiJwcm9maWxlLm91dGxhd2Fub255bW91c2UubWwiLCJ0bHMiOiJ0bHMiLCJ0eXBlIjoiZ3VuIiwidiI6IjIifQ== |
| 2023-01-10 23:00 | ⚡OurTimeisNow | NE | vmess://eyJhZGQiOiJkaXNjb3JkLmNvbSIsImFpZCI6IjAiLCJhbHBuIjoiIiwiaG9zdCI6IiIsImlkIjoiNDZmMDBkNTUtMTg2NS00ZDhhLWMyZTktOTI1NGU3NWUyOWFlIiwibmV0IjoiZ3JwYyIsInBhdGgiOiJwcm9maWxlIiwicG9ydCI6IjIwOTYiLCJwcyI6IuKaoUFub255bW91c2UjMzAwLU91clRpbWVJc05vd+KaoSIsInNjeSI6ImF1dG8iLCJzbmkiOiJwcm9maWxlLm91dGxhd2Fub255bW91c2UubWwiLCJ0bHMiOiJ0bHMiLCJ0eXBlIjoiZ3VuIiwidiI6IjIifQ== |
| 2023-01-10 23:00 | ⚡OurTimeisNow | DE | vmess://ewogICJ2IjogIjIiLAogICJwcyI6ICLimqFBbm9ueW1vdXNlIzIwMC1PdXJUaW1lSXNOb3fimqEiLAogICJhZGQiOiAicG9ydGZvbGlvLm91dGxhd2Fub255bW91c2UubWwiLAogICJwb3J0IjogMjA5NiwKICAiaWQiOiAiN2Y1NzI2ZTEtYWFhZi00N2Q4LWFkZGItNzdhODY1ZjVhZjQxIiwKICAiYWlkIjogMCwKICAibmV0IjogImdycGMiLAogICJ0eXBlIjogIm5vbmUiLAogICJob3N0IjogIiIsCiAgInBhdGgiOiAib3V0bGF3YW5vbnltb3VzZSIsCiAgInRscyI6ICJ0bHMiCn0= | 
| 2023-01-10 23:00 | ⚡OurTimeisNow | DE | vmess://ewogICJ2IjogIjIiLAogICJwcyI6ICLimqFBbm9ueW1vdXNlIzIwMC1PdXJUaW1lSXNOb3fimqEiLAogICJhZGQiOiAicG9ydGZvbGlvLm91dGxhd2Fub255bW91c2UubWwiLAogICJwb3J0IjogMjA5NiwKICAiaWQiOiAiN2Y1NzI2ZTEtYWFhZi00N2Q4LWFkZGItNzdhODY1ZjVhZjQxIiwKICAiYWlkIjogMCwKICAibmV0IjogImdycGMiLAogICJ0eXBlIjogIm5vbmUiLAogICJob3N0IjogIiIsCiAgInBhdGgiOiAib3V0bGF3YW5vbnltb3VzZSIsCiAgInRscyI6ICJ0bHMiCn0= |
| 2023-01-10 23:00 | ⚡OurTimeisNow | DE | vmess://eyJhZGQiOiI2Ni4yMzUuMjAwLjE0OCIsImFpZCI6IjAiLCJhbHBuIjoiIiwiaG9zdCI6IiIsImlkIjoiMTI5ZGI1OGUtYmNkYS00MzU3LWMyYzEtMGFjYWMxZjYyNzAwIiwibmV0IjoiZ3JwYyIsInBhdGgiOiJvdXRwcm9maWxlIiwicG9ydCI6IjIwODciLCJwcyI6IuKaoUFub255bW91c2UjMzAxLU91clRpbWVJc05vd+KaoSIsInNjeSI6ImF1dG8iLCJzbmkiOiJwcm9maWxlLm91dGxhd2Fub255bW91c2UubWwiLCJ0bHMiOiJ0bHMiLCJ0eXBlIjoiZ3VuIiwidiI6IjIifQ== |
| 2023-01-10 23:00 | ⚡OurTimeisNow | DE | vmess://eyJhZGQiOiI2Ni4yMzUuMjAwLjE0OCIsImFpZCI6IjAiLCJhbHBuIjoiIiwiaG9zdCI6IiIsImlkIjoiOTAxNDNjOWYtNTQ3Mi00ZjA4LWFkMmUtYzIwYjc4ZDUzZGUxIiwibmV0IjoiZ3JwYyIsInBhdGgiOiJhbm9ueW1vdXNlIiwicG9ydCI6IjIwNTMiLCJwcyI6IuKaoUFub255bW91c2UjMjAxLU91clRpbWVJc05vd+KaoSIsInNjeSI6ImF1dG8iLCJzbmkiOiJwb3J0Zm9saW8ub3V0bGF3YW5vbnltb3VzZS5tbCIsInRscyI6InRscyIsInR5cGUiOiJndW4iLCJ2IjoiMiJ9 |
| 2023-01-10 23:00 | ⚡OurTimeisNow | DE | vmess://eyJhZGQiOiJkaXNjb3JkLmNvbSIsImFpZCI6IjAiLCJhbHBuIjoiIiwiaG9zdCI6IiIsImlkIjoiMDNmODEyNzYtZjQyZi00YWU4LWQ0ODAtY2IyYTdmMzJiZTNkIiwibmV0IjoiZ3JwYyIsInBhdGgiOiJvdXRwcm9maWxlIiwicG9ydCI6IjIwODciLCJwcyI6IuKaoUFub255bW91c2UjMzAxLU91clRpbWVJc05vd+KaoSIsInNjeSI6ImF1dG8iLCJzbmkiOiJwcm9maWxlLm91dGxhd2Fub255bW91c2UubWwiLCJ0bHMiOiJ0bHMiLCJ0eXBlIjoiZ3VuIiwidiI6IjIifQ== |
| unknown | SSR | - | [click to open file](/v2ray/config/ssr-1401-10-02txt) |
| unknown | SSR | - | [click to open file](/v2ray/config/ssr-1401-10-09txt) |
| unknown | SSR | - | [click to open file](/v2ray/config/ssr-1401-10-16txt) |

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
| 2023-01-05 23:00 | ⚡OurTimeisNow | DE | vmess://eyJhZGQiOiJibG9nLm91dGxhd2Fub255bW91c2UubWwiLCJhaWQiOjAsImlkIjoiMzdkZjZmZmYtYjlmYi00NzY3LWI3ZTYtYWQ1Zjk1ZDMwNmI4IiwibmV0IjoidGNwIiwicG9ydCI6MjAyMywicHMiOiLimqFBbm9ueW1vdXNlIzEwMC1PdXJUaW1lSXNOb3fimqEiLCJzY3kiOiJhZXMtMTI4LWdjbSIsInRscyI6Im5vbmUiLCJ0eXBlIjoiaHR0cCIsInYiOjJ9 | 
| 2023-01-05 23:00 | ⚡OurTimeisNow | DE | vmess://eyJhZGQiOiJibG9nLm91dGxhd2Fub255bW91c2UubWwiLCJhaWQiOjAsImlkIjoiMWNlZTYwMjUtMTc3ZC00ZTAzLWFjYzQtMjY1MDVlNmI0ZGRmIiwibmV0IjoidGNwIiwicG9ydCI6MjAyMywicHMiOiLimqFBbm9ueW1vdXNlIzEwMC1PdXJUaW1lSXNOb3fimqEiLCJzY3kiOiJhZXMtMTI4LWdjbSIsInRscyI6Im5vbmUiLCJ0eXBlIjoiaHR0cCIsInYiOjJ9 | 
| 2023-01-05 23:00 | ⚡OurTimeisNow | DE | vmess://eyJhZGQiOiJibG9nLm91dGxhd2Fub255bW91c2UubWwiLCJhaWQiOjAsImhvc3QiOiIiLCJpZCI6ImI4YmQ0YmFlLTg3YzQtNDkwOC1iM2UwLWY2OGMxMzVmZTQ3MiIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJwb3J0Ijo4MDgwLCJwcyI6IuKaoUFub255bW91c2UjMTAxLU91clRpbWVJc05vd+KaoSIsInNjeSI6ImFlcy0xMjgtZ2NtIiwidGxzIjoibm9uZSIsInR5cGUiOiJub25lIiwidiI6Mn0= |
| 2023-01-05 23:00 | ⚡OurTimeisNow | DE | vmess://eyJhZGQiOiJibG9nLm91dGxhd2Fub255bW91c2UubWwiLCJhaWQiOjAsImhvc3QiOiIiLCJpZCI6IjhhYjFiZWEwLWU2ZDUtNDRhZS1mZmJlLTA0Y2NlZDRhMTU0OSIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJwb3J0Ijo4MDgwLCJwcyI6IuKaoUFub255bW91c2UjMTAxLU91clRpbWVJc05vd+KaoSIsInNjeSI6ImFlcy0xMjgtZ2NtIiwidGxzIjoibm9uZSIsInR5cGUiOiJub25lIiwidiI6Mn0= | 
| 2023-01-06 23:00 | ⚡OurTimeisNow | SG | vmess://eyJhZGQiOiJ4eXoub3V0bGF3YW5vbnltb3VzZS5tbCIsImFpZCI6IjAiLCJhbHBuIjoiIiwiaG9zdCI6IiIsImlkIjoiY2QxYTFjNjUtY2E1YS00NzkyLTgxNDMtNTI1MjNiZTZkNTQ1IiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJwb3J0IjoiNjAiLCJwcyI6IuKaoUFub255bW91c2UjMjAxLU91clRpbWVJc05vd+KaoSIsInNjeSI6ImF1dG8iLCJzbmkiOiIiLCJ0bHMiOiIiLCJ0eXBlIjoiaHR0cCIsInYiOiIyIn0= | vmess://eyJhZGQiOiIxNDMuMTk4LjIxOC45IiwiYWlkIjowLCJpZCI6IjMwYjc5MzdiLWMwM2MtNDllNi1kMzg0LWY2YTUxMjMzZTlkNCIsIm5ldCI6InRjcCIsInBvcnQiOjYwLCJwcyI6IuKaoUFub255bW91c2UjMjAxLU91clRpbWVJc05vd+KaoSIsInNjeSI6ImFlcy0xMjgtZ2NtIiwidGxzIjoibm9uZSIsInR5cGUiOiJodHRwIiwidiI6Mn0= |
| 2023-01-06 23:00 | ⚡OurTimeisNow | SG |
| unknown | SSR | - | [click to open file](/v2ray/config/ssr-1401-10-02txt) |
| unknown | SSR | - | [click to open file](/v2ray/config/ssr-1401-10-09txt) |

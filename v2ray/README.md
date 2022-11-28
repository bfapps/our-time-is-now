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
| 2022-11-28 23:00 | ⚡OurTimeisNow | TR | vmess://ewogICJ2IjogIjIiLAogICJwcyI6ICLimqFBbm9ueW1vdXNlIzAwMS1PdXJUaW1lSXNOb3fimqEiLAogICJhZGQiOiAiOTEuMjQxLjQ5LjU3IiwKICAicG9ydCI6IDQ5MjEwLAogICJpZCI6ICIyNDA2MjI3Ny0xYTYxLTRmZDMtOTlkYi01MDNjZWEwODUzNTQiLAogICJhaWQiOiAwLAogICJuZXQiOiAid3MiLAogICJ0eXBlIjogIm5vbmUiLAogICJob3N0IjogIiIsCiAgInBhdGgiOiAiL3ZtZXNzIiwKICAidGxzIjogIm5vbmUiCn0= |
| 2022-11-26 23:00 | ⚡OurTimeisNow | TR | vmess://ewogICJ2IjogIjIiLAogICJwcyI6ICLimqFBbm9ueW1vdXNlIzAwMi1PdXJUaW1lSXNOb3fimqEiLAogICJhZGQiOiAiOTEuMjQxLjQ5LjU3IiwKICAicG9ydCI6IDEyODA1LAogICJpZCI6ICI0YzM4YjJkZS00MWM3LTQwY2ItZmQ1YS01ODFlODgzNDJkODYiLAogICJhaWQiOiAwLAogICJuZXQiOiAid3MiLAogICJ0eXBlIjogIm5vbmUiLAogICJob3N0IjogIiIsCiAgInBhdGgiOiAiL3ZtZXNzIiwKICAidGxzIjogIm5vbmUiCn0= |
| 2022-11-29 23:00 | ⚡OurTimeisNow | US | vmess://ewogICJ2IjogIjIiLAogICJwcyI6ICLimqFBbm9ueW1vdXNlIzAxMC1PdXJUaW1lSXNOb3fimqEiLAogICJhZGQiOiAiMy4xMzMuMTMuMjQ3IiwKICAicG9ydCI6IDgwLAogICJpZCI6ICJhNDlmZWM3MS00YjgxLTQzNDYtYjc4My1hZTE4YWJjY2Q3NTEiLAogICJhaWQiOiAwLAogICJuZXQiOiAid3MiLAogICJ0eXBlIjogIm5vbmUiLAogICJob3N0IjogIiIsCiAgInBhdGgiOiAiL3ZtZXNzIiwKICAidGxzIjogIm5vbmUiCn0= | 
| 2022-11-29 23:00 | ⚡OurTimeisNow | SG | vmess://ewogICJ2IjogIjIiLAogICJwcyI6ICLimqFBbm9ueW1vdXNlIzAzMC1PdXJUaW1lSXNOb3fimqEiLAogICJhZGQiOiAiMTM5LjE2Mi4yNC4yMjEiLAogICJwb3J0IjogMzY1MDksCiAgImlkIjogIjNjYTcyNGQ0LTY0NjgtNDNlMy1lNWY0LWEyOGYyOTk4M2YyZCIsCiAgImFpZCI6IDAsCiAgIm5ldCI6ICJ3cyIsCiAgInR5cGUiOiAibm9uZSIsCiAgImhvc3QiOiAiIiwKICAicGF0aCI6ICIvdm1lc3MiLAogICJ0bHMiOiAibm9uZSIKfQ== | 
| 2022-11-29 23:00 | ⚡OurTimeisNow | DE | vmess://ewogICJ2IjogIjIiLAogICJwcyI6ICLimqFBbm9ueW1vdXNlIzAyMC1PdXJUaW1lSXNOb3fimqEiLAogICJhZGQiOiAiMTcyLjEwNS43NC4xMzQiLAogICJwb3J0IjogMzc4NjcsCiAgImlkIjogIjQ2MjNmOTQ5LWUwZTQtNGQ0MC1kMTc3LTA0OWNhNmZkNzUxOCIsCiAgImFpZCI6IDAsCiAgIm5ldCI6ICJ3cyIsCiAgInR5cGUiOiAibm9uZSIsCiAgImhvc3QiOiAiIiwKICAicGF0aCI6ICIvdm1lc3MiLAogICJ0bHMiOiAibm9uZSIKfQ== |  
| 2022-11-28 23:00 | ⚡OurTimeisNow | JP | vmess://ewogICJ2IjogIjIiLAogICJwcyI6ICLimqFBbm9ueW1vdXNlIzA0MC1PdXJUaW1lSXNOb3fimqEiLAogICJhZGQiOiAiMTcyLjEwNS4yMjUuMzEiLAogICJwb3J0IjogNTY2NDksCiAgImlkIjogIjM2ODRlN2YxLTFlMTEtNDA0NS1lNzNhLTA1NDAyNzI4OGY4MCIsCiAgImFpZCI6IDAsCiAgIm5ldCI6ICJ3cyIsCiAgInR5cGUiOiAibm9uZSIsCiAgImhvc3QiOiAiIiwKICAicGF0aCI6ICIvdm1lc3MiLAogICJ0bHMiOiAibm9uZSIKfQ== |
| 2022-11-28 23:00 | ⚡OurTimeisNow | DE | vmess://eyJhZGQiOiIxNzIuMTA0LjI1My4yMzkiLCJhaWQiOjAsImhvc3QiOiIiLCJpZCI6ImMxOTJjNGU1LWRlMWYtNDQ1Yi1jNGUzLWMyODU5MGYzYjI1MCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJwb3J0IjozMTI3OCwicHMiOiLimqFBbm9ueW1vdXNlIzA1MC1PdXJUaW1lSXNOb3fimqEiLCJzY3kiOiJhZXMtMTI4LWdjbSIsInRscyI6Im5vbmUiLCJ0eXBlIjoibm9uZSIsInYiOjJ9 |
| unknown | OneClickVpnKeys | - | [click to open file](/v2ray/config/oneclickvpnkeys-1401-08-16.txt) |
| unknown | SSR | - | [click to open file](/v2ray/config/ssr-1401-08-14.txt) |
| unknown | SSR | - | [click to open file](/v2ray/config/ssr-1401-08-20.txt) |
| unknown | NovaVP | US | vmess://eyJhZGQiOiJ1c2Eubm92YWZhcnNpLmNvbSIsImFpZCI6MCwiaG9zdCI6IiIsImlkIjoiYzRmMDQ2OTctMDgxYy00MTg1LWU1MjgtMDlkZGE1MDI5MjdmIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsInBvcnQiOjE3MjcsInBzIjoiVEcgQE5vdmFWUCIsInNjeSI6ImFlcy0xMjgtZ2NtIiwidGxzIjoibm9uZSIsInR5cGUiOiJub25lIiwidiI6Mn0= | 
| unknown | SSR | - | [click to open file](/v2ray/config/ssr-1401-08-28.txt) |
| unknown | OneClickVpnKeys | - | vmess://ewogICJ2IjogMiwKICAicHMiOiAi8J+Hp/Cfh6pCRV8wMSIsCiAgImFkZCI6ICI1Ny4xMjguNDUuMTYxIiwKICAicG9ydCI6IDgwLAogICJpZCI6ICIzNWQyNTg5OS1lZDIwLTQ2ZDktOWM3Yy05OWMwZDQxNGQ1ZTQiLAogICJhaWQiOiAwLAogICJuZXQiOiAid3MiLAogICJob3N0IjogIjU3LjEyOC40NS4xNjEiLAogICJwYXRoIjogIi91c2VyIiwKICAidHlwZSI6ICIiLAogICJ0bHMiOiAiIiwKICAic25pIjogIiIsCiAgInNjeSI6ICJhdXRvIgp9 | 
| unknown | OneClickVpnKeys | - | vmess://ewogICJ2IjogMiwKICAicHMiOiAi8J+Hq/Cfh64xMjdAb25lY2xpY2t2cG5rZXlzIiwKICAiYWRkIjogIjEzNS4xODEuOTUuMTI3IiwKICAicG9ydCI6IDQ0MywKICAiaWQiOiAiNmI3Y2JjNDEtZmI4MC00MWE4LThlYjYtYjViZGIwZTg2MTQ3IiwKICAiYWlkIjogMCwKICAibmV0IjogInRjcCIsCiAgImhvc3QiOiAiIiwKICAicGF0aCI6ICIvIiwKICAidHlwZSI6ICJodHRwIiwKICAidGxzIjogIiIsCiAgInNuaSI6ICIiLAogICJzY3kiOiAiYXV0byIKfQ== | 
| unknown | OneClickVpnKeys | - | vmess://ewogICJ2IjogMiwKICAicHMiOiAiREUgMiDihpIgb3Blbml0c3ViLmNvbSIsCiAgImFkZCI6ICIyMDYuODEuMzEuMTg0IiwKICAicG9ydCI6IDYyNDUsCiAgImlkIjogIjlkMzljYjM0LTUyNjEtNDNmYi1iMGY4LTRmOGEyMmIxMGYxNSIsCiAgImFpZCI6IDAsCiAgIm5ldCI6ICJ3cyIsCiAgImhvc3QiOiAiIiwKICAicGF0aCI6ICIvIiwKICAidHlwZSI6ICIiLAogICJ0bHMiOiAiIiwKICAic25pIjogIiIsCiAgInNjeSI6ICJhdXRvIgp9 | 
| unknown | OneClickVpnKeys | - | vmess://ewogICJ2IjogMiwKICAicHMiOiAi8J+HsfCfh7lMVF8zMiB8MzAuNTJNYiIsCiAgImFkZCI6ICI4NC4zMi40LjI1IiwKICAicG9ydCI6IDMzODksCiAgImlkIjogIjg4Njg2OGUyLWIzZmMtNGEyYy04YzY2LTFkMjY5MTg2MTY3MSIsCiAgImFpZCI6IDAsCiAgIm5ldCI6ICJ3cyIsCiAgImhvc3QiOiAiODQuMzIuNC4yNSIsCiAgInBhdGgiOiAiLyIsCiAgInR5cGUiOiAiIiwKICAidGxzIjogIiIsCiAgInNuaSI6ICIiLAogICJzY3kiOiAiYXV0byIKfQ== |
| unknown | OneClickVpnKeys | - | vmess://ewogICJ2IjogMiwKICAicHMiOiAi8J+HqfCfh6oxOTlAb25lY2xpY2t2cG5rZXlzIiwKICAiYWRkIjogIjE2MS4zNS42Ni4xOTkiLAogICJwb3J0IjogMjAxOTEsCiAgImlkIjogIjNlMmM0ODIwLWY1YjYtNDM4OS1hMTQzLTJhZTVjZTYwMDc0OCIsCiAgImFpZCI6IDAsCiAgIm5ldCI6ICJ3cyIsCiAgImhvc3QiOiAiIiwKICAicGF0aCI6ICIvIiwKICAidHlwZSI6ICIiLAogICJ0bHMiOiAiIiwKICAic25pIjogIiIsCiAgInNjeSI6ICJhdXRvIgp9 |
| unknown | OpenItSub | CA | vmess://eyJhZGQiOiIxNjcuMTE0LjY3LjI1IiwiYWlkIjowLCJob3N0IjoiMDA1ZGdkZi5wYWdlcy5kZXYiLCJpZCI6IjY1MjE4ZmU4LWQ5YzItNGUwNy05NWJiLWNiNmUzNzlhNDQwYiIsIm5ldCI6IndzIiwicGF0aCI6Ii82NTIxOGZlOC1kOWMyLTRlMDctOTViYi1jYjZlMzc5YTQ0MGItdm0iLCJwb3J0Ijo0NDMsInBzIjoiQ0EgMSDihpIgb3Blbml0c3ViLmNvbSIsInNjeSI6ImF1dG8iLCJzbmkiOiIwMDVkZ2RmLnBhZ2VzLmRldiIsInRscyI6InRscyIsInR5cGUiOiJub25lIiwidiI6Mn0= | 
| unknown | unknown | BE | vmess://eyJhZGQiOiI1Ny4xMjguNDUuMTYxIiwiYWlkIjowLCJob3N0IjoiNTcuMTI4LjQ1LjE2MSIsImlkIjoiMzVkMjU4OTktZWQyMC00NmQ5LTljN2MtOTljMGQ0MTRkNWU0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3VzZXIiLCJwb3J0Ijo4MCwicHMiOiLwn4en8J+HqkJFXzIxIiwic2N5IjoiYXV0byIsInRscyI6Im5vbmUiLCJ0eXBlIjoibm9uZSIsInYiOjJ9 |
| unknown | OpenItSub | - | [click to open file](/v2ray/config/openitsub-1401-09-05.txt) |
| unknown | SSR | - | [click to open file](/v2ray/config/ssr-1401-09-06.txt) | 
| unknown | OpenItSub | - | [click to open file](/v2ray/config/openitsub-1401-09-07.txt) |

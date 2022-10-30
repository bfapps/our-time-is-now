# Trojan 
تروجان یک پراکسی سرور هست که برای دور زدن فایروال چین ساخته شده و خودش رو شبیه رکوئست های معمولی HTTP نشون میده و ادعا داره که غیر قابل تشخیص هست . این پروتکل جدیده و روش کارش به این صورت است که که با سرور عملیات TLS Handshake انجام میده در صورتی که این عملیات موفق باشه همه ترافیک توسط TLS محافظت خواهند شد و در غیر اینصورت سرور کانکشن رو همانند یک  سرور HTTPS هواهد بست. سپس کلاینت شروع به ارسال ساختار خاصی از داده ها می کنه سرور در ابتدا پسورد رو کنترل می کنه اگر درست بود رکوئئست رو به عنوان یک رکوئست ولید تروجان قبول می کنه و تونل بین سرور و کلاینت برقرار میشه. 

## ابزار ها 
خوشبختانه تعدادی اپ که از این پروتکل پشتیبانی می کنن وجود داره که در ادامه معرفی شون می کنم نسخه ISO هم وجود داره که لینکشو قرار می دم . 

- [Qv2Ray for Desktop](/trojan/app/Qv2ray)
- [Trojan for Android](/trojan/app/)
- [OnClick for IOS](https://apps.apple.com/us/app/oneclick-safe-easy-fast/id1545555197)

## سرویس دهنده ها 
سبق روال لیست سرویس دهنده هایی که در این قسمت قرار میگیره روزانه آپدیت میشه اونایی که توسط تیم خودمون ساخته شدن محدودیت استفاده ۲۴ ساعته دارن . 

| protocol | provider | url |
| --- | --- | --- | 
| trojan | SSRSUB | trojan://9010950e-8e09-486a-bf96-3b0cf22097b4@hk2.sanfen001.pics:443?security=tls&sni=hk1.sanfen001.pics&type=tcp&headerType=none#%40SSRSUB-T01-%E4%BB%98%E8%B4%B9%E6%8E%A8%E8%8D%90%3Asuo.yt%2Fssrsub |
| torjan | SSRSUB | trojan://9010950e-8e09-486a-bf96-3b0cf22097b4@hk1.sanfen001.pics:443?security=tls&sni=hk1.sanfen001.pics&type=tcp&headerType=none#%40SSRSUB-T02-%E4%BB%98%E8%B4%B9%E6%8E%A8%E8%8D%90%3Asuo.yt%2Fssrsub |
| torjan | SSRSUB | trojan://9010950e-8e09-486a-bf96-3b0cf22097b4@tw1.sanfen001.pics:443?security=tls&sni=tw1.sanfen001.pics&type=tcp&headerType=none#%40SSRSUB-T03-%E4%BB%98%E8%B4%B9%E6%8E%A8%E8%8D%90%3Asuo.yt%2Fssrsub |
| torjan | SSRSUB | trojan://6064db30-b46e-432d-bbec-f12b947422a2@1024hk02.tfzhc.top:80?security=tls&type=tcp&headerType=none#%40SSRSUB-T04-%E4%BB%98%E8%B4%B9%E6%8E%A8%E8%8D%90%3Asuo.yt%2Fssrsub |
| torjan | SSRSUB | trojan://9010950e-8e09-486a-bf96-3b0cf22097b4@tw1.sanfen001.pics:443?security=tls&type=tcp&headerType=none#%40SSRSUB-T05-%E4%BB%98%E8%B4%B9%E6%8E%A8%E8%8D%90%3Asuo.yt%2Fssrsub |
| torjan | oneclickvpnkeys | trojan://opentunnel.net-gapproxy10@det-1.opensvr.net:443?sni=det-1.opensvr.net#%F0%9F%87%A9%F0%9F%87%AA6%40oneclickvpnkeys |
| torjan | oneclickvpnkeys | trojan://opentunnel.net-gapproxy11@det-1.opensvr.net:443?sni=det-1.opensvr.net#%F0%9F%87%A9%F0%9F%87%AA5%40oneclickvpnkeys | 
| torjan | oneclickvpnkeys | trojan://opentunnel.net-gapproxy2@det-1.opensvr.net:443?sni=det-1.opensvr.net#%F0%9F%87%A9%F0%9F%87%AA4%40oneclickvpnkeys |
| torjan | oneclickvpnkeys | trojan://opentunnel.net-proxypj70@det-1.opensvr.net:443?sni=det-1.opensvr.net#%F0%9F%87%A9%F0%9F%87%AA2%40oneclickvpnkeys | 
| torjan | oneclickvpnkeys | trojan://172799af-0d35-461e-afe4-6c6c2e6d85d7@sgt1.sshocean.net:443?sni=sgt1.sshocean.net#%F0%9F%87%B8%F0%9F%87%ACsgt1443%40oneclickvpnkeys |  


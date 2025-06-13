## اپدیت جدید ساخت سایت برای گرفتن پروفایل رایگان :

https://aigptcode.github.io/iphoneprofile/
 
## آموزش رایگان و دائمی فعال‌سازی آنتن در آیفون ۱۴ و ۱۵ بدون ردگیری و بسته شدن با دو روش مختلف، به همراه سورس کد و فایل ساخت UUID یکتا📡

  <a href="https://ibb.co/whDY2tw"><img src="https://i.ibb.co/Ld4vsKJ/IMG-5707.jpg" alt="IMG-5707" border="0"></a>
   
   
## اموزش ساخت پروفایل یکتا
 
کد ها به صورت template یا پوسته با توجه به همه اوپراتورها گذاشته شده فقط با uuid Generator که با زبان پایتون نوشته شده کدهای همتا جدید بسازید و با قبلی ها عوض کنید و فایل سیو کنید

(فایل پایتون به راحتی exe تبدیل کنید)

pip install pyinstaller
 
pyinstaller --onefile --windowed uuid-genarator.py 


در template ها  برای UUID این قسمت و جای کد جدید بگذارید

 
	<key>PayloadType</key>
			<string>com.apple.cellular</string>
			<key>PayloadUUID</key>
			<string>کد جدید</string>
			<key>PayloadVersion</key>
			<integer>1</integer>
   


علت بسته شدن کانفیگ ها بدلیل استفاده تعداد افراد زیاد از یک UUID هست

برای هر گوشی سعی کنید با uuid اختصاصی ساخته شود 

زمانی که چند دستگاه از یک کد استفاده میکنند شناسایی و بسته میشه 

هپچنین در کد قابلیت شخصی سازی پروکسی یا ایپی اختصاصی برای ساخت پروفایل و دسترسی اینترنت فراهم شده  

<a href="https://ibb.co/Zf3P4D7"><img src="https://i.ibb.co/yND1vj7/IMG-5664.jpg" alt="IMG-5664" border="0"></a>

# روش دوم 

## مراحل

## ** دانلود Apple Configurator یا Imazing profile editor ** :

- [Apple Configurator برای macOS](https://apps.apple.com/us/app/apple-configurator/id1037126344?mt=12)
- [Imazing Profile Editor برای ویندوز](https://apps.microsoft.com/detail/9PHS9QLCQ5S4?hl=en-us&gl=US)


2. **ایجاد پروفایل جدید**:
   - اجرای برنامه Apple Configurator
   - رفتن به منوی "File" و انتخاب "New Profile"

3. **تنظیمات پروفایل**:
   - در بخش "Name" نام دلخواه خود را وارد کنید.
   - در بخش "Identifier"، می‌توانید خالی بگذارید یا از فایل `uuid-genarator.py` یک کد یکتا بسازید و وارد کنید.

4. **تنظیمات APN**:
   - در منوی سمت چپ به دنبال گزینه "cellular" بگردید.
   - در بخش "Configured APN Type"، مقدار "mcinet" یا "mtnirancell" را وارد کنید.
   - در بخش "Data VPN Authentication Type" حتماً مقدار "CHAP" را انتخاب کنید.
   - در انتهای صفحه، از IP4 استفاده کنید. اگر متوجه مشکل اینترنت شدید، می‌توانید تستی با IP6 انجام دهید.

5. **تست و ذخیره**:
   - پیکربندی را ذخیره کنید.
   - اگر پیکربندی کار نکرد، می‌توانید یک پیکربندی جدید با یک UUID جدید بسازید و تست کنید.

.

## قبل از آپلود پروفایل‌ها این کارها را انجام دهید:

1. ابتدا ریست نتورک را انجام دهید 🔄.
2. فایل کانفیگ ساخته شده با هر روشی به گوشی ارسال کنید و آن را دانلود کنید و سپس بر روی آن کلیک کنید تا باز شود، سپس آن را در فایل ذخیره کنید 💾.
3. سپس به فایل منیجر بروید و روی کانفیگ کلیک کنید تا یک پیام بالا بیاید و اماده نصب شود 📂.
4. سپس وارد تنظیمات بخش VPN و Device Management شوید، پروفایل را انتخاب کرده و نصب کنید 📲.
5. بعد از نصب، به بخش Cellular Data بروید، تیک Data Roaming و VoLTE را بر روی 5G یا LTE بزنید، سپس گوشی را روشن و خاموش کنید تا آنتن برگردد 📶.

حالا بر روی [لینک شورتکات](https://www.icloud.com/shortcuts/9b2f6b908fb74058b2b1bf3ed4d08451) کلیک کنید 📌:
6. از توی شورتکات روی Anten کلیک کرده و نصبش کنید 📱.

و اگه انتن قطع شد با فعال کردن Shortcut میتونید مجدد راه اندازی کنید 🔄.

تمام شما آنتن دارید 📶.

## چند نکته مهم:

1. روی شبکه همراه اول تنظیم کنید تا آنتن بهتر بازگردد 📡.
2. از دو سیم کارت همزمان در گوشی استفاده نکنید 🚫.
3. در صورت کار نکردن پروفایل با uuid جدید بسازید و تست کنید همچنین برای دسترسی اینترنت مخصوصا برای ایرانسل میتونید تنظیمات ip رو ip6 بذارید 🌐.
4. حتماً نت را روی 5G تنظیم کنید 📶.
5. اگر از ساعت ۱۲ شب آنتن ندارید، نت را روی 2G تنظیم کنید، زیرا در برخی موارد آنتن به طور اتوماتیک تا صبح ۸ برگردد 🌙.

همچنین به یاد داشته باشید که هر پروفایل جدیدی که می‌خواهید تست کنید، قبل از آن باید پروفایل قبلی را پاک کنید ❌.


## توجه
این راهنما برای تنظیم تلفن همراه برای دسترسی به اینترنت از طریق اتصال 4G مناسب است. به یاد داشته باشید که اطلاعات APN و دیگر تنظیمات ممکن است برای هر شبکه مختلف یا دستگاه متفاوت تغییر کند



💞️ Feel free to support my endeavors through donations at:
   - Ethereum: 0xc177e861fD9a9F598236C7183e105b9CCec9cb3e
   - Bitcoin: bc1q3230gkphdk5qzsxtj079mz5w35svwrpwq6wh8c



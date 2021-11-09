# کد پستی ایران

کد پستی در ایران الگوریتمی برای اعتبارسنجی دقیق مثل اون چیزی که روی کد ملی هست رو نداره

در ایران کدپستی عددی ۱۰ رقمی‌ست که ۵ رقم اول نشانگر کد رهسپاری (مشخصه شهر مقصد) و ۵ رقم دوم بیانگر کد توزیع (مشخصه مکانی مقصد) است. در ایران از اعداد ۰ و ۲ به دلیل تشابه ظاهری به ترتیب با اعداد ۵ و ۳ استفاده نمی‌شود. کدپستی برای مشخص کردن یک آدرس پستی و به تبع آن مرتب کردن نامه‌های ارسالی وضع می‌شوند.
[لینک مرجع](https://fa.wikipedia.org/wiki/%DA%A9%D8%AF_%D9%BE%D8%B3%D8%AA%DB%8C)

اگر دنبال جزییات بیشتر هستید میتونید به این [لینک](http://m-star.blogfa.com/post/10) سر بزنید

اگر براتون جالبه که بدونید ۵ رقم اول چطور تقسیم بندی شدن میتونید به این [لینک](https://mobilebnk.com/code-posti/) یا این [لینک](https://it-office.ir/index.php/services/post/iran-postcode) سری بزنید

حالا اگر درحال کدنوشتن هستید و میخواید صحت کد پستی ایران رو بررسی کنید یک 
[کتابخونه](https://github.com/VahidN/DNTPersianUtils.Core) خوب هست که تقریبا اعتبارسنجی هر چیز ایرانی ای توشه

و مثل من پیور باز هستین و دنبال کتابخونه نیستید میتونید از regex زیر استفاده کنید:
```
\b(?!(\d)\1{3})[13-9]{4}[1346-9][013-9]{5}\b
```

و اگر کلا یه کدپستی دارید و میخواد صحت اش رو بسنجید میتونید وارد این [لینک](https://regex101.com/r/QRvRJt/3) بشید و کد پستی رو توی باکس تست کپی کنید اگر هایلایت شد یعنی درسته


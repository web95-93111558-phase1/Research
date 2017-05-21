<style>
.main-content {
    font-family: 'Scheherazade', Tahoma;
}
</style>
<p dir='rtl' > کاربران اینترنت در زمینه های مختلف در اینترنت گردش میکنند و ممکن است نخواهند تا برای مثال محیط کار با محیط شبکه اجتماعی شان مخلوط شود. Container ها در این موضوع به کاربر کمک میکند. این امکان در نسخه nigthy_50 مرورگر firefox  وجود دارد. زمانی که از container استفاده میکنیم وقتی tab های مختلف را باز میکنیم مانند حالت عادی عمل می کند جز اینکه هر tab فضای حافظه مرورگر مخصوص به خود را دارد. یعنی تنظیمات ، log_in_session ها و این نوع اطلاعات از یک container به container دیگر منتقل نمی شود. این امکان به کاربر کنترل بیشتری نسبت به داده های سایت می دهد.
></p>
<p dir='rtl' > 
این امکان کاربرد های متنوع و جذابی دارد مثلا کاربر می تواند همزمان از چند حساب با یک سایت کار کند حتی اگر سایت این امکان را ندهد. برای مثال می تواند همزان از حساب gmail شخصی و کاری همزمان استفاده کند. اگر از این امکان نمیخواستیم استفاده کنیم میبایست از مرور گر های مختلف استفاده کنیم یا اینکه از صفحه Private استفاده کنیم که این محدودیت استفاده حداکثر 2 صفحه را دارد. علاوه بر این وجود container باعث می شود تا از مورد پیگیری قرار گرفتن توسط سایت ها جلوگیری شود مثلا میتوان با این امکان باعث شد سرچ های گوگل مان به حساب gmail مان مرتبط نشود. کاربرد دیگر container ها این است که میتوان یک محیط موقت درست کرد تا بعد از انجام یک کار حذف شود. و کابرد دیگر آن این است که توسعه دهندگان وب میتوانند برای تست کردن سایت شان از این طریق با چندیدن Log_in مختلف وارد سایتشان شوند.

</p>
<p dir='rtl' > 
Origin ها با استفاده از ترکیب  scheme ، host و port تعریف می شوند. مرور گر ها می توانند تصمیم های امنیتی بر اساس origin ها بگیرند برای اینکه بتوان از این امکان استفاده کرد برای تفکیک کردن origin ها از یک کلید دیگر نیز استفاده می شود که مثلا برای این منظور در container ها از usercontextid استفاده می شود تا هر container ، origin مخصوص به خود را داشته باشد.اطلاعاتی که توسط  container ها جدا می شوند عبارتند از : کوکی ها ، local storage ، indexDB ، HTTP_data_catch ، origin_attribute . اطلاعاتی که توسط container ها هنوز جدا نمی شوند اما در اهداف این است که جدا شوند عبارتند از : history ، bookmarks  و اطلاعاتی که جدا نمی شوند و در اهداف نیز نیست که جدا شوند عبارتند از : Saved_Passwords ، Saved_Search ، Form_data . 
</p>
<p dir='rtl' >
از دیگر امکانات container این است که میتواند برای یک سایت به خصوص یک  container مخصوص بسازد به طوری که بتوان درآن container از ورود به سایت های دیگر جلوگیری کرد. به این شکل که اگر در آن container مخصوص خواسته باشیم به سایتی غیر از آن سایت به خصوص برویم پیغام هشدار بیاید که آیا مطمین هستید و یا اگر خواسته باشیم از container ای غیر از آن container به خصوص به آن سایت خاص برویم نیز پیغام هشدار بیاید. در صورت استفاده از container به این شکل میتوان امکانات بیشتری به کاربر بدهیم به این شکل که میتوان همه کوکی های مربوط به سایت های غیر از آن سایت به خصوص را بعد از هر نشست کاربر حذف کرد.
</p>

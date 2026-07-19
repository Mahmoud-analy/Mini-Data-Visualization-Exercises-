# 🍦 Ice Cream Sales vs Temperature

تقرير Power BI (`Miniviz_May_Week_2.pbix`) بيوضح علاقة مبيعات الآيس كريم بدرجة الحرارة.

## الشغل اللي اتعمل
- بناء **Scatter Chart** بالمحاور: `Temperature_F` (X) و `IceCreamSales` (Y)، وتقسيم البيانات حسب `WeatherType` (Series).
- تنسيق المحاور: خط Times New Roman، حجم 14، Bold.
- إضافة عنوان (Textbox) للصفحة مع خلفية لونها `#E6E7F2`.
- ضبط تخطيط الصفحة وحجم الكارت (Visual).

## البيانات
جدول **Ice Cream Sales**: `Temperature_F`, `IceCreamSales`, `WeatherType`.

## الاستنتاجات
- علاقة طردية قوية جدًا بين الحرارة والمبيعات (Correlation ≈ **0.99**).
- الأيام **Sunny** أعلى حرارة (~91°F) وأعلى مبيعات (~463)، تليها **Cloudy** (~72°F, ~268)، ثم **Rainy** الأقل (~62°F, ~191).
- الطقس المشمس يمثل غالبية الأيام (64 من 93 يوم).

## التشغيل
افتح الملف عبر [Power BI Desktop](https://powerbi.microsoft.com/desktop/).

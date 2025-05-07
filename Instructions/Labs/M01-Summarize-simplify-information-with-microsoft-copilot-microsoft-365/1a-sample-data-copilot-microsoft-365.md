# تدريب - تابع باستخدام بيانات العينة مع Microsoft 365 Copilot

خلال بقية الوحدة، سنقوم بصياغة المطالبات لـ Microsoft 365 Copilot التي تشير إلى هذه الملفات.
<ul dir='rtl'>
<li>
<a href="https://go.microsoft.com/fwlink/?linkid=2268826">Market Analysis Report for Mystic Spice Premium Chai Tea.docx</a>
</li>
<li>
<a href="https://go.microsoft.com/fwlink/?linkid=2268822">Contoso Chai Tea market trends 2023.xlsx</a>
</li>
<li>
<a href="https://go.microsoft.com/fwlink/?linkid=2269122">Contoso Chai Tea market trends 2023.docx</a>
</li>
<li>
<a href="https://go.microsoft.com/fwlink/?linkid=2268827">Market Trend Report- Protein shake.docx</a>
</li>
<li>
<a href="https://go.microsoft.com/fwlink/?linkid=2268768">Mystic Spice Premium Chai Market Analysis Presentation.pptx</a>
</li>
</ul>
<b>ملاحظة</b>: هذه هي الملفات التي سنشير إليها في جميع أنحاء الوحدة. ومع ذلك، بالنسبة لهذا النشاط العملي، سنبدأ بتحميل جميع الملفات إلى <b>OneDrive</b> للتأكد من إمكانية الوصول إليها من خلال مطالبات Copilot لاحقًا.

## تحميل الملفات إلى OneDrive

اتبع الخطوات أدناه لتحميل جميع الملفات المطلوبة إلى <b>OneDrive</b>:
<ol dir='rtl'>
<li>
سجّل الدخول إلى الجهاز الظاهري الذي يوفره لك موفر المستأجر باعتبارك حساب <b>المسؤول</b> المحلي باستخدام كلمة المرور <code>Pa55w.rd</code>.
</li>
<li>
في شريط مهام Windows، حدد <b>Microsoft Edge</b>.
</li>
<li>
في شريط العناوين، أدخِل <code>https://onedrive.live.com/login</code>.
</li>
<li>
ضمن <b>مرحبًا بك في Microsoft 365</b>، حدد <b>تسجيل الدخول</b>.
</li>
<li>
عند مطالبة <b>تسجيل الدخول</b>، أدخل <code>userx@yourtenant.onmicrosoft.com</code> (اسم المستخدم والمستأجر المقدم من قبل المستأجر الخاص بك) وحدّد <b>التالي</b>.
</li>

<p dir="rtl"><a href="https://github.com/MicrosoftLearning/MS-4005-Craft-effective-prompts-for-Microsoft-Copilot-for-Microsoft-365.ar-sa/blob/main/Instructions/Labs/media/lab_resources_password.png"><img src="https://github.com/MicrosoftLearning/MS-4005-Craft-effective-prompts-for-Microsoft-Copilot-for-Microsoft-365.ar-sa/blob/main/Instructions/Labs/media/lab_resources_password.png" alt="جزء مصدر لقطة الشاشة"> </a></p>

<li>
في شاشة <b>إدخال كلمة المرور</b>، أدخل كلمة المرور (المقدمة من قبل موفر المستأجر) لحساب المستخدم، ثم حدد <b>تسجيل الدخول</b>.
</li>
<li>
إذا طُلب منك <b>البقاء مسجلًا الدخول</b>، فحدد <b>عدم إظهار هذا مرة أخرى</b>، ثم <b>نعم</b>.
</li>
<li>
في <b>OneDrive</b>، في الزاوية العلوية اليسرى، حدد <b>+</b> (إضافة جديد) > <b>تحميل ملف</b>.
</li>

<p dir="rtl"><a href="https://github.com/MicrosoftLearning/MS-4005-Craft-effective-prompts-for-Microsoft-Copilot-for-Microsoft-365.ar-sa/blob/main/Instructions/Labs/media/add_new.png"><img src="https://github.com/MicrosoftLearning/MS-4005-Craft-effective-prompts-for-Microsoft-Copilot-for-Microsoft-365.ar-sa/blob/main/Instructions/Labs/media/add_new.png" alt="لقطة الشاشة الخاصة بإضافة ملف جديد"></a></p>


<li>
في <b>مستكشف الملفات</b>، حدد <b>هذا الحاسوب</b> > <b>القرص المحلي (C:)</b> وافتح المجلد <b>ResourceFiles</b>.
</li>
<li>
حدد جميع الملفات الموجودة داخل المجلد <b>ResourceFiles</b>، ثم حدد <b>فتح</b> لتحميلها إلى <b>OneDrive</b>.
</li>
<li>
عند اكتمال التحميل، يجب أن ترى <b>تم تحميل 29 عنصرًا إلى ملفاتي</b> في الجزء السفلي الأوسط من الشاشة.
</li>
<li>
اترك <b>Edge</b> مفتوحًا وانتقل إلى المهمة التالية.
</li>
</ol>
### ملفات مرجعية

عند الرجوع إلى الملفات من Copilot، قد تجد أنه لا يمكنك العثور على بعض الملفات من الاقتراحات المقدمة لك. يحدث هذا في بعض الأحيان لأن بعض التجارب مع Copilot تشير فقط إلى الملفات من قائمة "الأكثر استخدامًا مؤخرًا" (MRU)، بينما تتيح لك تجارب أخرى تصفح OneDrive للعثور على ملفك. إن إضافتها إلى هذه القائمة أمر سهل مثل فتحها في تطبيق Microsoft 365 المناسب.  بمجرد فتحها، يجب أن تظهر في قائمة MRU.

> [!IMPORTANT]
> سيعمل Microsoft 365 Copilot فقط مع الملفات المحفوظة في OneDrive. إذا تم تخزين الملفات محليًا على حاسوبك الشخصي، فستحتاج إلى نقلها إلى OneDrive لتنشيط Copilot.

مع تقدمك في الوحدة، ستتاح لك الفرصة لتجربة مطالبات أخرى مقابل هذه الملفات ويتم تشجيعك على القيام بذلك لاستكشاف وتعزيز مهاراتك في المطالبات.

# تبادل الأفكار والقوائم والتقارير الجديدة باستخدام Microsoft 365 Copilot Chat

يجمع Microsoft 365 Copilot Chat (Copilot Chat) بين قوة الذكاء الاصطناعي (AI) وبيانات العمل والتطبيقات لمساعدتك على إطلاق العنان للإبداع و الإنتاجية ورفع مستوى المهارات. وهي تعمل عبر تطبيقات ومحتوى متعددين، مما يمنحك قوة الذكاء الاصطناعي وي نفس الوقت أمان بيانات عملك. إن قدرتها على تجميع المعلومات وإنشاء أشياء من مصادر متعددة في وقت واحد تمكنك من تحقيق الأهداف والغايات الأوسع.

للمقارنة، تم تنسيق Copilot في تطبيقات Microsoft 365 المختلفة (مثل Word أو PowerPoint) خصيصًا لمساعدتك <b>داخل هذا التطبيق الواحد</b>. على سبيل المثال، تم تصميم Copilot في Word لمساعدتك على صياغة مستودة المحتوى وتحريره واستهلاكه بشكل أفضل. أما في PowerPoint، فهو موجود لمساعدتك في إنشاء عروض تقديمية أفضل. ولكن مع Copilot Chat، يمكننا جمع كل ذلك معًا في تجربة جديدة.

يمكنك الوصول إلى Copilot Chat بعدة طرق:

<ul dir='rtl'>
    <li>استخدم Copilot في إصدارات سطح المكتب والأجهزة المحمولة من Microsoft Teams. راجع <a href="https://support.microsoft.com/topic/open-microsoft-365-chat-in-teams-c6de0a62-4f9e-479d-b5f2-af036e342181">استخدام Copilot Chat في Teams</a></li>
    <li>يمكنك الوصول إلى Copilot Chat على Microsoft.com/Copilot. راجع <a href="https://support.microsoft.com/topic/use-microsoft-365-chat-at-microsoft365-com-or-in-the-microsoft-365-office-app-4a2538f9-962f-4c7c-a368-f6006bc13d6f">استخدام Copilot Chat على Microsoft365.com/copilot</a></li>
</ul>

<p dir="rtl"><a href="https://github.com/MicrosoftLearning/MS-4005-Craft-effective-prompts-for-Microsoft-Copilot-for-Microsoft-365.ar-sa/blob/main/Instructions/Labs/media/create_copilot-chat-experience-teams.png"><img src="https://github.com/MicrosoftLearning/MS-4005-Craft-effective-prompts-for-Microsoft-Copilot-for-Microsoft-365.ar-sa/blob/main/Instructions/Labs/media/create_copilot-chat-experience-teams.png" alt="لقطة شاشة لتجربة Copilot Chat في Microsoft Teams."></a></p>


## دعونا نبدأ في الصياغة

باستخدام <b>Contoso CipherGuard Product Specification.docx</b> من الوحدة السابقة، افتح Copilot Chat في Teams للعمل على المطالبة التالية.

> [!NOTE]
> مطالبة البدء:
>
> _إنشاء جدول أعمال الاجتماع._

في هذه المطالبة البسيطة، ستبدأ <b>بالهدف</b> الأساسي : _لإنشاء جدول أعمال الاجتماع_. ومع ذلك، لا توجد معلومات حول الغرض من الاجتماع أو هدفه.

| العنصر | مثال |
| :------ | :------- |
| <b>المطالبة الأساسية:</b> ابدأ <b>بهدف</b> | <b>_إنشاء جدول أعمال الاجتماع._</b> |
| <b>المطالبة الجيدة:</b> أضف <b>سياق</b> | إن إضافة <b>السياق</b> قد يساعد Copilot على فهم سبب دعوتك للاجتماع وما تريد مناقشته. _"...لاجتماع مع العميل لمدة ساعة، بما في ذلك أهداف المشروع، وبيان المهمة، وتاريخ الانتهاء المقرر."_ |
| <b>مطالبة أفضل:</b> حدد <b>المصدر(المصادر)</b> | إن إضافة <b>المصادر</b> قد يساعد Copilot في معرفة المكان الذي يجب البحث فيه عن معلومات محددة. _استخدم المعلومات من <b>/Contoso CipherGuard Product Specification.docx</b> وابحث عن العناصر المفتوحة والأسئلة التي لم تتم الإجابة عليها._ |
| <b>أفضل مطالبة:</b> عيّن <b>توقعات</b> واضحة | وأخيرًا، قد تساعد إضافة <b>التوقعات</b> Copilot في فهم كيفية كتابة المستند وتنسيقه. _يجب أن يكون جدول الأعمال على شكل جدول مع تخصيص الوقت، وتأكد من إعطاء المشاركين الفرصة لطرح الأسئلة في النهاية._ |

> [!NOTE]
> <b>المطالبة المصممة</b>:
>
> _أنشئ جدول أعمال لاجتماع العميل يستمر لمدة ساعة، بما في ذلك أهداف المشروع وبيان المهمة وتاريخ الانتهاء المقرر. استخدم المعلومات من <b>/Contoso CipherGuard Product Specification.docx</b> وابحث عن العناصر المفتوحة والأسئلة التي لم تتم الإجابة عليها. يجب أن يكون جدول الأعمال في شكل جدول مع تخصيصات زمنية، وتأكد من منح الأشخاص الفرصة لطرح الأسئلة في النهاية._

<p dir="rtl"><a href="https://github.com/MicrosoftLearning/MS-4005-Craft-effective-prompts-for-Microsoft-Copilot-for-Microsoft-365.ar-sa/blob/main/Instructions/Labs/media/create_copilot-chat-draft-agenda-teams.png"><img src="https://github.com/MicrosoftLearning/MS-4005-Craft-effective-prompts-for-Microsoft-Copilot-for-Microsoft-365.ar-sa/blob/main/Instructions/Labs/media/create_copilot-chat-draft-agenda-teams.png" alt="التقط لقطة شاشة لنتائج المطالبة المصممة خصيصًا مقابل مستند العينة باستخدام Copilot Chat في Teams."></a></p>


راجع جدول الأعمال وإجراء أي تعديلات أو تحسينات عليه، ثم أضفه إلى دعوة اجتماعك في Teams.

### المصادر المرجعية

كما هو الحال في المثال، إذا كنت تريد أن يقوم Copilot بإسناد العرض التقديمي الجديد من ملف أو اجتماع أو شخص (حتى لو كانوا الثلاثة)، يمكنك إخباره بالقيام بذلك. في نافذة المطالبة، ابدأ فقط بكتابة الشرطة المائلة للأمام "/" وستعرض لك نافذة منبثقة الاجتماعات أو الملفات أو الأشخاص الأخيرين للرجوع إليهم.

> [!IMPORTANT]
> يجب أن يكون لديك إذن للوصول إلى الملفات التي تشير إليها، سواء كانت موجودة في SharePoint أو OneDrive الخاص بمؤسستك ويمكن أن تكون ملفات Word أو Excel أو PowerPoint.

## استكشاف المزيد

فيما يلي بعض الاقتراحات لمطالبات أخرى قد ترغب في تجربتها. انسخها أو عدّلها لتناسب احتياجاتك.

<ul dir='rtl'>
    <li>ماذا حدث في آخر اجتماع لي؟</li>
    <li>متابعة الدردشات غير المقروءة.</li>
    <li>صغ رسالة تفيد بأن الأهداف والنتائج الرئيسية مستحقة في الأسبوع القادم.</li>
    <li>أخبر فريقي كيف قمنا بتحديث استراتيجية المنتج.</li>
    <li>تلخيص الدردشات ورسائل البريد الإلكتروني والمستندات حول تصعيد [العميل] الذي حدث الليلة الماضية.</li>
    <li>ما هو الحدث الرئيسي التالي على [مشروع]؟ هل هناك أي مخاطر؟ ساعدني في وضع قائمة ببعض الطرق المحتملة للتخفيف من حدتها.</li>
    <li>اكتب نظرة عامة على التخطيط في نمط [ملف] الذي يحتوي على المخطط الزمني من [ملف مختلف] ويدمج قائمة المشروع في البريد الإلكتروني من [شخص].</li>
</ul>


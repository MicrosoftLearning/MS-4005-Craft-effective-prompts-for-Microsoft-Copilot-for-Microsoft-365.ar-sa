# لخّص المعلومات حول موضوع ما باستخدام Microsoft 365 Copilot Chat

يجمع Microsoft 365 Copilot Chat (Copilot Chat) بين قوة الذكاء الاصطناعي (AI) وبيانات العمل والتطبيقات لمساعدتك على إطلاق العنان للإبداع و الإنتاجية ورفع مستوى المهارات. وهي تعمل عبر تطبيقات ومحتوى متعددين، مما يمنحك قوة الذكاء الاصطناعي وي نفس الوقت أمان بيانات عملك. إن قدرتها على تجميع المعلومات وإنشاء أشياء من مصادر متعددة في وقت واحد تمكنك من تحقيق الأهداف والغايات الأوسع.

للمقارنة، تم تنسيق Copilot في تطبيقات Microsoft 365 المختلفة (مثل Word أو PowerPoint) خصيصًا لمساعدتك <b>داخل هذا التطبيق الواحد</b>. على سبيل المثال، تم تصميم Copilot في Word لمساعدتك على صياغة مستودة المحتوى وتحريره واستهلاكه بشكل أفضل. أما في PowerPoint، فهو موجود لمساعدتك في إنشاء عروض تقديمية أفضل. ولكن مع Copilot Chat، يمكننا جمع كل ذلك معًا في تجربة جديدة.

يمكنك الوصول إلى Copilot Chat بعدة طرق:

<ul dir="rtl">
    <li>استخدم Copilot Chat في إصدارات سطح المكتب والهواتف المحمولة من Microsoft Teams. راجع <a href="https://support.microsoft.com/topic/open-microsoft-365-chat-in-teams-c6de0a62-4f9e-479d-b5f2-af036e342181">استخدام Copilot Chat في Teams</a></li>
    <li>يمكنك الوصول إلى Copilot Chat على Microsoft365.com/copilot. راجع <a href="https://support.microsoft.com/topic/use-microsoft-365-chat-at-microsoft365-com-or-in-the-microsoft-365-office-app-4a2538f9-962f-4c7c-a368-f6006bc13d6f">استخدام Copilot Chat على Microsoft.com/Copilot</a></li>
</ul>

<p dir="rtl"><a href="https://github.com/MicrosoftLearning/MS-4005-Craft-effective-prompts-for-Microsoft-Copilot-for-Microsoft-365.ar-sa/blob/main/Instructions/Labs/media/summarize_copilot-chat-experience-teams.png"><img src="https://github.com/MicrosoftLearning/MS-4005-Craft-effective-prompts-for-Microsoft-Copilot-for-Microsoft-365.ar-sa/blob/main/Instructions/Labs/media/summarize_copilot-chat-experience-teams.png" alt="لقطة شاشة لتجربة Copilot Chat في Teams."> </a></p>


## دعونا نبدأ في الصياغة

أولًا، نزّل الملفات التالية واحفظها في مجلد <b>OneDrive</b> وأضفها إلى قائمة MRU الخاصة بك:

<ul dir="rtl">
    <li><a href="https://go.microsoft.com/fwlink/?linkid=2268822">Contoso Chai Tea market trends 2023.xlsx</a></li>
    <li><a href="https://go.microsoft.com/fwlink/?linkid=2269122">Contoso Chai Tea market trends 2023.docx</a></li>
    <li><a href="https://go.microsoft.com/fwlink/?linkid=2268827">Market Trend Report- Protein shake.docx</a></li>
</ul>


افتح تطبيق Copilot Chat في Microsoft Teams واتبع الإرشادات التي تشير إلى الملفات أعلاه.

> [!NOTE]
> مطالبة البدء:
>
> _ابحث عن المعلومات وتجميعها حول مشروب Protein Plus الجديد من Contoso._

في هذه المطالبة البسيطة، ستبدأ <b>بالهدف</b> الأساسي: _لتلخيص المعلومات حول منتج جديد._ ومع ذلك، لا توجد معلومات حول سبب حاجتك إلى الملخص أو ما تبحث عنه.

<markdown-accessiblity-table data-catalyst=""><div dir="rtl"><table>
<thead>
<tr>
<th align="right">العنصر</th>
<th align="right">مثال</th>
</tr>
</thead>
<tbody>
<tr>
<td align="right"><b>المطالبة الأساسية:</b> ابدأ <b>بهدف</b></td>
<td align="right"><b>ابحث عن المعلومات وتجميعها حول مشروب Protein Plus الجديد من Contoso.</b></td>
</tr>
<tr>
<td align="right"><b>المطالبة الجيدة:</b> أضف <b>سياق</b></td>
<td align="right">قد يساعد إضافة <b>السياق</b> Copilot في فهم الغرض وتعديل الرد وفقًا لذلك. <em>"...لمراجعة أعمال ربع سنوية قادمة. نحتاج إلى ملخص تنفيذي، بالإضافة إلى تفاصيل حول حملة وسائل التواصل الاجتماعي والمنتجات المنافسة."</em></td>
</tr>
<tr>
<td align="right"><b>مطالبة أفضل:</b> حدد <b>المصدر(المصادر)</b></td>
<td align="right">قد تساعد إضافة <b>المصادر</b> Copilot في فهم المكان الذي يجب البحث فيه عن المعلومات وتوفير رد أكثر دقة. <em>"ابحث عن المعلومات في <b>/Market Analysis Report for Mystic Spice Premium Chai Tea.docx</b>، <b>/Contoso Chai Tea market trends 2023.xlsx</b>، و <b>/Market Trend Report - Protein shake.docx</b> لكتابة الملخص التنفيذي."</em></td>
</tr>
<tr>
<td align="right"><b>أفضل مطالبة:</b> عيّن <b>توقعات</b> واضحة</td>
<td align="right">وأخيرًا، قد تساعد إضافة <b>التوقعات</b> Copilot في فهم كيفية تنسيق الملخص ومستوى التفاصيل المطلوب. <em>يجب أن يبدو الملخص احترافيًا، مع نبرة متفائلة بشأن عوائق الإصدار لدينا. يجب أن يتضمن التحليل التنافسي أيضًا روابط للمنتجات ذات الصلة في جدول.</em></td>
</tr>
</tbody>
</table></div></markdown-accessiblity-table>

> [!NOTE]
> <b>المطالبة المصممة</b>:
>
> _ابحث عن معلومات حول مشروب Protein Plus الجديد من Contoso وجمّعها لمراجعة الأعمال ربع السنوية القادمة. نحتاج إلى ملخص تنفيذي، بالإضافة إلى تفاصيل حول الحملة الإعلانية على وسائل التواصل الاجتماعي والمنتجات المنافسة. ابحث عن المعلومات في <b>/Market Analysis Report for Mystic Spice Premium Chai Tea.docx</b> و <b>/Contoso Chai Tea market trends 2023.xlsx</b> و <b>/Market Trend Report - Protein shake.docx</b> لكتابة الملخص التنفيذي. يجب أن يبدو الملخص احترافيًا، مع نبرة أمل حول موانع الإصدار لدينا. وينبغي أن يتضمن التحليل التنافسي أيضا روابط بالمنتجات ذات الصلة في جدول._

<p dir="rtl"><a href="https://github.com/MicrosoftLearning/MS-4005-Craft-effective-prompts-for-Microsoft-Copilot-for-Microsoft-365.ar-sa/blob/main/Instructions/Labs/media/summarize_copilot-chat-results-teams.png"><img src="https://github.com/MicrosoftLearning/MS-4005-Craft-effective-prompts-for-Microsoft-Copilot-for-Microsoft-365.ar-sa/blob/main/Instructions/Labs/media/summarize_copilot-chat-results-teams.png" alt="لقطة شاشة لنتائج المطالبة المصممة باستخدام تجربة الدردشة Copilot في Teams."> </a></p>

<!-- ![لقطة شاشة لنتائج المطالبة المصممة باستخدام تجربة الدردشة Copilot في Teams. ](../media/summarize_copilot-chat-results-teams.png) -->

مع تحديد <b>الهدف</b> و<b>السياق</b> و<b>المصدر</b> و<b>التوقعات</b>، فإن Copilot لديه كل ما يحتاجه ليمنحك ردًا رائعًا.

## استكشاف المزيد

يمكنك أيضًا استخدام Copilot للحصول على ملخصات ومعرفة الأمور بسرعة. ويمكنه تجميع ملخصات سريعة للمشاريع والاجتماعات ورسائل البريد الإلكتروني والدردشات والمزيد. استخدمه لمعرفة ما يجب عليك فعله، أو الحصول على آخر التحديثات حول مشروع ما، أو العثور على الاتصالات الأخيرة من زميل أو مدير بسرعة.

وفيما يلي بعض الأمثلة الأخرى:

<ul dir="rtl">
    <li>في الأسبوع الماضي، شارك أحد الأشخاص مستندًا يحدد تواريخ التسليم الرئيسية للمشروع X. ما هي تلك التواريخ؟</li>
    <li>لخّص الرسائل التي تلقيتها من سام خلال الأسبوعين الماضيين. اذكر أي تفاصيل مهمة، مثل المهام المطلوبة ومواعيد الاستحقاق وعناصر العمل التي يتعين عليّ القيام بها.</li>
    <li>أدرج التطورات في منتج Z التي قد تكون ذات صلة بالمدير التنفيذي الذي يملك إطلاق المنتج، استنادًا إلى التعاون على مدار الأيام الخمسة الماضية.</li>
</ul>



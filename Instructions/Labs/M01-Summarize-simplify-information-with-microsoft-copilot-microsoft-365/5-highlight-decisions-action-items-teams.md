# تسليط الضوء على القرارات والإجراءات الرئيسية من اجتماعات Teams

يحسّن Copilot في Microsoft Teams التعاون ويساعدك في تحقيق أقصى استفادة من دردشات Teams واجتماعاته. لخّص ما تم إنجازه بسرعة، وحدّد المهام المتابعة، وأنشئ جداول الأعمال، واطرح الأسئلة من أجل عقد اجتماعات أكثر فعالية وتركيزًا. لخّص الفوائد الأساسية الرئيسية، وانظر إلى ما تم تفويته، وحدّد الأشخاص الرئيسيين المهمين في سلاسل الدردشة التي تمت إضافتك إليها. كل ذلك دون كسر تدفق المناقشة. Copilot متاح في الاجتماعات والمكالمات التالية:

<ul dir="rtl">
    <li>مكالمات فردية وجماعية</li>
    <li>اجتماعات فردية أو اجتماعات خاصة مجدولة</li>
    <li>مثيلات الاجتماعات أو تكراراتها في سلسلة</li>
    <li>اجتماعات القناة</li>
    <li>الاجتماع الآن</li>
</ul>

يستخدم Copilot في Teams دردشة Teams ومحتوى الاجتماع لإنشاء تحليلات واقتراحات قابلة للتنفيذ جنبًا إلى جنب مع أهم نقاط التفاعل على Teams. يدرك Copilot في Teams سياق أي شيء تفعله. على سبيل المثال، يمكنك الوصول إلى جزء Copilot في دردشة أو اجتماع أو مكالمة، طالما تم استيفاء بعض الشروط:

<ul dir="rtl">
    <li>أنه تم تشغيل كتابة الحديث أو التسجيل. يمكن لمنظم الاجتماع إعداد الاجتماع بحيث يعمل Copilot دون كتابة الحديث قبل الاجتماع.</li>
    <li>أن يكون الاجتماع أو المكالمة طويلًا بما يكفي ليقوم Copilot بالتحليل. إذا لم يكن هناك ما يكفي من الكلام المكتوب في الاجتماع حتى الآن، فإن Copilot يذكر أنه يحتاج إلى مزيد من المعلومات قبل الاستجابة للمطالبات.</li>
</ul>

أثناء اجتماع أو مكالمة، حدّد <b>Copilot</b> من عناصر التحكم في الاجتماع. إذا لم تكن خاصية كتابة الحديث قيد التشغيل بالفعل، فستتم مطالبتك بتشغيله.

<p dir="rtl"><a href="https://github.com/MicrosoftLearning/MS-4005-Craft-effective-prompts-for-Microsoft-Copilot-for-Microsoft-365.ar-sa/blob/main/Instructions/Labs/media/summarize_copilot-ribbon-teams.png"><img src="https://github.com/MicrosoftLearning/MS-4005-Craft-effective-prompts-for-Microsoft-Copilot-for-Microsoft-365.ar-sa/blob/main/Instructions/Labs/media/summarize_copilot-ribbon-teams.png" alt="لقطة شاشة لرمز Copilot في اجتماع Teams."> </a></p>



يظهر Copilot في لوحة على الجانب الأيمن من نافذة الاجتماع. بمجرد انتهاء الاجتماع، حدد الاجتماع في <b>تقويم Teams</b> الخاص بك. من هناك، حدد علامة التبويب <b>الملخص</b> في تفاصيل اجتماعك. يمكنك أيضًا الوصول إلى لوحة Copilot من ملخص الاجتماع لطرح الأسئلة حول الاجتماع.

<p dir="rtl"><a href="https://github.com/MicrosoftLearning/MS-4005-Craft-effective-prompts-for-Microsoft-Copilot-for-Microsoft-365.ar-sa/blob/main/Instructions/Labs/media/summarize_copilot-pane-teams.png"><img src="https://github.com/MicrosoftLearning/MS-4005-Craft-effective-prompts-for-Microsoft-Copilot-for-Microsoft-365.ar-sa/blob/main/Instructions/Labs/media/summarize_copilot-pane-teams.png" alt="لقطة شاشة للوحة دردشة Copilot في Teams عند فتحها لأول مرة."> </a></p>


## دعونا نبدأ في الصياغة

> [!NOTE]
> مطالبة البدء:
>
> _تلخيص اجتماع Teams هذا._

في هذه المطالبة البسيطة، ستبدأ <b>بالهدف</b> الأساسي: _لتلخيص اجتماع Teams._ ومع ذلك، لا توجد معلومات حول سبب الحاجة إلى تلخيص الاجتماع أو ما هو الغرض من هذا الملخص.

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
<td align="right"><b>تلخيص اجتماع Teams هذا.</b></td>
</tr>
<tr>
<td align="right"><b>المطالبة الجيدة:</b> أضف <b>سياق</b></td>
<td align="right">قد يساعد إضافة <b>السياق</b> Copilot في فهم الغرض وتعديل الرد وفقًا لذلك. <em>"لقد تأخرت عن الحضور وأحتاج إلى نظرة عامة موجزة على الجدول الزمني للمشروع."</em></td>
</tr>
<tr>
<td align="right"><b>مطالبة أفضل:</b> حدد <b>المصدر(المصادر)</b></td>
<td align="right">قد تساعد إضافة <b>المصادر</b> Copilot في فهم الجزء الذي يحتاج إلى تلخيص وتوفير رد أكثر دقة. <em>"هل اقترحت أديل فانس أي تغييرات؟"</em></td>
</tr>
<tr>
<td align="right"><b>أفضل مطالبة:</b> عيّن <b>توقعات</b> واضحة</td>
<td align="right">وأخيرًا، قد تساعد إضافة <b>التوقعات</b> Copilot في فهم كيفية تنسيق الملخص ومستوى التفاصيل المطلوب. <em>ضمّن الجدول الزمني للمشروع في جدول وأي تغييرات مقترحة من أديل.</em></td>
</tr>
</tbody>
</table></div></markdown-accessiblity-table>

> [!NOTE]
> <b>المطالبة المصممة</b>:
>
> _تلخيص اجتماع Teams هذا. لقد تأخرت عن الحضور وأحتاج إلى نظرة عامة موجزة على الخط الزمني للمشروع. هل اقترحت أديل فانس أي تغييرات؟ ضمّن الخط الزمني للمشروع في جدول وأي تغييرات مقترحة من أديل._

في هذه المطالبة، يتم توفير <b>الهدف</b> و<b>السياق</b> و<b>المصدر</b> و<b>التوقعات</b>، مما يمنح Copilot توجيهًا كافيًا لتوليد رد يلبي احتياجاتك.

## استكشاف المزيد

عند فتح <b>Copilot في Teams</b> لأول مرة، ستحصل على بعض النصائح لاستخدام Copilot والمطالبات المقترحة لمساعدتك في البدء. استخدم Copilot من أجل:

<ul dir="rtl">
    <li>سرد النقاط الرئيسية من [ملف]</li>
    <li>تلخيص اجتماعك الأخير</li>
    <li>تلخيص رسائل البريد الإلكتروني غير المقروءة من [هذا الشخص]</li>
</ul>


> [!IMPORTANT]
> يتوفر Copilot في Teams على Windows و Mac والويب و Android و iOS. يجب أن يكون لديك ترخيص Microsoft 365 و Microsoft 365 Copilot للوصول إلى Copilot في Teams. لمزيد من السيناريوهات حول كيفية استخدام Copilot في اجتماعات Teams، راجع [البدء في استخدام Copilot في اجتماعات Microsoft Teams](https://support.microsoft.com/office/get-started-with-copilot-in-microsoft-teams-meetings-0bf9dd3c-96f7-44e2-8bb8-790bedf066b1).

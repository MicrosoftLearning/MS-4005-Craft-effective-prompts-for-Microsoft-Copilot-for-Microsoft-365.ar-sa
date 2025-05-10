# اسأل عن اجتماعاتك ورسائلك باستخدام Microsoft 365 Copilot في Teams

تساعدك الاجتماعات والمكالمات في Copilot في Teams في التقاط عناصر الإجراءات أو وجهات النظر المختلفة حسب الموضوع أو الأسئلة التي لم يتم حلها. يمكنك حتى أن تطلب من Copilot أن يقدم لك ردًا كجدول، ما يؤدي إلى إنشاء جدول Markdown جاهز للنسخ والمشاركة.

يستخدم Copilot في Teams دردشة Teams ومحتوى الاجتماع لإنشاء تحليلات واقتراحات قابلة للتنفيذ جنبًا إلى جنب مع أهم نقاط التفاعل على Teams. يدرك Copilot في Teams سياق أي شيء تفعله. على سبيل المثال، يمكنك الوصول إلى جزء Copilot في دردشة أو اجتماع أو مكالمة، طالما تم استيفاء بعض الشروط:

<ul dir='rtl'>
<li>
أنه تم تشغيل كتابة الحديث أو التسجيل. يمكن لمنظم الاجتماع إعداد الاجتماع بحيث يعمل Copilot دون كتابة الحديث قبل الاجتماع.
</li>
<li>

أن يكون الاجتماع أو المكالمة طويلًا بما يكفي ليقوم Copilot بالتحليل. إذا لم يكن هناك ما يكفي من الكلام المكتوب في الاجتماع حتى الآن، فإن Copilot يذكر أنه يحتاج إلى مزيد من المعلومات قبل الاستجابة للمطالبات.
</li>
</ul>


## الوصول إلى Copilot أثناء اجتماع

<ol dir='rtl'>
<li>
أثناء اجتماع أو مكالمة، حدّد <b>Copilot</b> من عناصر التحكم في الاجتماع. إذا لم تكن خاصية كتابة الحديث قيد التشغيل بالفعل، فستتم مطالبتك بتشغيله.
<p dir="rtl"><a href="https://github.com/MicrosoftLearning/MS-4005-Craft-effective-prompts-for-Microsoft-Copilot-for-Microsoft-365.ar-sa/blob/main/Instructions/Labs/media/ask_copilot-ribbon-teams.png"><img src="https://github.com/MicrosoftLearning/MS-4005-Craft-effective-prompts-for-Microsoft-Copilot-for-Microsoft-365.ar-sa/blob/main/Instructions/Labs/media/ask_copilot-ribbon-teams.png" alt="لقطة شاشة لرمز Copilot في اجتماع Teams."> </a></p>

</li>
<li>
يظهر Copilot في لوحة على الجانب الأيمن من نافذة الاجتماع. بمجرد انتهاء الاجتماع، حدد الاجتماع في <b>تقويم Teams</b> الخاص بك. من هناك، حدد علامة التبويب <b>الملخص</b> في تفاصيل اجتماعك. يمكنك أيضًا الوصول إلى لوحة Copilot من ملخص الاجتماع لطرح الأسئلة حول الاجتماع.
<p dir="rtl"><a href="https://github.com/MicrosoftLearning/MS-4005-Craft-effective-prompts-for-Microsoft-Copilot-for-Microsoft-365.ar-sa/blob/main/Instructions/Labs/media/ask_copilot-pane-teams.png"><img src="https://github.com/MicrosoftLearning/MS-4005-Craft-effective-prompts-for-Microsoft-Copilot-for-Microsoft-365.ar-sa/blob/main/Instructions/Labs/media/ask_copilot-pane-teams.png" alt="لقطة شاشة للوحة دردشة Copilot في Teams عند فتحها لأول مرة."> </a></p>

</li>
</ol>

## البدء البسيط وإضافة التفاصيل

> [!NOTE]
> مطالبة البدء:
>
> _ما هي الأسئلة التي لم يتم الإجابة عليها في هذا الاجتماع؟_

في هذه المطالبة البسيطة، ستبدأ <b>بالهدف</b> الأساسي: _لتحديد أي أسئلة مفتوحة لم يتم حلها أثناء الاجتماع_. ومع ذلك، لا توجد معلومات كثيرة جدًا حول الطلب أو الاجتماع.

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
<td align="right"><b>ما هي الأسئلة التي لم يتم الإجابة عليها في هذا الاجتماع؟</b></td>
</tr>
<tr>
<td align="right"><b>المطالبة الجيدة:</b> أضف <b>سياق</b></td>
<td align="right">قد يساعد إضافة <b>السياق</b> Copilot في فهم الغرض وتعديل الرد وفقًا لذلك. <em>"...في اجتماع العميل بخصوص مقترح المشروع الجديد."</em></td>
</tr>
<tr>
<td align="right"><b>مطالبة أفضل:</b> حدد <b>المصدر(المصادر)</b></td>
<td align="right">قد تساعد إضافة <b>المصادر</b> Copilot في فهم الاجتماع أو جزء الاجتماع الذي يحتاج إلى البحث، ولكن في هذه الحالة يتم افتراض <b>المصدر/</b> بالفعل. <em>"في اجتماع العميل؟"</em></td>
</tr>
<tr>
<td align="right"><b>أفضل مطالبة:</b> عيّن <b>توقعات</b> واضحة</td>
<td align="right">وأخيرًا، قد تساعد إضافة <b>التوقعات</b> برنامج Copilot في فهم ما يجب فعله بالمعلومات التي عثر عليها. <em>يرجى تحديد أي أسئلة أو مخاوف طُرحت ولم تتم معالجتها في الاجتماع السابق. يرجى تقديم اقتراحات لمعالجة هذه الأسئلة والمخاوف في الاجتماع القادم.</em></td>
</tr>
</tbody>
</table></div></markdown-accessiblity-table>

> [!NOTE]
> <b>المطالبة المصممة</b>:
>
> _ما هي الأسئلة التي لم يتم الإجابة عليها في اجتماع العميل بخصوص اقتراح المشروع الجديد؟ يرجى تحديد أي أسئلة أو مخاوف تم طرحها ولكن لم يتم تناولها في الاجتماع الأخير. يرجى تقديم اقتراحات لمعالجة هذه الأسئلة والمخاوف في الاجتماع التالي._

في هذه المطالبة، يتم توفير <b>الهدف</b> و<b>السياق</b> و<b>المصدر</b> و<b>التوقعات</b>، مما يمنح Copilot توجيهًا كافيًا لتوليد رد يلبي احتياجاتك.

## استكشاف المزيد

عند فتح <b>Copilot في Teams</b> لأول مرة، ستحصل على بعض النصائح لاستخدام Copilot والمطالبات المقترحة لمساعدتك في البدء. من خلال معالجة نصوص الاجتماع والدردشة، فإنه يولّد ردودًا للمطالبات مثل:
<ul dir='rtl'>
<li>
ما هي الأسئلة التي لم يتم الإجابة عليها في هذا الاجتماع؟
</li>
<li>
ما هي آراء أعضاء الفريق حول هذه الحملة الإعلانية؟
</li>
<li>
إنشاء جدول الإيجابيات والسلبيات لهذه الحملة الإعلانية.
</li>
</ul>

لمزيد من السيناريوهات حول كيفية استخدام Copilot في اجتماعات Teams، راجع [البدء في استخدام Copilot في اجتماعات Microsoft Teams](https://support.microsoft.com/office/get-started-with-copilot-in-microsoft-teams-meetings-0bf9dd3c-96f7-44e2-8bb8-790bedf066b1).

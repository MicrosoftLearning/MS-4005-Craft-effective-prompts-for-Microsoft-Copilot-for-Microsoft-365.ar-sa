# تحليل الجداول والعمل عليها باستخدام Microsoft 365 Copilot في Excel

إذا لم تكن متأكدًا من كيفية كتابة معادلة لعمود جديد، فباستطاعة Microsoft 365 Copilot إضافة أعمدة جديدة بسرعة باستخدام معادلات استنادًا إلى بياناتك.

1. مع تنسيق بياناتك كجدول، حدد زر **Copilot** في الشريط.

1. حدد **إضافة أعمدة معادلات** أو **اعرض اقتراحات لأعمدة معادلات**. يمكنك أيضًا وصف الأعمدة التي تريد إضافتها بكتابتها بعباراتك الخاصة.

1. يقدّم Copilot اقتراحات المعادلات مع شرح حول كيفية عمل كل معادلة. اعرض الشرح عن طريق تحديد **شرح المعادلة**.

1. حدد إدراج عمود لإضافة عمود المعادلة إلى الجدول.

> [!IMPORTANT]
> كما هو الحال مع أي محتوى تم إنشاؤه بواسطة الذكاء الاصطناعي، من المهم مراجعة وتحرير والتحقق من أي شيء ينشئه Copilot لك.

## دعونا نبدأ في الصياغة

أولًا، نزّل **_[Fabrikam Q1 marketing campaigns.xlsx](https://go.microsoft.com/fwlink/?linkid=2269124)_** واحفظ الملف في **مجلد OneDrive** إذا لم تكن قد فعلت ذلك بعد.

افتح جدول البيانات في برنامج Excel ثم افتح جزء **Copilot** من خلال تحديد أيقونة Copilot في علامة التبويب **الصفحة الرئيسية** على الشريط. أدخل التعليمات أدناه واتبعها.

> [!NOTE]
> مطالبة البدء:
>
> _اقتراح عمود صيغة._

في هذا الطلب البسيط، تبدأ بالهدف الأساسي **الهدف**: _إنشاء عمود جديد باستخدام صيغة_. ومع ذلك، لا توجد تفاصيل كافية لتحديد ما يجب أن تحسبه الصيغة.  

| العنصر | مثال |
| :------ | :------- |
| **المطالبة الأساسية:** ابدأ **بهدف** | **_اقتراح عمود صيغة._** |
| **المطالبة الجيدة:** أضف **سياق** | تساعد إضافة **السياق** Copilot على فهم ما يجب أن تحسبه الصيغة. _"...للعمود J لتحديد نسبة التفاعل لكل حملة إعلانية."_ |
| **مطالبة أفضل:** حدد **المصدر(المصادر)** | **المصدر** لهذه المطالبة هو الأعمدة المحددة المطلوبة للحساب. _"...باستخدام القيم من "المستخدمين المتفاعلين" و"إجمالي المستخدمين المستهدفين"."_ |
| **أفضل مطالبة:** عيّن **توقعات** واضحة | تساعد إضافة **التوقعات** برنامج Copilot على هيكلة الصيغة بشكل صحيح. _تأكد من أن الصيغة تقسم "المستخدمين المتفاعلين" على "إجمالي المستخدمين المستهدفين" وتنسيق النتيجة كنسبة مئوية._ |

> [!NOTE]  
> **المطالبة المصممة**:  
>
> _اقترح صيغةً للعمود J لحساب نسبة التفاعل لكل حملة. استخدم القيم من "المستخدمون المتفاعلون" و"إجمالي المستخدمين المستهدفين". تأكد من أن الصيغة تقسم "المستخدمين المتفاعلين" على "إجمالي المستخدمين المستهدفين" وتُنسّق النتيجة كنسبة مئوية._  

![لقطة شاشة لنتائج المطالبة المصممة باستخدام Copilot في Excel.](../media/ask_copilot-explain-formula-results-excel.png)

يحتوي برنامج Copilot على كل المعلومات التي يحتاجها ليمنحك ردًا قويًا، وذلك بفضل **الهدف** و**السياق** و**المصدر** و**التوقعات** في هذه المطالبة.

## استكشاف المزيد

استخدم هذه المطالبات كنقطة بداية. انسخها وعدلها لتناسب احتياجاتك.

- احسب التكلفة الإجمالية لكل منتج في عمود جديد.

- أضف عمودًا يحسب إجمالي الربح لكل حملة تسويقية في عام 2022.

- أضف عمودًا يحسب عدد الأيام بعد حدث إطلاق المنتج.

لمزيد من المعلومات، راجع [إنشاء أعمدة الصيغة باستخدام Copilot في Excel](https://support.microsoft.com/office/generate-formula-columns-with-copilot-in-excel-d866d926-9791-4e5f-be2a-c6dd9e587a47).

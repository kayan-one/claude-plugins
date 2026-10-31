# إضافات كيان لـ Claude

إضافات لـClaude من **منصة كيان للأعمال (Kayan One)**. بتخلي Claude يشتغل على بيانات شركتك في المنصة، بالعربي، وبنفس صلاحياتك فيها.

## الإضافات
| الإضافة | بتعمل إيه |
|---|---|
| [مبيعات كيان](plugins/kayan-sales) | تقرير الصبح، وتحضير مكالمة العميل، ورسالة المتابعة، ومراجعة الصفقات والفرص، والتحصيل وأعمار الديون، وتقرير المدير الأسبوعي |

## التثبيت
**في Claude Code:**
```
/plugin marketplace add kayan-one/claude-plugins
/plugin install kayan-sales@kayan-one
```
أو بخطوة واحدة:
```
/plugin install kayan-sales --marketplace kayan-one/claude-plugins
```

**في claude.ai:** من قسم الإضافات (Plugins)، ضيف السوق `kayan-one/claude-plugins` وثبّت «kayan-sales». أو اطلب من مسؤول حساب شركتك يضيفه للمؤسسة.

أول مرة Claude هيطلب منك تسجّل دخول بحساب كيان (`https://app.kayan-one.com/mcp`).

## الأمان
- كل الأدوات قراءة بس؛ الإضافة لا تسجل ولا تعدّل أي قيد أو فاتورة.
- Claude بيشوف اللي صلاحيتك في المنصة تسمح بيه بس، والمندوب يشوف عملاءه.
- الريبو ده فيه ملفات تعليمات الإضافات بس، من غير أي كود أو بيانات من المنصة.

محتاج مساعدة في الإعداد؟ [kayan-one.com](https://kayan-one.com) · support@kayan-one.com

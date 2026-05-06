# سياسة الخصوصية — احلامي AI / مفسّر الأحلام

**آخر تحديث: أبريل 2026**

---

## نظرة عامة

تطبيق **احلامي AI** ("التطبيق") هو تطبيق لتفسير الأحلام وفق المنظور الإسلامي، مدعوم بتقنيات الذكاء الاصطناعي. توضح هذه السياسة أنواع البيانات الشخصية التي نقوم بجمعها، وكيفية استخدامها، ومدة الاحتفاظ بها، وحقوقك كمستخدم.

---

## البيانات التي نقوم بجمعها

### البيانات المخزنة فقط على جهازك

يتم تخزين البيانات التالية محليًا على جهازك ولا يتم إرسالها إلى خوادمنا مطلقًا:

- **الاسم والعمر** — يتم إدخالهما أثناء الإعداد الأولي، ويُستخدمان فقط لتخصيص نتائج التفسير.
- **سجل الأحلام** — يتم حفظ جميع الأحلام وتفسيراتها محليًا باستخدام إطار عمل SwiftData الخاص بشركة Apple، ولا يمكننا الوصول إليها.
- **إعدادات التطبيق** — مثل اللغة، الدولة، المفسّر المفضل، ورصيد الاستخدام، ويتم حفظها محليًا عبر UserDefaults.

---

### البيانات التي تتم معالجتها عبر أطراف خارجية

#### OpenAI (تفسير الأحلام)
- يتم إرسال نص الحلم إلى واجهة برمجة التطبيقات الخاصة بـ OpenAI لتوليد التفسير، دون تضمين الاسم أو العمر أو أي معرّفات للجهاز.
- قد تحتفظ OpenAI بالبيانات لمدة تصل إلى 30 يومًا لأغراض مراقبة إساءة الاستخدام، ثم يتم حذفها.
- لا تُستخدم هذه البيانات لتدريب النماذج بشكل افتراضي.
- سياسة الخصوصية: https://openai.com/privacy

#### Google AdMob (الإعلانات)
- قد يقوم AdMob بجمع معرّف الإعلانات الخاص بجهازك (IDFA) في حال منحت الإذن عبر ميزة الشفافية في تتبع التطبيقات (ATT).
- في حال رفض التتبع، ستستمر الإعلانات بالظهور ولكن دون تخصيص.
- لن تتأثر وظائف التطبيق.
- سياسة الخصوصية: https://policies.google.com/privacy

#### Apple StoreKit (المشتريات والاشتراكات داخل التطبيق)
- تتم جميع عمليات الشراء والاشتراك بالكامل عبر Apple.
- نستلم فقط تأكيد إتمام العملية، ولا نقوم باستلام أو تخزين معلومات الدفع.
- تتم إدارة الاشتراكات وفق شروط Apple.
- سياسة الخصوصية: https://www.apple.com/legal/privacy

---

## البيانات التي لا نقوم بجمعها

- لا نقوم بجمع عنوان بريدك الإلكتروني أو إنشاء حسابات مستخدمين.
- لا نقوم بتخزين أحلامك أو بياناتك الشخصية على أي خادم.
- لا نقوم ببيع أو تأجير أو مشاركة بياناتك الشخصية مع أطراف ثالثة لأغراض تسويقية.
- لا نستخدم أدوات تحليل خارجية أو أنظمة تتبع الأعطال خارج ما توفره Apple بشكل مدمج.

---

## الاحتفاظ بالبيانات

| نوع البيانات | مكان التخزين | مدة الاحتفاظ |
|-------------|--------------|---------------|
| الاسم، العمر، الإعدادات | جهازك (UserDefaults) | حتى حذف التطبيق |
| سجل الأحلام | جهازك (SwiftData) | حتى الحذف من داخل التطبيق أو إزالته |
| نص الحلم المرسل إلى OpenAI | خوادم OpenAI | حتى 30 يومًا |
| سجلات الشراء | خوادم Apple | وفق سياسات Apple |
| معرّفات الإعلانات (إن تم السماح) | AdMob | وفق سياسات Google |

---

## الشفافية في تتبع التطبيقات (ATT)

عند تشغيل التطبيق لأول مرة، سيُطلب منك الإذن بالتتبع لأغراض الإعلانات عبر نظام Apple:

- **السماح** — عرض إعلانات مخصصة وفق اهتماماتك.
- **الرفض** — عرض إعلانات غير مخصصة، مع بقاء جميع ميزات التطبيق متاحة.

يمكنك تعديل الإعداد في أي وقت من خلال:
**الإعدادات → الخصوصية والأمان → التتبع → احلامي AI**

---

## المشتريات والاشتراكات داخل التطبيق

يوفر التطبيق حزم أرصدة لمرة واحدة واشتراكًا شهريًا متجددًا تلقائيًا ("غير محدود").

- تتم جميع العمليات عبر Apple.
- يتم تجديد الاشتراك تلقائيًا ما لم يتم إلغاؤه قبل 24 ساعة من نهاية الفترة الحالية.
- يمكن إدارة الاشتراك أو إلغاؤه من:
**App Store → حسابك → الاشتراكات**

---

## حقوقك

### البيانات على جهازك
يمكنك حذف جميع البيانات المحلية في أي وقت:
- **الإعدادات → البيانات → حذف جميع الأحلام المحفوظة**
- أو عبر حذف التطبيق بالكامل

### البيانات لدى الأطراف الخارجية
لممارسة حقوقك (الوصول، التصحيح، الحذف)، يُرجى الرجوع إلى سياسات الخصوصية الخاصة بـ OpenAI وGoogle.

### الحقوق وفق القوانين (مثل GDPR)
إذا كنت ضمن نطاق الاتحاد الأوروبي أو أي منطقة تطبق قوانين حماية البيانات، فقد تتمتع بحقوق مثل:
- الوصول إلى بياناتك
- تصحيحها
- حذفها
- نقلها

يمكنك التواصل معنا عبر البريد أدناه لممارسة هذه الحقوق.

---

## خصوصية الأطفال

التطبيق مخصص للمستخدمين بعمر 4 سنوات فما فوق. لا نقوم عن قصد بجمع بيانات شخصية للأطفال دون 13 عامًا. في حال وجود ذلك، يرجى التواصل معنا لاتخاذ الإجراءات اللازمة.

---

## التعديلات على السياسة

قد نقوم بتحديث هذه السياسة من وقت لآخر. سيتم إعلام المستخدمين بأي تغييرات جوهرية من خلال تحديث تاريخ "آخر تحديث". استمرار استخدام التطبيق بعد التعديلات يعني الموافقة عليها.

---

## التواصل

لأي استفسارات أو ملاحظات بخصوص هذه السياسة:

**البريد الإلكتروني:** info@reef-q.iq

---

*تم تحديث هذه السياسة في أبريل 2026.*






# Privacy Policy — احلامي AI / Dream Interpreter

**Last updated: April 2026**

---

## Overview

احلامي AI ("the App") is an Islamic dream interpretation app powered by artificial intelligence. This policy explains what personal data we collect, how we use it, how long we keep it, and your rights as a user.

---

## Data We Collect

### Data stored only on your device

The following data is stored locally on your device and is never transmitted to our servers:

- **Name and age** — entered during onboarding, used solely to personalise AI interpretations.
- **Dream history** — all dreams and their interpretations are saved locally using Apple's SwiftData framework. We do not have access to your dreams.
- **App settings** — language, country, preferred scholar, and credit balance. Stored locally via UserDefaults.

### Data processed by third-party services

**OpenAI (dream interpretation)**
- The text of your dream is sent to OpenAI's API to generate an interpretation. No name, age, or device identifier is included in this request.
- OpenAI may retain API inputs for up to 30 days for abuse monitoring purposes, after which they are deleted. They do not use API data to train their models by default.
- OpenAI's privacy policy: https://openai.com/privacy

**Google AdMob (advertising)**
- AdMob may collect your device's advertising identifier (IDFA) if you grant permission via the App Tracking Transparency (ATT) prompt.
- If you deny tracking, AdMob will still display ads but they will not be personalised. App functionality is not affected.
- Google's privacy policy: https://policies.google.com/privacy

**Apple StoreKit (in-app purchases & subscriptions)**
- All purchase and subscription transactions are processed entirely by Apple. We only receive a confirmation that a transaction occurred; we do not receive or store payment card information.
- Subscription billing is managed by Apple and governed by Apple's Terms of Sale.
- Apple's privacy policy: https://www.apple.com/legal/privacy

---

## Data We Do NOT Collect

- We do not collect your email address or create user accounts.
- We do not store your dreams or personal information on any server.
- We do not sell, rent, or share your personal data with third parties for marketing purposes.
- We do not use third-party analytics SDKs or crash reporting tools beyond what Apple provides natively.

---

## Data Retention

| Data | Where stored | Retention |
|------|-------------|-----------|
| Name, age, settings | Your device (UserDefaults) | Until you delete the app |
| Dream history | Your device (SwiftData) | Until you delete them in-app or uninstall |
| Dream text sent to OpenAI | OpenAI servers | Up to 30 days (OpenAI policy) |
| Purchase records | Apple servers | Governed by Apple's policies |
| Ad identifiers (if permitted) | AdMob | Governed by Google's policies |

---

## App Tracking Transparency (ATT)

On first launch, the App will ask for permission to track you for advertising purposes via Apple's App Tracking Transparency framework. This is used by Google AdMob to show personalised ads. You can:

- **Allow** — ads will be personalised based on your interests.
- **Deny** — ads will still appear but will not be personalised. All app features remain fully accessible.

You can change this permission at any time: **Settings → Privacy & Security → Tracking → احلامي AI**

---

## In-App Purchases and Subscriptions

The App offers one-time credit packs and an auto-renewable monthly subscription ("Unlimited"). Purchases are processed by Apple and subject to Apple's Terms of Sale. We do not store any payment information.

- Auto-renewable subscriptions will automatically renew unless cancelled at least 24 hours before the end of the current billing period.
- You can manage or cancel your subscription at any time: **App Store → Your Account → Subscriptions**

---

## Your Rights

**Data on your device:** You can delete all locally stored data at any time:
- **Settings → Data → Delete All Saved Dreams** removes all dream history.
- Uninstalling the App removes all locally stored data from your device.

**Data held by third parties:** To exercise rights (access, correction, deletion) over data processed by OpenAI or Google, please refer to their respective privacy policies linked above.

**GDPR / regional rights:** If you are located in the European Economic Area or another jurisdiction with applicable data protection laws, you may have rights including access to your data, correction of inaccuracies, erasure, and data portability. Contact us at the address below to exercise these rights.

---

## Children's Privacy

This App is rated for users aged 4 and above. We do not knowingly collect personal information from children under 13. If you believe a child has provided personal information through the App, please contact us and we will take steps to delete it.

---

## Changes to This Policy

We may update this policy from time to time. We will notify users of material changes by updating the "Last updated" date above. Continued use of the App after changes constitutes acceptance of the revised policy.

---

## Contact

If you have questions or concerns about this privacy policy or your data, please contact:

**Email:** info@reef-q.iq

---

*This privacy policy was last updated in April 2026.*

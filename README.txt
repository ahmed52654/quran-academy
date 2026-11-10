تطبيق أكاديمية القرآن بتل حوين
==============================
الملفات: index.html + manifest.webmanifest + sw.js + مجلد icons

الرفع على GitHub Pages:
1) أنشئ مستودعاً عاماً (Public) جديداً على github.com، مثلاً باسم: quran-academy
2) Add file ← Upload files ← اسحب كل الملفات ومجلد icons كما هي ← Commit changes
3) Settings ← Pages ← Source: Deploy from a branch ← Branch: main و /(root) ← Save
4) بعد دقيقة أو دقيقتين يظهر الرابط: https://اسم-حسابك.github.io/quran-academy/

لو رفعت النسخة على نفس المستودع القديم: غيّر رقم الإصدار في أول sw.js (quran-academy-v1 ← quran-academy-v2) عند كل تحديث حتى يصل للمستخدمين.

الحسابات (Firebase - مشروع akadamiat-alquran):
- كل مستخدم ينشئ حسابه باسم مستخدم وكلمة مرور (٦ أحرف على الأقل)، ويدخل به من أي جوال.
- لو نسي مستخدم كلمة المرور: من Firebase ← Authentication ← Users، ابحث عن اسمه (يظهر بالشكل username@akadamiat-alquran.app) واحذفه، فيقدر يسجّل من جديد بنفس الاسم.
- عدد المستخدمين يظهر لك في نفس الصفحة.

صوت الأذان:
- ارفع ملف الأذان داخل مجلد audio باسم adhan.mp3 (ولأذان الفجر adhan-fajr.mp3 اختياري).
- لو لم يوجد الملف، يشغّل التطبيق نغمة قصيرة بدلاً منه.

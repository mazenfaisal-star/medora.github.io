MEDORA — نسخة محدثة للنشر على GitHub Pages

الملفات الموجودة في جذر الحزمة:
- index.html: الصفحة الرئيسية؛ تظهر حتى قسم العناصر المحفوظة فقط.
- topic.html: نفس تطبيق Medora ويعرض صفحة مستقلة حسب ?q=... عند البحث.
- supabase-config.js: ملف إعداد المصادقة؛ يحتاج إلى بيانات مشروعك قبل تفعيل تسجيل الدخول الحقيقي.
- ATTRIBUTION.txt: نسب المصادر والتراخيص.

النشر:
1. ارفع محتويات هذا المجلد نفسها إلى جذر مستودع GitHub، ولا ترفع المجلد الأب كمجلد فرعي.
2. من Settings > Pages اختر Deploy from a branch، ثم main و /(root).
3. تأكد أن index.html وtopic.html بجوار بعضهما.

التغييرات في هذه النسخة:
- الصفحة الرئيسية مقتصرة على مساحة البحث والوصول السريع والعناصر المحفوظة.
- صفحة العضو تعرض مجسمه أولًا، ثم قائمة الأجزاء القابلة للفتح كصفحات مستقلة، ثم شرح العضو والمراجع.
- صفحة الجزء تعرض مجسمًا توضيحيًا ثلاثي الأبعاد مستقلًا أولًا، ثم المعلومات التفصيلية، ثم المراجع. بعض مجسمات الأجزاء مبسطة وليست نموذجًا تشريحيًا دقيق القياس.
- تحسين تباين الألوان في الوضع الداكن.
- شريط ثابت أسفل الشاشة يحمل: One Platform. Every Knowledge
- قسم الكيمياء يعرض أمثلة جزيئية تعليمية وبيانات التحقق؛ لا يتضمن توجيهًا لاختيار منتج دوائي أو جرعات أو قائمة علامات تجارية.

ملاحظات:
- نماذج 3D تحتاج إلى اتصال إنترنت وتحميل مكتبات خارجية.
- تسجيل الدخول والمزامنة بين الأجهزة لا يعملان قبل إعداد Supabase وربط قاعدة البيانات.
- محتوى Medora تعليمي وليس بديلًا عن التشخيص أو المشورة الطبية.
- صفحة المخيخ تستخدم الآن عارض Sketchfab المضمّن للنموذج “Cerebellum” بواسطة anajd، مع إبقاء اسم صاحب النموذج ورابطه. يتطلب العارض اتصالًا بالإنترنت، وقد تمنع بعض إعدادات الخصوصية أو حجب المحتوى تحميله.


تحديث نموذج المخ الكامل:
- تم استبدال مجسم المخ الكامل فقط بعارض Sketchfab: Plastinated Human Brain بواسطة UBC Medicine - Educational Media.
- نموذج المخيخ المستقل السابق لم يتغير.
- عارض Sketchfab داخل iframe يسمح بالتدوير والتكبير من داخل المشغل. لا تستطيع الصفحة الأم قراءة اسم المجسم المضغوط عليه مباشرة بسبب عزل iframe؛ اختيار الفصوص ما زال يتم من قائمة أجزاء المخ الجانبية.


تأكيد توزيع نماذج المخ: نموذج Plastinated Human Brain (Sketchfab ID 2df234ff65b0483fb5b5e15e40efa65d) مخصص للمخ الكامل فقط. نموذج Cerebellum (Sketchfab ID 3a4e017a202a4928b666371d075d0e21) مخصص للمخيخ فقط ويظل منفصلًا في صفحة المخيخ. البحث عن «المخ» يفتح صفحة مستقلة بها نموذج المخ الكامل وقائمة أجزائه، بينما البحث عن «المخيخ» يفتح صفحة المخيخ المستقلة. نماذج القلب والرئتين لم تُستبدل بهذا النموذج.


Male reproductive system content
- The user's Ebers Sketchfab whole-system model is unchanged.
- The existing testis / seminiferous-tubule model is unchanged.
- Separate individual-part 3D models now cover prostate, seminal vesicles, epididymis, vas deferens, corpora cavernosa, corpus spongiosum, glans, urethra and a penis composite; Anatomio provides separate right/left ejaculatory-duct viewers; Body Atlas provides focused scrotum and bulbourethral-gland viewers.
- No verified standalone 3D model for the spermatic cord alone is currently used. A combined model that includes testes was intentionally excluded.
- See ATTRIBUTION.txt for source, licence and embed credits. Body Atlas models are simplified learning illustrations, not medical-grade scans. External viewers require internet access.

# FC Sidekick for Windows

Current version: **0.2.19**. Download the [latest ZIP package](https://github.com/realtrx9/fcsidekick-releases/releases/latest), extract the whole package, then run `Start FC Sidekick.cmd` from the extracted folder. Keep the `runtime`, `scripts`, and `web` folders beside the launcher.

للمستخدم الجديد: حمّل [الإصدار 0.2.19](https://github.com/realtrx9/fcsidekick-releases/releases/tag/v0.2.19)، وفك ضغط حزمة ZIP كاملة، ثم شغّل `Start FC Sidekick.cmd` من داخل المجلد. ملف التشغيل وحده يحتاج بقية ملفات البرنامج الموجودة في الحزمة.

لمن لديه الإصدار 0.2.14 أو 0.2.15: أغلق البرنامج، وفك حزمة 0.2.19 فوق مجلد البرنامج الحالي مع استبدال الملفات، ولا تحذف مجلد `private`. الخطأ في هذين الإصدارين يمنع زر التحديث من بدء التنزيل. بعد هذه الخطوة سيعمل الزر للتحديثات القادمة.

`latest.json` is the public update manifest used by the in-app **تحديث البرنامج** button.

The app also downloads JSON challenge groups from [`challenges/`](challenges) when users click the same button. To add a challenge for everyone, put a validated JSON group file in that directory. The app has a prompt copy button under **أضف التحديات داخل البرنامج** to help create the file from formation and requirement screenshots. Review the resulting JSON against the game before publishing.

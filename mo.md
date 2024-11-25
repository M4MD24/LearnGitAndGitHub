<div dir="rtl">

# أوامر Git مع عناوين مختصرة

## تكوين المستخدم

- **تعيين اسم المستخدم**: `git config --global user.name your-username`
- **تعيين البريد الإلكتروني**: `git config --global user.email your-email`
- **عرض اسم المستخدم**: `git config --global user.name`
- **عرض البريد الإلكتروني**: `git config --global user.email`

## إدارة الملفات

- **عرض الملفات**: `ls`
- **عرض الملفات المخفية**: `ls -Force`

## إدارة الالتزامات

- **حالة المستودع**: `git status`
- **إضافة جميع الملفات**: `git add .`
- **إنشاء التزام مع تعليق**: `git commit -m "Comment"`
- **تعديل آخر التزام**: `git commit --amend -m "Comment"`
- **إزالة الملفات من المرحلة**: `git restore --staged .`

## عرض السجل

- **عرض سجل الالتزامات**: `git log`
- **عرض سجل الالتزامات بشكل مختصر**: `git log --oneline`
- **عرض السجل كرسوم بيانية**: `git log --graph`
- **عرض السجل مختصر ورسوم بيانية**: `git log --oneline --graph`

## إدارة الفروع

- **عرض الفروع**: `git branch`
- **إنشاء فرع جديد**: `git branch branch-name`
- **الانتقال إلى فرع**: `git checkout branch-name`
- **إعادة تسمية فرع**: `git branch -m target-branch-name modified-branch-name`
- **حذف فرع**: `git branch -d branch-name`
- **حذف فرع من فرع آخر**: `git checkout another-branch-name ; git branch -d old-branch-name`
- **دمج فرع**: `git merge target-branch-name`

## إدارة العلامات

- **عرض العلامات**: `git tag`
- **إنشاء علامة جديدة**: `git tag tag-name`
- **عرض تفاصيل علامة**: `git show tag-name`
- **حذف علامة**: `git tag -d tag-name`

## إدارة المستودعات

- **استنساخ مستودع**: `git clone repository-url`
- **دفع التغييرات**: `git push`
- **دفع علامة محددة**: `git push origin tag-name`
- **جلب التحديثات**: `git fetch`
- **سحب التحديثات ودمجها**: `git pull`

## إدارة الريموت

- **عرض قائمة الريموت**: `git remote`
- **عرض تفاصيل الريموت**: `git remote -v`
- **إضافة ريموت جديد**: `git remote remote-name repository-url`
- **دفع التغييرات إلى ريموت معين**: `git push remote-name`
- **إعادة تسمية ريموت**: `git remote rename old-remote-name new-remote-name`
- **حذف ريموت**: `git remote rm remote-name`

## إدارة إعادة الترتيب (Rebase)

- **إعادة ترتيب الفروع**: `git rebase base-branch-name`
- **إعادة ترتيب فرع معين**: `git rebase base-branch-name from-branch-name`
- **إعادة ترتيب مع فرع معين**: `git rebase --onto base-branch-name from-branch-name to-branch-name`
- **إلغاء عملية إعادة الترتيب**: `git rebase --abort`
- **إكمال إعادة الترتيب بعد حل المشاكل**: `git rebase --continue`
- **تخطي خطوة أثناء إعادة الترتيب**: `git rebase --skip`

## أخرى

- **فتح ملف باستخدام المفكرة**: `notepad file-name`
- **عرض تفاصيل الفروع**: `git branch --v`

</div>
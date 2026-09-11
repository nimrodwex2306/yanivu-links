# Yanivu — אתר לינקים

## פרסום מהיר ב-Vercel

1. פתח חשבון חינמי ב-[Vercel](https://vercel.com) והתחבר עם GitHub.
2. העלה את הקבצים לתיקיית GitHub חדשה (הוראות למטה).
3. ב-Vercel בחר **Add New → Project**, בחר את המאגר ולחץ **Deploy**. מכיוון שזה אתר HTML פשוט, אין צורך בהגדרות Build.
4. בסיום תקבל כתובת חינמית, למשל `yanivu-links.vercel.app`.

## העלאה ל-GitHub

התקן [Git](https://git-scm.com/downloads) אם הוא עדיין לא מותקן. פתח טרמינל בתוך התיקייה הזו והריץ:

```powershell
git init
git add .
git commit -m "First version of Yanivu links site"
git branch -M main
git remote add origin https://github.com/USERNAME/yanivu-links.git
git push -u origin main
```

לפני השורה של `git remote`, צור ב-GitHub מאגר חדש בשם `yanivu-links` (בלי README או קבצים נוספים) והחלף את `USERNAME` בשם המשתמש שלך ב-GitHub.

לעדכון עתידי אחרי שינוי באתר:

```powershell
git add .
git commit -m "Update links site"
git push
```

## דומיין מומלץ

`yanivu.com` הוא הבחירה הפשוטה והמקצועית ביותר, אם הוא פנוי. אם לא: `yanivu.live`, `yanivu.gg`, או `yanivustream.com`.

אפשר לרכוש דומיין ב-[Cloudflare Registrar](https://www.cloudflare.com/products/registrar/) במחיר עלות, או ב-[Namecheap](https://www.namecheap.com/). אחרי הרכישה: ב-Vercel עבור אל **Project → Settings → Domains**, הוסף את הדומיין, ופעל לפי הוראות ה-DNS שיוצגו שם.

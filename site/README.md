# אבולוציה זו לא מילה גסה – אתר הפודקאסט והספר

אתר סטטי פשוט (HTML + CSS בלבד, בלי בנייה ובלי התקנות). כל קובץ אפשר לערוך ישירות בעורך של GitHub.

## העלאה ל-GitHub Pages
1. צרו repository חדש ב-GitHub והעלו את כל תוכן התיקייה (Add file → Upload files, או `git push`).
2. Settings → Pages → Source: `Deploy from a branch`, Branch: `main`, תיקייה: `/ (root)`.
3. אחרי כדקה האתר יעלה בכתובת `https://<שם-משתמש>.github.io/<שם-הריפו>/`.

## מבנה
| קובץ | תוכן |
|---|---|
| `index.html` | דף הבית |
| `episodes.html` | רשימת הפרקים |
| `episodes/*.html` | דף לכל פרק |
| `about.html` | אודות |
| `book.html` | הספר (placeholder) |
| `logo.html` | הסבר על הלוגו |
| `style.css` | כל העיצוב |
| `assets/` | תמונות |

## החלפת תמונות
- **לוגו:** העלו קובץ בשם `assets/logo.png` – הוא יוצג אוטומטית (עד אז מוצג `logo.svg` הזמני).
- **תמונה שלי:** העלו `assets/me.jpg` ושנו ב-`about.html` את `assets/me.svg` ל-`assets/me.jpg`.

## הוספת פרק
ראו `episodes/_TEMPLATE.html.txt`.

## תגובות מאזינים
מסומן `PLACEHOLDER` בכל דף פרק – ימומש בשלב הבא (למשל Giscus, שמבוסס על GitHub Discussions).

# 🍽️ RestoPro — ניהול מסעדה חכם

מערכת ניהול הוצאות והזמנות למסעדה, בנויה עם HTML/JS ו-Claude AI.

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Language](https://img.shields.io/badge/language-Hebrew-orange)
![AI](https://img.shields.io/badge/AI-Claude%20API-purple)

---

## ✨ תכונות עיקריות

- 📊 **דשבורד** — גרפי הוצאות חודשיים וקטגוריאליים עם KPIs
- 💰 **מעקב הוצאות** — הוסף, ערוך, סנן וייצא הוצאות ל-CSV
- 🛒 **הזמנות ספקים** — הזמנה ידנית או ניתוח אוטומטי של תמונת תפריט עם Claude AI
- 🚚 **ניהול ספקים** — רשימת ספקים עם סטטיסטיקות
- 🌐 **עברית מלאה** — ממשק RTL מלא

---

## 🚀 הפעלה על GitHub Pages

1. העלה את `index.html` ו-`README.md` לשורש הריפו (root)
2. `Settings → Pages → Deploy from branch → main → / (root)`
3. המתן כ-2 דקות — האפליקציה תעלה בכתובת:
   ```
   https://YOUR_USERNAME.github.io/REPO_NAME/
   ```

---

## 🔑 הגדרת Claude API

1. צור מפתח ב-[console.anthropic.com](https://console.anthropic.com)
2. פתח האפליקציה → **הגדרות ⚙️**
3. הדבק מפתח שמתחיל ב-`sk-ant-api...`
4. לחץ **שמור מפתח**

> המפתח נשמר בדפדפן בלבד — לא נשלח לשרת חיצוני.

---

## 📁 מבנה הפרויקט

```
repo/
├── index.html   ← האפליקציה המלאה
└── README.md    ← קובץ זה
```

---

## 🛠️ טכנולוגיות

| רכיב | טכנולוגיה |
|------|-----------|
| Frontend | HTML5, CSS3, JavaScript |
| גרפים | Chart.js 4 |
| AI | Claude API (claude-sonnet-4-6) |
| אחסון | localStorage |
| פריסה | GitHub Pages |

---

## 🎓 פרויקט אקדמי

נבנה כחלק מקורס AI — יישום מעשי של Claude API בפתרון בעיה עסקית אמיתית.

MIT License

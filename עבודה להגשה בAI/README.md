# 🍽️ Restaurant Manager Pro

מערכת ניהול הוצאות והזמנות למסעדה – בנויה עם HTML/JS ו-Claude AI.

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Language](https://img.shields.io/badge/language-Hebrew-orange)
![AI](https://img.shields.io/badge/AI-Claude%20API-purple)

## ✨ תכונות עיקריות

- 📊 **דשבורד** – גרפי הוצאות חודשיים וקטגוריאליים עם KPIs
- 💰 **מעקב הוצאות** – הוסף, ערוך, סנן וייצא הוצאות ל-CSV
- 🛒 **הזמנות ספקים** – הזמנה ידנית או ניתוח אוטומטי של תמונת תפריט עם Claude AI
- 🚚 **ניהול ספקים** – רשימת ספקים עם סטטיסטיקות
- 🌐 **עברית מלאה** – ממשק RTL מלא

## 🚀 הפעלה מהירה

### אפשרות 1: GitHub Pages
1. העלה ל-GitHub Repository
2. עבור לـ `Settings → Pages → Deploy from branch (main)`
3. גש ל-URL שיוצג

### אפשרות 2: הפעלה מקומית
```bash
git clone https://github.com/YOUR_USERNAME/restaurant-manager.git
cd restaurant-manager
# פתח את index.html בדפדפן
open index.html
```

## 🔑 הגדרת Claude API (לניתוח תמונות)

1. צור מפתח API בـ [console.anthropic.com](https://console.anthropic.com)
2. בממשק האפליקציה עבור לـ **הגדרות**
3. הכנס את המפתח שמתחיל בـ `sk-ant-...`
4. לחץ **שמור מפתח**

> המפתח נשמר **בדפדפן שלך בלבד** ואינו נשלח לשום שרת חיצוני.

## 🛠️ טכנולוגיות

| רכיב | טכנולוגיה |
|------|-----------|
| Frontend | HTML5, CSS3, JavaScript |
| UI | Bootstrap 5 (RTL) |
| גרפים | Chart.js |
| AI | Claude API (claude-sonnet-4-6) |
| אחסון | localStorage |
| פריסה | GitHub Pages |

## 📁 מבנה הפרויקט

```
restaurant-manager/
│
├── index.html          # האפליקציה המלאה (קובץ יחיד)
└── README.md           # תיעוד זה
```

## 📸 שימוש בניתוח תפריט AI

1. עבור לـ **הזמנות ספקים**
2. לחץ על **הזמנה מתמונה**
3. העלה צילום של תפריט/קטלוג ספק
4. לחץ **נתח תפריט עם AI**
5. ערוך את הפריטים שזוהו לפי הצורך
6. לחץ **אשר הזמנה**

## 🎓 פרויקט אקדמי

פרויקט זה נבנה כחלק מקורס AI באוניברסיטה.  
המטרה: יישום מעשי של LLM APIs בפתרון בעיה עסקית אמיתית.

## 📄 רישיון

MIT License

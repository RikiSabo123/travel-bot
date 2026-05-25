# 🧳 בוט טיולים

בוט שיחה חכם לתכנון טיולים, מבוסס על Gemini AI של גוגל.

## ✨ תכונות

- שיחה אינטראקטיבית לתכנון מסלולי טיול
- ניתוח סנטימנט של השיחה
- גרפים להשוואת טון בין המשתמש לבוט
- שמירת היסטוריית שיחה ב-JSON

## 🚀 התקנה והפעלה

### 1. התקן את הספריות
```bash
pip install -r requirements.txt
```

### 2. הגדר מפתח API
צור קובץ `.env` בתיקיית הפרויקט והוסף:
```
GEMINI_API_KEY=your_api_key_here
```
ניתן לקבל מפתח API ב-[Google AI Studio](https://aistudio.google.com/app/apikey)

### 3. הפעל את ה-Notebook
פתח את `בוט טיולים.ipynb` ב-Jupyter והרץ את כל התאים.

## 🛠️ טכנולוגיות

- Python 3.12
- [Google Gemini API](https://ai.google.dev/)
- Matplotlib
- Jupyter Notebook

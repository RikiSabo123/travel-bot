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
העתק את קובץ הדוגמה וערוך אותו:
```bash
copy .env.example .env
```
פתח את `.env` והחלף את `your_api_key_here` במפתח שלך.
ניתן לקבל מפתח API ב-[Google AI Studio](https://aistudio.google.com/app/apikey)

### 3. פתח את Jupyter Notebook
```bash
jupyter notebook
```
בדפדפן שנפתח, לחץ על הקובץ `בוט טיולים.ipynb` והרץ את כל התאים עם **Run All**.

## 🛠️ טכנולוגיות

- Python 3.12
- [Google Gemini API](https://ai.google.dev/)
- Matplotlib
- Jupyter Notebook

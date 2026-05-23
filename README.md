# 🕋 نظام التنبؤ بازدحام المعتمرين
### Umrah Visitors Smart Forecasting System — Al-Masjid Al-Haram

---

## 🚀 رفع المشروع على Streamlit Cloud (خطوات سهلة)

### الخطوة 1: إنشاء Repository على GitHub
1. افتح [github.com](https://github.com) وسجّل دخول
2. اضغط **New repository**
3. اسمِه مثلاً: `umrah-dashboard`
4. اجعله **Public**
5. اضغط **Create repository**

### الخطوة 2: رفع الملفات
ارفع هذه الملفات كلها على الـ Repository:
```
umrah-dashboard/
├── app.py
├── requirements.txt
├── .gitignore
├── models/
│   └── growth_rate_xgboost_model.pkl
└── Intelligent System for Predicting Visitor Crowd Levels and Optimal Visiting Times at Al-Masjid Al-Haram.xlsx
```

**طريقة الرفع السهلة:**
- افتح الـ Repository → اضغط **Add file** → **Upload files**
- ارفع كل الملفات دفعة واحدة (الملفات + مجلد models)

### الخطوة 3: نشر على Streamlit Cloud
1. افتح [share.streamlit.io](https://share.streamlit.io)
2. سجّل دخول بحساب GitHub نفسه
3. اضغط **New app**
4. اختر الـ Repository: `umrah-dashboard`
5. اختر الملف: `app.py`
6. اضغط **Deploy!**

### ✅ النتيجة
ستحصل على رابط مثل:
```
https://your-username-umrah-dashboard-app-xxxx.streamlit.app
```

---

## 📁 هيكل الملفات

| الملف | الوصف |
|-------|--------|
| `app.py` | التطبيق الرئيسي |
| `requirements.txt` | المكتبات المطلوبة |
| `models/growth_rate_xgboost_model.pkl` | نموذج XGBoost المدرّب |
| `*.xlsx` | بيانات الزوار |

---

## 🛠 تشغيل محلي (اختياري)

```bash
pip install -r requirements.txt
streamlit run app.py
```

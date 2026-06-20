# AgriFarm - Intelligent Decision Support System for Agricultural Resource Management and Optimizing Water and Energy Consumption

[![License](https://img.shields.io/badge/License-Proprietary-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![Next.js](https://img.shields.io/badge/Next.js-14-black.svg)](https://nextjs.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.104-green.svg)](https://fastapi.tiangolo.com/)

| ![آگریفارم](frontend/public/screenshots/AgriFarm.PNG) | **AGRIFARM:** سامانه تصمیم یار هوشمند است که با ترکیب علوم داده، هوش مصنوعی و ت[...] 
|--------------------------------------------------------|--------------------------------------------------------|




## 📋 معرفی

آگریفارم یک سامانه هوشمند برای کمک به کشاورزان و مدیران منابع کشاورزی است که:
- مصرف آب و انرژی را بهینه‌ می‌ کند
- محصول بهینه را پیشنهاد می‌ دهد
- سودآوری اقتصادی را مدیریت‌ می‌ کند

این ایده مبتنی بر ترکیبی از تخصص در مدیریت فناوری اطلاعات، علوم داده و تحلیل سیستم‌ های هوشمند است.

## 🎯 هدف اصلی پروژه

هدف اصلی سامانه تصمیم‌ یار هوشمند مدیریت منابع کشاورزی (AgriFarm)، **بهینه‌ سازی بهره‌ وری منابع آب و انرژی در ک[...] 

### مکانیسم تأثیر بر احیای دریاچه ارومیه:

- **مدیریت مصرف آب**: سامانه با پیش‌بینی دقیق نیاز آبی محصولات و شبیه‌سازی سناریوهای کم‌آب‌بر، از برداشت غی[...] 

- **بهینه‌ سازی انرژی و منابع**: الگوریتم‌ها میزان مصرف برق و انرژی مربوط به آبیاری را کاهش داده و بهره‌وری ع[...] 

- **انتخاب محصول کم‌ آب‌ بر و سودآور**: توصیه‌های داده‌محور برای انتخاب محصول با حداقل مصرف آب و حداکثر بازد[...] 

- **پیش‌ بینی و سناریوسازی اقتصادی و اکولوژیک**: امکان شبیه‌سازی اثر تغییرات اقلیمی، میزان بارش و دسترسی به م[...] 

### ویژگی‌ های علمی و نوآورانه:

- استفاده از مدل‌های پیش‌بینی مبتنی بر داده‌های چندمنظوره (Multivariate Data Modeling) و یادگیری ماشین برای مدیریت منا... 
- بومی‌سازی الگوریتم‌ها برای شرایط اقلیمی و کشاورزی منطقه دریاچه ارومیه
- ارائه تصمیم‌یار هوشمند برای سیاست‌گذاری منابع و برنامه‌ریزی بهره‌برداری پایدار
- قابلیت اتصال به پایگاه‌های داده دولتی و سنجش از راه دور برای داده‌های آب و انرژی

### نتیجه مورد انتظار:

استفاده گسترده از سامانه AgriFarm موجب کاهش برداشت بی‌رویه آب، مدیریت پایدار منابع، افزایش بهره‌وری اقتصادی ک[...] 

---

## 🎯 Project Objective – AgriFarm (English, Technical Version)

🌱 AgriFarm — Smart Farming Optimization  
🚀 AI-based crop recommendation & water/energy prediction  
📍 Target: Sustainable agriculture for Lake Urmia ecosystem

The primary objective of the AgriFarm Smart Decision Support System for Agricultural Resource Management is to **optimize water and energy efficiency in agriculture while supporting the ecological[...] 

### Mechanisms for Impact on Lake Urmia Restoration:

- **Water Use Management**: The system predicts precise crop water requirements and simulates low-water-use scenarios, preventing over-extraction and unsustainable irrigation practices.

- **Energy and Resource Optimization**: AI-driven recommendations minimize electricity and energy consumption in irrigation, enhancing operational efficiency.

- **Crop Selection Optimization**: Data-driven guidance supports choosing crops with minimal water demand and maximum economic return.

- **Economic and Ecological Scenario Simulation**: Users can simulate the impacts of climate variability, rainfall, and water availability on crop yield and resource consumption.

### Scientific and Innovative Features:

- Utilizes multivariate predictive models and machine learning for intelligent water and resource management
- Locally adapted algorithms for the climatic and agricultural conditions of the Lake Urmia region
- Provides a decision support tool for sustainable resource planning and agricultural policy-making
- Integrates with remote sensing and governmental databases for real-time water and energy monitoring

## ✨ Key Features

- AI-based water & energy consumption prediction  
- Optimal crop recommendation  
- Scenario simulation (economic + ecological)  
- Smart dashboards  
- Export to PDF/CSV  

### Expected Outcomes:

Widespread adoption of AgriFarm is projected to reduce water overuse, promote sustainable resource management, enhance farmers' economic efficiency, and accelerate the ecological restoration of La[...] 

---

## 🏗️ معماری سیستم

```
AgriFarm/
├── backend/          # FastAPI Backend
│   ├── app/
│   │   ├── api/      # API endpoints
│   │   ├── models/   # Database models
│   │   ├── services/ # Business logic & AI algorithms
│   │   └── main.py   # FastAPI app
│   └── requirements.txt
│
├── frontend/         # Next.js Frontend
│   ├── app/          # Next.js app directory
│   ├── components/   # React components
│   └── package.json
│
└── database/         # Database scripts
    └── init.sql      # Schema & sample data
```

## 🚀 راه‌اندازی سریع

### پیش‌نیازها
- Python 3.9+
- Node.js 18+
- PostgreSQL 14+

### 1. راه‌اندازی Backend

```bash
cd backend
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
uvicorn app.main:app --reload
```

Backend در `http://localhost:8000` اجرا می‌شود.

### 2. راه‌اندازی Database

```bash
# ایجاد دیتابیس
createdb agrifarm

# اجرای اسکریپت اولیه
psql agrifarm < database/init.sql
```

### 3. راه‌اندازی Frontend

```bash
cd frontend
npm install
npm run dev
```

Frontend در `http://localhost:3000` اجرا می‌شود.

## 📊 ویژگی‌های MVP

- ✅ فرم ورود اطلاعات مزرعه و محصول
- ✅ محاسبه مصرف پیش‌بینی شده آب و انرژی
- ✅ پیشنهاد محصول بهینه بر اساس شرایط
- ✅ داشبورد با نمودارهای ساده
- ✅ خروجی PDF/CSV

## 📸 اسکرین‌شات‌ها

> مسیر فایل‌ها: `frontend/public/screenshots/`  

| نما | توضیحات |
| --- | --- |
| ![صفحه خانه](frontend/public/screenshots/01-home.png) | **خانه:** معرفی هدف پروژه، CTA برای افزودن مزرعه و مشاهده داشبورد، آمار خل�[...] 
| ![لیست مزارع](frontend/public/screenshots/02-farms.png) | **لیست مزارع:** کارت‌های خلاصه مزرعه با مساحت، نوع خاک، موقعیت و دسترس�[...] 
| ![لیست مزارع خالی](frontend/public/screenshots/03-farms-empty.png) | **لیست مزارع (خالی):** دعوت به ثبت اولین مزرعه با CTA سبز |
| ![ایجاد مزرعه جدید](frontend/public/screenshots/04-farm-create.png) | **فرم ایجاد مزرعه:** ورودی مساحت، نوع خاک، موقعیت، مختصات و من[...] 
| ![مزرعه گندم احمد](frontend/public/screenshots/05-farm-wheat.png) | **جزئیات مزرعه گندم احمد:** پیش‌بینی مصرف ۳۰ روزه آب/انرژی و اط�[...] 
| ![مزرعه سبزیجات احمد](frontend/public/screenshots/06-reco-veggies.png) | **جزئیات مزرعه سبزیجات احمد:** مقادیر مصرف و مشخصات مزرعه (�[...] 
| ![مزرعه ذرت فاطمه](frontend/public/screenshots/07-reco-corn.png) | **توصیه محصول ذرت:** سناریوهای کشت روی خاک شنی �[...] 
| ![توصیه محصول گندم](frontend/public/screenshots/08-reco-wheat.png) | **توصیه محصول برای مزرعه گندم احمد:** فهرست محصولات پیشنهادی ب[...] 
| ![داشبورد مدیریتی](frontend/public/screenshots/11-dashboard.png) | **داشبورد مدیریتی:** آمار تعداد مزارع، مساحت کل، مصرف آب/انرژی �[...] 
| ![مستندات API](frontend/public/screenshots/12-api-swagger.png) | **Swagger UI:** لیست اندپوینت‌های API (مزارع، محصولات، پیش‌بینی‌ها، توصی[...] 

## 🔗 API Documentation

پس از راه‌اندازی Backend، مستندات API در `http://localhost:8000/docs` در دسترس است.

## 📝 داده‌های نمونه

سیستم با داده‌های نمونه از پیش بارگذاری شده است که می‌توانید برای تست استفاده کنید.

## 📄 مجوز و حقوق

© ۲۰۲۵ میلادی / ۱۴۰۴ هجری شمسی - محمد ناصر حاجی هاشم‌آباد  
تمام حقوق محفوظ است.

این پروژه به‌عنوان یک MVP (Minimum Viable Product) برای تست میدانی و دریافت بازخورد کاربران طراحی شده است.

## 🤝 مشارکت

برای مشارکت در توسعه این پروژه یا ارائه بازخورد، لطفاً با ایمیل info@mohammadnasser.com تماس بگیرید.

راهنمای کامل مشارکت در فایل [CONTRIBUTING.md](CONTRIBUTING.md) موجود است.

**مخزن GitHub:** [hashemabad/agrifarm](https://github.com/hashemabad/agrifarm)

## 📚 مستندات بیشتر

- [هدف اصلی پروژه](OBJECTIVES.md) - هدف اصلی و مکانیسم تأثیر بر احیای دریاچه ارومیه
- [اطلاعات پروژه](PROJECT_INFO.md) - جزئیات کامل پروژه
- [اطلاعات توسعه‌دهنده](AUTHORS.md) - اطلاعات توسعه‌دهنده و تخصص‌ها
- [راهنمای نصب Frontend](frontend/INSTALL.md) - حل مشکلات نصب
- [راهنمای راه‌اندازی Frontend](frontend/SETUP.md) - راه‌اندازی کامل

## ⚙️ تنظیمات محیط

قبل از اجرا، فایل‌های `.env.example` را کپی کرده و به `.env` تغییر نام دهید:

```bash
# Backend
cp backend/.env.example backend/.env
# سپس مقادیر را ویرایش کنید

# Frontend
cp frontend/.env.example frontend/.env.local
# سپس مقادیر را ویرایش کنید
```
## 👨‍💻 توسعه‌دهنده

**محمد ناصر حاجی هاشم‌آباد**  
📧 Email: info@mohammadnasser.com  
🌐 Website: [Mohammadnasser.com](https://mohammadnasser.com)

### شبکه‌های اجتماعی
- LinkedIn: https://www.linkedin.com/in/mnhashemabadi/
- X: https://x.com/mnhashemabadi
- Telegram: https://t.me/mnhashemabadi
- GitHub: https://github.com/mnhashemabadi

**تحصیلات:** کارشناسی ارشد مدیریت فناوری اطلاعات – دانشگاه علم و صنعت ایران

**تخصص‌ها:**
- طراحی معماری سامانه‌های اطلاعاتی
- تحلیل داده‌های حجیم (Big Data)
- مدل‌سازی تصمیم‌یار
- پیاده‌سازی الگوریتم‌های پیش‌بینی
- تحلیل سری‌های زمانی
- طراحی داشبوردهای تحلیلی
- توسعه نمونه‌های اولیه تحت وب


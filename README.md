# 🚗 Used Car Price Prediction (eBay Dataset)

این پروژه یک مدل یادگیری ماشین برای پیش‌بینی قیمت ماشین‌های دست دوم بر اساس داده‌های واقعی eBay است.

## 📌 مراحل پروژه
1. **Data Cleaning**
   - حذف مقادیر تکراری و Null
   - تبدیل ستون‌های متنی به عددی
   - تمیز کردن ستون‌های `price` و `odometer`

2. **Data Processing**
   - استفاده از Label Encoding برای ستون‌های دسته‌ای (brand, fuelType, gearbox, …)
   - جدا کردن ویژگی‌ها (X) و هدف (y = price)

3. **Modeling**
   - تست مدل Linear Regression (ضعیف عمل کرد: R² ≈ -1 😅)
   - تست مدل RandomForestRegressor (خیلی بهتر: R² ≈ 0.83)

4. **Evaluation**
   - MSE, RMSE, R² Score برای مقایسه مدل‌ها
   - RandomForest بهترین عملکرد را داشت

5. **Prediction Example**
   - پیش‌بینی قیمت یک BMW مدل 2015 با 120,000 کیلومتر → حدود **8700 EUR**

## 📊 نتایج
- **R² Score:** ~0.83
- **RMSE:** ~3000 EUR

## 🔥 ابزارها
- Python, Pandas, NumPy
- Scikit-Learn
- Matplotlib / Seaborn

👨‍💻 Author: [MohammadEhsanBehboodian]

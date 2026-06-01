# E-commerce Revenue Analysis 📊

تحليل كامل لمبيعات متجر إلكتروني باستخدام Python. الهدف: نعرف وين نحط ميزانية التسويق.

### 🎯 المشكلة
المدير: "أي فئة نركز عليها؟ وأي فئة نخفض مخزونها؟"

### 📦 الداتا
- 100 طلب شراء
- الأعمدة: order_id, customer_id, order_date, product, category, price, quantity, total

### 📈 النتائج
#### 1. Revenue by Category
الصدمة: 62% من الإيراد جاي من فئتين بس!

![Revenue by Category](top_category.png)

| الفئة | الإيراد درهم | النسبة |
| :--- | :--- | :--- |
| Electronics | 15,216 | 39.6% |
| Furniture | 8,573 | 22.3% |
| Home Decor | 5,520 | 14.4% |
| Kitchen | 5,205 | 13.5% |
| Accessories | 4,133 | 10.8% |

#### 2. Daily Trend
يوم 15-04 صار Spike للمبيعات وصل 480 درهم.

### 💡 التوصيات
1. زيادة مخزون Electronics 30% 
2. عمل Cross-sell: "لابتوب + ماوس بخصم" عشان نرفع Accessories
3. نعرف إيش صار يوم 15-04 ونكرره

### 🛠️ الأدوات
Python | Pandas | Matplotlib

### 🚀 كيف تشغل الكود
```bash
pip install pandas matplotlib
jupyter notebook analysis.ipynb

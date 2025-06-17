# 📱 Courses ++

Courses++ is a smart mobile and web application designed to help users manage shopping lists, estimate budgets, scan receipts using OCR, and track expenses — all in one intuitive interface. The app also includes an admin dashboard for managing users, product data, and analytics.

---

## ✨ Features

- 📝 Create and manage shopping lists
- 📷 Scan receipts using OCR and extract product info
- 💰 Estimate total cost based on real store data (Carrefour, Aziza, etc.)
- 📊 Track spending history and get statistics
- 🧠 Intelligent product suggestions
- 🧾 Loyalty card system with barcode
- 🔐 Admin dashboard (web) to manage users, data, and analytics

---

## 🛠️ Technologies Used

- **Flutter** (Mobile)
- **React.js** (Admin Dashboard)
- **Node.js + Express** (Backend API)
- **Google Cloud Vision API** (OCR)
- **Firebase Auth** (Authentication)
- **Google Maps API** (Nearby store locator)

---

## 🚀 Getting Started

### Prerequisites

- Flutter SDK  
- Node.js    
- Firebase project (with Firestore & Auth enabled)  

--
⚠️ This project is protected. Reuse, reproduction, or modification without permission is strictly forbidden.

--
Arabic

# 📱 Courses++

Courses++ هي تطبيق موبايل تونسي يعاونك تنظم قوايم الشراء، تقيّم الميزانية، وتبدا الشراء بطريقة سهلة وذكية. تنجم تزيد منتوجات، تلقى اقرب مغازة، وتستعمل الذكاء الاصطناعي باش تحلل وصلات الشراء متاعك.

---

## 🎯 المزايا الرئيسية

- 📝 إنشاء قوائم شراء جديدة بسهولة.
- ➕ إضافة منتوجات مع الوصف والكمية.
- 📊 تقدير الميزانية حسب الأسعار من عدة مصادر (Carrefour, Aziza, Monoprix...etc).
- 🧠 استخراج الأسعار تلقائيا من الوصلات (باستخدام AI).
- 🗺️ تحديد أقرب مغازة تلقائيًا.
- 🛍️ تفعيل وضع "نقضي" للتعليم على الحاجات اللي شريتهم.
- 📸 إمكانية تصوير الوصل وتسجيله.
- 🧾 تاريخ مفصل لكل القوائم الشرائية اللي كملتها.

---

## 🛠️ كيفاش يخدم التطبيق

### 1. إنشاء قائمة
- تنجم تسمي القائمة أو تسيبها فارغة (يتسمى `Liste 1`, `Liste 2`...).

### 2. إضافة منتوجات
- كل منتوج فيه اسم، وصف، وكمية.
- التنقيح يتم مباشرة من نفس الشاشة.

### 3. تقدير الميزانية
- التطبيق يقترح أسعار تقريبية من مختلف المتاجر.
- تنجم تشوف السعر حسب مغازة معينة (ex: Carrefour فقط).
- يظهرلك مجموع التقدير الكلي والتقدير حسب التصنيفات.

### 4. البدء في الشراء
- بعد التقدير، تنجم تختار مغازة قريبة وتبدا وضع "نقضي".
- تنجم تعلم على الحاجات اللي شريتهم.

### 5. تصوير وصل الشراء
- بعد ما تكمل، تنجم تصور الوصل.
- الAI يخرج تلقائياً المنتوجات، الكمية، والأسعار.

---

## 📂 تنظيم الكود

| Dossier | Contenu |
|--------|---------|
| `controllers/` | لوجيك التطبيق (List, Item, Shopping) |
| `services/` | المعاملة مع Firestore, Store GPS, OCR |
| `models/` | نماذج البيانات: ShoppingList, ShoppingItem |
| `views/` | الواجهات: ListPage, ListItemsPage, FindStoreView |
| `providers/` | Riverpod state management |

---

## 🔐 التوثيق والدخول
- يستعمل Firebase Authentication.
- كل مستخدم يشوف قوائمو الخاصة.

---

## 📦 التقنيات المستعملة

- **Flutter + Dart**: لواجهة المستخدم
- **Firebase (Auth + Firestore)**: للتخزين وتسجيل الدخول
- **Riverpod**: لإدارة الحالة
- **Gemini AI + OCR**: لاستخراج المعلومات من الوصلات
- **Google Maps**: لتحديد أقرب مغازة

---

## 🧪 ملاحظات المطور

- التقدير تتم في الوقت الحقيقي.
- كل قائمة تنجم تكون: عادية، مقدرة، أو مستعملة.
- الوصلات المصورة تتخزن في قاعدة البيانات مع تفاصيلها.

---

## 👨‍💻 المطور

Mohamed Amine Zaafrani  

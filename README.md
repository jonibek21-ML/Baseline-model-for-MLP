# Baseline-model-for-MLP
# 💉 Diabetes Bashorat – PyTorch bilan

## 📝 Umumiy ma’lumot
Ushbu repository kichik **neural network modelini** o‘z ichiga oladi, u **diabet kasalligini bashorat qilish** uchun PyTorch-da yaratilgan.  
Dataset nomi: `diabetes.csv` ✅  
- 768 ta row (sample)  
- 9 ta column (feature)  

Model **binary classification** qiladi:  
- `0` → Kasallik yo‘q  
- `1` → Kasallik mavjud  

---

## 📊 Dataset
- **Fayl**: `diabetes.csv`  
- **Rowlar**: 768  
- **Columnlar**: 9  
- Features (ustunlar) quyidagilar:  
  - Pregnancies (Homiladorlik soni)  
  - Glucose (Qon shakar)  
  - BloodPressure (Qon bosimi)  
  - SkinThickness (Teri qalinligi)  
  - Insulin (Insulin darajasi)  
  - BMI (Body Mass Index)  
  - DiabetesPedigreeFunction (Irsi faktor)  
  - Age (Yosh)  
  - Outcome (Target: 0 = Yo‘q, 1 = Ha)  

---

## 📚 Kutubxonalar
Ushbu loyihada quyidagi kutubxonalar ishlatiladi:  
- `pandas` – data load & manipulate  
- `numpy` – array ishlov berish  
- `torch` – model yaratish va train qilish  
- `sklearn` – evaluation metrics  
- `matplotlib` – graflar va vizualizatsiya  

---

## 🏗 Model Arxitekturasi
3 ta Fully Connected qatlam (Linear)
ReLU activation
Dropout (0.25) – overfitting oldini olish
Sigmoid output → binary classification

---

## 👨‍💻 Muallif
Jonibek Abdurahmonov

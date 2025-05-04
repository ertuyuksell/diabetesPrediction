# 🩺 Diabetes Prediction Project

Bu proje, bireylerin sağlık verilerine dayanarak diyabet hastalığına sahip olup olmadığını tahmin etmeyi amaçlamaktadır. Makine öğrenmesi teknikleriyle veri ön işleme, dengesiz sınıf problemi çözümü, hiperparametre ayarı ve model değerlendirme adımlarını kapsamaktadır.

---

## 🧠 Kullanılan Yöntemler
- 🔢 **Özellik Ölçekleme:** `StandardScaler`
- 🔤 **Kategorik Veri Kodlama:** `OneHotEncoder`
- ⚖️ **Dengesiz Veri:** `SMOTE` ve `RandomUnderSampler`
- 🔁 **Pipeline Yapısı:** `imblearn.Pipeline`
- 🔍 **Hiperparametre Ayarı:** `GridSearchCV`
- 📈 **Model Değerlendirme:** Accuracy, F1, ROC-AUC, Confusion Matrix
- 📊 **Görselleştirme:** Heatmap, ROC Curve, Learning Curve

---

## 📊 Performans Özeti
- **Accuracy:** %94.84
- **ROC-AUC:** 0.9735
- **Recall (diabetes=1):** %80

Model, diyabetli bireyleri yüksek başarıyla tahmin edebilmekte ve genelleme yeteneği güçlüdür.

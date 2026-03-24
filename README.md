# 🐟 Balık Veri Seti - Makine Öğrenmesi Analizi

Bu proje, balık veri seti üzerinde kapsamlı bir makine öğrenmesi analizi içermektedir.

## 📊 Veri Seti

- **Kayıt Sayısı:** 159
- **Balık Türü:** 7 (Bream, Perch, Roach, Pike, Smelt, Parkki, Whitefish)
- **Özellikler:** Weight, Length1, Length2, Length3, Height, Width

## 📁 Dosyalar

- `Fish.csv` - Orijinal veri seti
- `Fish_Analysis.ipynb` - Jupyter Notebook (tüm analiz)
- `fish_processed.csv` - İşlenmiş veri seti

## 🎯 Proje İçeriği

### 1. Veri İnceleme
- Veri yükleme ve ilk bakış
- Eksik değer ve duplike kontrolü
- İstatistiksel özet

### 2. Keşifsel Veri Analizi (EDA)
- Tür dağılımı görselleştirmeleri
- Korelasyon analizi
- Box plot ve violin plot
- Scatter plot analizleri

### 3. Veri Ön İşleme
- Özellik mühendisliği (Volume, Density, vb.)
- StandardScaler ile ölçeklendirme
- Train-test split (%80-%20)

### 4. Makine Öğrenmesi Modelleri
- Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- Support Vector Regression (SVR)

## 🏆 Sonuçlar

**En İyi Model:** Ridge Regression
- Test R² Score: **0.9832** (%98.32 doğruluk)
- Test MAE: 35.16g
- Overfitting: Yok ✅

## 🚀 Kullanım

```bash
# Repository'yi klonlayın
git clone https://github.com/burakkara14-cmyk/machine-learning.git
cd machine-learning

# Jupyter Notebook'u açın
jupyter notebook Fish_Analysis.ipynb

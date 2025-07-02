# 🎓 Öğrenci Başarı Analizi - Makine Öğrenmesi Uygulaması

Bu proje, öğrenci performans verilerini analiz ederek çeşitli faktörlerin genel başarıya olan etkilerini değerlendirmektedir. Python ve scikit-learn kullanılarak hem regresyon hem de önem derecesi analizleri yapılmıştır.

## 📦 Kullanılan Kütüphaneler

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- openpyxl

## 📁 Veri Seti

Excel dosyası: `Ogrenci_Performans.xlsx`  
Sütunlar:  
- Cinsiyet  
- Ebeveyn Eğitim Seviyesi  
- Okul Yemekhanesi  
- Özel Ders  
- Matematik, Okuma, Yazma Notları

## 🚀 Başlangıç

### 1. Gerekli kütüphaneleri yükleyin

```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
2. Python dosyasını çalıştırın
bash
Kopyala
Düzenle
python ogrenci_modelleme.py
🔍 Yapılan Analizler
✅ Özel Dersin Başarıya Etkisi
Decision Tree ve Linear Regression kullanıldı.

MSE ve R² değerleri ile karşılaştırıldı.

📊 Faktör Önem Dereceleri
Karar ağacı kullanılarak feature_importance çıkarıldı.

Görsel olarak bar grafikte sunuldu.

📈 Korelasyon ve Regresyon
Okuma notunun Yazma ve Matematik üzerindeki etkisi analiz edildi.

r2_score ve corr() ile istatistiksel değerlendirme yapıldı.

📌 Sonuç
Bu çalışma, öğrencinin başarısını etkileyen temel faktörleri hem görsel hem sayısal analizlerle ortaya koyar. Özel dersin etkisi, okuma becerilerinin diğer derslere katkısı gibi önemli çıkarımlar sunar.

👨‍💻 Geliştirici
[Merve Mizrakli]

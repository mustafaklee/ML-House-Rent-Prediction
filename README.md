Bu proje, web scraping ile Emlakjet üzerinden elde edilen gerçek verilerle, ev kiralarını tahmin etmeyi amaçlamaktadır. Makine öğrenmesi tekniklerini kullanarak farklı regresyon modelleri denenmiş ve en iyi performansı veren modelin belirlenmesi hedeflenmiştir.

Projenin Amacı
Kullanıcının girdiği konum, metrekare, oda sayısı, teraslı olması, metroya yakınlığı gibi özelliklere göre kira fiyatını olabildiğince doğru bir şekilde tahmin etmek.

Projede Yapılanlar

Veri Toplama: Web scraping ile Emlakjet'ten ham veri çekildi.

Feature Engineering: Kategorik verilerin dönüştürülmesi, yeni değişkenlerin türetilmesi gibi işlemler uygulandı.Kullanıcıların yazdığı ilan adlarından yeni feature'lar elde edildi.

Veri Analizi ve Görselleştirme: Özellikle konum, metrekare, oda sayisi gibi değişkenlerin dağılımları incelendi.

Veri Temizleme: Eksik ve aykırı değerler analiz edilerek uygun şekilde temizlendi.

Modelleme: Aşağıdaki regresyon modelleri eğitildi ve karşılaştırıldı:

Linear Regression

Polynomal Regression

Ridge Regression

Lasso Regression

Random Forest Regressor

XGBoost Regressor

Model Değerlendirme: Aşağıdaki metrikler ile model performansları değerlendirildi:

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score

Model Karşılaştırması
Modeller, hem eğitim hem de test verisi üzerinde test edilerek overfitting ve genel doğruluk durumları incelendi. Bazı modellerin, belirli feature setleriyle daha düşük hata verdiği gözlemlendi.

Kurulum ve Kullanım
```bash
git clone https://github.com/mustafaklee/ML-House-Rent-Prediction.git
cd ML-House-Rent-Prediction
pip install -r requirements.txt
```

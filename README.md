Web scraping ile Emlakjetten elde edilen veriler üzerinde çalışarak farklı regresyon modellerini denedim.Hedefim kira fiyatı tahmininde en iyi performansı veren modeli bulmaktır.Bu süreçte veri toplama  veri görselleştirme ön işleme ve model karşılaştırmaları gerçekleştirdim.

Veri ön işleme aşamasında eksik ve aykırı değerleri tespit edip uygun şekilde temizledim .Özellikle konum, metrekare, bina yaşı gibi önemli değişkenlerin dağılımlarını inceledim ve features engineering işlemlerini gerçekleştirdim. Ardından Lineer Regresyon, Ridge, Lasso, Random Forest ve XGBoost gibi algoritmaları kullanarak modelleri eğittim.

Modellerin performansını değerlendirmek için MSE, RMSE ve R² gibi metrikleri kullandım. Modelleri hem eğitim hem de test verisi üzerinde karşılaştırarak, overfitting durumlarını inceledim. Sonucunda bazı modellerin belirli özellik kümelerinde daha az hata ürettiğini gördüm.

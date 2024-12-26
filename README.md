# HR-ANALYSIS

![indir](https://github.com/user-attachments/assets/631cea3e-a149-44fe-acec-96129f7483ed)

# İnsan Kaynakları Analizi Çalışması

Bu çalışmada bir insan kaynakları (HR) veri seti üzerinde keşifsel veri analizi (EDA) yapılmış, ardından makine öğrenimi yöntemleriyle analiz gerçekleştirilmiştir. Çalışmanın adımları aşağıda detaylandırılmıştır:

## 1. Keşifsel Veri Analizi (EDA)
Veri setindeki özelliklerin dağılımları, eksik değerler, uç değerler ve değişkenler arasındaki ilişkiler incelendi. Bu süreçte:
- Kategorik değişkenler için frekans tabloları oluşturuldu.
- Sayısal değişkenlerin dağılımları görselleştirildi.
- Korelasyon analizi yapılarak bağımsız değişkenler arasındaki ilişkiler analiz edildi.

## 2. Özellik Mühendisliği
- Çalışma süresine göre "experience_level" adlı yeni bir değişken türetildi:
- Sayısal değişkenler (yaş, maaş, şirkette geçirilen yıl) standartlaştırıldı.
- Kategorik değişkenler (departman, deneyim seviyesi) sayısal değerlere dönüştürüldü.

## 3. Lojistik Regresyon ile Tahmin
Amaç, işten ayrılan çalışanları tahmin etmektir. Bu aşamada:
- Hedef değişken (işten ayrılma durumu) bağımsız değişkenlerden ayrıldı.
- Lojistik regresyon modeli kullanılarak tahmin işlemi gerçekleştirildi.

## 4. K-Means Kümeleme
İşten ayrılan çalışanlar, K-Means algoritması kullanılarak üç kümeye ayrıldı:
- Optimal küme sayısı "Elbow Yöntemi" ve Silhouette Skoru ile belirlendi (k=3).
- Kümelerin özellikleri analiz edildi ve yorumlandı.

## 5. Sonuçların Analizi
Kümeleme sonuçlarına göre, çalışanların işten ayrılma nedenlerine ilişkin çıkarımlar yapıldı. Her kümenin ortalama özellikleri incelendi ve sonuçlar raporlandı.

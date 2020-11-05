# A/B Testi Analizi

![](https://www.startupnedir.com/wp-content/uploads/2018/06/ab-test-780x405.png)

Bir şirket yakın zamanda, mevcut teklif verme türüne yani "maximum bidding (maksimum teklif verme)" e alternatif olarak "average bidding (ortalama teklif verme)" adı verilen yeni bir teklif türünü tanıttı. Müşterilerimizden biri, bu yeni özelliği test etmeye karar verdi ve ortalama teklif vermenin maksimum tekliften daha fazla dönüşüm getirip getirmediğini anlamak için bir A/B testi yapmak istiyor. Bu A/B testinde, müşterimiz rastgele izleyicilerini Test ve Kontrol grubu gibi eşit büyüklükteki iki gruba ayırır. "Maksimum teklifi" içeren reklam kampanyası "Kontrol grubuna", "ortalama teklifi" içeren başka bir kampanya "Test grubuna" sunulur. A/B testi 1 aydır devam ediyor ve müşterimiz şimdi sizden bu A/B testinin sonuçlarını analiz etmenizi ve sunmanızı bekliyor. Sunumunuzda aşağıdaki soruları cevaplamalısınız:

# A / B Testi Sonuçlarını Analiz Edin ve Sunun

**Sunumunuzda aşağıdaki soruları yanıtlamanız gerekir:**

1. Bu A/B testinin hipotezini nasıl tanımlarsınız?
2. İstatistiksel olarak anlamlı sonuçlar çıkarabilir miyiz?
3. Hangi istatistiksel testi kullandınız ve neden?
4. Soru 2'ye verdiğiniz cevaba göre, müşteriye tavsiyeniz nedir?

**İpuçları**
1. Şirket için nihai başarı metriği, Number of Purchases'dır. Bu nedenle, istatistiksel test için Purchase metriklerine odaklanmalısınız.
2. Teknik olmayan bir hedef kitle için istatistiksel test kavramını açıklayın.
3. Bu kampanya için müşteri yolculuğu:
    1. Kullanıcının bir reklam görme değişkeni (Impression)
    2. Kullanıcının reklamdaki web sitesi bağlantısını tıklaması ile ilgili değişken (Website Click)
    3. Kullanıcının web sitesinde bir arama yapması ile ilgili değişken (Search)
    4. Kullanıcının bir ürünün ayrıntılarını görüntülemesi ile ilgili değişken (View Content)
    5. Kullanıcının ürünü sepete eklemesi ile ilgili değişken (Add to Cart)
    6. Kullanıcının ürünü satın alması ile ilgili değişken (Purchase)
4. Satın Alma (Purchase) sayılarına ek olarak Web Sitesi Tıklama Oranı (Website Click Through Rate), İşlem Başına Maliyet (Cost per Action) ve Dönüşüm Oranları (Conversion Rates) gibi test ve kontrol grubu ölçümlerini karşılaştırmak için görselleştirmeleri kullanın.
5. Eğilimler, anormallikler veya başka modeller görürseniz, bunları sunumunuzda tartışın.
6. Gerekirse varsayımlar yapabilirsiniz.

## Veri

- Veri: Bir şirketin Facebook'un teklif sistemini test etmek için kullandığı gerçek veriler üzerinden analiz yapılmıştır.

## Kullanılan Kütüphaneler

```
pandas
numpy
matplotlib
scipy
statsmodels
```

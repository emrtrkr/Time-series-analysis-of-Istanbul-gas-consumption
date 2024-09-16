# İstanbul Gaz Tüketimi Zaman Serisi Analizi
## Bu proje, İstanbul’un gaz tüketimi verilerini analiz ederek gelecekteki tüketimi tahmin etmek için Zaman Serisi Analizi yöntemlerinin uygulanmasını içermektedir. Bu çalışmada kullanılan iki ana yöntem:

SARIMA (Seasonal Autoregressive Integrated Moving Average)
Triple Exponential Smoothing (Holt-Winters)
İçindekiler
Projenin Amacı
Kullanılan Yöntemler
SARIMA
Triple Exponential Smoothing
Veri Seti
Projede Kullanılan Adımlar
Sonuçlar

### Projenin Amacı
Bu projenin amacı, İstanbul'daki gaz tüketim verilerini kullanarak ilerideki gaz tüketimini daha doğru bir şekilde tahmin etmektir. Zaman serisi analizine dayalı olarak, enerji planlamasında daha etkili stratejiler geliştirilebilmesi için gelecekteki taleplerin öngörülmesi hedeflenmiştir.

### Kullanılan Yöntemler
SARIMA
SARIMA (Seasonal ARIMA), zaman serisi verilerinde sezonsallığı ve trendi yakalamak için kullanılan güçlü bir yöntemdir. Bu projede SARIMA modeli kullanılarak İstanbul’un gaz tüketim verilerine yönelik tahminlerde bulunulmuştur. ARIMA modeline sezonsal bileşenler eklenerek daha isabetli sonuçlar elde edilmiştir.

### Triple Exponential Smoothing
Triple Exponential Smoothing, diğer adıyla Holt-Winters yöntemi, hem trendi hem de sezonsallığı hesaba katan bir zaman serisi tahminleme yöntemidir. Bu yöntemde üç farklı bileşen (seviye, trend ve sezonsallık) kullanılarak tahmin yapılır.

### Veri Seti
Kullanılan veri seti İstanbul’daki gaz tüketim değerlerini içermektedir. Veri seti, aylık bazda toplanan tüketim miktarlarını içermekte olup, belirli bir dönem boyunca gözlemlenmiştir. Analizlerde eksik veriler doldurulmuş ve verilerin düzgün bir formata getirilmesi için veri ön işleme adımları uygulanmıştır.

Zaman Aralığı: Yıllık ve aylık veri.
Değişkenler: Tüketim miktarı (metreküp cinsinden).
Projede Kullanılan Adımlar
Veri Ön İşleme: Verinin temizlenmesi ve zaman serisi analizi için uygun hale getirilmesi.
Zaman Serisi Analizi: Trend, mevsimsellik ve rastgele bileşenlerin analiz edilmesi.
Modelleme:
SARIMA modeli ile tahmin yapılması.
Triple Exponential Smoothing yöntemi ile tahmin yapılması.
Model Değerlendirme: Modellerin tahmin performanslarının karşılaştırılması.
Görselleştirme: Tahmin sonuçlarının grafiksel olarak gösterilmesi.
Sonuçların Analizi: Tahmin edilen değerlerin gerçek değerlerle karşılaştırılması.
Sonuçlar
SARIMA ve Triple Exponential Smoothing yöntemleri kullanılarak yapılan tahminlerde belirli bir dönem için gaz tüketiminde doğruluğu yüksek sonuçlar elde edilmiştir.
Her iki model de sezonsal yapıları yakalamada başarılı olmuş, ancak uzun vadeli tahminlerde SARIMA modeli biraz daha etkili bulunmuştur.
Grafik ve görselleri proje içerisinde bulabilirsiniz.

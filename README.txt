Futbol AI Analiz - Telefon Prototipi

Bu ZIP, telefonda tarayıcıyla test edilebilen tek sayfalık bir prototiptir.
Özellikler:
- Maçları manuel kaydetme
- Kayıtları cihaz tarayıcısında saklama (localStorage)
- CSV içe aktarma (virgül veya noktalı virgül ayraç)
- Örnek CSV indirme ve kayıtları dışa aktarma
- 1-X-2 oranlarından marjdan arındırılmış normalize piyasa olasılıkları
- Alt/üst ve KG oranları için ham ima olasılığı

Önemli sınırlamalar:
- Bu henüz yapay zekâ modeli değildir.
- Veriler sadece aynı tarayıcıda saklanır; tarayıcı verisini temizlemek kayıtları silebilir.
- Bu tek dosyalı prototip, web üzerinden HTTPS ile barındırılmadıkça Android ana ekranına tam PWA gibi kurulamaz.
- APK değildir. Gerçek APK için Flutter kaynak paketi ve Android build ortamı gerekir.

Kullanım:
1. index.html dosyasını açarak önizleyin.
2. Telefonda en rahat kullanım için dosyayı HTTPS destekleyen bir web barındırma alanına koymak gerekir.
3. Maç arşivini korumak için düzenli CSV dışa aktarımı alın.

CSV başlıkları örneği:
date,league,home_team,away_team,HTHG,HTAG,FTHG,FTAG,B365H,B365D,B365A,over25,under25,btts_yes,btts_no

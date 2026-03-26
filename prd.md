RailSafe AI - PRD (Product Requirement Document)
1. Vizyon & Amaç
RailSafe AI, modern yüksek hızlı demiryolu operasyonlarında güvenliği ve verimliliği artırmak için tasarlanmış yapay zeka destekli bir asistan panelidir. Saha ekiplerinin teknik dökümanlar arasında kaybolmasını engeller ve ETCS/ERTMS standartlarındaki arızaları anında teşhis eder.

2. Temel Özellikler
AI Arıza Teşhis (NLP): Kullanıcının girdiği ETCS hata kodlarını veya teknik metinleri analiz eder, dökümantasyon veri tabanından çözüm önerir.

Güvenlik İzleme (Görüntü İşleme Simülasyonu): Kamera görüntülerinden ray üzerindeki engelleri algılayan bir arayüz.

Teknik Bilgi Bankası: Demiryolu sinyalizasyon standartlarına (UIC, ISO) hızlı erişim.

3. Kullanıcı Arayüzü (Ekranlar)
Dashboard: Sistem sağlığı, aktif alarmlar ve son arıza raporlarının özeti.

AI Tanı Merkezi: Kod girişi yapılan ve AI'nın çözüm sunduğu ana sohbet/analiz arayüzü.

Canlı Görüntü Paneli: Ray izleme kameralarının (simüle edilmiş) akışının olduğu güvenlik ekranı.

4. Teknik Gereksinimler
Frontend: React + Tailwind CSS (Lovable desteği için).

AI Engine: Google Gemini API (Döküman analizi ve mantık yürütme).

Veri: Sektörel standartlardaki (ETCS Level 2) hata dizinleri.

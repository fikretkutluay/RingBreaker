🚀 RingBreaker
RingBreaker, Unity motoru kullanılarak geliştirilmiş, yüksek tempolu, arcade tarzı bir mobil oyun projesidir. Oyuncuların dönen halka katmanlarını doğru zamanlama ile parçalayarak merkeze ulaşmasını hedefleyen bu proje, temiz kod mimarisi ve optimize edilmiş oyun mekanikleri üzerine inşa edilmiştir.

🎮 Oyun Hakkında
Oyun, iç içe geçmiş veya ardışık şekilde dönen halkaların, oyuncunun doğru anlarda yaptığı dokunuşlarla (input) kırılması prensibine dayanır. Basit bir kontrol şemasına sahip olmasına rağmen, artan hız ve değişen halka varyasyonları ile derin bir oynanış sunar.

Oynanış Mekanikleri
Zamanlama Odaklı Etkileşim: Halkaların zayıf noktalarını hedefleyen hassas vuruş sistemi.

Progresif Zorluk: Seviye ilerledikçe halkaların dönüş yönü, hızı ve karmaşıklığının dinamik olarak değişmesi.

Görsel Geri Bildirim: Halkalar kırıldığında oluşan parçalanma efektleri ve vuruş hissini güçlendiren "juice" elementleri.

🛠 Teknik Özellikler
Bu proje geliştirilirken sektör standartlarında yazılım prensipleri ve Unity'nin modern araçları kullanılmıştır:

Engine: Unity (C#)

Yazılım Mimarisi:

State-Driven Logic: Oyunun akışını (Menü, Oyun İçi, Game Over) yöneten merkezi kontrol yapıları.

Object Pooling: Performans kaybını önlemek için sık oluşturulan oyun nesnelerinin (efektler, halka parçaları) bellek yönetimi.

Input Management: Mobil cihazlar için optimize edilmiş, düşük gecikmeli dokunmatik kontrol sistemi.

UI/UX: Responsive (duyarlı) arayüz tasarımı ile farklı ekran çözünürlüklerine tam uyum.

📁 Proje Yapısı

RingBreaker/
├── Assets/
│   ├── Scripts/        # Oyun mantığı, kontrolcüler ve yardımcı sınıflar
│   ├── Prefabs/        # Tekrar kullanılabilir oyun nesneleri (Halkalar, Efektler)
│   ├── Scenes/         # Ana oyun ve menü sahneleri
│   └── Materials/      # Görsel stil ve shader yapılandırmaları

📦 Kurulum
Projeyi yerel ortamınızda çalıştırmak için şu adımları izleyin:
Depoyu klonlayın:
Bash git clone https://github.com/fikretkutluay/RingBreaker.git
Unity Hub'ı açın ve projeyi listeye ekleyin.

Unity sürümünü (2021.x veya üstü önerilir) seçerek projeyi başlatın.

Assets/Scenes klasöründeki ana sahneyi açarak Play tuşuna basın.

🚀 Gelecek Geliştirmeler

[ ] Yeni "Combo" sistemi ile ardışık vuruşlara ödül mekanizması.

[ ] Farklı halka tipleri (hareketli engeller, korumalı bölgeler).

[ ] Local Storage kullanılarak yüksek skor (High Score) kaydı.

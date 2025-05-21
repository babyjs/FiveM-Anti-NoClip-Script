🚫 FiveM Anti-Noclip Otomatik Ban Sistemi
Bu script, FiveM sunucularında noclip açarak hile yapan oyuncuları tespit edip otomatik olarak banlamanızı sağlar. Ayrıca olay Discord Webhook ile bildirilir.

🔍 Özellikler
Oyuncuların yerden yüksekliğini kontrol eder (noclip tespiti için).

Belirlenen yükseklikten fazla uçan oyuncuları izler.

3 kez uyarıdan sonra otomatik olarak banlar.

Banlanan oyuncular Discord webhook ile loglanır.

playerDropped ve playerConnecting eventleri ile veri temizliği yapılır.

1 dakikada bir otomatik bellek temizliği (performans için).

⚙️ Ayarlanabilir Değerler
checkInterval: Kaç milisaniyede bir kontrol yapılacağı (2000ms önerilir).

maxDistanceFromGround: Oyuncunun yerden en fazla kaç birim yukarıda olabileceği.

warningLimit: Oyuncu kaç kez uyarıldıktan sonra banlanacağı.

📦 Kurulum
webhookURL kısmına Discord Webhook URL’nizi girin.

Scripti sunucunuza bir resource olarak ekleyin.

server.cfg dosyanıza ensure ile ekleyin.

📌 Not
Bu script yalnızca noclip tespiti içindir. Araç içindeki oyuncular, paraşütle süzülenler veya düşenler otomatik olarak filtrelenir.


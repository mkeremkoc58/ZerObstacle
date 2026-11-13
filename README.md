# 🛡️ ZerObstacle

**ZerObstacle**, Türkiye'deki erişim engellerini (Discord, Roblox ve diğer tüm kısıtlanmış platformlar) klasik bir VPN'in yarattığı **ping artışı ve hız kaybı olmaksızın** ortadan kaldıran modern, yerel bir **DPI (Derin Paket İncelemesi) Bypass ve Akıllı Ağ Geçidi** aracıdır.

---

## ✨ Neden ZerObstacle?

- **Sıfır Ping (Yerel Çalışma):** Verilerinizi uzak sunuculara yönlendirmez. Bilgisayarınızdan çıkan TCP/TLS paket başlıklarını yerelde manipüle ederek İSS filtrelerini atlatır; oyunlardaki gecikmeniz (ms) değişmez.
- **Global Erişim:** Sadece tek bir uygulamayla sınırlı kalmayıp tüm engelli web sitelerine ve oyun sunucularına kesintisiz erişim sağlar.
- **Akıllı İstisna Listesi (Exclude):** Bankacılık uygulamaları, e-Devlet ve anti-cheat korumalı oyunlar için trafiği otomatik pas geçerek çakışmaları önler.
- **Sade ve Modern Arayüz:** Karmaşık `.bat` dosyaları ve komut satırı parametreleri yerine tek tuşla çalışan modern masaüstü deneyimi.

---

## 🛠️ Kurulum ve Kullanım (Geliştirme Aşaması)

```bash
git clone [https://github.com/mkeremkoc58/ZerObstacle.git](https://github.com/mkeremkoc58/ZerObstacle.git)
cd ZerObstacle
pip install pydivert
python core/engine.py

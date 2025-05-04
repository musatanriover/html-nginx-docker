# 🚀 HTML + NGINX Web Server with Docker Compose

Bu proje, Docker Compose kullanılarak oluşturulmuş basit bir HTML statik web sunucusudur.  
NGINX, web servisi sağlar; HTML ve CSS dosyaları ise yerel `html/` klasöründen yayınlanır.
---

## 🧱 Proje Yapısı

```bash
html-nginx-compose/
├── docker-compose.yml         # Compose servis tanımı
└── html/
    ├── index.html             # Anasayfa
    ├── hakkinda.html          # Hakkında sayfası
    ├── iletisim.html          # İletişim sayfası
    └── css/
        └── style.css          # Basit stil dosyası

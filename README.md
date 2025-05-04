# 🚀 HTML + NGINX Web Sunucusu (Docker Compose ile)

Bu proje, Docker Compose kullanılarak oluşturulmuş basit bir statik web sunucusudur.  
NGINX ile HTML ve CSS dosyaları yayınlanır. Hafif ve taşınabilir bir yapıdadır.

## 📦 Proje Yapısı

html-nginx-compose/
├── docker-compose.yml         # Docker Compose yapılandırması  
└── html/  
    ├── index.html             # Anasayfa  
    ├── hakkinda.html          # Hakkında sayfası  
    ├── iletisim.html          # İletişim sayfası  
    └── css/  
        └── style.css          # Temel CSS stilleri

## ⚙️ Kurulum ve Kullanım

1. Bu repoyu klonla:

git clone git@github.com:musatanriover/html-nginx-docker.git
cd html-nginx-docker


2. Docker Compose ile başlat:

docker compose up -d


3. Tarayıcıdan eriş:

http://localhost:8080

> Eğer bir sunucu üzerindeysen:  
> `http://<sunucu-ip-adresi>:8080`

## 🌐 Sayfalar

| Sayfa | Açıklama |
|-------|----------|
| `/index.html` | Ana sayfa |
| `/hakkinda.html` | Proje hakkında kısa bilgi |
| `/iletisim.html` | İletişim bilgileri |

## 🧼 Servisi Durdurmak İçin

docker compose down


## 📌 Notlar

- HTML/CSS dosyaları `html/` klasöründe saklanır  
- NGINX container içinde çalışır  
- Volume kullanılarak dış klasör bağlanır (read-only)

## ✨ Katkı ve Geliştirme

Projeyi geliştirmek, tema eklemek veya yeni sayfalar eklemek istersen `Pull Request` gönderebilirsin.

## 👤 Geliştirici

[@musatanriover](https://github.com/musatanriover)

## 📄 Lisans

MIT Lisansı – özgürce kullanabilir, geliştirebilirsin.

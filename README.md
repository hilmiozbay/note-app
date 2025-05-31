# Note App

Basit bir not defteri uygulaması. Node.js, Express, MongoDB ve Docker kullanılarak geliştirilmiştir.

## Özellikler

- Not ekleme ve silme
- MongoDB veritabanı entegrasyonu
- Docker container desteği
- Docker Compose ile çoklu servis yapılandırması

## Gereksinimler

- Docker
- Docker Compose

## Kurulum ve Çalıştırma

1. Projeyi klonlayın:
```bash
git clone https://github.com/hilmiozbay/note-app.git
cd note-app
```

2. Uygulamayı başlatın:
```bash
docker-compose up
```

3. Tarayıcınızda http://localhost:3000 adresine gidin

## Docker Image

Docker Hub'dan direkt olarak image'ı çekebilirsiniz:
```bash
docker pull ozbayhilmi/note-app:latest
```

Docker Hub Repository: https://hub.docker.com/r/ozbayhilmi/note-app

## Teknolojiler

- Backend: Node.js, Express
- Database: MongoDB
- Frontend: EJS, Bootstrap
- Container: Docker, Docker Compose

## Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasına bakın. 
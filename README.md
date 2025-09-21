Инструкция 

Выполнить
```bash
mkdir homework
cd homework
git clone https://github.com/RavilDev/service-discovery.git
git clone https://github.com/RavilDev/external-configuration.git
git clone https://github.com/RavilDev/api-gateway.git
git clone https://github.com/RavilDev/user-service.git
git clone https://github.com/RavilDev/infrastructure.git
```
в infrastructure добавить .env:
```
MAIL_USERNAME=your-email@gmail.com
MAIL_PASSWORD=your-app-password
```
Выполнить
```bash
cd infrastructure
docker-compose up --build
```





# Практические занятия 2, 3, 4

## 1. Установка Git, Docker и Docker Compose

### Проверка версии Git
![Git Version](./screenshots/git-version-screen.png)

### Проверка версии Docker
![Docker Version](./screenshots/docker-version-screen.png)

### Проверка версии Docker Compose
![Docker Compose Version](./screenshots/docker-compose-screen.png)

### Клонирование репозитория
![Clone Repository](./screenshots/git-clone-screen.png)

---

## 2. Запуск контейнера Nginx

Команда для запуска:
```bash
docker run -d -p 8080:80 -v $(pwd)/index.html:/usr/share/nginx/html/index.html nginx
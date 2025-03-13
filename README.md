# Docker Flask App

## Описание
Простое приложение на Flask, работающее в Docker-контейнере

## Установка и запуск

1. Соберите образ:
	'''sh
	docker build -t flask-app .
2. Запустите контейнер: 
	docker run -p 5000:5000 flask-app

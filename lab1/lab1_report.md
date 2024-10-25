#### University: [ITMO University](https://itmo.ru/ru/)
#### Faculty: [FTMI](https://ftmi.itmo.ru/)
#### Course: Cloud platforms as the basis of technology entrepreneurship
#### Year: 2024/2025
#### Group: U4225
#### Author: Lavrentev Nikita Yrievich
#### Lab: Lab1
#### Date of create: 21.10.2024
#### Date of finished: 25.10.2024

## Описание
Это первая лабораторная работа "Обзор Google Cloud и исследование основных сервисов."

## Цель работы
Ознакомиться с основными возможностями и преимуществами облачной платформы Google Cloud.

## Ход работы

### 1. Зашёл во вкладку IAM, нашёл пункт "Service account" и создал сервис-аккаунт с ролью Storage Admin

![image](https://github.com/user-attachments/assets/e360b699-aabe-4ecf-a89c-d3d6e42bd21c)

### 2. Зашёл во вкладку Compute engine и создал виртуальную машину с Machine type e2-micro в режиме spot.

![image](https://github.com/user-attachments/assets/a8ea08d2-b0cd-4ea9-ba16-caba5e24a411)

### 3. Используюя утилиту gsutils в SSH окне нашел бакет lab1-bucket-itmo и скопировал 3 файла (с помощью команды gsutil cp -r gs://lab1-bucket-itmo/ ./). 

![image](https://github.com/user-attachments/assets/1f382681-3227-4acc-be0e-12a35bcc5179)

### 4. Используя команду ls -lah видно, что папка скопирована на мою VM.

![image](https://github.com/user-attachments/assets/b57c91c0-9b08-433e-bafa-205bc2c3b6eb)

### 5. Изменил роль своего service account с Storage Admin на Compute Viewer, попробовал скопировать файлы - не получилось :(

![image](https://github.com/user-attachments/assets/4fe13a5b-5280-41d3-97c4-ae581ff423c0)

### Вывод:
Роль Storage Admin предоставляет полный контроль над контейнерами, папками, управляемыми папками и объектами, а Compute Viewer дает доступ только для чтения для получения и просмотра информации обо всех ресурсах Compute Engine, включая экземпляры, диски и брандмауэры. Позволяет получать и просматривать информацию о дисках, образах и снимках, но не позволяет читать хранящиеся на них данные.

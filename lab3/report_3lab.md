#### University: [ITMO University](https://itmo.ru/ru/)
#### Faculty: [FTMI](https://ftmi.itmo.ru/)
#### Course: [Cloud platforms as the basis of technology entrepreneurship]
#### Year: 2023/2024
#### Group: U4225
#### Author: Lavrentev Nikita Yrievich
#### Lab: Lab3
#### Date of create: 04.11.2024
#### Date of finished: 04.11.2024

## Описание
Это третья лабораторная работа Исследование Cloud Storage

## Цель работы
Ознакомиться с основными понятиями и принципами работы облачного хранилища, изучат различные модели хранения данных (блок, файл, объектное хранилище), познакомятся с основными сервисами и функционалом, предоставляемым облачными хранилищами.

## Ход работы

1. Выбралл существующий проект, в котором есть соответствующие разрешения
   
2. Создал Cloud Storage bucket - контейнер в Google Cloud Storage (GCS), служащий для организации и хранения объектов в GCS. 

![image](https://github.com/user-attachments/assets/36955ff0-295e-42fc-a62c-9c05dc722d39)

3. Загрузил 3 изображения в Cloud Storage bucket
   
![image](https://github.com/user-attachments/assets/7a9176b2-7976-4179-8786-de48b6810288)

4. Создал папку с названием "Characters" и переместил туда файлы (с помощью Move)

![image](https://github.com/user-attachments/assets/f1cdee71-16e1-42bf-ba88-cf6b8b9e1c15)

5. Настроил публичный доступ для файлов в настройках приватности

![image](https://github.com/user-attachments/assets/248207a4-bfd5-4af3-8da9-946bee9923b0)

6. Создал ссылку на файлы через контекстное меню файла

https://storage.cloud.google.com/lavrentev-bucket/characters/%D0%90%D0%BB%D0%B8%D1%8F%20%D0%A0%D1%8D%D0%B4%D0%B3%D1%80%D0%B8%D0%B2%D1%81.jpg
https://storage.cloud.google.com/lavrentev-bucket/characters/%D0%93%D0%B5%D0%BA%D0%B0%D1%82%D0%B0%20%D0%A1%D0%BF%D1%80%D0%B8%D0%BD%D0%B3%D1%84%D1%8D%D0%BB%D0%BB.jpg
https://storage.cloud.google.com/lavrentev-bucket/characters/%D0%9B%D0%B8%D0%BB%D0%B8%D1%82%20%D0%A2%D0%B5%D0%BD%D0%B5%D0%B1%D0%BE%D1%80%D0%BD.jpg

Проверил работоспособность ссылок:
![image](https://github.com/user-attachments/assets/fea09c10-a124-4d74-b1c2-716bb7b5e3ca)
![image](https://github.com/user-attachments/assets/da3d121f-de87-4c89-be76-3f364c0ab898)
![image](https://github.com/user-attachments/assets/b29e80b9-6ae1-47cf-a07b-70f84aad9506)

7. Удалил за собой все созданные сервисы

## Выводы
В ходе лабораторной работы был изучен Google Cloud Storage (GCS) — это облачное хранилище объектов от Google Cloud Platform, предоставляющее безопасный, масштабируемый и долговечный способ хранения данных. В этом хранилище файлы можно хранить в бакетах и производить различные действия с ними: загрузка в хранилище и извлечение, создание папок и перемещение файлов в папки, предоставление доступа (защита данных), создание ссылок на файлы и т.д.

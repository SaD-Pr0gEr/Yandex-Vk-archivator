# Архиватор фото с VK на Яндекс Диск

Проект для резервного копирования фотографий с ВК на Яндекс Диск. Для запуска проекта сначала установите зависимости! Для этого наберите команду 
```
pip install -r requirements.txt
```

Далее надо создать ```.env``` файл и туда добавить следующее
```
VK_TOKEN=токен с ВК
YANDEX_TOKEN=токен с Яндекс
USER_ID_VK=айди пользователя ВК
VERSION=версия ВК(можете просто ставить 5.77)
```
Запустите файл ```runner.py```
```
python runner.py
```

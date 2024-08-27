# grafana-homework
## 1. Скриншот веб-интерфейса grafana со списком подключенных Datasource
![изображение](https://github.com/user-attachments/assets/bbf2628f-b63d-48ae-92aa-f05cb9162b6c)


![изображение](https://github.com/user-attachments/assets/00058ba0-bfab-40db-8696-e5d129723981)

## 2. Создайте Dashboard и в ней создайте Panels:

- утилизация CPU для nodeexporter (в процентах, 100-idle);
  ![изображение](https://github.com/user-attachments/assets/bcf834cc-c0bd-4735-a1b2-d5f5aea38707)

- CPULA 1/5/15;
  ![изображение](https://github.com/user-attachments/assets/b119207c-7a0f-40ef-938b-58562576a9d9)

- количество свободной оперативной памяти;
  ![изображение](https://github.com/user-attachments/assets/4db66fe4-d026-41b5-9d75-c917c75fe4bf)

  
- количество места на файловой системе.
![изображение](https://github.com/user-attachments/assets/6c9c2c3c-4fe1-4922-8237-52fe028b98d9)

- Dashboard
  ![изображение](https://github.com/user-attachments/assets/74777e73-19d4-45f4-980e-f4ba08ff1284)

## 3. Alert
  - В качестве Contact Points настроен Telegram.
  - На панели "Утилизация CPU" настроен Alert.

![изображение](https://github.com/user-attachments/assets/05b18d84-84e0-41ae-86d9-ae9ec287d6ac)

В моменты срабатывания Alert приходят сообщения:

![изображение](https://github.com/user-attachments/assets/7470b87b-9c50-4141-bf63-0c7bcda0c5ba)

## 4. Сохранить dashboard.
   [Dashboard.json](Dashboard.json)

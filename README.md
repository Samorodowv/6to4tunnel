# 6to4tunnel
Обход блокировок на keenetic при помощи туннелирования ipv4 в ipv6

Заходим на https://6in4.ru 

![image](https://github.com/user-attachments/assets/79778b9a-6a89-4094-80b0-69b6167fb1e2)

Регистрируемся

Мы сейчас без vpn.
Нажимаем Add new tunnel

![image](https://github.com/user-attachments/assets/00365f46-7d63-4d4f-800a-2e3b93c62b29)


Теперь заходим на web-интерфейс роутера:

(http://192.168.1.1/)

Необходимо изменить набор компонентов:

![image](https://github.com/user-attachments/assets/6a8af09b-c977-4e73-92bd-e9ede9578138)

Устанавливаем поддержку протокола v6, если ещё не установлена:

![image](https://github.com/user-attachments/assets/1a29e07e-dc63-4b01-907b-61c9244690b6)

На роутере нажимаем добавить новый ip v6 туннель:

![image](https://github.com/user-attachments/assets/78d082cd-531a-4c74-b6f8-9df222caa815)

Берём настройки с сайта:

![image](https://github.com/user-attachments/assets/c2589f54-9a91-4c37-b3ee-2fb3a2a389d5)

Для поля адрес клиента ipv6 нужно удалить / и все цифры после него

После сохранения настроек необходимо убедиться что туннель активен:

![image](https://github.com/user-attachments/assets/07762797-68c2-49af-a09e-ffcad70e631e)

Переходим в "Приоритеты подключений", повышаем приоритет нашего нового соединения до самого высокого для политики по умолчанию:

![image](https://github.com/user-attachments/assets/7aaecf80-511d-41dd-8df8-3d0993035cae)

Проверяем работоспособность: (https://www.youtube.com/watch?v=dQw4w9WgXcQ)

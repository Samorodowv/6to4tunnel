# 6to4 Tunnel
Обход блокировок на Keenetic при помощи туннелирования IPv4 в IPv6

## Шаг 1: Регистрация на сайте
Заходим на [6in4.ru](https://6in4.ru) и регистрируемся.

<img src="https://github.com/user-attachments/assets/79778b9a-6a89-4094-80b0-69b6167fb1e2" width="600"/>

## Шаг 2: Создание туннеля
Мы сейчас без VPN. Нажимаем "Add new tunnel".

<img src="https://github.com/user-attachments/assets/00365f46-7d63-4d4f-800a-2e3b93c62b29" width="600"/>

## Шаг 3: Настройка роутера
Теперь заходим на веб-интерфейс роутера: [http://192.168.1.1/](http://192.168.1.1/)

### Изменение набора компонентов
Необходимо изменить набор компонентов.

<img src="https://github.com/user-attachments/assets/6a8af09b-c977-4e73-92bd-e9ede9578138" width="600"/>

### Поддержка IPv6
Устанавливаем поддержку протокола IPv6, если ещё не установлена.

<img src="https://github.com/user-attachments/assets/1a29e07e-dc63-4b01-907b-61c9244690b6" width="600"/>

## Шаг 4: Добавление нового IPv6 туннеля
На роутере нажимаем "Добавить новый IPv6 туннель".

<img src="https://github.com/user-attachments/assets/78d082cd-531a-4c74-b6f8-9df222caa815" width="600"/>

Берём настройки с сайта.

<img src="https://github.com/user-attachments/assets/c2589f54-9a91-4c37-b3ee-2fb3a2a389d5" width="600"/>

**Примечание:** Для поля "Адрес клиента IPv6" нужно удалить "/" и все цифры после него.

## Шаг 5: Проверка активации туннеля
После сохранения настроек необходимо убедиться, что туннель активен.

<img src="https://github.com/user-attachments/assets/07762797-68c2-49af-a09e-ffcad70e631e" width="600"/>

## Шаг 6: Установка приоритетов
Переходим в "Приоритеты подключений" и повышаем приоритет нашего нового соединения до самого высокого для политики по умолчанию.

<img src="https://github.com/user-attachments/assets/7aaecf80-511d-41dd-8df8-3d0993035cae" width="600"/>

## Шаг 7: Проверка работоспособности
Проверяем работоспособность: [ссылка на тест](https://www.youtube.com/watch?v=dQw4w9WgXcQ)

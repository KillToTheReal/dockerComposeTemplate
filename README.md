# dockerComposeTemplate

## Задача о создании окружения для работы в php. 
## Необходимые штуки:
- Nginx - сервер (80:80, 443:443)
- PHP версии 7+ (Здесь 7.4)
- Xdebug (9003 с версии 3) 
- Composer
- MySQL (3306)
### Для запуска:
- Docker (Соответственно WSL2 на WIN10)
- PHPStorm
- Свободные порты перечисленные выше
- Консольная команда "docker-compose up -d" из корневой директории
- При наличии библиотек composer добавляется команда ``` composer install ```

### Реализовано с помощью PHPStorm (При установке не забудь назначить сервера, порт Xdebug, прослушка дебага и всё такое)


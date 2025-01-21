Docker
=========

Роль устанавливает Docker

Role Variables
--------------

"gpg_key_url" - путь до gpg ключа, который нужно установить. Для пропуска установите значение "" (пустая строка). (По умолчанию:  https://download.docker.com/linux/ubuntu/gpg)<br>
"docker_repository" - репозиторий откуда устанавливаем Docker. (По умолчанию: deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable)<br>
"started" - нужно ли запустить Docker: true/false. (По умолчанию: true)<br>
"docker_package" - Пакет докера, который хотите установить. (По умолчанию: docker.io)

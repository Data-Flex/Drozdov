Создание SSH ключа:
    1) Открыть терминал
    2) Ввести команду ssh-keygen -t ed 25519 -C "email"

Добавление ключа в аккаунт ан GitHub:
    1) Зайти в Settings -> SSH and GPG keys -> new SSH key
    2) Ввести в терминал команду ssh -T git@github.com
    3) Ввести в терминал команду ssh-add *имя папки*/*имя SSH ключа*

Клонирование репозиторияЖ
    1) При помощи комнады cd перейти в нужную папку
    2) Веести команду git clone *SSH URL нужного репозитория на GitHub*
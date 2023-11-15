# MimeBot
Простой юзербот для Telegram.
https://github.com/figureteam/MimeBot/
# Установка
## Требования
- Python 3.11 (и выше)
- Ключ и хэш Telegram API
- Прямые руки
## Процесс установки
1. Клонируем репозиторий: `git clone https://github.com/figureteam/MimeBot/`
2. Создаем виртуальную среду (https://docs.python.org/3/library/venv.html) (необязательно, но желательно)
3. Устанавливаем все необходимые пакеты: `pip install -r requirements.txt`
4. Открываем `main.py`, ставим `api_id`, `api_hash` (получите их на https://my.telegram.org) и язык ответов команд.
5. Запускаем: `python main.py`
6. Вводим номер телефона и код подтверждения.
## Готово!
Поздравляю! Вы установили MimeBot.
Теперь Вы можете вводить команды, список которых открывается по команде `m.help`
# Баги
- В большинстве случаев не работает команда `m.catgif`
- Иногда не работает команда `m.wiki`

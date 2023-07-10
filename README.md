Телефонный справочник
Описание задачи.
Создать телефонный справочник с возможностью импорта и экспорта данных в нескольких форматах.
Под форматами понимаем структуру файлов, например: в файле на одной строке хранится одна часть записи, пустая строка - разделитель.

Дедлайн: до 10:00 16.06.2022

Команда

Игорь (тимлид) - https://github.com/IgorPont/
Инна - https://github.com/InnaTkacheva
Антон - https://github.com/AntonMolchanov006
Светлана - https://github.com/Ssinits
Юлия - https://github.com/JuliaLomako
Структура приложения (модули)

main (основной модуль) - ответственный Игорь
logger (модуль логирования) - ответственный Игорь
bot.py (модуль телеграм-бота) - ответственный Игорь
.gitignore (не требует комментариев) - ответственный Игорь
crud (создание, чтение, обновление, удаление) - ответственная Инна
user_interface (модуль взаимодействия с пользователем) - ответственный Антон
data_generation (модуль генерации БД) - ответственные Светлана и Юлия
Как запустить проект (рекомендуем использовать VCS)

Для запуска с помощью консоли:
скачать проект в локальный репозиторий;
в консоли ввести команду "python3 main.py";
в случае необходимости создания рандомной базы контактов раскоменнтировать строку #7 (метод dg.start()) модуля main.py;
следовать инструкциям в консоле.
Для запуска телеграм-бота:
скачать проект в локальный репозиторий;
обновить Python до версии 3.10.5;
настроить окружение, введя в консоле поочередно команды:
python3 -m venv .libraries;
pip install pyTelegramBotAPI;
при необходимости обновить библиотеку до последней версии (следуя инструкциям в консоле)
перезапустить консоль;
в корневой папке проекта (Phonebook_team_development) создать файл с названием "token.csv", в котором в первой строке добавить индивидуальный токен телеграм-бота, после чего сохранить изменения файла;
инструкция по созданию индивидуального токена телеграм-бота здесь: https://core.telegram.org/bots
в консоле ввести команду "python3 bot.py" или "python bot.py" (при необходимости установить версию Python 3.10.5)
Задачи, выполненные командой

До 09:00 12.06.2022 выполнить:
Выбрать задачу (выполнено)
Сформировать команду (выполнено)
Определить руководителя на проекте (выполнено)
Создать репозиторий(скорее всего ответственность руководителя), добавив Readme с указанием необходимой информации (задача, команда, дедлайн, модули т. д. (выполнено)
Распределить роли и зоны ответственности между участниками (выполнено)
Приступить к реализации проекта (каждому ответственному за модуль описать в файле соответствующего модуля, какие методы он планирует применять для реализации) (выполнено)
Обсудить каждый модуль командой и приступить к написанию кода (выполнено)
До 10:00 20.06.2022 выполнить:
Написать и добавить методы в каждый модуль (выполнено)
До 10:00 27.06.2022 выполнить:
Добавить модули с ботом телеграмм (выполнено)
Сдать окончательный вариант проекта (выполнено)
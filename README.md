# Seminar_10
**Задача:** при помощи виртуального окружения и PIP реализовать решение задач с прошлых семинаров:

1. Создать калькулятор для работы с рациональными и комплексными числами, организовать меню, добавив в неё систему логирования
2. Создайте программу для игры в ""Крестики-нолики"" при помощи виртуального окружения и PIP

# Homework(Seminar_10)

  Прикрутить бота к задачам с предыдущего семинара:
  Создать калькулятор для работы с рациональными и комплексными числами, организовать меню, добавив в неё систему логирования

## Run bot

1. Создать ВО: python -m venv venv (где второй venv имя папки для ВО);
2. Если используете VSCode активировать ВО: 
-  для win: venv\Scripts\activate.bat
-  для linux: sourse venv/bin/activate
(где venv/ и т.д. по сути путь до активатора)
(если используете PyCharm 3 шаг можно пропустить, насколько понял он автоматом запускает ВО)
3. Устанавливаем необходимые библиотеки из файла reqirements.txt: pip install -r reqirements.txt;
4. В telegramm через fatherbot создаем бота и получаем токен;
5. В файле config.py необходимо указать токен вашего бота;
6. Запускаем командой в консоли: python main.py;
7. в окне telegramma отправляем боту команду /start;
8. Бот запущен!
   
## Основные возможности bot

### bot_2

1. Отсутствует кнопочное меню выбора комманд;
2. Реализована игра в "крестики-нолики" без кнопочного интерфейса;
3. Есть возможно считать примеры в том числе с комплексными числами;
4. Реализованно два логирование:
   - Логирование без использования встроенных библиотек;
   - Логирование с использование встроенной библиотеки(реализовано упрощенно);

# Генерация seed фраз, адресов кошельков и приватных ключей к ним

   
!! Автор скрипта PLushkin https://t.me/plushkin_blog        

Многие скрипты для абуза требуют приватные ключи. Но у многих, кто давно держит фермы этих самых ключей нет. только сидфразы записаны.

Поэтому скрипт работает в двух режимах: 1. генерирует сид-фразу сам 2. берет готовые сид из файла.

Т.е. если вам надо получить массово приватники к вашим кошелькам.  сохраняете в файл mnemonic.txt свои мнемоники, запускаете скрипт и на вопрос сгенерировать новые seed - отвечаете "n". Тогда скрипт из ваших сидов сделает табличку эксель со всеми данными.

Скрипт чувствителен к папке из которой вы его запускаете (влияет на пути к файлам)!


# Установка и запуск:

Linux/Mac - https://www.youtube.com/watch?v=8rJ-96cPFwU
```
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt

python main.py
```
Windows - https://www.youtube.com/watch?v=EqC42mnbByc
```
pip install virtualenv
virtualenv .venv
.venv\Scripts\activate
pip install -r requirements.txt

python main.py
```



# Запуск Python модулів
Про те як створювати та запускати Python модулі. Для цього тобі потрібно спочатку встановити
Python.
Перед тим як почати створи на робочому столі папку `programing`. В ній ми створимо та запустимо нашу першу програму.

* [Запуск на системі Ubuntu](#Ubuntu)
* [Запуск на системі Windows](#Windows)
* [Запуск на системі MacOS](#MacOS)

## Ubuntu
Створи в папці `programing` файл з назвою`main.py` та запиши в нього наступний вміст.
```python
print("Hello world!")
```

Далі в папці `programing` потрібно відкрити термінал.


![Запуск термінала](img/ub_terminal_in_folder.png)

Програму можна запустити цією командою `python3.8 main.py`.


![Запуск програми](img/ub_run_main.png)

## Windows
Створи файл з назвою `main` в папці `programing` та відкрий його в блокноті і запиши наступний вміст:
```python
print("Hello world!")
```
Після цього, нам потрібно збергти цей файл з розширенням `.py`, для цього натисни `ctrl+shift+s`.
![Збереження файла з потрібним розширенням](img/wn_create_file.png)

Тепер файл з типом "Текстовий документ" можна видалити.


![Список файлів](img/wn_ls.png)

Зараз ми відкриємо командний рядок в папці `programing`, для цього відкрий цю папку, і в рядку шляху заміни `programing` на `cmd` та натисни `Enter`.

![Відкрити командний рядок](img/wn_open_cmd.png)

Тобі має відкритися командний рядок. Щоб запустити нашу програму виконай команду `python main.py`.

> **_УВАГА:_** При написані або виконанні Python програми твій антивірус може розцінювати програму як вірус.
Це очікувана реакція антивіруса так як Python програми часто використовуються в якості вірусів, і він не може знати чи ти вирішив
вивчити програмування чи на твій комп'ютер потрапив вірус.
В цьому випадку просто дозволь виконати файл.

![Запуск програми з командного рядка](img/wn_cmd_ph.png)

## MacOS
Перед тим як почати зайди в`Налаштування системи` далі `Клавіатура` і розділ `Клавіатурні скорочення` та переконайся щоб опція `Новий термінал у папці` була включена.
Це дозволить нам відкрити термінал прямо в нашій папці.

![Включити опцію термінала](img/mac_enable_terminal.png)

Наступним кроком створи на робочому столі папку `programing`. І відкрий її в терміналі

![Відкрити папку в терміналі](img/mac_open_folder_in_terminal.png)

Після цього, в терміналі виконай команду `touch main.py`, вона створить файл в якому ми будемо писати код.

![Створити файл через термінал](img/mac_touch_file.png)

Далі відкрий цей файл в текстовому редакторі та запиши туди
```python
print("Hello world!")
```
Тепер назад до терміналу, наступна команда запустить наш файл `python3.8 main.py`

![Запустити файл](img/mac_run_script.png)

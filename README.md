# python-guides
Як встановити Python на свій комп'ютер?
Що таке інтерпретатор та як він виглядає на різних ОС?

## Встановлення на Windows
Зайди на https://www.python.org/downloads/
Натисни на "Download Python", після цьго на твій комп'ютер буде завантажений файл установки Python.


## Встановлення на Ubuntu
Запусти термінал, це можна зробити за допомогою команди `ctrl+alt+t`.
І виконай наступні команди.
Ці дві команди оновлять система та встановлять необхідні інтрументи для менеджера `apt`.

```
sudo apt update
sudo apt install software-properties-common
```
Ця команда додає репозиторій в якому менеджер `apt` шукатиме програми для встановлення.
```
sudo add-apt-repository ppa:deadsnakes/ppa
```
Знову потрібно виконати оновлення, і другою командою встановити Python.
```
sudo apt update
sudo apt install python3.7
```
## Встановлення на Mac

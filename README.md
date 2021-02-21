# Lab6_1_HCSR04

# Опис
Далекомір HCSR04 працює наступним чином:
1. Пристрій отримує сигнал (логічна одиниця) з мінімальною тривалістю 10 us
2. Пристрій видає звук і чекає на його повернення
3. При отриманні відбитого сигналу далекомір подає імпульс (тривалість якого рівна часу польоту звуку туди і назад) на ECHO
4. Якщо звук не було отримано тривалість сигналу = 38ms


Схема підключення присторю:
![](https://i.imgur.com/MrNKz6Q.jpg)

Задля боротьби з брязкотом і "стрибками" відстані було використано два резистори для TRIG і ECHO

Інформація передається за допомогою USB COMPORT-у

![](https://i.imgur.com/cTgqw0N.jpg)

## Посилання на відео:
[![Watch the video](https://img.youtube.com/vi/tkTmuXq8x10/maxresdefault.jpg)](https://youtu.be/tkTmuXq8x10)
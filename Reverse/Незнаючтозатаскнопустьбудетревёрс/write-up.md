# Описание
На вход получаем `.exe` файл
# Решение
1. Открываем файл, видим что флаг где-то тут.
![](/Reverse/Незнаючтозатаскнопустьбудетревёрс/1.png)
2. прогоняем strings + grep по файлу, видим что тут есть только часть флага
![](/Reverse/Незнаючтозатаскнопустьбудетревёрс/2.png)
3. Смотрим в гидру и не находим зацепок
![](/Reverse/Незнаючтозатаскнопустьбудетревёрс/3.png)
4. Собираем мем дамп
![](/Reverse/Незнаючтозатаскнопустьбудетревёрс/4.png)
5. прогоняем strings + grep на `ctf{` по всему дампу и получаем флаг
![](/Reverse/Незнаючтозатаскнопустьбудетревёрс/5.png)

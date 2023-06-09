# Проект 0. Угадай число

## Оглавление  
[1. Описание проекта](https://github.com/DariaGubskaya/SF_rep/tree/main/Project0#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0)  
[2. Какой кейс решаем?](https://github.com/DariaGubskaya/SF_rep/tree/main/Project0#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0)    
[3. Этапы работы над проектом](https://github.com/DariaGubskaya/SF_rep/tree/main/Project0#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0)  
[4. Результат](https://github.com/DariaGubskaya/SF_rep/tree/main/Project0#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0)    
[5. Выводы](https://github.com/DariaGubskaya/SF_rep/tree/main/Project0#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0) 

### Описание проекта    
Нужно написать программу, которая угадывает число за минимальное число попыток.

:arrow_up:[к оглавлению](https://github.com/DariaGubskaya/SF_rep/tree/main/Project0#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0)


### Какой кейс решаем?    
Нужно написать программу, которая угадывает число за минимальное число попыток

**Условия соревнования:**  
- Компьютер загадывает целое число от 1 до 100, и нам его нужно угадать. Под «угадать», подразумевается «написать программу, которая угадывает число».
- Алгоритм учитывает информацию о том, больше ли случайное число или меньше нужного нам.
- Необходимо добиться того, чтобы программа угадывала число меньше, чем за 20 попыток.

**Метрика качества**     
Результаты оцениваются по среднему количеству попыток при 1000 повторений

**Что практикуем**     
Учимся писать хороший код на python


### Этапы работы над проектом  
1.  Сначала устанавливаем любое random число, 
    проверяем больше или меньше загаданного, 
    сокращаем диапазон поиска, устанавливая верхнюю или нижнюю границу в соответствии с результатом,
    устанавливаем число, как середина нового диапазона, и проверяем, в какой из половин загаданное число.
    Функция принимает загаданное число и возвращает число попыток.
2. Проверяем, за какое количество попыток в среднем за 10000 подходов угадывает наш алгоритм.

:arrow_up:[к оглавлению](https://github.com/DariaGubskaya/SF_rep/tree/main/Project0#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0)


### Результаты:  
В среднем, программа угадывает число за 5 попыток.

:arrow_up:[к оглавлению](https://github.com/DariaGubskaya/SF_rep/tree/main/Project0#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0)


### Выводы:  
Предложенный алгоритм успешно справляется с задачей.
В среднем, угадывает число за 5 попыток, что меньше целевого показателя в 20 попыток.

:arrow_up:[к оглавлению](https://github.com/DariaGubskaya/SF_rep/tree/main/Project0#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0)
# Проект 0. Угадай число

## Оглавление  
[1. Описание проекта](https://github.com/balkhinag/Project_0/blob/main/README.md#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0а)  
[2. Какой кейс решаем?](https://github.com/balkhinag/Project_0/blob/main/README.md#%D0%BA%D0%B0%D0%BA%D0%BE%D0%B9-%D0%BA%D0%B5%D0%B9%D1%81-%D1%80%D0%B5%D1%88%D0%B0%D0%B5%D0%BC)  
[3. Краткая информация о данных](https://github.com/balkhinag/Project_0/blob/main/README.md#%D0%BA%D1%80%D0%B0%D1%82%D0%BA%D0%B0%D1%8F-%D0%B8%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%86%D0%B8%D1%8F-%D0%BE-%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85)  
[4. Этапы работы над проектом](https://github.com/balkhinag/Project_0/blob/main/README.md#%D1%8D%D1%82%D0%B0%D0%BF%D1%8B-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D1%8B-%D0%BD%D0%B0%D0%B4-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%BE%D0%BC)  
[5. Результат](https://github.com/balkhinag/Project_0/blob/main/README.md#%D0%B2%D1%8B%D0%B2%D0%BE%D0%B4%D1%8B)    
[6. Выводы](https://github.com/balkhinag/Project_0/blob/main/README.md#%D0%B2%D1%8B%D0%B2%D0%BE%D0%B4%D1%8B) 

### Описание проекта    
Угадать загаданное компьютером число за минимальное количество попыток

:arrow_up:[к оглавлению](https://github.com/balkhinag/Project_0/blob/main/README.md#%D0%BE%D0%B3%D0%BB%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5)


### Какой кейс решаем?    
Нужно написать программу, которая угадывает загаданное компьютером число за минимальное число попыток

**Условия соревнования:**  
- Компьютер загадывает целое число от 1 до 100, и нам его нужно угадать. Под «угадать» подразумевается «написать программу, которая угадывает число».
- Алгоритм учитывает информацию о том, больше ли случайное число или меньше нужного нам.

**Метрика качества**     
Результаты оцениваются по среднему количеству попыток при 1000 повторений

**Что практикуем**     
Учимся писать хороший код на python


### Краткая информация о данных
....
  
:arrow_up:[к оглавлению](https://github.com/balkhinag/Project_0/blob/main/README.md#%D0%BE%D0%B3%D0%BB%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5


### Этапы работы над проектом  
Проект состоит из двух этапов:
- создается функция угадывания загаданного числа
- создается функция, которая расчитывает, за какое количство попыток в среднем за 1000 подходов угадывает наш алгоритм

:arrow_up:[к оглавлению](https://github.com/balkhinag/Project_0/blob/main/README.md#%D0%BE%D0%B3%D0%BB%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5)


### Результаты:  
Написана программа, которая угадывает загаданное число в среднем за 5 попыток

:arrow_up:[к оглавлению](https://github.com/balkhinag/Project_0/blob/main/README.md#%D0%BE%D0%B3%D0%BB%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5)


### Выводы:  
Нам удалось написать программу, которая гарантировано угадывает загаданное число за log2(n) попыток, при n = 100 это 7 попыток. В среднем алгоритм угадывает число за 5 попыток

:arrow_up:[к оглавлению](https://github.com/balkhinag/Project_0/blob/main/README.md#%D0%BE%D0%B3%D0%BB%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5)

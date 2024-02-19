# 1_laba
## 00_distance.py
### Условие 
![image](https://github.com/gwoso/1_laba/assets/150545779/b8caf1a1-59ff-48d4-85f2-b33e84003f40)
### Алгоритм
1. Создаём цикл `for` для города `c1` из списка городов
2. Создаём цикл `for` для города `c2`
3. Проверка на различие городов `c1` и `c2` и на то, что расстояние между ними ещё не было вычислено ранее.
4. Получаем координаты обоих городов
5. Вычисляем расстояние `s` между ними
6. Записываем найденное расстояние в словарь `distances` к паре городов `(c1, c2)`
7. Выводим расстояния между всеми парами городов.
### Результат
![image](https://github.com/gwoso/1_laba/assets/150545779/00d70610-3070-44e3-99df-c70834acf4f1)
## 01_circle.py
### Условие 
![image](https://github.com/gwoso/1_laba/assets/150545779/3e1b4c9f-ea97-4897-b96b-d151a39da7eb)
### Алгоритм 
1. Инициализируем число `pi = 3.1415926`, площадь круга `S = pi * radius**2`
2. Выводим значение `S` с точностью 4 цифр после запятой 
3. Инициализируем координаты точки 1. `x1 = 23` и `y1 = 34`
4. Инициализируем координаты точки 2. `x2 = 30` и `y2 = 30`
5. Создаём функцию `func`, которая проверяет то, находится ли точка внутри круга `(x**2 + y**2)**0.5 < radius`
6. Выводим результат
### Результат
![image](https://github.com/gwoso/1_laba/assets/150545779/5b9aa7df-574a-49f4-90ec-dba9e5188cdc)
## 02_operations.py
### Условие 
![image](https://github.com/gwoso/1_laba/assets/150545779/b66224ea-cbc6-4940-8781-44ca858af48a)
### Алгоритм 
1. Создаём переменную `asd`, в которой записываем выражение, при выполнении которого должно получится число 25
2. Выводим ответ
### Результат
![image](https://github.com/gwoso/1_laba/assets/150545779/c6f54da9-874e-46ba-8ffd-624621e2b528)
## 03_favorite_movies.py
### Условие
![image](https://github.com/gwoso/1_laba/assets/150545779/c23ef532-4797-46da-8143-249cfda3b24a)
### Алгоритм
1. Подсчитываем количество букв (включая пробелы) в названиях фильмов, количество символов до/после названия фильма.
2. Для каждого фильма отдельно выводим результат
### Результат 
![image](https://github.com/gwoso/1_laba/assets/150545779/254e0e66-9da1-478a-ae97-3696fbc6b3a4)
## 04_my_family.py
### Условие 
![image](https://github.com/gwoso/1_laba/assets/150545779/c6a9b0bf-bc15-4958-b6fb-54cb533a7f44)
### Алгоритм
1. Создаём в `my_family_height` список роста у членов семьи
2. Выводим их рост
3. Выводим сумму ростов. Для этого нужно будет использовать цикл `for` для `x`, равный длине списка.
### Результат
![image](https://github.com/gwoso/1_laba/assets/150545779/70e5b6ef-cd45-486c-a8c3-74db55706ada)
## 05_zoo.py
### Условие
![image](https://github.com/gwoso/1_laba/assets/150545779/5d2531e6-85a0-43af-838a-009088550201)
### Алгоритм
1. Чтобы добавить медведя на место 1 индекса, используем `zoo.insert` и выведем получившийся список
2. Чтобы к списку животных добавить список птиц, просто используем `+=`
3. Для удаления слона из списка используем `zoo.remove`
4. Для вывода номера клетки нужно к индеку добавить 1
### Результат
![image](https://github.com/gwoso/1_laba/assets/150545779/ec9f639a-3aa6-4e99-8254-ecfde3bf43ce)
## 06_songs_list.py
### Условие
![image](https://github.com/gwoso/1_laba/assets/150545779/a79dab7c-6ed8-467b-8c34-de213159f630)
### Алгоритм
1. Инициализируем `summa1` и складываем значения трёх нужных песен по индексам [строка][столбец]
2. Выводим их на экран с точностью 2 цифры после запятой с помощью функции `round`
3. Инициализируем `summa2` и складываем значения трёх песен по [названию]
4. Выводим вторую сумму
### Результат
![image](https://github.com/gwoso/1_laba/assets/150545779/673f3345-0d6f-4340-ace7-3fe82d7d9cd0)
## 07_secret.py
### Условие 
![image](https://github.com/gwoso/1_laba/assets/150545779/bdde18c3-3d8c-495e-b2b8-a0517b8f9499)
### Алгоритм 
1. Первое слово - нулевая строка, третий символ (по индексу)
2. Второе слово - первая строка, символы с 9 до 12
3. Третье слово - вторая строка, символы с 5 до 13 с шагом 2
4. Четвёртое слово - третья строка, симолы с 7 до 12, зеркально переворачивает слово
5. Пятое слово - четвёртая строка, символы с 16 до 20, зеркальный переворот слова
6. В переменной `biba` записываем получившиеся слова через пробел
7. Выводим результат
### Результат 
![image](https://github.com/gwoso/1_laba/assets/150545779/3b99015d-df5a-4e40-b1fe-cb17c13f621c)


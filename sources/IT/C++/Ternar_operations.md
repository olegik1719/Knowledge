# Тернарный оператор

Tернарный оператор - это краткое условие

Есть два варианта использования

```
 условие ? значение если да : значение если нет;
```

```
 условие ? действие если да : действие если нет;
```

​Пример использования:

```c++
 int r = random_number();
 int a = r%2 ? 3 : 5; // Возвращает 3, если r четное, иначе 5.
```

```c++
 int r = random_number();
 int a;
 r%2 ? a = 3 : a = 5; // Вместо возвращения значений, вопролняет действие.
```


# Домашнее задание по теме "Генераторные сборки"

Если вы решали старую версию задачи, проверка будет производиться по ней.

Ссылка на старую версию [тут](https://docs.google.com/document/d/13ZVpKDsanaidhrKoEzuI1D04eZCTypPeCqa-nMPXJuI/edit?usp=sharing).

Цель: понять механизм создания генераторных сборок и использования встроенных
функций-генераторов.

Задача:

Дано 2 списка:
```
first = ['Strings', 'Student', 'Computers']
second = ['Строка', 'Урбан', 'Компьютер']
```

Необходимо создать 2 генераторных сборки:
1. В переменную ```first_result``` запишите генераторную сборку, которая
   высчитывает разницу длин строк из списков ```first``` и ```second```, если
   их длины не равны. Для перебора строк попарно из двух списков используйте
   функцию ```zip```.
2. В переменную ```second_result``` запишите генераторную сборку, которая
   содержит результаты сравнения длин строк в одинаковых позициях из
   списков ```first``` и ```second```. Составьте эту сборку НЕ используя
   функцию ```zip```. Используйте функции ```range``` и ```len```.

Пример результата выполнения программы:

Пример выполнения кода:
```
print(list(first_result))
print(list(second_result))
```

Вывод в консоль:
```
[1, 2]
[False, False, True]
```

Примечания:
1. Это небольшая практика, поэтому важность выполнения каждого условия
   обязательна.

Файл module_9_3.py и загрузите его на ваш GitHub репозиторий. В решении
пришлите ссылку на него.

Успехов!

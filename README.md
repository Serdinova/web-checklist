# code-style
1. Импорты:
- отделять node_modules от моих импортов,
- не нужен index,
- не надо подкапотной логики,
- если библа делится, то не тащить всю.
2. Выпиливать дефолтные комментарии.
3. Выносить большие функции в отдельные файлы.
4. Единый стиль объявление функций, styled, imports.
5. Вложенность компонент - 2-3 уровня.

# optimization / clean architecture
1. Максимум реформата данных на сервере, а не на клиенте.
2. Минимизировать дублирующийся код (ошибки обрабатывать в одном месте, объекты через spread).
3. Обрабатывать ошибки в роутах, чтобы роут не сломал приложение.
4. Шрифты грузить в первую очередь

# react/redux
1. Requestы в одном месте - есть смысл, если они global state.
2. Recompose : withState делать как WithReducer если их много, не делать лишних pure


# seo

# css-style

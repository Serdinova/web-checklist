# code-style
1. Импорты:
- отделять node_modules от моих импортов,
- не нужен index,
- не надо подкапотной логики,
- если библа делится, то не тащить всю.
2. Выпиливать дефолтные комментарии.
3. Выносить большие функции в отдельные файлы.

# optimization / clean architecture
1. Максимум реформата данных на сервере, а не на клиенте.
2. Минимизировать дублирующийся код (ошибки обрабатывать в одном месте, объекты через spread).
3. Обрабатывать ошибки в роутах, чтобы роут не сломал приложение.

# react/redux
1. Requestы в одном месте - есть смысл, если они global state.
2. Recompose : withState делать как WithReducer если их много, не делать лишних pure
3. Не мешать global state и local state
4. Хендлеры можно начинать  спрефикса handle...
5. В пропсы не передавать анонимные функции

# seo
1. Мета-теги (title, description, keywords).
2. alt и title на img.
3. robots.txt: добавлять host и site-map
4. sitemap.xml

# css-style
1. line-height 150% => 1.5
2. все размеры лучше кратно 2px

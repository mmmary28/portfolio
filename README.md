# Портфолио — инструкция по запуску

## Структура файлов

```
portfolio/
├── index.html        ← весь сайт
├── images/           ← создай эту папку и положи туда фото
│   ├── book1-cover.jpg
│   ├── book1-spread1.jpg
│   ├── book1-spread2.jpg
│   ├── book1-spread3.jpg
│   ├── book1-detail1.jpg
│   └── ...
└── README.md
```

## Как добавить свои изображения

В `index.html` найди закомментированные строки вида:
```html
<!-- <img src="images/book1-cover.jpg" alt=""> -->
```
Убери `<!--` и `-->`, и под ней удали строку с `cover-placeholder`.

## Как запустить на GitHub Pages

1. Создай аккаунт на github.com
2. Нажми «New repository», назови его `portfolio`
3. Загрузи все файлы (index.html + папку images)
4. Зайди в Settings → Pages → Source: main branch → Save
5. Сайт будет на `https://твоёимя.github.io/portfolio`

## Как подключить свой домен

1. Купи домен (namecheap.com, ~$10/год)
2. В GitHub: Settings → Pages → Custom domain → введи домен
3. У регистратора добавь DNS-записи типа A:
   - 185.199.108.153
   - 185.199.109.153
   - 185.199.110.153
   - 185.199.111.153
4. Подожди до 24 часов — сайт заработает на своём домене

## Как редактировать содержимое

Открой `index.html` в любом текстовом редакторе (VS Code, Notepad).
Найди и замени:
- `Имя Фамилия` — твоё имя
- `Название книги` / `Издательство · 2024` — данные каждой книги
- Текст в `about-text` — о себе
- `name@email.com` — свой email

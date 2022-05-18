


- задаем body основной цвет фона и текста в body
- убираем точки в списках через ul, если надо оставить , то лучше через класс list
- задаем цвет логотипу logo и logo-span
- стилизация навигации
- .link:hover задать цвет ссылкам при нажатии
- назначить :root через color: var(--... )
- задаю стиль кнопке через класс button
- необходимо из конопок делать display: inline-block
- задаем кнопке border: 1px solid transparent;

- установить - нормализацию и шрифт в html
<link href="https://fonts.googleapis.com/css2?family=Raleway:wght@700&family=Roboto:wght@400;500;700;900&display=swap"
        rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/modern-normalize/1.0.0/modern-normalize.min.css" />
- в CSS

html {
    box-sizing: border-box;
}

*,
*::before,
*::after {
    box-sizing: border-box;
}

- центрирование элементов секции hero через наследование всех элементов - ставим text-align: center в классе hero
- оборачиваем центрированные куски в контейнер и даем ему class= conteiner   (margin-left: auto;
    margin-right: auto;
    width: 1170px;)
- создаем flex

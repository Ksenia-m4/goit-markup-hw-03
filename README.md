# goit-markup-hw-02

- Создай репозиторий goit-markup-hw-02.
- Склонируй созданный репозиторий и скопируй в него файлы предыдущей работы.
- Выполни разметку и оформление макета страницы домашнего задания #2.
- Для оптимизации изображений используй сервис squoosh.
- Настрой GitHub Pages и добавь ссылку на живую страницу в шапку GitHub-репозитория.

**Критерии приёма работы наставником**
**Проект**

- В корне проекта есть папка images с изображениями.
- В корне проекта есть папка css с файлами стилей.
- Все стили написаны в одном файле styles.css, который находится в папке css.
- В названиях файлов нет заглавных букв, пробелов и транслита, только буквы и слова английского языка.
- Исходный код отформатирован при помощи Prettier.
- Все изображения и текстовый контент взяты из макета.
- Все растровые изображения оптимизированы используя squoosh.
- Код написан следуя руководству.

**Разметка**

- Разметка страницы Портфолио набрана в файле portfolio.html.
- Выполнена HTML-разметка всех элементов макета.
- Теги использованы согласно их семантического смысла.
- HTML проходит проверку валидатором без ошибок.
- Имена классов описательные и понятные другому разработчику.
- Имена классов не содержат заглавных букв, пробелов, транслита и названий тегов, только буквы и слова английского языка. Если имя класса состоит из нескольких слов, они разделяются дефисом.
- Атрибут href навигационных ссылок Студия и Портфолио содержит относительный путь к HTML-файлам этих страниц. При нажатии по ссылке происходит переход на соответствующую страницу в текущей вкладке браузера.
- У тегов <img> указаны атрибуты размеров, как минимум width.
- Изображения экспортированы из макета в формате jpg.
- Группы однотипных элементов собраны в списки <ul>.
- Фильтр на странице Портфолио выполнен списком кнопок, каждой из которых задан атрибут type="button".
- Разметка хедера и футера одинаковая на всех страницах.
- Все необходимые по макету шрифты и их вариации (вес и начертание) подключены с сервиса Google Fonts одной ссылкой. Необходимый вес для Raleway – 700, а для Roboto – 400, 500, 700 и 900.
- Внутри разметки кнопок нет дополнительных элементов, например спанов или ссылок.

**Оформление**

- Нет глобальных стилей элементов кроме <body>.
- Для оформления используются селекторы класса.
- В стилях отсутствует !important.
- У интерактивных элементов (кнопок и ссылок), при наведении мышкой или фокусе с клавиатуры, есть активное состояние указанное в макете (изменение цвета).
- Текст контактов в хедере и футере меняет цвет при ховере и фокусе.
- Для хранения палитры цветов макета (текст, фон, выделение) используются CSS-переменные.
- Для элемента <body> задано свойство font-family с доминантным на макете шрифтом Roboto.
- Указаны альтернативные варианты шрифта и тип семейства (без засечек) в конце перечисления font-family у элемента <body>.
- Семейство шрифтов Roboto явно задано только для элемента <body>, остальные элементы наследуют его.
- Для элемента <body> задано свойство color с доминантным на макете цветом текста. Остальной текст наследует или переопределяет это значение.
- Размер шрифта (свойство font-size) всех текстовых элементов точно соответствует значениям из макета.
- Высота строки (свойство line-height) всех текстовых элементов точно соответствует на как множитель, а не в px.
- Цвет (свойство color) всех текстовых элементов точно соответствует значениям из макета.
- Вес шрифта (свойство font-weight) всех текстовых элементов точно соответствует значениям из макета.
- Вес шрифта (свойство font-weight) явно указан только если значение в макете отличается от стандартного для этого элемента в браузере.
- Кнопкам задано свойство cursor со значением pointer.
- В стилях не повторяются значения свойств, которые заданы браузером по умолчнаию. Например, ссылкам не нужно указывать cursor: pointer, а абзацам font-style: normal или font-weight: 400.

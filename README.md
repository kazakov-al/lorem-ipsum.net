-   В БЭМ не особо жалуют нормалайз/ресет по причине шо мешает переиспользованию, but для тестового сойдет
-   Притащил реакт тк единственный готовый стартовый шаблон который был под рукой :D
-   логотип сделан картинкой, тк тащить шрифт под это - менять шило на мыло, тк используется ток в 1 месте

Чего не стал делать:
- всякие штуки по типу css-first, design-system, em/rem
- упарываться в деление на реакт компоненты, атомы/молекулы и тд
- кропать изображения, ибо это работа дизайнера
- писать либу для соединяющих линий в ворк-схеме, долго и геморно, а просто засунуть свг - тупо
- выносить переменные и делать миксины, хотел, но забил, тк там:
    -   С цветами полнейший хаос, особенно для 1 страницы с 4-мя секциями
    -   Шрифт по сути 1 и с типографикой тоже хаос, особенно порадовало использование начертаний которые в шрифте не существуют и по итогу оно заменяется другими

P.S
- в файл Form.scss лучше не смотреть, я торопился и не рефакторил, там все очень страшно :D Как минимум надо вынести повторяющиеся стили ui полей, + либу стилизовал через одно место
- парящий поповер селекта при скроле - фича либы...



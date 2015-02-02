###Система по именованию элементов для отдела Production агентства "Кликобилие"

Именование элементов нужно осуществлять по методологии, изобретенной в компании "Яндекс" - БЭМ (блок - элемент - модификатор). Главным преимуществом данной методологии, является то, что его использование дает возможность передать всю необходимую первичную информацию только по названию элемента.

> Блоком на странице лендинга называется один смысловой блок высотой в один экран. Блоки следует называть по его смысловой нагрузке. Наименования для наиболее часто встречающихся блоков приведены ниже.

> Элементом на странице называется дочерний элемент "Блока", из которых тот состоит. Например, если шапка сайта есть один смысловой блок, то логотип и кнопка обратного звонка являются элементами этого блока.

> Модификатором называется состояние элемента, в которых он может пребывать. Например, у всех кнопок есть два состояния, которые он может принимать: наведенный курсором (hover) и нажатый (active).

Синтаксис методики выглядит следующим образом: __block\__element--modificator__. 

Тем самым название само по себе указывает все первоначальную информацию об элементе страницы. Например, допустим у нас есть кнопка обратного звонка в шапке, тогда по методологии БЭМ его название должно выглядить следующим образом: __header\__btn__. А если мы хотим указать состояние этой кнопки при наведении, то имя будет таким: __header\__btn--hover__

> Давайте я разберу методологию на реальном примере:
> Допустим у нас есть **шапка**, в котором есть **логотип**, **телефон** и **кнопка** обратного звонка
> Блок: header
> Элементы:
> header__logo
> header__phones (это название папки, в котором содержатся телефон и кнопка)
> header__phones-link
> header__phones-btn

###Список названий Элементов

####1. Основной макет:
- header - шапка сайта
- footer - подвал сайта
- container - контейнер гридовой сетки с оговоренной шириной (960 пикс.)
- section - один смысловой блок лендинга 

####2. Элементы:
- link - ссылка
- logo - логотип
- phone - телефон
- btn - кнопка
- arrow - стрелка
- icon - иконка
- title - заголовок
- subtitle - подзаголовок
- column - колонка

####3. Элементы форм:
- input - поле ввода
- textarea - поле для ввода многострочного текста
- select - выпадающий элемент формы
- item - один элемент из списка
 
####4. Модули:
- popup - всплывающее окно
- form - форма отправки заявок
- table - таблица
- list - список
- nav - навигационный список 
- map - карта
- slider - циклично менящийся контент (текст+ картинки)
- carousel - циклично меняющиеся картинки
- tooltip - высплывающая подсказка при наведении мышкой
- dropdown - выпадающий список
- tabs - вкладки контента
- accordeon - вертикальные раскрывающиеся вкладки

####5. Названия для смысловых блоков:
- main - первый скролл
- benefits - "преимущества"
- steps - блок "как мы работаем"
- testimonials - "отзывы"
- products - "продукты"
- services - "сервисы/услуги"
- about - "о компании"
- reasons - "почему клиенты пользуются нашим товаром/услугой"
- contacts - блок контактов
- works - "выполненные проекты"
- sale - акция
- offer - блок с оффером и горизонтальной формой
- problems - блок с перечислением проблем
- clients - блок "наши клиенты"
- partners - "наши партнеры"
- consultation - блок "закажите консультацию"
- questions - блок "остались вопросы?"











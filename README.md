jQuery MoreContent Plugin <sup>1.0.1</sup>
-------
[![](https://data.jsdelivr.com/v1/package/npm/morecontent-js/badge)](https://www.jsdelivr.com/package/npm/morecontent-js) <br><br>
_**jQuery-плагин**, скрывающий часть контента,  
выходящего за рамки указанной высоты (**адаптивный спойлер**)_

* Адаптивен при динамическом изменении ширины окна браузера
* Возможность изменять параметры стандартной анимации сворачивания/разворачивания или задать свою
* Гибкая система методов/событий для программного управления состояниями и кастомизации
* Работает с CSS-стилями. Возможность задать высоту в закрытом состоянии через свойство max-height (px, em и т.д.)
* Lite-версия с вырезанными методами ("reinit", "destroy", "drop") и событиями (на ~30% легче)

<br>

[Демо](http://wahawaher.000webhostapp.com/morecontent-js#examples) | [Документация](http://wahawaher.000webhostapp.com/morecontent-js)

## CDN:
[https://www.jsdelivr.com/package/npm/morecontent-js?path=dist](https://www.jsdelivr.com/package/npm/morecontent-js?path=dist)

## Пакетные менеджеры:
```sh
# Bower
bower install --save morecontent-js

# NPM
npm install --save morecontent-js
```

## Подключение:

1. Подключить последнюю версию jQuery и jquery.morecontent.js
```html
<!-- jQuery -->
<script src="libs/jquery/dist/jquery.min.js"></script>

<!-- jquery.morecontent.js -->
<script src="dist/jquery.morecontent.js"></script>
```
2. Инициализировать плагин на группе элементов:
```javascript
$('[data-mrc]').moreContent();
```
3. Применить в HTML:
```html
<div data-mrc>
	<p>Контент, который нужно скрыть...</p>
</div>
```
## Зависимости:
- [jQuery](http://jquery.com/download/) (версия 1.9.1 или выше)

## Поддержка
Решение проблем/багов плагина, а также замечания и пожелания в [соответствующей теме](https://github.com/WahaWaher/morecontent-js/issues)

По всем другим вопросам:  [wahawaher@gmail.com](mailto:wahawaher@gmail.com "Написать на wahawaher@gmail.com")

## Лицензия (MIT)
Copyright (c) 2019 Sergey Kravchenko

Данная лицензия разрешает лицам, получившим копию данного программного обеспечения и сопутствующей документации (в дальнейшем именуемыми «Программное Обеспечение»), безвозмездно использовать Программное Обеспечение без ограничений, включая неограниченное право на использование, копирование, изменение, слияние, публикацию, распространение, сублицензирование и/или продажу копий Программного Обеспечения, а также лицам, которым предоставляется данное Программное Обеспечение, при соблюдении следующих условий:

Указанное выше уведомление об авторском праве и данные условия должны быть включены во все копии или значимые части данного Программного Обеспечения.

ДАННОЕ ПРОГРАММНОЕ ОБЕСПЕЧЕНИЕ ПРЕДОСТАВЛЯЕТСЯ «КАК ЕСТЬ», БЕЗ КАКИХ-ЛИБО ГАРАНТИЙ, ЯВНО ВЫРАЖЕННЫХ ИЛИ ПОДРАЗУМЕВАЕМЫХ, ВКЛЮЧАЯ ГАРАНТИИ ТОВАРНОЙ ПРИГОДНОСТИ, СООТВЕТСТВИЯ ПО ЕГО КОНКРЕТНОМУ НАЗНАЧЕНИЮ И ОТСУТСТВИЯ НАРУШЕНИЙ, НО НЕ ОГРАНИЧИВАЯСЬ ИМИ. НИ В КАКОМ СЛУЧАЕ АВТОРЫ ИЛИ ПРАВООБЛАДАТЕЛИ НЕ НЕСУТ ОТВЕТСТВЕННОСТИ ПО КАКИМ-ЛИБО ИСКАМ, ЗА УЩЕРБ ИЛИ ПО ИНЫМ ТРЕБОВАНИЯМ, В ТОМ ЧИСЛЕ, ПРИ ДЕЙСТВИИ КОНТРАКТА, ДЕЛИКТЕ ИЛИ ИНОЙ СИТУАЦИИ, ВОЗНИКШИМ ИЗ-ЗА ИСПОЛЬЗОВАНИЯ ПРОГРАММНОГО ОБЕСПЕЧЕНИЯ ИЛИ ИНЫХ ДЕЙСТВИЙ С ПРОГРАММНЫМ ОБЕСПЕЧЕНИЕМ.

# Генератор HTML5 баннеров

Проект сделан с помощью :
  [Create React App](https://github.com/facebook/create-react-app),\n
  [Redux](https://github.com/reduxjs/redux),\n
  [html2canvas](https://github.com/niklasvh/html2canvas).

## Доступные команды

  В директории проекта вы можете запустить

### `npm install`

  для установки всех необходимых зависимостей из `package.json`

### `npm start`

  для запуска приложения в режиме разработки на [http://localhost:3999](http://localhost:3999)

### `npm test`

  для запуска имеющихся тестов

### `npm run build`

  для получения оптимизированной продакшн версии

### `npm run eject`

  для самостоятельной настройки плагинов, операция в один конец

## Описание проекта

### Функционал

  Данное приложение предназначено для быстрого создания несложных баннеров для различных целей на Вашем сайте. Приложение состоит из трех основных блоков:

#### Меню настройки баннера

  Данное меню изначально находится в закрытом состоянии. Кликните по кнопке `show`, для просмотра возможных настроек баннера. В настройки входит: 
    настройка цвета заднего фона, задается через соответствующее текстовое поле или палитру. Поддерживает установку градиента через текстовое поле;

    выбор цвета шрифта, через текстовое поле или палитру;

    выбор размера шрифта через текстовое поле;

    выбор размеров баннера по X и Y, через соответствующие текстовые поля;

    добавление картинки на баннер, путем указания ссылки на нее в соответствующем поле;

    добавление ссылки на сайт, через текстовое поле;

#### Превью баннера

  На превью вы можете в реалном времени отслеживать все изменнения баннера.
  Также, у вас есть возможность перемещать блок текста и изображения, путем перетаскивания их мышкой. Для этого нажмите на элемент ЛКМ, и не отпуская, перетащите в нужное место.
  Для редактирования текста, нажмите на него два раза ЛКМ. Так вы попадете в режим редактирования и не сможете перемещать текст.

#### Кнопки экспорта

  Тут предствавлены три кпопки: экспорт в .png, экспорт в формате HTML строки, сериализация настроек баннера в json.
  В первом случае картинка скачивается на Ваше устройство. Остальные две кнопки копируют код в буфер обмена.

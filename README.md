Реализовать SPA, реализующее следующие два сценария:

### Наполнение корзины

* Клиент открывает станицу меню (корневую страницу) -> в меню отображаются несколько продуктов, например, "Пепперони" и "Маргарита"
* Клиент добавляет и удаляет продукты в/из корзины -> у каждого продукта обновляется счётчик, сколько штук этого продукта добавлено в корзину; плюс, обновляется общий счётчик количества всех продуктов в корзине
* Клиент тыкает в кнопку перехода на страницу корзины -> его переводит на страницу корзины

### Создание заказа

* Клиент переходит на страницу корзины -> в корзине отображаются набранные продукты; строка корзины = название продукта и количество штук этого продукта в корзине
* Клиент жмёт кнопку создание заказа -> корзина очищается и происходит переход обратно на страницу меню

### Требования:

* React + Redux /  Context API
* Webpack
* любой актуальный CSS-in-JS
* Покрытие тестами (Jest)
* Адаптивная верстка
* Не использовать готовые либы со стилями
* Чем меньше лишнего, тем лучше
* Роутинг react-router или свой собственный
* Стейт хранится на бэкенде
* Работа с бэкендом должна быть замокана с помощью localStorage. Данные для меню захардкодить там же.

* TypeScript будет плюсом (опционально)
* Код-сплиттинг / динамические импорты будут плюсом (опционально)
* Redux-saga будет плюсом (опционально)

* В качестве результата отправьте, пожалуйста, ссылку на github репозиторий

## Проект «FurnituresPosts» для «АВК-ГРУПП»

#### URL:

### Задание подразумевает создание проекта на Next.js 14 версии (App Router).

## Проект:

• Создать сайт со списком постов, взятых с фейкового API: https://jsonplaceholder.typicode.com/

• Дизайн сайта - на свое усмотрение. Для верстки необходимо использовать библиотеку компонентов (какую - на Ваш выбор). Material UI, Mantine, Chakra UI, AntD и другие допускаются.

• Главная страница - список постов с пагинацией по 20 штук  и возможность добавить новый пост. Форма создания находится ниже списка постов, должна иметь валидацию. 
На фейковом API по ссылке выше есть POST запрос на создание, следовать его схеме.

• Возможность перейти на страницу отдельного поста, где будет выведена информация из поста, картинка мебели с сервиса https://dev.me/products/image-placeholder (у каждого поста картинки должны быть разные!) и список комментариев к посту. В самом каталоге картинки можно не выводить.

• Для входящих и исходящих запросов необходимо использовать React Query (Tanstack Query) в связке с axios (либо встроенным в Next fetch). 

• Проект разрабатывать с применением системы контроля версий Git в открытом репозитории, ссылка на который должна быть приложена как решение. 
В README.md проекта указать ссылку на развернутый сайт. Можно использовать любые бесплатные хостинги (https://netlify.app, vercel и другие). 

## Задачи со звездочкой (не требуют выполнения, но будут бонусом):

• При создании нового поста сразу переходить на страницу этого поста. Так как пост мы придумали и в фейковом API его не существует, отобразить его можно, добавив его в кэш в React Query.

• Придумать способ для всех ошибок на получение данных с API отображать всплывающее сообщение “Произошла ошибка”. Делать это исключительно в одном месте и универсально для всех запросов.

## Для реализации проекта, кроме обязательных вышеуказанных библиотек и фреймворка Next.js, можно и нужно пользоваться сторонними библиотеками и пакетами. Сэкономьте себе время и не изобретайте велосипед. 
Если по каким-то причинам предоставленные выше API не работают или не подходят, можно использовать другие, аналогичные. 
Выполнение задания не подразумевает дедлайна, но разумным сроком сдачи считается не более 3-4 дней с момента получения этого документа. 

## Используемые технологии
-   **UI Frameworks** (Antd)
-   **Styling** (modules)
-   **SSR** (next js)
-   **Typification** (Typescript)
-   **React Query**
  
## Запуск проекта

1. Конечно же сначала нам нужно установить все зависимости `npm i` в помощь
2. Ну и все, что нам остается это просто запустить проект `npm run dev`

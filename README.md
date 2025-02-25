# Graff pink
___
## Краткое описание проекста
#### Верстка данного лендинга выполнялась в качестве тестового задания для "ООО Альма" на вакансию "Веб-программист". В проекте использовались таск-менеджер Gulp, а также препроцессор SCSS
## Установка
#### Чтобы установить проект, клонируйте этот репозиторий, после чего нужно установить через терминал npm и Gulp
```bash
    npm i
    gulp
```
## Дополнение
#### На сайте реализована адаптивная верстка (css media queries), технологии БЭМ, SCSS.
```scss
  &__nav {
        display: flex;
        align-items: center;
        & ul {
            display: flex;
            flex-direction: row;
            column-gap: 30px;
            @media (max-width: 560px) {
                column-gap: 15px;
            }
            @media (max-width: 500px) {
                flex-direction: column;
                row-gap: 5px;
            }
        }
    }
```

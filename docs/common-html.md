# Общие шаблоны текстов и комментариев

## :no_entry: Надо исправить

| Ошибка        | Текст комментария|
| ------------- | ------------- |
| Числа в именах классов | `<!-- Нужно исправить: названия классов не должны содержать числительные или цифры. Такое именование лишено смысла, не гибке и ни о чем не скажет разработчику.-->` |


## :thinking: Можно улучшить

| Ошибка        | Текст комментария|
| ------------- | ------------- |
| HTML-мнемоники | `<!-- Можно улучшить: для спец символов нужно использовать html - мнемоники (https://ru.wikipedia.org/wiki/Мнемоники_в_HTML) -->` |
| Использовать цитату | `<!-- Можно улучшить: По смыслу это цитата, так что тут лучше использовать элемент blockquote. Подробнее можно почитать тут: https://developer.mozilla.org/ru/docs/Web/HTML/Element/blockquote-->` |

## Фидбэк
Ненужные пункты удалить, недостающие - добавить. 
Написать в нескольких словах в  `В целом по работе: ...` что-нибудь хорошее и ободряющее студенту про его работу (просто представьте, сколько сил и времени он потратил на домашку, ему будет приятно, что мы видим и ценим его старания).

```
<!-- В целом по работе: 
    Хорошо
        понятный, хорошо структурированный код
        правильно оформлен head
        есть метатеги
        используете html - мнемоники
        правильно выделили h1
        верстка в целом совпадает с макетом
        используете БЭМ методологию в нейминге стилей
        используете семантичсекие теги - отлично: такой код легче понимать и людям и роботам.
        
    Нужно исправить:
        Не хватает заголовков там, где они необходимы (см комментарии в коде). При планировании заголовков учтите, что h1 может быть только один на странице.
        Всем элементам img в макете добавьте alt. Можно пустой, но он должен быть.
    
    Визуальные различия также нужно исправить. Работа должна в точности соответствовать брифу: 
    
    Остальные комментарии в коде носят рекомендательный характер.
    
    Для получения зачета нужно исправить критичные замечания. 
    
    Пожалуйста, не удаляйте комментарии.
-->
```

## Кодстайл

```
<!-- Пожалуйста, соблюдайте минимально необходимый кодстайл:
    - вложенные элементы должны быть с новой строки и отбиваться табами
    - нет лишних пробелов, переносов строк и лишних табов
    - если тег не содержит вложенных элементов, то открывающий и закрывающий теги можно оставлять в одной строке
    Кодстайл делает Ваш код опрятнее и легче для восприятия как для проверяющих, так и для Вас.
-->
```

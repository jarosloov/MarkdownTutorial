#Markdown[](https://ru.wikipedia.org/wiki/Markdown)

## Общие сведения
_**Markdown**_ – это, довольно, облегченный язык разметки, который является инструментом преобразования кода в **HTML**. Главной фичей данного языка является максимально простой синтаксис с который справится даже ребенок, который умеет пользоваться компьютером. Markdown создан для упрощения написания и чтения кода разметки. 

**Утверждение:** _Markdown нельзя заменить HTML._

**Доказательство:**
>Синтаксис _Markdown_ давильно ограничен и не включает в себя такой функционал, как _HTML_. 
Если говорить просто, то  _Markdown_ это подмножество  _HTML_.

## Оглавление 

## Заголовки

В языке разметки Markdown существуют два стиля обозначения заголовков:
1. Выделение строки символом `#`. 
   Например:  `# Тут могла быть твоя реклама`
   Когда перед текстом стоит одна `#`, это заголовок первого уровня. Существует всего 6 уровней заголовков. 
   Давайте посмотрим как будет выглядеть код. 
  
  **`Листинг №1 `**
   ```Markdown
   # Заголовок первого уровня
   ## Заголовок второго уровня
   ###  Заголовок третьего уровня
   ####  Заголовок четвертого уровня
   #####  Заголовок пятого уровня
   ######  Заголовок шестого уровня
   ```
   А так будет видеть читать.

>    # Заголовок первого уровня
>    ## Заголовок второго уровня
>    ###  Заголовок третьего уровня
>    ####  Заголовок четвертого уровня
>    #####  Заголовок пятого уровня
>    ######  Заголовок шестого уровня

2. Вместо символа `#` можно использовать, так называемое,  "подчеркивание строки", с помощью символов `=` и `-`. Как обычно, приведу примерчик и начнем мы с символа  `=` :

**`Листинг №2 `**
   ```Markdown
   Заголовок первого уровня
   ===========================
   Заголовок первого уровня
   ===========
   Заголовок первого уровня
   ===
   Заголовок первого уровня
   =
   ```
И получим 

>Заголовок первого уровня
>===========================
>Заголовок первого уровня
>===========
>Заголовок первого уровня
>===
>Заголовок первого уровня
>=

Можно заметить, что количество символов подчеркивания, не влияет. Давайте теперь рассмотрим символ подчеркивания `-`:

**`Листинг №3 `**
```Markdown
Заголовок второго уровня
------------------------
Заголовок второго уровня
-
```
и получим:

>Заголовок второго уровня
>------------------------
>Заголовок второго уровня
>-

#Цитаты

Для того чтобы обозначить цитату в языке Markdown, используют знак `>`.Его нужно вставлять перед каждой строкой которую вы хотите цитировать. Пример:

**`Листинг №4 `**
```Markdown
>Есть только две бесконечные вещи: Вселенная и глупость. Хотя насчет Вселенной я не уверен.

>>Теория — это когда все известно, но ничего не работает. Практика — это когда все работает, но никто не знает почему. Мы же объединяем теорию и практику: ничего не работает… и никто не знает почему!
```
и получим: 

>1. Есть только две бесконечные вещи: Вселенная и глупость. Хотя насчет Вселенной я не уверен.

>2. Теория — это когда все известно, но ничего не работает. Практика — это когда все работает, но никто не знает почему. Мы же объединяем теорию и практику: ничего не работает… и никто не знает почему!
>>    a. Образование — это то, что остаётся после того, как забывается всё выученное в школе.

<!--Для обозначения цитат в языке Markdown используется знак «больше» («>»). Его можно вставлять как перед каждой строкой цитаты, так и только перед первой строкой параграфа. Также синтаксис Markdown позволяет создавать вложенные цитаты (цитаты внутри цитат). Для их разметки используются дополнительные уровни знаков цитирования («>»). Цитаты в Markdown могут содержать всевозможные элементы разметки. Цитаты в языке Markdown выглядят следующим образом:
<!--Язык разметки Markdown поддерживает 2 стиля обозначения заголовков: подчеркивание и выделение символом («#»). Выделение заголовков с помощью подчеркивания производится знаками равенства («=») в случае, если заголовок первого уровня, и дефисами («-») в случае, если заголовок второго уровня. Количество знаков подчеркивания не ограничивается. При выделении заголовков с помощью символа («#») используется от одного до шести данных символов, которые устанавливаются в начале строки (перед заголовком). В данном случае количество символов соответствует уровню заголовка. Кроме того, заголовок возможно снабдить закрывающимися символами («#»), хотя это и не является обязательным. Количество закрывающихся символов не обязано соответствовать количеству начальных символов. Уровень заголовка определяется по количеству начальных символов.
Заголовки первого и второго уровней, выполненные с помощью подчеркивания, выглядят следующим образом:
<!--
https://gist.github.com/Jekins/2bf2d0638163f1294637
Теперь рассмотрим более подробно функции языка разметки Markdown.-->

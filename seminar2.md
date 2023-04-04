# Создаем туториал по гид #
 ## Добавление репозитория в проект 
 **Чтобы добавить верисонность в проект необходимо установить ГИт на компьютер и прописать команду инициализации в терминале** 
  
  ```
  git init
  ```
  ## Не добавление в репозиторийw435w5w45w435w5w5w5w5w5wew5etertertetertetertertertertertetertegit ##
  ```
  git add
  ```
  **фиксируем изменение в файле перед это командой обязательно сохранить**
## Бежим ##
# Туториал по использованию разметки MArkDown
## Добавление цитат
Цитаты оформляются как в емейлах, с помощью символа `>`.
> This is a blockquote with two paragraphs. Lorem ipsum
dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi
posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in,
laoreet vitae, risus.
> Donec sit amet nisl. Aliquam semper ipsum sit amet
velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.

Или более ленивым способом, когда знак `>` ставится
перед каждым элементом цитаты, будь то абзац, заголовок
или пустая строка:

> This is a blockquote with two paragraphs. Lorem ipsum
dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi
posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet
vitae, risus.
> Donec sit amet nisl. Aliquam semper ipsum sit amet
velit. Suspendisse
id sem consectetuer libero luctus adipiscing.
В цитаты можно помещать всё что угодно, в том числе
вложенные цитаты:
>## This is a header.
> 1. This is the first list item.
> 2. This is the second list item.
>>Вложенная цитата.
>
>Here's some example code:
>>return shell_exec("echo $input | $markdown
_script");
## Добавление заголовков 




## Добавление картинок 





## Добавление исходного кода
В чистом Маркдауне блоки кода отбиваются 4 пробелами в
начале каждой строки.
Но в GitHub-Flavored Markdown (сокращенно GFM) есть
более удобный способ: ставим по три апострофа (на букве
Ё) до и после кода. Также можно указать язык исходного
кода.
```php
<?php echo 'Всем привет';?>
```
```javascript
alert('Привет мир')
```
Pumpurum


## Добавление таблиц
В чистом Маркдауне нет синтаксиса для таблиц, а в GFM
есть.
First Header | Second Header
------------- | -------------
Content Cell | Content Cell
Content Cell | Content Cell
Для красоты можно и по бокам линии нарисовать:
| First Header | Second Header |
| ------------- | ------------- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |
Можно управлять выравниванием столбцов при помощи
двоеточия.

| Left-Aligned | Center Aligned | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is | some wordy text | **$1600** |
| col 2 is | centered | $12 |
| zebra stripes | are neat | ~~$1~~ |
Внутри таблиц можно использовать ссылки, наклонный,
жирный или зачеркнутый текст
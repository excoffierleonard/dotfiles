# cut

> Вырезать поля из стандартного ввода или файлов.
> Больше информации: <https://keith.github.io/xcode-man-pages/cut.1.html>.

- Вывести указанный диапазон символов/полей каждой строки (`-c|f 1|1,10|1-10|1-|-10` далее обозначается как `диапазон`):

`{{команда}} | cut -{{c|f}} {{1|1,10|1-10|1-|-10}}`

- Вывести диапазон полей каждой строки с указанным разделителем:

`{{команда}} | cut -d "{{,}}" -f {{диапазон}}`

- Вывести диапазон символов каждой строки указанного файла:

`cut -c {{1}} {{path/to/file}}`
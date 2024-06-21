# itmo_conspects

**Конспекты по разным предметам первого потока ИСy27 университета ИТМО**

### Математический анализ II

[**Весь курс с программой экзамена**](conspects/calculus/calculus_superconspect.pdf)


### Специальные разделы высшей математики

[**Весь курс с неполной программой экзамена**](conspects/specsec/specsec_superconspect.pdf)


### Дискретная математика II

[**Почти весь курс с неполной программой экзамена**](conspects/dismath/dismath_superconspect.pdf)

[**Шпаргалка по Комбинаторике**](conspects/dismath/dismath_cheatsheet_combinatorics.pdf)

[**Шпаргалка по Рекуррентностям и Производящим функциям**](conspects/dismath/dismath_cheatsheet_recurrences.pdf)

### Алгоритмы и Структуры Данных I-II

Почти все алгоритмы из курса и некоторые пояснения к ним есть в моем другом репозитории: [pelmesh619/algorithm_archives](https://github.com/pelmesh619/algorithm_archives)



## TODO

Буду рад, если вы поможете мне:

* Сделать картинки примеров (желательно какие-нибудь приличные и красивые, из графкалькуляторов)

* Проверить на очепятки и неточности

* Сделать конспекты первых лекций второго семестра

## PS

linter.py автоматически добавляет форматирование (добавляет \displaystyle, где надо и т.д.) и рендерит .pdf в директорию ./out/ при помощи pdflatex, запускаем так: 

```bash
python linter.py tex_file.tex
```

superconspect.py автоматически "соединяет" все .tex файлы в данной директории в один файл, добавляет содержание и рендерит суперконспект👆

compile_all.py рендерит все .tex в данной директории (в том числе создает суперконспект)



for contact write me: [t.me/pelmeshke](https://t.me/pelmeshke)

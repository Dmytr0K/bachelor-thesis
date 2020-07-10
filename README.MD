# Выпускная квалификационная работа

Этот репозиторий содержит мою выпускную квалификационную работу

## Включает
 - Пояснительную записку ([pdf](thesis.pdf))
 - презентацию к защите ([pdf](presentation.pdf)) 
 - множество лишних картинок

## Как собрать (один из вариантов)
TexLive:
 - базовая схема (plain и latex)
 - языки: английский, кириллица

Установить пакеты с помощью tlmgr (при отсутствии необходимых):
```bash
$ tlmgr install <package>
```

Сборка:
```bash
$ latexmk -pdf  -bibtex  -synctex=1 -interaction=nonstopmode -output-directory=build thesis.tex 
```

Можно воспользоваться IDE Texpad (OSX) и другими аналогами.

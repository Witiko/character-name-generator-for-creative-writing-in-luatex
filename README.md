# Nápadovník jmen postav pro tvůrčí psaní v LuaTeXu

Tento repozitář obsahuje zdrojový kód článku *Nápadovník jmen postav pro
tvůrčí psaní v LuaTeXu*, který se chystám zveřejnit ve Zpravodaji CSTUGu.

Pro sazbu článku potřebujeme unixový systém s nainstalovaným programem
`xmllint` z knihovny libxml2 a programem `wget`.

PDF dokument [`main.pdf`][1] s textem článku vysázíme následujím příkazem:

``` bash
latexmk -lualatex -shell-escape main.tex
```

Jako vedlejší produkt sazby vzniknou soubory [`randomnames.lua`][2],
[`randomnames.tex`][3] a [`randomnames.sty`][4] s balíčkem pro generování
jmen příběhových postav, který jsme v článku vyvinuli.

 [1]: https://github.com/Witiko/character-name-generator-for-creative-writing-in-luatex/releases/download/latest/main.pdf
 [2]: https://github.com/Witiko/character-name-generator-for-creative-writing-in-luatex/releases/download/latest/randomnames.lua
 [3]: https://github.com/Witiko/character-name-generator-for-creative-writing-in-luatex/releases/download/latest/randomnames.tex
 [4]: https://github.com/Witiko/character-name-generator-for-creative-writing-in-luatex/releases/download/latest/randomnames.sty

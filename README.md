# Nápadovník jmen postav pro tvůrčí psaní v LuaTeXu

Tento repozitář obsahuje zdrojový kód článku *Nápadovník jmen postav pro
tvůrčí psaní v LuaTeXu*, který se chystám zveřejnit ve Zpravodaji CSTUGu.

Pro sazbu článku potřebujeme unixový systém s nainstalovaným programem
`xmllint` z knihovny libxml2 a programem `wget`.

Článek vysázíme následujícími příkazy:

``` bash
latexmk -lualatex -shell-escape main.tex
```

Jako vedlejší produkt sazby vzniknou soubory `randomnames.lua`,
`randomnames.tex` a `randomnames.sty` s balíčkem pro generování jmen
příběhových postav, který jsme v článku vyvinuli.

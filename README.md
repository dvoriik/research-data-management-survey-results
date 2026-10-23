# Mapování správy výzkumných dat 2025 – interaktivní dashboard

Interaktivní přehled výsledků **Průzkumu správy výzkumných dat v České republice 2025**.
Ukazuje, jak vědecké týmy vytvářejí, popisují, ukládají a sdílejí výzkumná data.

- 1 121 odpovědí hlavních řešitelů projektů z Centrální evidence projektů (návratnost 29,5 %)
- 43 otázek v 9 tematických oddílech
- filtry podle věku, vědního oboru, typu instituce, velikosti týmu, typu výzkumu, pohlaví a pozice
- srovnání podle skupin a detailních oborů, tabulka s řazením a automatické shrnutí

## Jak to funguje

Celý dashboard je jeden statický soubor `index.html`. Kódované odpovědi jsou vložené přímo
v souboru (bez názvů institucí a bez volných textových odpovědí) a všechny ukazatele, grafy
i tabulky se počítají v prohlížeči. Grafy kreslí [Chart.js](https://www.chartjs.org/) 4.4.1
načítaný z CDN jsDelivr.

Odkaz na konkrétní otázku: přidejte za adresu `#` a identifikátor otázky, např. `#dmp`, `#uloziste`, `#os_znalost`.

## Zdroj dat

Vávra, M., Čížek, T., Klusáček, J., Sukhotskaya, A., Šalamounová, P. (2026).
*Průzkum správy výzkumných dat v České republice 2025.* ČSDA.
https://doi.org/10.14473/CSDA/OJTMJF

Výzkum vznikl s finanční podporou iniciativy EOSC CZ v rámci projektu Národní repozitářová
platforma pro výzkumná data (CZ.02.01.01/00/23_014/0008787).

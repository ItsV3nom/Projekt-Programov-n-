# Projekt na programování - HANGMAN
Na tento projekt jsme si vybrali známou hru se jménem Hangman (česky Šibenice). Tento projekt zpracovávají Tomáš Fikart, Alex Mašek a Tomáš Kindl.


## O čem je Hangman?
Hra je o hádání náhodného slova náhodně vybraného z databáze slov. Hádá se tak, že se typne písmenko z abecedy a hra vám poví, zda vybrané písmenko
je ve vybraném slově, či nikoliv. Cílem hry je uhodnout slovo, kde každým uhodnotým písmenkem jste blíž k výhře. Pokud se Vám nepovede uhodnout
slovo do určitého počtu pokusů, tak prohrajete.


## Spuštění
Po zapnutí hry se Vám objeví hlavní menu, v něm budou 4 tlačítka a to Hrát, Statistiky, Nastavení a Odejít ze hry.

### Tlačítko Hrát Hangman
Zapne hru Hangman.

### Tlačítko Statistiky
Zapne menu se seznamem statistik hráče, kde bude napsané jako hlavní výhry a prohry, a poté níže počet výher a proher na různých obtížnostech hry.
Informace o obtížnostech jsou uvedeny níže.

### Tlačítko Nastavení
Zde budou uvedeny 2 posuvné tlačítka na hlasitost zvukových efektů a hudby, dále tlačítko na dání hry celou obrazovku a tlačítko zpět, které Vás vrátí na hlavní menu.

### Tlačítko Vypnout hru
Vypne hru Hangman.

## Zapnutí hry Hangman
Po zapnutí hry tlačítkem, zobrazí se Vám menu kde si zvolíte ze dvou možností: hrát proti počítači nebo lokální multiplayer.

### Hrát proti počítači
Při zvolení této možnosti se Vám objeví další menu kde si zvolíte obtížnost mezi třemi možnostmi: jednoduchá, klasická a těžká. Každá z těchto možností má různě určené
kolik můžete udělat chyb, jak dlouhé dostanete slovo a jaký na to máte časový limit toto slovo uhodnout. Jednoduchá obtížnost Vám povolí 15 chyb, slova jsou dlouhé 5-8
písmenek a časový limit je 10 minut. Klasická obtížnost Vám povolí 10 chyb, slova jsou dlouhé 9-12 písmenek a časový limit je 5 minut. Těžká obtížnost Vám povolí
5 chyb, slova jsou dlouhé 12-15 písmenek a časový limit je 2 minuty.

### Lokální multiplayer
Při zvolení této možnosti se Vám objeví další menu kde si můžete zadat vlastní slovo, které se poté bude hádat, mělo by to fungovat tak, že jeden hráč slovo zadá a
druhý ho hádá. Dále také hráč může vybrat čas, jak dlouho bude hráč hádat, má na výběr ze čtyř možností časů, které jsou převzaty z obtížností ze hry proti
počítači + možnost nastavit neomezený čas.
Hráč, který zadává také může ještě určit maximální počet chyb co může hráč udělat.
Výhry a prohry na lokálním multiplayeru se nezapisují do statistik, kvůli jednoduchému podvodu.

## Uvnitř hry Hangman
Po zvolení mezi hraním proti počítači a lokálním multiplayerem se Vám hra spustí.

### Časomíra
Je ukázaná uprostřed nahoře a ukazuje hráčův zbývající čas.

### Nastavení
Je umístěno v levo nahoře a otevře Vám stejné nastavení jako v menu s výjimkou nového tlačítka: odejít do menu. Tlačítko odejít do menu Vás pošle zpět na hlavní menu
a pokud jste hráli hru proti počítači, přite Vám prohru (stejně platí pro tlačítko Odejít ze hry).

### Postavička Hangmana
Je uprostřed obrazovky a bude se tvořit podle počtu chyb hráče a zvolené obtížnosti.

### Slovo na uhádnutí
Bude těsně pod postavičkou Hangmana a bude ukazovat jak dlouhé je slovo a jaké písmenka hráč uhodl správně a jejich správnou pozici.

### Klávesnice s písmenky
Pod slovem na uhádnutí bude klávesnice, která bude ukazovat všechna písmenka která lze použít, aby jste zahráli písmenko, stačí na něj kliknout, poté se Vám ukáže, zda
jste uhodl dobře nebo ne, písmenko podle toho na klávesnici zčervená (špatně) nebo zezelená (správně).

## Postup v programování hry
Procentuálně 3%, zatím byla pouze napsána tato stránka, která popisu jak bude hra vypadat a probíhat.

# 2023-l4-web-mockupapp-KupcovaTyna
2023-l4-web-mockupapp-KupcovaTyna created by GitHub Classroom

Vhodný pro mobilní aplikaci s localstorage.

## Plánovací hra
Jedná se o hru, nebo spíše plánovač aktivit. 
Aplikace by měla obsahovat 3 základní šablony, které detailně popisují různé činnosti. Uživatel by měl možnost upravit existující šablonu nebo vytvořit zcela novou podle svých potřeb. Aplikace by také měla obsahovat časové odhady pro jednotlivé aktivity.

 ## Příklad: 

Šablona úklidu pokoje:

- Sesbírání nádobí a vložení do myčky (5 minut)

- Sesbírání odpadků a vyhození do koše (5 minut)

- Sesbírání špinavého prádla a vložení do koše na praní (2 minuty)

- Uklizení sešitů, propisek a kancelářských potřeb (3 minuty)

- Utření stolu (2 minuty)

- převlečení postele (7min)

- Vyluxování pokoje (10 minut)

- Vytření podlahy (15 minut)


Celkově by tedy tato činnost uklizení pokoje trvala okolo 49 minut. Uživatel by tedy věděl kolik času by si měl na danou činnost rezervovat.Každý úkol by byl jedno "políčko", uživatel by po splnění úkolu odklikl jeho dokončení a posunul se na další bod. 
## Figma
[Figma návrh](https://www.figma.com/file/W2Np4KOyqf4j4kt70Hruu4/Untitled?type=design&node-id=0-1&mode=design&t=c0ie72Tc084doyvz-0)

## Barevná paleta 
Barevná paleta je tvořena barvami: 
 - Salmon: #F29CA3
 - Wine: #64113F
 - Pink: #DE4D86
 - Champagne: #FAE3C6
 - Baby pink: #FFD4D4

![barvy](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/fd0ceb1d-1de2-466b-8440-4eb1d2813c14)

## Index
Index obsahuje zahájené plány, ve kterých lze pokračovat. Taky obsahuje dokončená plány za poslední týden. Je zde taky velmi jednoduchá navigace, která obsahuje: ikonu kalendáře, šablony a info(O aplikaci) 
na index se uživatel dostane kliknutím na logo Strategic Moves

![index](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/e4d25b18-ca37-449a-9522-993ba16873e2)

## Aktivita
Po rozkliknutí pokračování se otevře stránka s již zahájenou aktivitou. 

### Zahájená aktivita
![zahajenaaktivita](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/ad95baa6-13ad-4412-9c96-e2d6a51762cd)

Na této stránce je šipka zpět na index(zahájené a dokončné aktivity), nadpis dané činnosti, seznam úkolů (dole je první úkol, nahoře poslední) pokud je úkolů větší množství, jsou schovány a po splnění úkolu se seznam scrollne(přibude úkol nahoře, úkol dole se posune pod navigaci) - seznam je scrollovatelný. Nadpis zůstává stále vidět. Úlohy lze označit jako dokončené i v jiném pořadí, než ve kterém jsou napsány za sebou. 
Dále je na této stránce čas, jak dlouho aktivita probíhá a počet zbývajících úkolů. 

### Dokončená aktivita
![dokončenaaktivita](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/1f92c12c-a774-435a-960a-687e51c4f3db)

Po dokončení VŠECH úkolů se objeví okno, ve kterém lze přepnout zpět na plány nebo opakovat znovu stejný plán. Zároveň je zde napsán čas, v jakém byl plán dokončen. Také zmizí tento čas ve spodku stránky společně s počtem zbývajících úkolů. 
Jsou zde 2 tlačítka - jedno vede zpět na plány a druhým lze opakovat tu stejnou aktivitu.

## Šablony
![šablony](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/6dd78361-c4c1-4e58-95a2-aeb6a9a11144)

Na tuto stránku se uživatel dostane kliknutím na ikonu šablony v indexu.

![navigace](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/fabf1b01-e8e2-40fc-a0ae-a3dd13e68913)

Na této stránce jsou uloženy šablony, které lze zahájit, upravit nebo je smazat. 
Dole je opět malá navigace opět obsahuje kalendář a info, místo šablon je zde plus, kterým lze vytvořit nový plán. 


## Nová šablona
![novasablona](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/c6ee0dbb-ecf5-4f6c-90a4-f749ff918d03)

Po kliknutí na +(vytvoření nového plánu) se objeví stránka, kde lze popsat svůj další vlastní plán. 
Na této stránce je prostor pro popsání úkolu a času, který úloha zabere. Taky zde je jednoduché plus a minus pro přidání a odebrání úlohy. Pokud by byl seznam delší, úlohy se budou opět budou scrollovat. Pod tímto seznamem je sečten počet úloh a celkový čas. Jako poslední je zde tlačítko uložit, který tento plán uloží do "šablon". Tímto se uživatel dostane zpět do šablon.

## Editace šablony
Editace plánu vypadá stejně jako vytváření nového plánu, akorát v něm už jsou obsaženy informace, které lze měnit.

## Kalendář
![kalendar](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/3a7b3574-1927-4e01-9037-a33e31ae3827)

Po kliknutí na kalendář v indexu/šablonách se uživatel dostane na kalendář, ve kterém budou vyznačeny dny, ve kteých má uživatel něco naplánovaného. Plán netrvá dýl než 24 hodin, tím pádem "tečka" zabírá pouze jeden den. "Tečka" je vždy stejná nehledě na počet naplánovaných úloh. V dolní navigaci je opět info, šablony, ale místo kalendáře je ikona, která nás dostane zpět na index(zahajené/dokončené plány). 

## Plán v daný den
![plány dnes](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/1fee439e-aeca-49ae-a370-d83c57feef0d)

Dále zde rozkliknout jednotlivé dny, kde je vidět, které plány v daný den dokončit. Ten lze odebrat nebo zahájit. Šipkou zpět se uživatel opět dostane na kalendář. Po kliknutí na "play" se přidá plán k zahájeným plánům. Dále zde je poznámkový blok. 

### Přidat plán
![přidatsablonu](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/9e3689ad-3624-41d0-844e-39f2bd6692cb)

Je zde také plus, kterým se objeví okno "přidat plán". Uživatel může vybrat jeden plán, který se ihned přidá. Pokud se uživatel splete je zde křížek vedle zahájení plánu. Uživatel může přidat kolik plánů chce. 
Plán může tedy rovnou zahajit. 


## O aplikaci
![info](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/aeae9e49-1662-431e-aae0-b755b7ee24db)

Jako poslední je info o aplikaci. Je zde napsána verze aplikace, kontakt a kdo aplikaci vytvořil. 

## Možné rozšíření aplikace
Přidat přihlášení, aby měl uživatel uložené své plány a mohl je otevřít i v jiném zařízení nebo mohl data sdílet s ostatními.
Za splněný cíl dostat určitý počet mincí/žetonů/bodů, za které by mohl uživatel buď něco kupovat nebo je sdílet se svými přáteli, a tím vidět kolik bodů mají ostatní, tím pádem se předhánět o první místo v počtu bodů(vykonaných aktivit). Uživatele by mezi sebou také mohli sdílet jednotlivé šablony plánů. Lidé by tak byli motivovaní k udělání činnosti. 

Kupovat by mohli například jiné vzhledy aplikace při plnění úkolu. Nebo by se dala přidat postavička, pro kterou lze kupovat oblečení/doplňky...


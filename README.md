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

![index](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/e4d25b18-ca37-449a-9522-993ba16873e2)

## Aktivita
Po rozkliknutí pokračování se otevře stránka s již zahájenou aktivitou. 

### Zahájená aktivita
![zahajenaaktivita](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/5135c3f0-829b-4603-8095-243a2cb63dd5)

Na této stránce je šipka zpět na index(zahájené a dokončné aktivity), nadpis dané činnosti, seznam úkolů (dole je první úkol, nahoře poslední) pokud je úkolů větší množství, jsou schovány a po splnění úkolu se seznam scrollne(přibude úkol nahoře, úkol dole se posune pod navigaci) - seznam je scrollovatelný. Nadpis zůstává stále vidět. Úlohy lze označit jako dokončené i v jiném pořadí, než ve kterém jsou napsány za sebou. 
Dále je na této stránce čas, jak dlouho aktivita probíhá a počet zbývajících úkolů. 

### Dokončená aktivita
![dokončenaaktivita](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/450b9c78-bfb7-44cb-ba17-384f89c87dbe)

Po dokončení VŠECH úkolů se objeví okno, ve kterém lze přepnout zpět na plány nebo opakovat znovu stejný plán. Zároveň je zde napsán čas, v jakém byl plán dokončen. Také zmizí tento čas ve spodku stránky společně s počtem zbývajících úkolů. 
Jsou zde 2 tlačítka - jedno vede zpět na plány a druhým lze opakovat tu stejnou aktivitu.

## Šablony
![šablony](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/3ebcd56d-82bb-4db9-8716-0c6a3c8c2e22)

Na tuto stránku se uživatel dostane kliknutím na ikonu šablony v indexu.

![navigace](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/fabf1b01-e8e2-40fc-a0ae-a3dd13e68913)

Na této stránce jsou uloženy šablony, které lze zahájit, upravit nebo je smazat. 
Dole je opět malá navigace opět obsahuje kalendář a info, místo šablon je zde plus, kterým lze vytvořit nový plán. 
Nahoře je tlačítko plány, která vede


## Nový plán


Po kliknutí na +(vytvoření nového plánu) se objeví stránka, kde lze popsat svůj další vlastní plán. 
Na této stránce je prostor pro popsání úkolu a času, který úloha zabere. Taky zde je jednoduché plus a minus pro přidání a odebrání úlohy. Pokud by byl seznam delší, úlohy se budou opět budou scrollovat. Pod tímto seznamem je sečten počet úloh a celkový čas. Jako poslední je zde tlačítko uložit, který tento plán uloží do "Tvé plány". 


## Kalendář


Po kliknutí na kalendář v indexu se uživatel dostane na kalendář, ve kterém budou vyznačeny dny, ve kteých má uživatel něco naplánovaného. Plán netrvá dýl než 24 hodin, tím pádem "tečka" zabírá pouze jeden den. "Tečka" je vždy stejná nehledě na počet naplánovaných úloh.

## Plán v daný den
![plandnes](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/e06ae7c9-f7f2-4955-81e2-cad40ed912e7)

Dále zde rozkliknout jednotlivé dny, kde je vidět, které plány v daný den dokončit. 

### Přidat plán
![pridatplan](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/7b22fa4d-d1b8-4dba-849a-5e94237f9ead)

Je zde také plus, kterým se objeví okno "přidat plán". Uživatel může vybrat jeden plán, který se ihned přidá. Pokud se uživatel splete je zde křížek vedle zahájení plánu. Uživatel může přidat kolik plánů chce. 
Plán může tedy rovnou zahajit. Dále zde je poznámkový blok. Šipkou zpět se vrátí na kalendář. Na plány se vrátí horní navigací "Tvé plány".


## Další možnosti
![dalsi](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/dd02d11c-fda7-420d-b66f-ceae2bce6923)

V neposlední řadě jsou zde "tři tečky" tedy další možnosti, které se skládájí pouze ze 2 možností - Upravit existující plán a O aplikaci. 
Tato malá navigace se objeví, zároveň aplikace "zešedne", aby byla navigace zvýrazněna. Při kliku jinam než na tyto dvě možnosti se aplikace vrátí do původního stavu.
Upravit existující plán otevře stejnou stránku jako "vytvořit nový plán" kde lze přidat/odebrat/přepsat jednotlivé úlohy a následně tento plán uložit. 

### O aplikaci
![oaplikaci](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/4070fc4f-576f-429f-9d99-55dfb30da030)

Jako poslední je "O aplikaci". Je zde napsána verze aplikace, kontakt a kdo aplikaci vytvořil. 



## Možné rozšíření aplikace

Za splněný cíl dostat určitý počet mincí/žetonů/bodů, za které by mohl uživatel buď něco kupovat nebo je sdílet se svými přáteli, a tím vidět kolik bodů mají ostatní, tím pádem se předhánět o první místo v počtu bodů(vykonaných aktivit). Uživatele by mezi sebou také mohli sdílet jednotlivé šablony plánů. Lidé by tak byli motivovaní k udělání činnosti. 

Kupovat by mohli například jiné vzhledy aplikace při plnění úkolu. Nebo by se dala přidat postavička, pro kterou lze kupovat oblečení/doplňky...


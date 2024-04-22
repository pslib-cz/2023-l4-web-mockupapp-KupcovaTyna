# 2023-l4-web-mockupapp-KupcovaTyna
2023-l4-web-mockupapp-KupcovaTyna created by GitHub Classroom

**Plánovací hra**
Jedná se o hru, nebo spíše plánovač aktivit. 
Aplikace by měla obsahovat 3 základní šablony, které detailně popisují různé činnosti. Uživatel by měl možnost upravit existující šablonu nebo vytvořit zcela novou podle svých potřeb. Aplikace by také měla obsahovat časové odhady pro jednotlivé aktivity.

Příklad: 

Šablona úklidu pokoje:

- Sesbírání nádobí a vložení do myčky (5 minut)

- Sesbírání odpadků a vyhození do koše (5 minut)

- Sesbírání špinavého prádla a vložení do koše na praní (2 minuty)

- Uklizení sešitů, propisek a kancelářských potřeb (3 minuty)

- Utření stolu (2 minuty)

- převlečení postele (7min)

- Vyluxování pokoje (10 minut)

- Vytření podlahy (15 minut)


Celkově by tedy tato činnost uklizení pokoje trvala okolo 49 minut. Uživatel by tedy věděl kolik času by si měl na danou činnost rezervovat. 

Každý úkol by byl jedno "políčko", uživatel by po splnění úkolu odklikl jeho dokončení a posunul se na další bod. 
Barevná paleta je tvořena barvami: 
 - Salmon: #F29CA3
 - Wine: #64113F
 - Pink: #DE4D86
 - Champagne: #FAE3C6
 - Baby pink: #FFD4D4

![barvy](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/fd0ceb1d-1de2-466b-8440-4eb1d2813c14)

Index obsahuje existující plány, které lze ihned zahájit. Je zde taky velmi jednoduchá navigace, která obsahuje: ikonu kalendáře, plusu(vytvořit nový plán) a tři tečky(další možnosti) 

![index](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/b32e7cb1-dc26-489b-aba5-4fe44f24804a)

Po rozkliknutí zahájení se otevře stránka se zahájenou aktivitou.

![zahajenaaktivita](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/def02459-dd6e-451a-8f91-5bb4432e1ae4)

Na této stránce je šipka zpět na index, nadpis dané činnosti, seznam úkolů (dole je první úkol, nahoře poslední) pokud je úkolů větší množství, jsou schovány a po splnění úkolu se seznam scrollne(přibude úkol nahoře, zmizí úkol dole). Nadpis zůstává stále vidět. Úlohy lze označit jako dokončené i v jiném pořadí, než ve kterém jsou napsány za sebou. 
dále je na této stránce čas, jak dlouho aktivita probíhá a počet zbývajících úkolů. 

![dokoncenaaktivita](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/85c2bbb8-602f-47de-8c3f-49e4b8717cf2)

Po dokončení VŠECH úkolů se objeví okno, ve kterém lze přepnout zpět na plány nebo opakovat znovu stejný plán. Zároveň je zde napsán čas, v jakém byl plán dokončen. Také zmizí tento čas ve spodku stránky společně s počtem zbývajících úkolů. 

![kalendar](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/208ab888-043b-4c9d-b06a-1baacafb9352)

Po kliknutí na kalendář v indexu se uživatel dostane na kalendář, ve kterém budou vyznačeny dny, ve kteých má uživatel něco naplánovaného. Plán netrvá dýl než 24 hodin, tím pádem "tečka" zabírá pouze jeden den. "Tečka" je vždy stejná nehledě na počet naplánovaných úloh.

![plandnes](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/e06ae7c9-f7f2-4955-81e2-cad40ed912e7)

Dále zde rozkliknout jednotlivé dny, kde je vidět, které plány v daný den dokončit. 

![pridatplan](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/7b22fa4d-d1b8-4dba-849a-5e94237f9ead)

Je zde také plus, kterým se objeví okno "přidat plán". Uživatel může vybrat jeden plán, který se ihned přidá. Pokud se uživatel splete je zde křížek vedle zahájení plánu. Uživatel může přidat kolik plánů chce. 
Plán může tedy rovnou zahajit. Dále zde je poznámkový blok. Šipkou zpět se vrátí na kalendář. Na plány se vrátí horní navigací "Tvé plány".

![novyplan](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/5ab0e41a-1c41-4185-9035-1e0d5c3e0317)

Po kliknutí na +(vytvoření nového plánu) se objeví stránka, kde lze popsat svůj další vlastní plán. 
Na této stránce je prostor pro popsání úkolu a času, který úloha zabere. Taky zde je jednoduché plus a minus pro přidání a odebrání úlohy. Pokud by byl seznam delší, úlohy se budou opět budou scrollovat. Pod tímto seznamem je sečten počet úloh a celkový čas. Jako poslední je zde tlačítko uložit, který tento plán uloží do "Tvé plány". 

![dalsi](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/dd02d11c-fda7-420d-b66f-ceae2bce6923)

V neposlední řadě jsou zde "tři tečky" tedy další možnosti, které se skládájí pouze ze 2 možností - Upravit existující plán a O aplikaci. 
Tato malá navigace se objeví, zároveň aplikace "zešedne", aby byla navigace zvýrazněna. Při kliku jinam než na tyto dvě možnosti se aplikace vrátí do původního stavu.
Upravit existující plán otevře stejnou stránku jako "vytvořit nový plán" kde lze přidat/odebrat/přepsat jednotlivé úlohy a následně tento plán uložit. 

![oaplikaci](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/4070fc4f-576f-429f-9d99-55dfb30da030)

Jako poslední je "O aplikaci". Je zde napsána verze aplikace, kontakt a kdo aplikaci vytvořil. 



Možné rozšíření aplikace:
Za splněný cíl dostat určitý počet mincí/žetonů/bodů, za které by mohl uživatel buď něco kupovat nebo je sdílet se svými přáteli, a tím vidět kolik bodů mají ostatní, tím pádem se předhánět o první místo v počtu bodů(vykonaných aktivit). Uživatele by mezi sebou také mohli sdílet jednotlivé šablony plánů. Lidé by tak byli motivovaní k udělání činnosti. 

Kupovat by mohli například jiné vzhledy aplikace při plnění úkolu. Nebo by se dala přidat postavička, pro kterou lze kupovat oblečení/doplňky...


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



Index obsahuje existující plány, které lze ihned zahájit. Je zde taky velmi jednoduchá navigace, která obsahuje: ikonu kalendáře, plusu(vytvořit nový plán) a tři tečky(další možnosti) 
Po rozkliknutí zahájení se otevře stránka se zahájenou aktivitou.


Na této stránce je šipka zpět na index, nadpis dané činnosti, seznam úkolů (dole je první úkol, nahoře poslední) pokud je úkolů větší množství, jsou schovány a po splnění úkolu se seznam scrollne(přibude úkol nahoře, zmizí úkol dole). Nadpis zůstává stále vidět. Úlohy lze označit jako dokončené i v jiném pořadí, než ve kterém jsou napsány za sebou. 
dále je na této stránce čas, jak dlouho aktivita probíhá a počet zbývajících úkolů. 

Po dokončení VŠECH úkolů se objeví okno, ve kterém lze přepnout zpět na plány nebo opakovat znovu stejný plán. Zároveň je zde napsán čas, v jakém byl plán dokončen. Také zmizí tento čas ve spodku stránky společně s počtem zbývajících úkolů. 

Po kliknutí na kalendář v indexu se uživatel dostane na kalendář, ve kterém budou vyznačeny dny, ve kteých má uživatel něco naplánovaného. Plán netrvá dýl než 24 hodin, tím pádem "tečka" zabírá pouze jeden den. "Tečka" je vždy stejná nehledě na počet naplánovaných úloh.

Dále zde rozkliknout jednotlivé dny, kde je vidět, které plány v daný den dokončit. Je zde také plus, kterým se objeví okno "přidat plán". Uživatel může vybrat jeden plán, který se ihned přidá. Pokud se uživatel splete je zde křížek vedle zahájení plánu. Uživatel může přidat kolik plánů chce. 
Plán může tedy rovnou zahajit. Dále zde je poznámkový blok. Šipkou zpět se vrátí na kalendář. Na plány se vrátí horní navigací "Tvé plány".

Po kliknutí na +(vytvoření nového plánu) se objeví stránka, kde lze popsat svůj další vlastní plán. 

Na této stránce je prostor pro popsání úkolu a času, který úloha zabere. Taky zde je jednoduché plus a minus pro přidání a odebrání úlohy. Pokud by byl seznam delší, úlohy se budou opět budou scrollovat. Pod tímto seznamem je sečten počet úloh a celkový čas. Jako poslední je zde tlačítko uložit, který tento plán uloží do "Tvé plány". 

V neposlední řadě jsou zde "tři tečky" tedy další možnosti, které se skládájí pouze ze 2 možností - Upravit existující plán a O aplikaci. Tato malá navigace se objeví, zároveň aplikace "zešedne", aby byla navigace zvýrazněna. při kliku jinam než na tyto dvě možnosti se aplikace vrátí do původního stavu.
Upravit existující plán otevře stejnou stránku jako "vytvořit nový plán" kde lze přidat/odebrat/přepsat jednotlivé úlohy a následně tento plán uložit. 

Jako poslední je "O aplikaci". Je zde napsána verze aplikace, kontakt a kdo aplikaci vytvořil. 



Možné rozšíření aplikace:
Za splněný cíl dostat určitý počet mincí/žetonů/bodů, za které by mohl uživatel buď něco kupovat nebo je sdílet se svými přáteli, a tím vidět kolik bodů mají ostatní, tím pádem se předhánět o první místo v počtu bodů(vykonaných aktivit). Uživatele by mezi sebou také mohli sdílet jednotlivé šablony plánů. Lidé by tak byli motivovaní k udělání činnosti. 

Kupovat by mohli například jiné vzhledy aplikace při plnění úkolu. Nebo by se dala přidat postavička, pro kterou lze kupovat oblečení/doplňky...


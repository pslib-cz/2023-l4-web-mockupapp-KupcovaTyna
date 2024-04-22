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


![index](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/66df3bf4-5cba-4494-a673-ea7b8d5a89a0)

Index obsahuje existující plány, které lze ihned zahájit. Je zde taky velmi jednoduchá navigace, která obsahuje: ikonu kalendáře, plusu(vytvořit nový plán) a tři tečky(další možnosti) 
Po rozkliknutí zahájení se otevře stránka se zahájenou aktivitou.

![zahajenaaktivita](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/dc0abfdc-510d-4d20-aa24-329b14d34da8)

Na této stránce je šipka zpět na index, nadpis dané činnosti, seznam úkolů (dole je první úkol, nahoře poslední) pokud je úkolů větší množství, jsou schovány a po splnění úkolu se seznam scrollne(přibude úkol nahoře, zmizí úkol dole). Nadpis zůstává stále vidět.
dále je na této stránce čas, jak dlouho aktivita probíhá a počet zbývajících úkolů. 
![dokoncenaaktivita](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/4e3d3657-50e8-4e2c-afe8-040e5dce888d)

Po dokončení všech úkolů se objeví okno, ve kterém lze přepnout zpět na plány nebo opakovat znovu stejný plán. Zároveň je zde napsán čas, v jakém byl plán dokončen. Také zmizí tento čas ve spodku stránky společně s počtem zbývajících úkolů. 

Po kliknutí na kalendář v indexu se uživatel dostane na kalendář, ve kterém budou vyznačeny dny, ve kteých má uživatel něco naplánovaného. Plán netrvá dýl než 24 hodin, tím pádem tečka zabírá pouze jeden den. "Tečka" je vždy stejná nehledě na počet naplánovaných úloh.
![kalendar](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/5af545cc-77db-4db4-a249-ad91c09edd2e)

Dále zde rozkliknout jednotlivé dny, kde je vidět, které plány jsou 
Po kliknutí na +(vytvoření nového plánu) se objeví stránka, kde lze popsat svůj další vlastní plán. 
![novyplan](https://github.com/pslib-cz/2023-l4-web-mockupapp-KupcovaTyna/assets/107682347/38a84931-03b8-4e81-99ef-00aa57f7bce3)

Na této stránce je prostor pro popsání úkolu a času, který úloha zabere. Taky zde je jednoduché plus a minus pro přidání a odebrání úlohy. Pokud by byl seznam delší, úlohy se budou opět buudou scrollovat. Pod tímto seznamem je sečten počet úloh a celkový čas. Jako poslední je zde tlačítko uložit, který tento plán uloží do "Tvé plány". 









Na závěr by za splněný cíl dostal určitý počet mincí/žetonů/bodů, za které by mohl buď něco kupovat nebo je sdílet se svými přáteli, a tím vidět kolik bodů mají ostatní, tím pádem se předhánět o první místo v počtu bodů(vykonaných aktivit). Uživatele by mezi sebou také mohli sdílet jednotlivé šablony. Lidé by tak byli motivovaní k udělání činnosti. 

Kupovat by mohli například oblečení/doplňky ke své postavičce nebo například jiné vzhledu “cesty” při plnění úkolu.


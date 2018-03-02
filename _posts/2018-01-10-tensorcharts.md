---
layout: post

published: true

date: 2018-01-10 14:03:00 +0100
#update: 2018-01-10 11:23:00 +0100

author: https://twitter.com/tradingfanbois
author_name: tradingfanbois

comments: true

stories: false
note: 'Feature'
genres: Blog

permalink: tensorcharts/
german: false
enslug: tensorcharts

tickers: false

title: "TensorCharts - Webová aplikace s orderbook vizualizací"
description: "TensorCharts jsou momentálně dostupné zadarmo, jsou to data která jejich developer potřeboval na jiný projekt."

feature: "/features/tensorcharts.png"

categories: ["no-ico", "trading"]

tags: ["popular", "footprint-charts", "tensor-charts", "crypto-trading", "whale-watching", "altcoin-trading"]

---

Myšlenka [TensorCharts](https://tensorcharts.com/) je podobná té, která stojí za grafy [Footprint Charts](https://footprintchart.com/) - grafy, které vám umožňují "podívat se donitř svíček", což je jejich slogan. Jedná se o pokročilý softwarový nástroj, který je vhodný hlavně pro daytradery a scalpery, napište si o bezplatné demo [přes marketdelta.com](https://marketdelta.com/solutions/footprint-charts/). TensorCharts jsou dostupné jednoduše přes webový browser.

"Tenzorové grafy" fungují na podobném principu, v něčem jsou zjednodušené a v něčem lepší než Footprints.

V obou případech jde o to, že rozdělujete každou svíčku na klasickém candlestick grafu na stejně velké bloky, například v kroku po 100 dolarech. S Footprints dostanete přesnou hodnotu, která se v každém bloku zobchodovala. Každý blok je barevný a s číslicí uvnitř. Pomocí TensorCharts oproti tomu získáte pouze relativní informaci: Bloky jsou zabarveny na základě relativního objemu, který se v nich obchoduje. Je to přesnější verze [Volume Flow indikátoru](https://www.tradingview.com/script/EHTKtnIt-ST-Volume-Flow-v6/).

[TensorCharts](https://tensorcharts.com/) ale mají i něco navíc - vizualizované orderbooks: Zatímco vývoj ceny je je zobrazen jako zelené a červené bloky, limit orders které čekají na každé straně trhu jsou vykresleny v odstínech modré a rozlišené podle velikosti objednávky:

![](/features/tensor/tensor5.png)

Díky tomu je mnohem snazší všimnout si buy walls nebo spooferů. Když chcete vidět spoofera při práci, musíte přestat zírat na graf, otevřít si order book a chvíli nad ní meditovat. Když se objeví buy wall a za chvíli ji její autor stáhne, v order books už nepoznáte nic. Na rozdíl od toho ve vizualizaci tahle informace zůstává.

Vizualizace je také dobrá, když chcete mít představu o tom, kde by se mohly vytvořit support a resistance úrovně. Tady jsou třeba vidět dost velké buy orders na BCH trhu:

![](/features/tensor/tensor4.png)

V neposlední řadě se na první pohled projevují i ​​rozdíly mezi jednotlivými trhy s kryptoměnami.

Tato 5m vizualizace na trhu ETHUSD ukazuje velké množství malých objednávek, většinou dost rozptýlené, jen některé z nich jsou na podobných úrovních a vytváří resistance level:

![](/features/tensor/tensor9.png)

Na tomto grafu BTCUSD 5m vidíte, že rozdíly v hodnotě objednávek jsou výraznější. Vzniklo několik klíčových úrovní s velkými objednávkami, ale zbývající objednávky mezi nimi jsou relativně bezvýznamné:

![](/features/tensor/tensor7.png)


[TensorCharts](https://tensorcharts.com/) jsou v tuto chvíli zdarma k dispozici s daty z Bitfinex API, jedná se o kolaterální data z jiného projektu toho samého vývojáře.

Ten projekt se nazývá [cointerminal.io](https://cointerminal.io/). Existuje další projekt s tím samým jménem [který je ale agregátor zpráv](https://site.cointerminal.co/) podobně jako terminál Bloomberg, je placený a nemá co do činění s cointerminal.io.

![](/features/cointerminal.png)

[Cointerminal.io](https://cointerminal.io/) se zaměřuje na statistiku trhu. Můžete si vybrat své oblíbené kryptoměny a podívat se na přehled cenového vývoje v timeframech 1H, 4H, 1D a 15D, nebo na přehled indikátorů (MACD, RSI). K dispozici jsou cenové alerty a také rozhraní pro trading, kde budete moci obchodovat na krypto-burzách pomocí API - cointerminal.io bude zpoplatněná aplikace a tenzorové mapy by měly být dostupné ve verzi PRO.

Grafy ze standardní verze jsou na podobné úrovni jako cryptowatch. Máte možnost přepínat mezi svíčkovými grafy a Heikin-Ashi. Po rozkliknutí tlačítka "Analýza" dostanete graf a sadu nejpoužívanějších indikátorů (MACD s alertem na divergence). Většina těchto funkcí je stále ve vývoji, ale můžete se už zaregistrovat - vše zatím zdarma, ale signupy jsou omezené. Tady jsou dva signup kódy: `q7zg46fu`,` ogsqr1b9`.

#### Naučte se používat TensorCharts

Na anglickém webu v sekci [Strategie](https://www.altcointrading.net/strategy/) se objeví příspěvek o tom, jak tenzorovým grafům porozumět a jaké informace v nich hledat. Co se týče základů, na YouTube je série krátkých videí (každé má asi 1 minutu).

[Série krátkých video tutoriálů na YouTube](https://www.youtube.com/watch?v=YZCUMtV8rBU&list=PLV2igM-bP06wcjn5J2Msu9nI3VYhvhu6T)


#### Shrnutí: Výkonný nástroj

Kdyby na [TensorCharts](https://tensorcharts.com/) byly dostupné programovatelné indikátory, byla by to podstatně lepší platforma než TradingView. I teď vám tyhle grafy mohou dát docela dobrou výhodu - možná je zvláštní volat po něčem takovém, ale TensorCharts by vážně měly být placeným nástrojem. Prozatím si můžete vystačit s kombinací TradingView a TensorCharts a taky doufat, že servery TensorCharts nebudou moc přetížené.

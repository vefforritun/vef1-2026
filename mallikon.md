# Notkun mállíkana í vefforritun 1

## Rammi notkunar

Ekki er leyfilegt að nota stór mállíkön (LLM, „gervigreind“, t.d. ChatGTP eða Claude) til að skrifa lausn á verkefnum, hvort sem það er partur eða heild. Undir lausn fellst allur kóði (hvort sem það er HTML, CSS eða JavaScript) sem skilað er til yfirferðar á verkefni.

Eingöngu er leyfilegt að fá aðstoð sambærilega við þá sem dæmatímakennari myndi veita, t.d. að útskýra námsefni, fá ráðleggingar um næstu skref eða að leysa úr villuskilaboðum.

Út frá stigum sem skilgreind eru á „[Gervigreind við Háskóla Íslands](https://setberg.hi.is/is/gervigreind)“ undir „[Stig notkunar gervigreindar í námskeiðum](https://setberg.hi.is/is/stig-notkunar-gervigreindar-i-namskeidum)“ fellur notkun undir stig 2 „Gervigreind sem glósufélagi“.

## Notkun

Þegar mállíkan er notað til aðstoðar við verkefni verður að taka það fram í skilum, annað hvort í skiluðum gögnum eða í skilum á Canvas (t.d. sem athugasemd) með gagnsæisyfirlýsingu, sjá [Heiðarleiki, heimildir og persónuvernd](https://setberg.hi.is/is/nemendur/vidmid-um-sidferdi-og-vinnubrogd). Koma þarf fram:

1. Hvaða mállíkan var notað.
2. Hvaða part af verkefninu var fengin aðstoð við.
3. Afrit af „spjalli“.
4. Túlkun og hvernig nemandi staðfesti að upplýsingar væru réttar og í samræmi við námsefni.

### Grunn fyrirmæli

Þegar mállíkön eru notuð skal nota grunn fyrirmæli sem minnka líkur á að verkefni sé leyst fyrir nemanda. Að minnsta kosti skal nota:

> Hlutverk þitt er að aðstoða nemendur í háskólanámi við HÍ í tölvunarfræði við að læra vefforritun. Aldrei skal leysa verkefni, hvort sem er í heild sinni eða að hluta. Eingöngu skal hjálpa nemenda með því að útskýra, gefa leiðsögn og endurgjöf.
> 
> Það sem má gera:
> - Útskýra hugtök, námsefni og samhengi
> - Leggja til skref til lausnar á verkefnum án þess að gefa beina lausn
> - Útskýra villur eða vandamál sem nemendur lenda í, þetta skal gera í skrefum þar sem nemenda er beint í rétta átt með leiðbeinandi spurningum
> 
> Það sem má ekki gera:
> - Útfæra verkefni í heild sinni eða að hluta
> - Ljúka við eða lagfæra verkefni sem er skrifað að hluta
> - Endurskrifa hluta af verkefni til að vera „betra“
> - Gefa löng dæmi um kóða
> 
> Verklag við að aðstoða nemendur:
> 1. Fá á hreint hvert verkefnið eða vandamálið er með því að spyrja leiðbeinandi spurninga
> 2. Vísa í námsefni, lykilhugtök og fyrirlestra þar sem við á í stað þess að gefa bein svör
> 3. Leggja til næstu skref í stað þess að útfæra
> 4. Fara yfir kóðabrot og spyrja leiðbeinandi spurninga sem leiða til úrbóta
> 5. Útskýra hvers vegna, ekki bara hvernig
> 
> Ef gefin eru kóðadæmi skal halda þeim í lágmarki (2-3 línur), gera óháð verkefni sem verið er að leysa (t.d. með því að nota annað sambærilegt verkefni, önnur breytuheiti) og einblína á eitt hugtak í einu.
> 
> Nánari efni sem skal nota til grundvallar:
> - [Námsefni](https://bok.vefforritun.is/)
> - [Fyrirlestrar og dæmi](https://github.com/vefforritun/vef1-2026/tree/main/namsefni)
> - [Lykilhugtök](https://github.com/vefforritun/vef1-2026/tree/main/lykilhugtok.md)

Þessi fyrirmæli má setja inn í viðkomandi kerfi sem _instructions_ bæði í ChatGTP og Claude. Verkefni munu hafa þessi fyrirmæli uppsett í [`AGENTS.md`](https://agents.md/) skrá sem fylgir.

### Dæmi um notkun

Hér er dæmi um hvernig nemandi gæti skilað inn upplýsingum um notkun á mállíkani við lausn á [verkefni 1](https://github.com/vefforritun/vef1-2026-v1).

> Við lausn á verkefni 1 var mállíkanið Claude (ChatGPT) notað til að fá aðstoð við að komast af stað.
> Afrit af spjalli má sjá hér: [Claude dæmi](https://claude.ai/share/80194b84-4c96-442b-94e9-522e8e4550f7), [ChatGPT dæmi](https://chatgpt.com/share/688383d3-5b14-8013-ad9a-8f41ac0d80f8).
> Eftir að hafa fengið þessar upplýsingar skoðaði ég nánar námsefni og las mér nánar til um [hyperlink](https://bok.vefforritun.is/03.html#3.1.2) og [hvernig við vísum í efni](https://bok.vefforritun.is/04.element#4.6.1).
> Með því að vinna í og útfæra verkefnið staðfesti ég að allt virkaði rétt og gat skilað samkvæmt verkefnalýsingu.

## Spurt og svarað

### Af hverju má ekki nota mállíkön til að skrifa lausn á verkefni?

Í þessu námskeiði lærum við grunn vefforritunar út frá gefnu námsefni og verkefnum. Að nota þessi tól til að skrifa lausnir fyrir okkur fer gegn því markmiði. Áður en hægt er að meta lausnir sem við fáum skrifaðar fyrir okkur þurfum við að skilja grunninn.

### Af hverju þarf að taka fram alla notkun á notkun gervigreindar?

Til að geta gefið endurgjöf á notkun og bætt kennslu er mikilvægt að sjá hvernig nemendur nota þessi tól.

## Tilvísanir

Byggt að einhverju leiti á [The University In The AI Era](https://htmx.org/essays/universities-and-ai/) og [AI Agent Guidelines](https://gist.github.com/1cg/a6c6f2276a1fe5ee172282580a44a7ac) eftir Carson Gross.

> Útgáfa 0.1

## Útgáfusaga

| Útgáfa | Lýsing        |
| ------ | ------------- |
| 0.1    | Fyrsta útgáfa |

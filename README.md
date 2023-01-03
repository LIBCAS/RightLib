## **RightLib – elektronické zpřístupnění chráněných publikací**

Identifikační kód projektu: `DG18P02OVV002`

Projekt RightLib je řešen Knihovnou AV ČR, v. v. i., Moravskou zemskou knihovnou v Brně a Národní knihovnou České republiky.

Koordinátorem vývoje je Knihovna AV ČR, v. v. i., zastoupená Ing. Martinem Lhotákem, lhotak@knav.cz.

Hlavním cílem projektu je vytvoření funkčního poloprovozu ošetřujícího zpřístupnění chráněných dokumentů na základě různých parametrů s názvem RightLib, který bude propojen s Českou digitální knihovnou - národním agregátorem digitálních knihoven.

Poloprovoz [Česká digitální knihovna - RightLib ](https://czechdigitallibrary.cz/)

Poloprovoz je provozován Moravskou zemskou knihovnou v Brně a využívá komponenty vyvinuté v rámci projektu RightLib. Řešení umožňuje přístup k chráněným-licencovaným publikacím a jako hlavní softwarové řešení je využíván systém Kramerius ve verzi 7, jehož funkčnost byla v rámci projektu Rigtlib vyvíjena s účelem zajistit řešení pro zpřístupnění digitální dokumentů s různými typy licencí současně se zajištěním správy uživatelů s různými identitami. 

Software [Kramerius 7](https://github.com/ceskaexpedice/kramerius/wiki/K7) je open source řešení pro zpřístupnění digitálních dokumentů. Primárně je určen pro digitalizované knihovní sbírky, monografie a periodika. Využit může být ke zpřístupnění dalších typů dokumentů např. map, hudebnin a starých tisků, kronik, případně částí dokumentů jako jsou články a kapitoly. Systém je vhodný také pro digital born dokumenty, tedy dokumenty, které vznikly v elektronické podobě. Kramerius je průběžně upravován tak, aby struktura metadat odpovídala standardům vyhlašovaným Národní knihovnou České republiky. Systém poskytuje rozhraní pro přístup koncových uživatelů, zajišťující vyhledávání v metadatech a v plných textech, generování vícestránkových PDF dokumentů z vybraných stran, vytváření virtuálních sbírek a další operace nad uloženou sbírkou digitálních dokumentů.

Verze 7 využívá plně úložiště Akubra a nového schéma indexu vyhledávacího systému SOLR. Klientské prostředí zahrnuje uživatelského klienta a administrátorského určeného na správu systému. Nově vyvinutá funkcionalita : administrace, virtuální sbírky, podpora PDF/ePUB, licencování a další. Pro migrace z předchozí verze jsou připraveny pomocné utility. Pro správu uživatelů je využito řešení Keycloak a k jejich identifikaci technologie Shibboleth a Česká akademická federace identit eduID.cz.

V rámci projektu RightLib byli vytvořeni speciální klienti pro mobilní zařízení:

* [Mobilní klient pro iOS](https://github.com/ceskaexpedice/kramerius/wiki/Aplikace-pro-iOS) Klient pro mobilní zařízení s iOS, který zpřístupňuje obsah digitálních knihoven prostřednictvím portálu Digitalniknihovna.cz.
* [Mobilní klient pro Android](https://github.com/ceskaexpedice/kramerius/wiki/Aplikace-pro-Android) Klient pro mobilní zařízení s OS Android, který zpřístupňuje obsah digitálních knihoven prostřednictvím portálu Digitalniknihovna.cz.

Součástí výstupů projektu je [Metodika pro zajištění bezpečného přístupu k datům v rámci různých režimů zpřístupnění digitálního obsahu](https://lib.cas.cz/dokumenty/Metodika_RightLib.pdf)

**Česká digitální knihovna - RightLib je hlavním aplikovaným výstupem výzkumného projektu s názvem „RightLib – elektronické zpřístupnění chráněných publikací “, identifikační kód projektu: DG18P02OVV002, financovaného z programu NAKI Ministerstva kultury ČR v letech 2018-2022.**




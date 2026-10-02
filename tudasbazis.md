# Ládonyi Adrienn – tudásbázis

> Csak igaz, ellenőrzött tények kerülhetnek ide. Amit ide írsz, azt az asszisztens állítani fogja.

## Röviden
- Épületgépész mérnök, 12 éves tapasztalattal a távhőszolgáltatásban, hatósági (MEKH) felügyelet alatt működő, szabályozott energiaipari környezetben.
- Jelenleg négy távhőszolgáltatás területi vezetője, kettőnek ügyvezetője.
- Erőssége, hogy a működési és szabályozási igényekből maga épít működő megoldást: eljárásrendeket, szabályzatokat és saját fejlesztésű digitális eszközöket.

## Milyen szerepet keres
- Energetikai, közmű-, digitalizációs vagy folyamatfejlesztési területen keres vezetői vagy szakértői szerepet.
- Vezetőként olyan munkát keres, ahol nap mint nap együtt dolgozhat a kollégáival, nem egymástól távol. Szakértőként is szívesen vállal munkát.
- A szabályozott környezetben végzett munka nem okoz neki problémát. Álláspontja szerint a szabályozott környezet nem gátolja a folyamatok egyszerűsítését és optimalizálását.

## Szakmai tapasztalat
- 2024-től ügyvezető: Distherm Kft., Cellhő Kft.
- 2022-től területi vezető: Distherm Kft., Cellhő Kft., Bakony-Távhő Kft., Veolia Energia Magyarország Zrt. zirci távhő. Feladata a négy távhőszolgáltatás operatív, pénzügyi és szabályozási működtetése.
- 2016–2022: műszaki vezető a Distherm Kft.-nél; a műszaki terület mellett a lakossági ügyfélszolgálatot is irányította.
- 2014–2016: ügyfélszolgálati munkatárs a Distherm Kft.-nél.
- Összesen 8 évet dolgozott a lakossági ügyfélszolgálat területén (munkatársként, majd irányítóként).
- Az újonnan csatlakozó távhőszolgáltató társaságokat ő tanította be.
- Kapcsolatot tart a MEKH-kel, önkormányzatokkal és kiemelt ügyfelekkel; nagyvállalati mátrixszervezetben dolgozik.

## A munkája részletesen
- 49 munkatárs munkáját irányítja a négy távhőszolgáltatásnál.
- A távhőszolgáltatás összetett tevékenység: a műszaki üzemeltetés, az ügyfélkapcsolatok, a hatósági szabályozás és a pénzügyek egyszerre vannak jelen benne.
- Napi kapcsolatban dolgozik a kontrolling, a számvitel, a pénzügy, a jog és a HR területével.
- Részt vesz a munkaerő-kiválasztásban.
- Részt vesz az éves tervezésben, működési (OPEX) és beruházási (CAPEX) oldalon is.

## Szabályozás és dokumentumok
- MEKH-adatszolgáltatások és a MEKH által előírt fejlesztési tervek elkészítése (hőenergia-mérleg, veszteségelemzés mért adatokból, VDI 2055 szerinti hőveszteség-számítás, fejlesztési változatok energia- és költséghatással).
- Részt vett egy önkormányzati távhőrendelet megírásában; az önkormányzat 2025 júliusában elfogadta.
- Megírt egy teljes üzletszabályzatot a belső szabályzatokkal és a külső jogszabályokkal összhangban; bevezetése folyamatban, várható hatálybalépése 2027. január 1.
- Eljárásrend épületrészek távhőszolgáltatáshoz csatlakozására és leválására: célja, hogy a megfelelő információ a megfelelő időben jusson el a megfelelő emberhez. Word-sablonok (igénybejelentő, feltétellevél, kivitelezési hozzájárulás, megvalósulási jegyzőkönyv), folyamatleírás, folyamatábra, védett nyilvántartás. Mind a négy szolgáltatónál bevezetve. Tervezett továbbfejlesztés: a dokumentumok AI-alapú előállítása a sablonokból.
- Számozott üzemeltetési és karbantartási szabályzatrendszer (ÜZEM-100, KARB-100) és üzemi naplók. Szabályozza a gyűjtendő adatok körét és gyakoriságát, a karbantartások ütemezését és a karbantartási tervek elkészítésének időpontját, a meghibásodások és a nem azonnali hibaelhárítás dokumentálását, az üzemzavari teendőket, valamint a munkavállalók végzettségeinek és vizsgáinak nyilvántartását, érvényességét és az ismétlő vizsgák ütemezését. Bevezetve a Veolia Energia öt távhőrendszerénél (Zirc, Cegléd, Budapest, Szilas-park, Algyő); továbbfejlesztése folyamatban, hogy a többi társaságnál is alkalmazható legyen.
- ISO 9001, 14001, 37001, 45001 és 50001 szerint tanúsított környezetben dolgozik; auditált félként részt vett ISO 50001 és ISO 37001 auditokon.

## Saját digitális fejlesztések
Minden fejlesztést maga valósított meg, a rendelkezésére álló eszközökkel, alacsony költséggel; nem rendelte meg másoktól.
- QR-kódos mérőleolvasás fotós visszaellenőrzéssel (Google Forms, Google Sheets, Google Apps Script, triggerek). Minden mérő gyári szám alapján QR-kódot kapott. Beolvasás után megjelenik a hőközpont-azonosító és a gyári szám, a kolléga beírja a mérőállást és fotót csatol. Az adat táblázatba kerül, a fotót a rendszer automatikusan átnevezi (gyári szám és készítési időpont) és az elszámolási hónap mappájába menti (a hónap 15-éig beküldött kép az előző hónaphoz kerül). A táblázatban látszik a fotó miniatűrje, a rendszer kiszámolja a fogyasztást az előző leolvasáshoz képest, és jelöli a túl magas vagy túl alacsony értékeket. Egy fűtési időszaki leolvasás kb. 500 mérőt jelent; korábban 10–15 helyszínre kellett visszamenni újraleolvasni vagy ellenőrizni, most 2-re, és ott is a feltöltött kép minősége volt a gond. Tervezett továbbfejlesztés: AI-alapú képfelismerés (OCR) és automatikus adatellenőrzés.
- Havi zárás-előkészítő Excel-tábla, kb. 2018-ban készítette; azóta a Veolia összes távhő-leányvállalata használja. Makró nélkül, csak képletekkel működik: legördülő menüből kiválasztott társasághoz betölti a használt főkönyvi számokat, a számlázóprogram exportját változtatás nélkül kell beilleszteni (a képletes cellák védettek), és a tábla a számvitel számára értelmezhető formába rendezi az adatokat.
- H8i: ISO-szabványokhoz igazodó műszaki adatplatform, amelyhez különböző közműszolgáltatók és felhasználók modulárisan csatlakozhatnak. Céljai: műszaki adatok és dokumentumok tárolása, adatalapú lekérdezések, adatszolgáltatások automatizálása, költségkalkuláció és összevetése a ténnyel, nagy mennyiségű mért adat elemzése és előrejelzése; a parancsok megadhatók hagyományosan vagy szövegesen, AI segítségével. Jelenleg működő prototípus: a mag (hierarchikus adatmodell helyszíntől a mérőeszközig, egységes űrlapok, logikai törlés) működik, a további modulok fejlesztés alatt. Python, Streamlit, SQLite. Az igényeket, funkciókat és prioritásokat ő határozza meg, és ő fejleszti.
- Automatizálás és riportok Excel/Power Query, VBA és Google Apps Script eszközökkel; beszerzési tervezés számla- és rendelési adatokból.

## Mesterséges intelligencia
- A generatív AI-t (Claude) rendszeresen használja szabályzatok, dokumentumok, elemzések és kód előkészítésében.
- A kimeneteket mindig szakmailag ellenőrzi; az AI-t gyorsításra használja, a felelősség az övé.
- Ezt az asszisztenst AI-támogatással maga tervezte, építette és telepítette (Python, Streamlit, Claude API), úgy, hogy csak ellenőrzött tudásbázisból válaszoljon.

## Eszközök
- Python (Streamlit, SQLite), Google Apps Script, VBA, Excel és Power Query.
- Power BI: képzésen vett részt.

## Végzettség
- Épületgépész mérnök MSc – Pécsi Tudományegyetem MIK (folyamatban). Diplomamunka: Szekunder távhőhálózatok primerizálása és átállása változó tömegáramú üzemre: veszteségfeltárási metodika adathiányos környezetben.
- Épületgépész mérnök BSc – Pécsi Tudományegyetem MIK, 2021–2025. Szakdolgozat: 40 lakásos távfűtött társasház fűtési rendszerének rekonstrukció tervezése.
- Felsőfokú jogi asszisztens – Károli Gáspár Református Egyetem, 2016–2018. Záródolgozat: a távhődíj-hátralékok behajtása, a szerződésszegések következményei.
- Közgazdász BSc, logisztika szakirány – Budapesti Kommunikációs Főiskola, 2007–2012. (Közgazdász gyakorlata nincs, a végzettséget szerzett.)

## Munkastílus (saját megfogalmazása szerint)
- Proaktív és célorientált, folyamatosan keresi a fejlődési lehetőségeket. Stratégiailag gondolkodik, és ha jobb eredményt vár, eltér a megszokott módszerektől.
- Önállóan azonosítja az elvégzendő feladatokat, nem vár külső utasításra; a kezdeményező és irányító szerepekben érzi magát a legjobban.
- Olyan közegben dolgozik a legjobban, ahol értékelik a kezdeményezést, a teljesítményt és a gyors, hatékony megvalósítást, és támogatják az új ötleteket.
- Példák a kezdeményezőkészségére: a QR-kódos mérőleolvasás, a havi zárás-előkészítő tábla és a 2025-ös ajkai faültetés ötlete.

## Önkéntesség
- 2025-ben fákat ültettek Ajkán; az akció ötletgazdája ő volt, és több cég fogott össze a cél érdekében.
- Magánemberként is előfordult már, hogy a természetben eldobált szemetet összeszedte és elszállította.

## Nyelv és egyéb
- Angol: középfokú komplex (írásbeli és szóbeli) nyelvvizsga.
- B kategóriás jogosítvány, aktív vezetési tapasztalattal.

## Kapcsolat
- E-mail: adrienn.ladonyi@gmail.com
- Portfólió: https://claude.ai/artifact/QiRGfb67wkuPaR4gvht8Ap

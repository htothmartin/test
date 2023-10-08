# Film bérlés Projektterv 2023

## 1. Összefoglaló

A projekt egy online platform létrehozását célozza, ahol felhasználók filmeket bérelhetnek. A weboldal lehetővé teszi a felhasználók számára, hogy böngésszenek egy széles filmkínálat között, és egyszerűen bérelhessenek vagy vásároljanak különböző műfajokban és nyelveken elérhető filmeket. A weboldal létrehozásának fő célja az, hogy kényelmes és gyors hozzáférést biztosítson a legfrissebb és klasszikus filmekhez egy helyen. Ezen kívül segít a felhasználóknak, hogy otthonuk kényelméből élvezhessék a moziélményt, miközben támogatja a filmipart a bérlésekből származó bevétel révén.

## 2. A projekt bemutatása

Ez a projektterv a Film bérlés projektet mutatja be, amely 2023-10-05-től 2023-12-04-ig tart, azaz összesen 59 napon keresztül fog futni. A projekten nyolc fejlesztő fog dolgozni, az elvégzett feladatokat pedig négy alkalommal fogjuk prezentálni a megrendelőnek, annak érdekében, hogy biztosítsuk a projekt folyamatos előrehaladását.

### 2.1. Rendszerspecifikáció

A Film Bérlő rendszer célja az online filmkölcsönzés lehetővé tétele, amely lehetővé teszi a felhasználók számára, hogy filmeket böngésszenek, béreljenek. A rendszernek képesnek kell lennie a weboldalon elérhető filmekek állapotát (cím, hossz, ár, leírás, borítókép, megjegyzések, értékelések) nyilván tartsa és hogy a rendszer a bejövő bérléseket rendszerezze. 
Ezen felül kepesnek kell lennie a filmkatalógus, a felhasználói fiókok és a bérlési folyamat kezelésére. A rendszer különbőző szerepköröket támogat, a regisztrált felhasználók akiknek a következő funkciók érhetöek  majd el: filmek böngészése, bérlése, fiók kezelése, kedvenc filmek, film watchlist, értékelés, megjegyzések, az  adminisztrátoroknak elérhető funkciók: felhasználói fiókok kezelése, bérlési folyamat felügyelete, filmek hozzáadása. 
A rendszernek rendelkeznie kell egy kereső funkcióval, amivel a felhasználók kereshetnek az elérhető filmek között. Az oldalnak lehetőséget kell biztosítania a felhasználóknak arra, hogy kapcsolatba lépjenek az oldal üzemeltetőivel, ha bármilyen problémájuk van.

### 2.2. Funkcionális követelmények

- Felhasználó kezelés (CRUD)
- Felhasználói munkamenet megvalósítása több jogosultsági szinttel
- Filmek kezelése (CRUD)
- Filmek értékelése (kommentek, értékelések)
- Bérlések kezelése (CRUD):
  - Kosár kezelés (CRUD)
- Virtuális pénznem kezelés (Pénz feltöltése az oldalra, majd annak használata)

// TODO: Kiegészíteni

### 2.3. Nem funkcionális követelmények

- A kliens oldal böngészőfüggetlen legyen
- Reszponzív megjelenés
- Az érzékeny adatokat biztonságosan tároljuk
- A legfrissebb technológiákat használja a rendszer

// TODO: Kiegészíteni

## 3. Költség- és erőforrás-szükségletek

// TODO: Kitalálni személynap igény

Az erőforrásigényünk összesen `??` személynap, átlagosan 10 személynap/fő.

A rendelkezésünkre áll összesen 8 \* 70 = 560 pont.

## 4. Szervezeti felépítés és felelősségmegosztás

A projekt megrendelője Dr. Pflanzner Tamás. A Film bérlés projektet a projektcsapat fogja végrehajtani, amely jelenleg nyolc fejlesztőből áll. A csapatban található tapasztalt és pályakezdő webprogramozó is, A tapasztalt projekttagok kb. egy éve dolgoznak az iparban.

- Székesi Marcell (1 év ipari tapasztalat a Frontendart Kft-nél)
- Merena Gábor (gyakorlat a Hansa-Kontakt Kft-nél)

// TODO: Kiegészíteni

### 4.1 Projektcsapat

A projekt a következő emberekből áll:

| Név                  | Pozíció          | E-mail cím (stud-os)       |
| -------------------- | ---------------- | -------------------------- |
| Székesi Marcell      | Projektmenedzser | `h269707@stud.u-szeged.hu` |
| Batancs Donát        | Projekt tag      | `h253438@stud.u-szeged.hu` |
| Bánhidai Nóra        | Projekt tag      | `h255196@stud.u-szeged.hu` |
| Hajagos-Tóth Martin  | Projekt tag      | `h261000@stud.u-szeged.hu` |
| Merena Gábor         | Projekt tag      | `h267531@stud.u-szeged.hu` |
| Péter Gergely Dániel | Projekt tag      | `h268642@stud.u-szeged.hu` |
| Rác Ákos             | Projekt tag      | `h268858@stud.u-szeged.hu` |
| Rózsa Dominik        | Projekt tag      | `h051106@stud.u-szeged.hu` |

## 5. A munka feltételei

### 5.1. Munkakörnyezet

A projekt a következő munkaállomásokat fogja használni a munka során:

// TODO: Kiegészíteni

- Munkaállomások: `x` db, Windows 10-es, Windows 11-es, Ubuntu, stb... operációs rendszerrel
- Asztali számítógép (CPU: i7 2600k, RAM: 16GB, GPU: Nvidia RTX2070)
- Asztali számítógép (CPU: i5 6600k, RAM: 16GB, GPU: Nvidia GTX1060)
- Laptop (CPU: i7 8550u, RAM: 16GB, GPU: Intel UHD Graphics 620)

A projekt a következő technológiákat/szoftvereket fogja használni a munka során:

- PostgreSQL adatbázisszerver
- Spring Boot backend keretrendszer
- Maven szoftverprojekt menedzselő szoftver
- VSCode, IntelliJ IDEA fejlesztőkörnyezetek
- Git verziókövető (GitLab)
- React frontend keretrendszer

// TODO: Kiegészíteni

### 5.2. Rizikómenedzsment

| Kockázat                                  | Leírás                                                                                                                                                                                   | Valószínűség | Hatás |
| ----------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ----- |
| Betegség                                  | Súlyosságtól függően hátráltatja vagy bizonyos esetekben teljes mértékben korlátozza a munkavégzőt, így az egész projektre kihatással van. Megoldás: a feladatok átcsoportosítása        | nagy         | erős  |
| Kommunikációs fennakadás a csapattagokkal | A csapattagok között nem elégséges az információ áramlás, nem pontosan, esetleg késve vagy nem egyértelműen tájékoztatjuk egymást. Megoldás: még gyakoribb megbeszélések és ellenőrzések | kis          | erős  |

// TODO: Kiegészíteni

## 6. Jelentések

### 6.1 Munka menedzsment

A munkát Székesi Marcell koordinálja. Fő feladata, hogy folyamatosan egyeztessen a csapattagokkal az előrehaladásról és a fellépő problémákról, esetlegesen a megoldásban is segítséget nyújhat a projekt csúszásának elkerülése végett. További feladata a heti szinten tartandó csoportgyűlések időpontjának és helyszínének leszervezése, erről üzenetben tájékoztatja a projektcsapatot. Emellett a projekt fejlesztésében is részt vesz a nagyobb mértékű haladás érdekében.

### 6.2 Csoportgyűlések

A projekt hetente ülésezik, hogy megvitassák az azt megelőző hét problémáit, illetve hogy megbeszéljék a következő hét feladatait. A megbeszélésről minden esetben memó készül.

1. megbeszélés:

- Időpont: 2023. 10. 05.
- Hely: SZTE József Attila Tanulmányi és Információs Központ - Szeged, Ady tér 10, 6722
- Résztvevők: Székesi Marcell, Batancs Donát, Bánhidai Nóra, Hajagos-Tóth Martin, Merena Gábor, Péter Gergely Dániel, Rác Ákos
- Érintett témák: Projekttéma kiválasztása, projektterv megkezdése, átbeszélése

### 6.3. Minőségbiztosítás

Az elkészült terveket a terveken nem dolgozó csapattársak közül átnézik, hogy megfelel-e a specifikációnak és az egyes diagramtípusok összhangban vannak-e egymással. A meglévő rendszerünk helyes működését a prototípusok bemutatása előtt a tesztelési dokumentumban leírtak végrehajtása alapján ellenőrizzük és összevetjük a specifikációval, hogy az elvárt eredményt kapjuk-e. További tesztelési lehetőségek: unit tesztek írása az egyes modulokhoz vagy a kód közös átnézése (code review) egy, a vizsgált modul programozásában nem résztvevő csapattaggal. Szoftverünk minőségét a végső leadás előtt javítani kell a rendszerünkre lefuttatott kódelemzés során kapott metrikaértékek és szabálysértések figyelembevételével.
Az alábbi lehetőségek vannak a szoftver megfelelő minőségének biztosítására:

Specifikáció és tervek átnézése (kötelező)
Teszttervek végrehajtása (kötelező)
Unit tesztek írása (választható)
Kód átnézése (választható)

### 6.4. Átadás, eredmények elfogadása

A projekt eredményeit a megrendelő, Dr. Pflanzner Tamás fogja elfogadni. A projektterven változásokat csak a megrendelő írásos engedélyével lehet tenni. A projekt eredményesnek bizonyul, ha specifikáció helyes és határidőn belül készül el. Az esetleges késések pontlevonást eredményeznek.
Az elfogadás feltételeire és beadás formájára vonatkozó részletes leírás a következő honlapon olvasható: https://okt.inf.szte.hu/rf1/

### 6.5. Státuszjelentés

Minden mérföldkő leadásnál a projekten dolgozók jelentést tesznek a mérföldkőben végzett munkájukról a a megadott sablon alapján. A gyakorlatvezetővel folytatott csapatmegbeszéléseken a csapat áttekintik és felmérik az eredményeket és teendőket. Továbbá gazdálkodnak az erőforrásokkal és szükség esetén a megrendelővel egyeztetnek a projektterv módosításáról.

## 7. A munka tartalma

### 7.1. Tervezett szoftverfolyamat modell és architektúra

A szoftver fejlesztése során az agilis fejlesztési modellt alkalmazzuk, mivel a fejlesztés során nagy hangsúlyt fektetünk a folyamatos kommunikcióra. A fejlesztés során a szoftver specifikációi rugalmasan vátozhatnak, és ezzel a módszertannal tudunk a leggyorsabban alkalmazkodni az új elvárásokhoz.
A webalkalmazás az MVC (modell-view-controller) felépítést követi, a szerver és a kliens függetlenek, csupán API végpontok segítségével kommunikálnak.

### 7.2. Átadandók és határidők

A főbb átadandók és határidők a projekt időtartama alatt a következők:

| Szállítandó |                                 Neve                                  | Határideje |
| :---------: | :-------------------------------------------------------------------: | :--------: |
|     D1      |       Projektterv és Gantt chart, prezentáció, egyéni jelentés        | 2023-10-09 |
|    P1+D2    |    UML, adatbázis- és képernyőtervek, prezentáció, egyéni jelentés    | 2023-10-23 |
|    P1+D3    |       Prototípus I. és tesztelési dokumentáció, egyéni jelentés       | 2023-11-10 |
|    P2+D4    | Prototípus II. és frissített tesztelési dokumentáció, egyéni jelentés | 2023-12-04 |

## 8. Feladatlista

A következőkben a tervezett feladatok részletes összefoglalása található.

### 8.1. Projektterv (1. mérföldkő)

Ennek a feladatnak az a célja, hogy megvalósításhoz szükséges lépéseket, az erőforrásigényeket, az ütemezést, a felelősöket és a feladatok sorrendjét meghatározzuk, majd vizualizáljuk Gantt diagram segítségével.

Részfeladatai a következők:
-valami 
-rfsdfsdf sadf fs ad-f asdfasd f
f asdfasd fasdf asdf as

#### 8.1.1. Projektterv kitöltése

Felelős: Mindenki

Tartam: 4 nap

Erőforrásigény: 1 személynap/fő

#### 8.1.2. Bemutató elkészítése

Felelős: // TODO

Tartam: 2 nap

Erőforrásigény: 0.5 személynap

### 8.2. UML és adatbázis- és képernyőtervek (2. mérföldkő)

Ennek a feladatnak az a célja, hogy a rendszerarchitektúrát, az adatbázist és webalkalmazás kinézetét megtervezzük.

Részfeladatai a következők:

#### 8.2.1. Use Case diagram

Felelős: // TODO

Tartam: 3 nap

Erőforrásigény: 1 személynap

#### 8.2.2. Class diagram

Felelős: // TODO

Tartam: 4 nap

Erőforrásigény: 2 személynap

#### 8.2.3. Sequence diagram

Felelős: // TODO

Tartam: 3 nap

Erőforrásigény: 2 személynap

#### 8.2.4. Egyed-kapcsolat diagram adatbázishoz

Felelős: // TODO

Tartam: 4 nap

Erőforrásigény: 2 személynap

#### 8.2.5. Package diagram

Felelős: // TODO

Tartam: 3 nap

Erőforrásigény: 0.5 személynap

#### 8.2.6. Képernyőtervek

Felelős: // TODO

Tartam: 3 nap

Erőforrásigény: 1 személynap

#### 8.2.7. Bemutató elkészítése

Felelős: // TODO

Tartam: 1 nap

Erőforrásigény: 0.5 személynap

### 8.3. Prototípus I. (3. mérföldkő)

Ennek a feladatnak az a célja, hogy egy működő prototípust hozzunk létre, ahol a vállalt funkcionális követelmények nagy része már prezentálható állapotban van.

Részfeladatai a következők:

// TODO: Feladatokat kiírni

#### 8.3.18. Tesztelési dokumentum az összes funkcióhoz (TP, TC)

Felelős: Mindenki

Tartam: 7 nap

Erőforrásigény: 1 személynap/fő

// TODO: Szétszedni 8.3.18

#### 8.3.19. A prototípus kitelepítése éles környezetbe

Felelős: // TODO

Tartam: 1 nap

Erőforrásigény: 1 személynap

### 8.4. Prototípus II. (4. mérföldkő)

Ennek a feladatnak az a célja, hogy az előző mérföldkő hiányzó funkcióit pótoljuk, illetve a hibásan működő funkciókat és az esetlegesen felmerülő új funkciókat megvalósítsuk. Továbbá az alkalmazás alapos tesztelése is a mérföldkőben történik az előző mérföldkőben összeállított tesztesetek alapján.

Részfeladatai a következők:

#### 8.4.1. Javított minőségű prototípus új funkciókkal

Felelős: // TODO

Tartam: 5 nap

Erőforrásigény: 2.5 személynap

#### 8.4.2. Javított minőségű prototípus javított funkciókkal

Felelős: // TODO

Tartam: 5 nap

Erőforrásigény: 2 személynap

#### 8.4.3. Javított minőségű prototípus a korábbi hiányzó funkciókkal

Felelős: // TODO

Tartam: 5 nap

Erőforrásigény: 1.5 személynap

// TODO: Teszt Report feladatok

#### 8.4.12. A prototípus kitelepítésének frissítése

Felelős: // TODO

Tartam: 1 nap

Erőforrásigény: 0.5 személynap

## 9. Részletes időbeosztás

// TODO: Gannt diagram

## 10. Projekt költségvetés

// TODO

### 10.1. Részletes erőforrásigény (személynap)

| Név                  | M1  | M2  | M3  | M4  | Összesen |
| -------------------- | --- | --- | --- | --- | -------- |
| Székesi Marcell      |     |     |     |     |          |
| Batancs Donát        |     |     |     |     |          |
| Bánhidai Nóra        |     |     |     |     |          |
| Hajagos-Tóth Martin  |     |     |     |     |          |
| Merena Gábor         |     |     |     |     |          |
| Péter Gergely Dániel |     |     |     |     |          |
| Rác Ákos             |     |     |     |     |          |
| Rózsa Dominik        |     |     |     |     |          |

### 10.2. Részletes feladatszámok

| Név                  | M1  | M2  | M3  | M4  | Összesen |
| -------------------- | --- | --- | --- | --- | -------- |
| Székesi Marcell      |     |     |     |     |          |
| Batancs Donát        |     |     |     |     |          |
| Bánhidai Nóra        |     |     |     |     |          |
| Hajagos-Tóth Martin  |     |     |     |     |          |
| Merena Gábor         |     |     |     |     |          |
| Péter Gergely Dániel |     |     |     |     |          |
| Rác Ákos             |     |     |     |     |          |
| Rózsa Dominik        |     |     |     |     |          |

### 10.3. Részletes költségvetés

| Név                                | M1  | M2   | M3   | M4   | Összesen  |
| ---------------------------------- | --- | ---- | ---- | ---- | --------- |
| Maximálisan megszerezhető pontszám | (7) | (20) | (35) | (28) | 100% (70) |
| Székesi Marcell                    |     |      |      |      |           |
| Batancs Donát                      |     |      |      |      |           |
| Bánhidai Nóra                      |     |      |      |      |           |
| Hajagos-Tóth Martin                |     |      |      |      |           |
| Merena Gábor                       |     |      |      |      |           |
| Péter Gergely Dániel               |     |      |      |      |           |
| Rác Ákos                           |     |      |      |      |           |
| Rózsa Dominik                      |     |      |      |      |           |

Szeged, 2023. 10. 08.

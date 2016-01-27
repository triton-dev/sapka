# SAP-ka
---
## SAP okítás kicsiknek és nagyoknak
- Miről **NEM** lesz szó...
- Miért nem lesz róla szó...
- Mi fér bele 4 órába???

---

> Kezdetben vala a sötétség...
> Teremté az embert. Szorgalmasakat és lustákat. Majd hívá a lustákat _infomatikusnak_ és megbélyegzé őket...

- egyiptomi, maya, sumér birodalmak, Nagy Sándor, Római birodalom, Nagy Fal -> hogyan oldották meg?
- Okosabbak voltak? Volt elég idejük? 


---
## ERP rendszerek
- mik azok,
- mit várunk tőlük,
- sziget alkalmazások <-> integrált rendszerek <-> modul rendszer
- adatbázis kezelők - felhasználói felületek
  * **az adatbázis egy**
  * **minden mindennel összefügg**
  * **az a jó adat, amin nincs! nem kell kezelni, karbantartani, tárolni, stb...**
- OLAP, OLTP rendszerek
- üzleti folyamatok
- felhasználók - szereplők

## SAP a Kezdetektől
- kb. 40 év munkája, 
- assembly -> modern eszközök
- saját adatbázismotor
- saját nyelv (ABAP)
- JAVA alapú kliens
- drága és nagyon drága üzemeltetni 
  * SAP jogok a felhasználónak, és a tanácsadónak
  * minden változás pénzbe kerül!
  * minden kérdés pénzbe kerül

## Beveztés
- folyamatok átvilágítása - külsö <-> belső?
- miért csináljuk így? így szoktuk, vagy így kell?
- megvalósítható? 
  * a javítás nem gyártás, a gyártás nem javítás!
  * melyik modult kell előbb bevezetni (tyúk és a tojás problémája)?
  * a műszaki, vagy a gazdasági érdek az erősebb?
- projekt alapú bevezetés - módszertanok
  * miért nem mennek a projektek?
  * költségek, eredmények
- milyen kompromisszumokra van szükség
- testreszabás (customizing) ???
- TESZTELÉS!!!
- átadás-átvétel
- tapasztalatok
- működtetés, változtatás

## Üzleti folyamataink nagy vonalakban (interaktív)
- konkrét példa elemzése, lebontása
- modulok címszavakban (fekete doboz)
- modul bemenet - kimenet -> kapcsolódás (fekete doboz)

## Szint és szerepvakság (-tévesztés)
- minden modul első sorban önmagáért felel! (bemenetek)
- a kimenet **jósága** a bemenettől függ
  * egy-egy pipa megléte vagy hiánya, stb...
  * szinonímák - homonímák stb...
- a bemeneti hibák halmozódnak, végeredmény katyvasz -> bogozza ki az, aki akarja
- Törzsadatok!
  * cikktörzs
  * művelettervek
  * darabjegyzékek
  * költséghelyek
  * költségnemek
  * főkönyvi számok
  * automatikus könyvelések
  * tárgyi eszközök
  * de akár dolgozók

> Ha csak a saját modulodat ismered, valamelyik **vak** leszel!
>> Minden modul egyenrangú de vannak adat szolgáltató és adat felhasználó modulok.
>> Az adatfelhasználók azt hiszik, hogy a _ranglétrában_ feljebb állnak. ;-)

## Tranzakciók
- lényegük  (atomi műveletek)
- fajtáik xx01,xx02,xx03 (létrehoz, módosít, megjelenít) adatbázisul CRUD, de itt nincs DELETE
- COOIS, KSB1, ME2N, VA05, FS10N, S_ALR_xxxxxxx, stb...
- tömeges karbantartások szinte teljes hiánya, de speciális jogokkal (programmal) lehet, egy-két kivételtől eltekintve
- előre gyártott lekérdezés-sablonok, paraméterezhetők, de sokszor nem elegendőek. -> írj queryt, ha tudsz, vagy FIZESS!!!
- írj queryt -> találd meg, mit hol tároltak (nem egyszerű - tábla-nézet-program?)
- felhasználói(???) felületek
- felhasználóbarát kezelés (csak megválogatja a barátait, mi nem mindig vagyunk barátok)
- fejlesztés - olyan pór felhasználóknak mint mi lehetetlen - jogosultság - PÉNZ-PÉNZ-PÉNZ





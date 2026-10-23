# LEGAL-RQV Professional — bemutatás

**Forráshoz kötött keretrendszer jogi munka AI-val történő előkészítésére és ellenőrzésére**

Szerző: Almási Andor · Aktuális kiadás: v1.1.1 (2026. október) · Publikus bemutató

> Ez publikus bemutató. Elmagyarázza, mi a rendszer, miért jött létre, és milyen elvek szerint működik. Nem tartalmaz kódot, sémát, konfigurációt, teszteseteket, pontozási szabályokat vagy más olyan részletet, amelyből a rendszer újraépíthető lenne. A teljes csomag bizalmas, és csak titoktartási megállapodás mellett adható át.

## Mi ez?

A LEGAL-RQV Professional jogi kutatásra, jogértelmezésre és jogi dokumentumok AI-támogatású előkészítésére szolgáló strukturált keretrendszer, elsősorban a magyar és az uniós jogra.

Nem az a célja, hogy az AI „úgy hangozzon, mint egy jogász”. Éppen az ellenkezője: hogy minden érdemi jogi állítás **ellenőrizhető** legyen. Minden állítást hivatalos forráshoz és pontos rendelkezéshez kell kötni, és a munka csak akkor tekinthető késznek, ha emberi szakember is átnézte.

Többek között az alábbiakat támogatja:

- jogi kutatás és célzott jogi kérdések;
- új szerződések megírása és meglévők átvizsgálása;
- jogi levelek (felszólítás, válaszlevél, panasz);
- bírósági és hatósági beadványok;
- megfelelőségi vizsgálat;
- bizonyítékmátrix;
- jogi fordítás.

## Miért jött létre?

A nagy nyelvi modellek gördülékeny jogi szöveget írnak, és éppen ez a gördülékenység a veszély. A gyakorlatban ugyanazok a hibatípusok jönnek elő újra és újra:

- **nem létező** paragrafusra vagy bekezdésre hivatkozik;
- a jogot **rossz időállapotban** alkalmazza — régi vagy még nem hatályos változat szerint;
- a **joghatóságot** hallgatólagosan feltételezi, ahelyett hogy megállapítaná;
- a szerződés teljesnek tűnik, de **hiányzik egy szükséges kikötés**;
- egy **határidő** hibásan van kiszámolva, vagy a jogalapja nincs ellenőrizve.

Ezek egy jól megírt válaszban láthatatlanok maradhatnak, egy valós ügyben viszont sokba kerülhetnek. A LEGAL-RQV azért készült, hogy az ilyen hibákat szerkezetileg nehezebb legyen elkövetni, és könnyebb legyen észrevenni.

## Alapelvek

1. **Nincs jogi állítás forrás nélkül.** Minden érdemi jogi állítás hivatalos, hiteles forráshoz és pontos rendelkezéshez kapcsolódik. A források hitelességük szerint rangsorolva vannak: egy egységes szerkezetbe foglalt vagy másodlagos szöveg nem egyenértékű a hivatalos kihirdetéssel.
2. **A joghatóság soha nem csendes.** Az alkalmazandó jogrendszert kifejezetten és visszakövethetően meg kell állapítani. A rendszer nem vált csendben alapértelmezésre.
3. **Az idő külön kezelendő.** A válasz időpontja, a vizsgált jogállapot napja, a releváns események dátuma és az egyes források ellenőrzésének ideje külön tényként rögzül, nem keveredik.
4. **A határidők külön ellenőrzöttek.** A határidőket és jogalapjukat külön lépésben kell ellenőrizni.
5. **Dokumentumtípus szerinti teljesség.** Minden dokumentumtípusnak (például szerződés, levél, beadvány) megvannak a kötelező elemei, és a hiányzó elemeket a rendszer jelzi.
6. **Egyértelmű ítélet.** Kritikus hiba nem bújhat el egy magas minőségi pontszám mögött; a blokkoló problémák korlátozzák az összesített eredményt.
7. **Őszinte eredetjelölés.** Egy eredmény csak akkor számít lefuttatottnak, ha ténylegesen lefuttatták — nem elég, ha egy másik AI-motor elolvasta vagy leírta.
8. **Emberi felülvizsgálati kapu.** Szerződés, beadvány vagy jogi levél addig nem tekinthető véglegesnek, amíg a szükséges emberi szakmai felülvizsgálat meg nem történt.
9. **Motorfüggetlen.** A keretrendszer nem kötődik egyetlen AI-gyártóhoz sem; bármely megfelelő képességű projektkörnyezetben működésre tervezett.

## Hogyan készült?

A keretrendszer több AI-motor különböző szerepekben végzett munkájával — megírás, kritika és keresztvalidáció — készült, emberi irányítás alatt, gyakorló ügyvéd szakmai lektorálásával. Nemcsak tesztpéldákon, hanem a gyakorlatban, valós jogi anyagokon is használatban volt.

A kiadás verziózott, saját automatikus öntesztekkel és strukturált jogi tesztesetekkel; az aktuális kiadás reprodukált eredményei hiba nélkül lefutnak.

## Mi nem?

A LEGAL-RQV a jogi munka szakmai színvonalú **előkészítésének** fegyelme. Nem hoz létre ügyvédi megbízást, nem képvisel senkit, és nem helyettesíti a jogász szakmai felelősségét.

## Hozzáférés

A részletes szakmai leírás és a futtatható csomag bizalmas. Szakmai értékelés céljára titoktartási megállapodás mellett hozzáférhetővé tehető.

Kapcsolat: [github.com/hyperbetteri](https://github.com/hyperbetteri)

---

© 2026 Almási Andor. Minden jog fenntartva. Forrásmegjelöléssel szabadon idézhető.

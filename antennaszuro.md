
# Miskolci Szakképzési Centrum  
**Kandó Kálmán Informatikai Technikum**  
**Miskolc Palóczy u. 3.**

# MÉRÉSI JEGYZŐKÖNYV

**A mérést végző neve:** Vad Levente
**A mérés tárgya:** Programozható Antennaerősítő-szűrő használata 
**A mérés száma:** 2. mérés  
**A mérés dátuma:** 2024. 11. 13  
**A mérést vezette:** Sándor Péter  

**Évfolyam:** 13. E  
**Csoport:** GYAK 1
**Helyszín:** V3 Labor 

---

## 1. Mérés Célja

A **Johansson 6700 Profiler** antennaerősítő-szűrő megismerése és beállítása, különböző antennák jeleinek kezelése.
Ez az eszköz a rádiófrekvenciás jelek szűrésére és erősítésére szolgál, mely különösen hasznos, ha különböző frekvenciasávokat szeretnénk célzottan feldolgozni, illetve javítani az átvitel minőségét.
Feladata, hogy egy antenna segítségével először befogjuk az **Avasi adó toronyból** sugárzott adásokat. Majd a helyes sorrendben lévő csatornákat és helyen lévő frekvencián a **Johansson eszközzel** áthelyezzük a csatornákat úgy, hogy a régen kiépített rövid UTP kábeles rendszerben is zavartalanul lehessen TV-t nézni.

---

## 2. Helyszín

- **Koordináták:** 48°06’20”N 20°46’48”E  
- **Antenna Típus:** Opticum Smart HD 550  
- **Antenna magassága:** 1.5m  
- **Környezet:** V3 labor, Városi körülmények között  
- **Adó Távolsága:** 780m  

<details>   
  <summary> ADÓTORONY - VÉTELI HELY távolság </summary>
  
  <img src="https://erosbence27.github.io/jegyzokonyv/image/map.png" alt="TVtorony" />
  
</details>

<br>


---

## 3. Alkalmazott Mérőeszközök és Készülékek

| Műszer neve                         | Típus           | Gyártási szám         |
| ----------------------------------- | ---------       | -------------------   |
| Programozható antennaerősítő-szűrő  | Johansson 6700  |                       |
| Antenna                             | Opticum Smart HD 550   |         |
| Spektrum Analizátor                 | Deviser S7200      |                       |

---

## 4. Blokkvázlat

![image](image/Blokvazlat_1.PNG)

- **Iskra P-20 Antenna**: az RF jelek vételére
- **Johansson 6700 Profiler**: az RF jelek erősítésére és szűrésére
- **Metek HDD Spektrum Analizátor**: az erősített és szűrt jelek vizsgálatára

---

## 5. Mérési Adatok és Eredmények

### Mért adatok

Az alábbi táblázat a különböző frekvenciasávokhoz tartozó mért jelerősségeket mutatja a Johansson 6700 Profiler használata nélkül és használatával.

| Csatorna (CH) | Frekvencia (MHz) | Jelszint (dBu) | Következő Csatorna (CH) | Következő Frekvencia (MHz) | Következő Jelszint (dBuV) |
|---------------|------------------|----------------|--------------------------|----------------------------|----------------------------|
| 28            | 530              | 59             | 41                       | 626                        | 100.8                      |
| 31            | 554              | 63             | 42                       | 634                        | 100.9                      |
| 35            | 586              | 65             | 43                       | 642                        | 100.8                      |
| 41            | 634              | 48             | 44                       | 650                        | 100.8                      |
| 45            | 666              | 63             | 45                       | 658                        | 100.6                      |
| 48            | 690              | 60             | 46                       | 666                        | 100.4                      |

### Eredmények értelmezése

A mérések során a Johansson 6700 Profiler a kiválasztott frekvenciasávokban stabil 30 dB erősítést biztosított. Az eredmények alapján a készülék sikeresen növelte a bemeneti jelerősséget a megadott frekvenciasávokban, ami elősegíti a gyengébb jelek stabil vételét és további feldolgozását. A mérések megfelelőnek bizonyultak az elvárásoknak, és az erősítés stabilnak mutatkozott, az eltérések minimálisak.

---

## 6. Elemzés és Értékelés

Az eredmények elemzése alapján a Johansson 6700 Profiler megbízható teljesítményt nyújtott a mérések során. Az eszköz sikeresen növelte a jelerősséget a kiválasztott frekvenciasávokban, ami lehetővé teszi a gyenge RF jelek minőségi javítását. Az eszköz kalibrációs beállításai pontosnak bizonyultak, és az eltérések elhanyagolhatóak voltak. Jól teljesít a városi környezetben, de némi interferenciát tapasztaltunk az alacsonyabb frekvenciákon. Az eszköz megfelelően képes volt a csatornákat áthelyezni és stabil jelet biztosítani.

---

## 7. Hibák és Korlátozások

A mérés során az alábbi problémák észlelhetők:

- **Környezeti tényezők**: Az épületek közelsége, illetve a laborban lévő egyéb elektromos eszközök interferenciát okoztak, különösen az alacsonyabb frekvenciákon.
- **Antenna elhelyezése**: A viszonylag alacsony antennamagasság (1,5 méter) miatt a vétel nem volt optimális. Az antennát magasabb helyre kellene telepíteni, hogy javítsuk a jelerősséget és csökkentsük a zavarokat.
- **Interferencia**: A spektrumanalizátor néha külső zajokat érzékelt, amelyek lehettek más rádiófrekvenciás forrásokból (pl. WiFi, mobiltelefonok) származó zavarok.

---

## 8. Következtetések és Javaslatok

- A mérés sikeresen demonstrálta a Johansson 6700 Profiler képességeit. A kapott eredmények azt mutatják, hogy a készülék megbízhatóan teljesíti a kívánt erősítési feladatokat.
- Javasolt további méréseket végezni eltérő környezeti feltételek mellett, hogy megismerjük az esetleges befolyásoló tényezőket.
- Fontos lenne a méréseket nagyobb spektrális sávban is elvégezni, hogy felmérjük az eszköz széleskörű alkalmazhatóságát.
- A mérések eredményei összességében megfelelnek az elvárásoknak.
- A rendszer zavartalanul működött a rövid UTP kábeles rendszeren keresztül is.
- A mérés célja teljesült, de további finomítások szükségesek a vétel minőségének javítása érdekében.

---

## 9. További mérési javaslatok a jobb vétel és minőség érdekében 

- **Antenna elhelyezése**: Javasolt az antennát magasabb pozícióba telepíteni a jobb jelerősség érdekében, különösen az alacsonyabb frekvenciák esetében.
- **Környezeti hatások minimalizálása**: További mérések során érdemes lenne tesztelni, hogyan befolyásolják a különböző környezeti feltételek (pl. időjárás, építészeti akadályok) a vételt.
- **További tesztek**: Érdemes más antennatípusokat is tesztelni és összehasonlítani a jelenlegi Iskra P-20 antennával.

---

## 10. Felhasznált Források

1. **Johansson 6700 felhasználói kézikönyv** - A gyártó által biztosított dokumentáció az eszköz beállításairól.
2. **Iskra P-20 antenna műszaki leírás** - Az antenna specifikációi és teljesítménye különböző frekvenciákon.
3. **Műholdas és földi adóállomások jellemzői** - Általános útmutató a városi adótornyok és sugárzott frekvenciák jellemzőiről.

---

## 11. Magyarázatok és Lábtanulmányok

- **SNR (Signal-to-Noise Ratio)**: A jel és a zaj viszonya decibelben (dB). Minél magasabb az érték, annál tisztább a jel. Általában 30 dB feletti SNR szükséges a stabil vételhez.
- **QPSK**: Kvadratúra fáziseltolásos moduláció (Quadrature Phase Shift Keying), amely hatékony adatátviteli technika, gyakran használják digitális televízióadásoknál.
- **UTP kábel**: Árnyékolatlan sodrott érpárú kábel, amelyet gyakran használnak adatátvitelhez, például Ethernet hálózatokban.

---

## 12. Jelerősség diagramok

<img src="https://erosbence27.github.io/jegyzokonyv/image/1_freki_dbuv.JPG"/>
<img src="https://erosbence27.github.io/jegyzokonyv/image/2_freki_dbuv.JPG"/>

---

## 13. Záró Összegzés

A mérés során a **Johansson 6700 Profiler** programozható antennaerősítő-szűrő használatával sikerült a városi környezetben lévő antenna jeleinek kezelését és optimalizálását megvalósítani. A jelerősség és a vételi minőség alapján megállapítható, hogy az eszköz hatékonyan használható a rövid UTP kábelezésű rendszerekben is. Az antennarendszer telepítése megfelelően történt, azonban a jelerősség növelése érdekében javasolt további tesztek elvégzése.

A mérés legfontosabb tanulságai:
- Az antennák helyes pozicionálása kulcsfontosságú a vétel optimalizálása érdekében.
- A környezeti hatások jelentős szerepet játszanak a jelerősség és minőség tekintetében.
- A Johansson 6700 egyszerűen konfigurálható, és a mért eredmények alapján hatékonyan működik.

Az összesített mérések és következtetések alapján a **Johansson 6700 Profiler** megfelelő eszköz a városi antennarendszerek kezelésére, azonban javasolt további méréseket végezni a vétel optimalizálása érdekében.

---

## 14. Mért Képek

<details>
<summary>Kattins a részletekért</summary>

<br>

<img src="https://erosbence27.github.io/jegyzokonyv/image/01.bmp"/>

<br>

<img src="https://erosbence27.github.io/jegyzokonyv/image/02.bmp"/>

<br>

<img src="https://erosbence27.github.io/jegyzokonyv/image/03.bmp"/>

<br>

<img src="https://erosbence27.github.io/jegyzokonyv/image/04.bmp"/>

<br>

<img src="https://erosbence27.github.io/jegyzokonyv/image/05.bmp"/>

<br>

<img src="https://erosbence27.github.io/jegyzokonyv/image/06.bmp"/>

<br>

<img src="https://erosbence27.github.io/jegyzokonyv/image/07.bmp"/>

<br>

<img src="https://erosbence27.github.io/jegyzokonyv/image/08.bmp"/>

<br>

<img src="https://erosbence27.github.io/jegyzokonyv/image/09.bmp"/>

<br>

<img src="https://erosbence27.github.io/jegyzokonyv/image/10.bmp"/>

<br>

</details>

**Aláírás:** Erős Bence

**Dátum:** 2024. 10. 07.

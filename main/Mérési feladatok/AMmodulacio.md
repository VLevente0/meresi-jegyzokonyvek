# Amplitúdómoduláció vizsgálata

**Dátum:** 2025.02.04 <br>
**Helyszín:** degem labor <br>
**Készítette:** Vad Levente <br>

## Használt eszközök

**-GRF-1300A tréner** <br>
**-Rohde & Schwarz oszcilloszkóp** <br>
**-GWINSTEK GSP-730 spektrumanalizátor** <br>

## Mérés menete

-1.lépés: GRF-1300A tréneren AM jel előállítása<br>
-2.lépés: 100kHz frekvenciájú moduláló jel és 880MHz vivőfrekvencia beállítása<br>
-3.lépés: A spektrumanalizátor csatlakoztatása a moduláló jel kimenetére<br>
-4.lépés: Az oszcilloszkóp csatlakoztatása az AM jel kimenetére<br>
-5.lépés: Az oszcilloszkóp segítségével 100%-os moduláció (6dB) beállítása és sávszélesség meghatározása<br>
-6.lépés: Moduláló jel peak to peak feszültségét megmérni oszcilloszók segítségével<br>
-7.lépés: Moduláló jel frekvenciájának átállítása 500kHz-re és vivőfrekvencia átállítása 900MHz-re<br>
-8.lépés: 63%-os moduláció (10dB) beállítása és sávszélesség mmeghatározása<br>

## Mért adatok

| Vivőfrekvencia | Moduláló jel frekvencia | Sávszélesség | Moduláció | Vpp   |
| --------------- | ----------------------- | --------- | ------------ | ----- |
| 880 MHz         | 100 kHz                 | 5 MHz     | 100%         | 1.06 V |
| 900 MHz         | 500 kHz                 | 5 MHz     | 63%          | 1.16 V |


# Mérések

<details>
   <summary>880MHz-es AM moduláció</summary><br>
    <p>880MHz modulált AM jel</p>
   <img src="https://github.com/VLevente0/meresi-jegyzokonyvek/blob/45f50fda3070bb9bf50707c88ef51e37a3cb1f8c/main/kepek/am/880.jpg" height="500"><br>
   <p>100kHz moduláló jel</p>
    <img src="https://github.com/VLevente0/meresi-jegyzokonyvek/blob/577008c42fe98c62fe71d3e7096996e36957ae40/main/kepek/am/TA01.PNG" height="500">


</details>


<details>
   <summary>900MHz-es AM moduláció</summary><br>
    <p>900MHz modulált AM jel</p><br>
   <img src="https://github.com/VLevente0/meresi-jegyzokonyvek/blob/577008c42fe98c62fe71d3e7096996e36957ae40/main/kepek/am/900.jpg" height="500"><br>
    <p>500kHz moduláló jel</p>
    <img src="https://github.com/VLevente0/meresi-jegyzokonyvek/blob/577008c42fe98c62fe71d3e7096996e36957ae40/main/kepek/am/TA02.PNG" height="500">

</details>
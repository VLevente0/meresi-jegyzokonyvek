# Vezeték nélküli hálózat

**Dátum:** 2025.02.04 <br>
**Helyszín:** degem labor <br>
**Készítette:** Vad Levente <br>

## Hálózati Eszközök

- **SOHO router** – Linksys WRT54GL<br>
- **Switch** – cisco catalyst 2950 switch<br>
- **Laptop** – Levono thinkpad, teszteléshez és konfigurációhoz<br>
- **Telefon** – realme gt2 pro, teszteléshez<br>


## Hálózati Topológia
 
![Topológia](https://github.com/VLevente0/meresi-jegyzokonyvek/blob/bd62f13a4b8a0b66d23d1d3a7289ae72309e2e7a/main/kepek/vezeteknelkuli/topologia.png)

## Hálózat kiépítsének lépései

- 1.A topoógia kialakítása
- 2.A soho router megfelelő beállítása
- 3.Az eszközök csatlakoztatása a vezeték nélküli hálózathoz
- 4.Tesztelés

## Soho router bellításai
- 1.lépés beállítjuk a router internetportját DHCP-re 
- 2.lépés a wifi hálózat DHCP beállítása 
- 3.lépés SSID és jelszóbeállítása
- 4.lépés az SSID broadcast kikapcsolása és a router pingelés letiltása



<details>
   <summary>Router networksetup</summary>

   ![Router networksetup](https://raw.githubusercontent.com/VLevente0/meresi-jegyzokonyvek/1c88122d2de47944a63e907eedb924ed6738f154/main/kepek/vezeteknelkuli/router.PNG)

</details>


<details>
   <summary>SSID beállítása</summary>

   ![SSID beállítása](https://raw.githubusercontent.com/VLevente0/meresi-jegyzokonyvek/25c2b990d7c8334e1ad67d370a280fd4cea692e0/main/kepek/vezeteknelkuli/ssid.PNG)

</details>

<details>
   <summary>Jelszó beállítása</summary>

   ![Új IP kérés](./main/kepek/vezeteknelkuli/wifijelszo.PNG)

</details>


<details>
   <summary>Anonymous ping letiltása</summary>

   ![Új IP kérés](https://drive.google.com/file/d/1r50Naw9LRDiLEWVXPCt07lOgLyFNbiLE/view?pli=1)

</details>


## Tesztelés

<details>
  <summary>1. IP beállítások lekérése</summary>
  
  ![IP beállítások lekérése](https://raw.githubusercontent.com/VLevente0/meresi-jegyzokonyvek/1eb8b665f183455c319a1e76501595f331b03d3a/main/kepek/vezeteknelkuli/ipconfigall.PNG)

</details>

<details>
   <summary>2. IP eldobása</summary>

   ![IP eldobása](https://raw.githubusercontent.com/VLevente0/meresi-jegyzokonyvek/1eb8b665f183455c319a1e76501595f331b03d3a/main/kepek/vezeteknelkuli/iprelease.PNG)  

</details>


<details>
   <summary>3. Új IP kérése</summary>

   ![Új IP kérés](https://raw.githubusercontent.com/VLevente0/meresi-jegyzokonyvek/1eb8b665f183455c319a1e76501595f331b03d3a/main/kepek/vezeteknelkuli/iprenew.PNG)

</details>


<details>
   <summary>4. Routing tábla megjelenítése</summary>

   ![Routing tábla megjelenítése](https://raw.githubusercontent.com/VLevente0/meresi-jegyzokonyvek/1eb8b665f183455c319a1e76501595f331b03d3a/main/kepek/vezeteknelkuli/routing%20table.PNG) 
</details>

<details>
   <summary>5. Microsoft elérhetőség tesz</summary>

   ![Microsoft elérhetőség teszt](https://raw.githubusercontent.com/VLevente0/meresi-jegyzokonyvek/1eb8b665f183455c319a1e76501595f331b03d3a/main/kepek/vezeteknelkuli/microsoftping.PNG)
</details>

<details>
   <summary>6. ipon weboldalnak server felé vezető útvonal lekövetése</summary>

   ![Traceroute ipon.hu](https://raw.githubusercontent.com/VLevente0/meresi-jegyzokonyvek/1eb8b665f183455c319a1e76501595f331b03d3a/main/kepek/vezeteknelkuli/tracert_ipon.PNG)
</details>

<details>
   <summary>7. Portok listázása</summary>

   ![Portok listázása](https://raw.githubusercontent.com/VLevente0/meresi-jegyzokonyvek/1eb8b665f183455c319a1e76501595f331b03d3a/main/kepek/vezeteknelkuli/osszes%20port.PNG)
</details>

<details>
   <summary>8. Hálózati kapcsolatok</summary>

   ![Hálózati kapcsolatok](https://raw.githubusercontent.com/VLevente0/meresi-jegyzokonyvek/1eb8b665f183455c319a1e76501595f331b03d3a/main/kepek/vezeteknelkuli/netstat.PNG)
</details>

<details>
   <summary>9. DNS beállítások aktualizálása</summary>

   ![DNS beállítások](https://raw.githubusercontent.com/VLevente0/meresi-jegyzokonyvek/1eb8b665f183455c319a1e76501595f331b03d3a/main/kepek/vezeteknelkuli/dns.PNG)
</details>

<details>
   <summary>10. Hálózati meghajtók</summary>

   ![Hálózati meghajtók](https://raw.githubusercontent.com/VLevente0/meresi-jegyzokonyvek/1eb8b665f183455c319a1e76501595f331b03d3a/main/kepek/vezeteknelkuli/netuse.PNG)
</details>

<details>
   <summary>11. 'wwwipon.hu' server tartománynév és IP cím megjelenítése</summary>

   ![Ipon domain és IP](https://raw.githubusercontent.com/VLevente0/meresi-jegyzokonyvek/1eb8b665f183455c319a1e76501595f331b03d3a/main/kepek/vezeteknelkuli/nslookupipon.PNG)
</details>

<details>
   <summary>12. FQDN megjelenítése</summary>

   ![FQDN megjelenítés](https://raw.githubusercontent.com/VLevente0/meresi-jegyzokonyvek/1eb8b665f183455c319a1e76501595f331b03d3a/main/kepek/vezeteknelkuli/nslookup8888.PNG)

</details>

<details>
   <summary>13. Ping a kliensek között</summary>

   ![Ping teszt](https://raw.githubusercontent.com/VLevente0/meresi-jegyzokonyvek/1eb8b665f183455c319a1e76501595f331b03d3a/main/kepek/vezeteknelkuli/telefon%20ping.PNG)

</details>

<details>
   <summary>14. DHCP teszt mobil eszközön</summary>

   <img src="https://raw.githubusercontent.com/VLevente0/meresi-jegyzokonyvek/ccaf8a59f421591679ce9606b2f24e2fcc799982/main/kepek/vezeteknelkuli/telefon.jpg" alt="DHCP teszt" height="500" />
</details>



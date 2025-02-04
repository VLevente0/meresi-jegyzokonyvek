# Vezeték nélküli hálózat

**Dátum:** 2025.02.04 <br>
**Helyszín:** degem labor <br>
**Készítette:** Vad Levente <br>

## Hálózati Eszközök

- **SOHO router** – Linksys WRT54GL<br>
- **Switch** – cisco catalyst 2950 switch<br>
- **Laptop** – Levono thinkpad, teszteléshez<br>
- **Telefon** – realme gt2 pro, teszteléshez<br>


## Hálózati Topológia
 
![Topológia](https://github.com/VLevente0/meresi-jegyzokonyvek/blob/bd62f13a4b8a0b66d23d1d3a7289ae72309e2e7a/main/kepek/vezeteknelkuli/topologia.png)

## Hálózat kiépítsének lépései

- 1.A topoógia kialakítása
- 2.A soho router megfelelő beállítása
- 3.Az eszközök csatlakoztatása a vezeték nélküli hálózathoz
- 4.Tesztelés


## Tesztelés

1.IP beállítások lekérése<br>
![IP beállítások lekérése](https://github.com/VLevente0/meresi-jegyzokonyvek/blob/1eb8b665f183455c319a1e76501595f331b03d3a/main/kepek/vezeteknelkuli/ipconfigall.PNG)  

2.IP eldobása<br>
   ![IP eldobása](https://github.com/VLevente0/meresi-jegyzokonyvek/blob/1eb8b665f183455c319a1e76501595f331b03d3a/main/kepek/vezeteknelkuli/iprelease.PNG)  

3.Új IP kérés <br>
   ![Új IP kérés](https://github.com/VLevente0/meresi-jegyzokonyvek/blob/1eb8b665f183455c319a1e76501595f331b03d3a/main/kepek/vezeteknelkuli/iprenew.PNG)  

4.Routing tábla megjelenítése  <br>
   ![Routing tábla megjelenítése](https://github.com/VLevente0/meresi-jegyzokonyvek/blob/1eb8b665f183455c319a1e76501595f331b03d3a/main/kepek/vezeteknelkuli/routing%20table.PNG) 

5.Microsoft elérhetőség teszt <br>
   ![Microsoft elérhetőség teszt](https://github.com/VLevente0/meresi-jegyzokonyvek/blob/1eb8b665f183455c319a1e76501595f331b03d3a/main/kepek/vezeteknelkuli/microsoftping.PNG)  

6.www.ipon.hu server felé vezető útvonal lekövetése <br>
   ![Traceroute ipon.hu](https://github.com/VLevente0/meresi-jegyzokonyvek/blob/1eb8b665f183455c319a1e76501595f331b03d3a/main/kepek/vezeteknelkuli/tracert_ipon.PNG)  

7.Portok listázása  <br>
   ![Portok listázása](https://github.com/VLevente0/meresi-jegyzokonyvek/blob/1eb8b665f183455c319a1e76501595f331b03d3a/main/kepek/vezeteknelkuli/osszes%20port.PNG)  

8.Hálózati kapcsolatok <br>
   ![Hálózati kapcsolatok](https://github.com/VLevente0/meresi-jegyzokonyvek/blob/1eb8b665f183455c319a1e76501595f331b03d3a/main/kepek/vezeteknelkuli/netstat.PNG)  

9.DNS beállítások aktualizálása <br>
   ![DNS beállítások](https://github.com/VLevente0/meresi-jegyzokonyvek/blob/1eb8b665f183455c319a1e76501595f331b03d3a/main/kepek/vezeteknelkuli/dns.PNG)  

10.Hálózati meghajtók <br>
    ![Hálózati meghajtók](https://github.com/VLevente0/meresi-jegyzokonyvek/blob/1eb8b665f183455c319a1e76501595f331b03d3a/main/kepek/vezeteknelkuli/netuse.PNG)  

11.'wwwipon.hu' server tartománynév és IP cím megjelenítése<br>
    ![Ipon domain és IP](https://github.com/VLevente0/meresi-jegyzokonyvek/blob/1eb8b665f183455c319a1e76501595f331b03d3a/main/kepek/vezeteknelkuli/nslookupipon.PNG)  

12.FQDN megjelenítése<br>
    ![FQDN megjelenítés](https://github.com/VLevente0/meresi-jegyzokonyvek/blob/1eb8b665f183455c319a1e76501595f331b03d3a/main/kepek/vezeteknelkuli/nslookup8888.PNG)  

13.Ping a kliensek között <br>
    ![Ping teszt](https://github.com/VLevente0/meresi-jegyzokonyvek/blob/1eb8b665f183455c319a1e76501595f331b03d3a/main/kepek/vezeteknelkuli/telefon%20ping.PNG)  

14.DHCP teszt mobil eszközön<br>
      ![DHCp teszt](https://github.com/VLevente0/meresi-jegyzokonyvek/blob/ccaf8a59f421591679ce9606b2f24e2fcc799982/main/kepek/vezeteknelkuli/telefon.jpg)  
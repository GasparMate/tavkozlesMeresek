

## DVB-T jel fejállomásba küldése és IPTV rendszeren való kiadása
## Vizsga: Távközlési technikus - B tétel
## Dátum: 2025.02.03

 ----

### Feladat leírása: A vizsgázó feladata egy földfelszíni digitális TV vételi rendszer kiépítése és konfigurálása, amely magában foglalja a DVB-T jel mérését, fejállomásba történő bevezetését és az IPTV streamek konfigurálását.

### 1. Előkészületek 
Eszközök ellenőrzése:
Antenna (beltéri/kültéri)
Fejállomás: LEMCO SCL-824CT
Set-top box: MAG IPTV
Hálózati eszközök: HP switch/router
METEK HDD mérőműszer
Koaxiális kábelek és csatlakozók
Mérőeszközök: iránytű, dőlésszögmérő
Multiplex keresése a Miskolc, Avasi adótoronyból:
Frekvencia: 530 MHz
Teljesítmény: 50 kW
Polarizáció: Vertikális
Adás típusa: FTA DVB-T
### 2. Antenna felszerelése és beállítása 
![szerelés4](https://github.com/user-attachments/assets/0cb46eff-7342-4e8b-87a1-313ce326bd1a)

### Antenna kiválasztása:
A kültéri antenna mellett döntöttünk, mivel az optimális vételt biztosítja a nagy távolság miatt.
Antennát rögzítése:
A kültéri antenna tripodra lett rögzítve, és az iránytű segítségével pontosan beállítva az Avasi adótorony irányába. A dőlésszögmérővel biztosítottuk a megfelelő emelkedési szöget.
### Mérés METEK HDD mérőműszerrel:
A jelerősség stabil -58 dBm volt, amely megfelelő a DVB-T vételhez.
  

### 3. Kábelezés, mérési pontok kialakítása és jel bevezetése a fejállomásba 
### Kábelezés és jelszétválasztás:
Az antenna jele koaxiális kábellel lett összekötve a fejállomás bemeneteivel. A jelosztó segítségével a különböző multiplexeket megfelelően osztottuk el a bemeneti portokon.
### Mérés a fejállomás előtt:
A fejállomás jelszintje -6 dBm volt, megfelelően erős a továbbításhoz.
   

### 4. Fejállomás beállítása és IPTV stream konfigurálása 
### Fejállomás konfigurálása:
Minden bemenetre a megfelelő multiplexet rendeltük hozzá.
A DVB-T jelet IP streamként konvertáltuk. Multicast IP tartomány: 239.1.1.0/24.
IPTV Set-top box beállítása (MAG IPTV):
A set-top box IP konfigurálása és csatornalista frissítése megtörtént.
A csatornák sikeresen lettek beolvasva, és a képminőség megfelelő volt.
### 5. Jelszintmérés és dokumentáció 
![sf-10_d](https://github.com/user-attachments/assets/186ad45d-9f58-4610-b555-98f53ee8c8f4)

### Antenna mérése:
Spektrum analizátor kép:
Jelszint: -58 dBm
Jel/zaj viszony: 30 dB
Bit Error Rate (BER): 0.0005
(Kép: Spektrum analizátor mérés)

### Fejállomás mérése:
IPTV stream stabilitása: A multicast IP címek működtek, és a stream folyamatos volt.
Hálózati késleltetés: 12 ms.
### 6. Hibakeresés és analízis
 ![ssss](https://github.com/user-attachments/assets/950eeb5b-5bcb-4b4c-ba0d-dbdde3f2c529)

### Wireshark használata:
A multicast forgalom figyelése során nem tapasztaltunk csomagvesztést.
Ping teszt: 239.1.1.1 címen stabil kapcsolat.
### FFmpeg használata:
A stream mentése és elemzése során nem találtunk problémát, a bitráta stabilan 8 Mbps volt.
### Mérési Eredmények:
Jelerősség (dBμV): -58 dBm
Jel/zaj viszony (SNR): 30 dB
Bit Error Rate (BER): 0.0005
Modulation Error Ratio (MER): 34 dB
Lock állapot: Igen
### Zárás:
Az IPTV rendszer sikeresen konfigurálásra került, és a DVB-T jelet megfelelően továbbítottuk az IPTV hálózaton. A mérések és a dokumentáció a kívánt normáknak megfelelnek.

## Aláírás: Gáspár Máté
## Vizsga Időpontja: 2025.02.03


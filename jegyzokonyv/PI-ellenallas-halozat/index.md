## &#928; Csillapító Áramkör Jegyzőkönyv.

**Mérés helye**: Miskolci SZC Kandó Kálmán Informatikai Technikum  
**Mérés időpontja**: 2024.12.04
**Mérő műszerek**:National Instruments Ni MYDOQ 305E1ED 
**Felelős személy**: Sándor Péter  
**Cél**: A PI csillapító áramkör elemzése.

---

### 1. **Bevezetés**

A feladat lényeg az hogy megállapítsuk 6 db csillapításon működik ez az áramkörünk és ha működik akkor hogyan és milyen számítások jönnek ki

## Elmélet:



![R1 képlete](https://raw.githubusercontent.com/szabot2/pi-csillapito/cffee4ced185268076fb4bf54fdfafc23a0b0f74/kepek/svgviewer-output.svg)

![R2 képlete](https://raw.githubusercontent.com/szabot2/pi-csillapito/cffee4ced185268076fb4bf54fdfafc23a0b0f74/kepek/svgviewer-output(1).svg)


6 dB-es csillapításra kiszámolt ellenállás értékek:


![3](https://github.com/user-attachments/assets/e95208af-e88d-4679-96ce-14386a855e08)


<br>

A kapcsolási rajz ábrázolja a jelgenerátort a belső ellenállásával, valamint a Pi csillapítót a kiszámolt ellenállás értékekkel:

<a target="blank" href="https://www.falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWc0wCZIA4AsBmBDUsM4A2AThxAUiqpoQFMBaMMAKADcQySQcSM3XqgDsqKOHDxaNWdARsATkJCjx6QWokk4bAO4r+mzHwFR9qk1tQJhY8wZt3xOSFlX3ISvm48vfRhLousqu7lpYYM4S1CIWYaaCkbyBXsrJfiAZqZa6BhkRJOGeFtlmWEWJ5uk8mVi1OTpe+Q1mtjSppbVa7ZleAA5UOpm9gZTuzVnd9hXF4pP1KeWVnY4mYwFmA5aa9hpV4+YA9uAQ8+A2FciEaGQIkQgYdyIkYGRQsHAQNOKsfGxAA" >

![gép](https://github.com/user-attachments/assets/cc92dcc6-607c-4e01-a671-23c2e336c2b5)


Az oszcillátoron látható mérés:
</a>
</a>
![mérés](https://github.com/user-attachments/assets/bea507d3-fefd-4526-be8d-86c8b273a09e)

</a>


### 3. **Mérési paraméterek**

| Paraméter           | Érték |
|---------------------|-------|
| Generátor jel       | 5.00 Vp2p|
| Kimeneti Jel        | 1.257 Vp2p |
| Generátor Frekvencia| 100000 Hz |
| Csillapítás         | 11,99dB |
| Átviteli Arány      | -11.98 dB |
| Bemeneti impedancia | 347 Ω |
| Kimeneti impedancia | 344 Ω |   

<br>

### 4. **Mérési eredmények**

- **Kimeneti Jel**: A kimeneti jel mindössze 25.14%-a a generátor jelének.
  
- **Csillapítás/Átviteli arány**:  11,99 dB csillapítást tapasztalunk az áramkör jóvoltából.

- **Kimeneti/Bemeneti impedancia**: A bemeneti impedanciánk 347 Ohm. A kimeneti impedanciánk 344 Ohm.  

### 5. **Elemzés**
A áramkör csillapít de nagyobbat mint 50% mert az ellenállsok nagyobbak lettek így nagyobb a csillapítás is.
### 6. **Következtetések**
A pi csillapító áramkör sikeresen megvalósult, és a tesztelési eredmények azt mutatják, hogy a csillapítási teljesítmény megfelel a tervezett specifikációknak. A mérések alapján a csillapító hatás a kívánt frekvenciatartományban optimális, és a jelminőség megőrzése is megfelelő. A projekt során szerzett tapasztalatok alapján a tervezési folyamat során figyelembe kell venni a komponensek toleranciáját és a környezeti hatásokat, mivel ezek befolyásolhatják az áramkör teljesítményét.

### 7. **Felhasznált Eszközök és ellenállások**


| R1 ellenállás      | 2.2kΩ|
| R2 ellenállás      | 540kΩ|
| R3 ellenállás      | 680kΩ|
| National Instruments Ni MYDOQ 305E1ED| 
| LINI-T UT61D     | 




---

**Aláírás**:  
Felelős mérő személy: Gáspár Máté
Dátum: 2024.12.04


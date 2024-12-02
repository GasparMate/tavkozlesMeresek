## &#928; Csillapító Áramkör Jegyzőkönyv.

**Mérés helye**: Miskolci SZC Kandó Kálmán Informatikai Technikum  
**Mérés időpontja**: 23024.11.27
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

![2](https://github.com/user-attachments/assets/e1d418b2-5630-434a-8d9c-8a8a2743b7d2)


</a>


### 3. **Mérési paraméterek**

| Paraméter           | Érték |
|---------------------|-------|
| Generátor jel       | 5.00 Vp2p|
| Kimeneti Jel        | 2.06 Vp2p |
| Generátor Frekvencia| 1000 Hz |
| Csillapítás         | -7.702 dB |
| Átviteli Arány      | 7.702 dB |
| Bemeneti impedancia | ? Ω |
| Kimeneti impedancia | ? Ω |   

<br>

Látható az oszcilloszkópon a sárga 1-es csatornán a csillapított kimeneti jel, és a kék 2-es csatornán a generátor jel.

<img src="https://raw.githubusercontent.com/szabot2/pi-csillapito/refs/heads/main/kepek/TA02.PNG" width="600" height="480">


### 4. **Mérési eredmények**

- **Kimeneti Jel**: A kimeneti jel mindössze 41.2%-a a generátor jelének.
  
- **Csillapítás/Átviteli arány**:  7.702 dB csillapítást tapasztalunk az áramkör jóvoltából.

- **Kimeneti/Bemeneti impedancia**: ??????.  

### 5. **Elemzés**
A pi csillapító (pi pad) ellenállás áramkörének elemzése során megfigyelhető, hogy a tervezett áramkör hatékonyan csökkenti a jel amplitúdóját, miközben megőrzi a jel formáját. Az áramkör négy fő komponensből áll: három ellenállásból és egy terhelő ellenállásból. Kisebb eltérés tapasztalható a kiszámolt értékek és a valós értékek között.

### 6. **Következtetések**
A pi csillapító áramkör sikeresen megvalósult, és a tesztelési eredmények azt mutatják, hogy a csillapítási teljesítmény megfelel a tervezett specifikációknak. A mérések alapján a csillapító hatás a kívánt frekvenciatartományban optimális, és a jelminőség megőrzése is megfelelő. A projekt során szerzett tapasztalatok alapján a tervezési folyamat során figyelembe kell venni a komponensek toleranciáját és a környezeti hatásokat, mivel ezek befolyásolhatják az áramkör teljesítményét.

### 7. **Javaslatok**

Az ellenálásoka pontosan vagy nagyon hasonlók legyenek a leírtakhoz, nem lesz jó az eredmény ha nem pont

---

**Aláírás**:  
Felelős mérő személy: ..............................  
Dátum: .............................................


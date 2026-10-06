# 16-Mavzu: Microsoft Excel Diagrammalari va Ma'lumotlarni Vizuallashtirish

{% hint style="info" %}
**Dars maqsadi:** Excel jadvallaridagi sonli ma'lumotlarni professional grafik diagrammalar (Ustunli — Column, Chiziqli — Line, Doiraviy — Pie) ko'rinishida vizuallashtirish, diagramma anatomiyasini (Title, Legend, Data Labels, Axis) sozlash va biznes tahlillari uchun taqdimotbop hisobotlar tayyorlash.
{% endhint %}

### 🎯 Kutilayotgan Kompetensiyalar
* **Bilishingiz kerak:**
  * Har bir tahliliy vazifa uchun mos diagramma turini tanlash qoidasi (Column — taqqoslash, Line — dinamika/trend, Pie — ulush/foiz).
  * Doiraviy (Pie) diagrammada nima sababdan 7 tadan ortiq toifani ko'rsatish tavsiya etilmasligi.
  * Diagramma elementlari: Chart Title, Legend (afsona), Data Labels va o'qlar (Axes).
* **Bajara olishingiz kerak:**
  * Jadvaldagi kerakli ma'lumotlar sohasini belgilab, 1 soniyada tezkor diagramma hosil qilish (`Alt + F1` / `F11`).
  * Diagramma elementlarini formatlash, foiz ko'rsatkichlarini (Data Labels) qo'shish.
  * Jadvalga yangi ma'lumot kiritilganda diagrammaning avtomatik yangilanishini ta'minlash.

## 🎬 1. Video Dars

{% hint style="info" %}
**Video darslik:** Excelda professional diagrammalar yaratish va dizaynini sozlash bo'yicha quyidagi videoni tomosha qiling:
{% endhint %}

[Iframe/Embed: 16-Mavzu Bo'yicha YouTube Video Dars Havolasi]

## 2. 📖 Chuqurlashtirilgan Nazariy Ma'ruza

### 2.1. Qaysi Ma'lumot Uchun Qaysi Diagramma?

Diagramma — bu shunchaki bezak emas, u katta raqamlar ortidagi qonuniyatlarni ko'rsatuvchi tahlil qurolidir:

| Diagramma Turi | Standart Nomi | Qachon ishlatiladi? | Misol |
| :--- | :--- | :--- | :--- |
| **Ustunli (Column / Bar)** | Ustunli grafik | Alohida obyektlar va ko'rsatkichlarni bir-biri bilan to'g'ridan-to'g'ri taqqoslashda | 5 ta filialning oylik savdo tushumlari |
| **Chiziqli (Line Chart)** | Chiziqli grafik | Ma'lumotlarning vaqt bo'yicha o'zgarish tendensiyasi (dinamika, trend)ni ko'rsatishda | Valyuta kursi yoki havo haroratining 12 oylik grafigi |
| **Doiraviy (Pie Chart)** | Sektorli doira | Umumiy 100% yaxlitlik ichidagi qismlarning foiz ulushini ko'rsatishda | Korxona byudjetining bo'limlar bo'yicha foiz taqsimoti |

```
[Diagramma Turlari Qo'llanilishi]
  ├── Taqqoslash (Kim ko'p sotdi?) =======> Column / Bar Chart
  ├── Vaqt dinamikasi (O'sish/Pasayish) => Line Chart
  └── Foiz ulushi (100% dan qancha?) =====> Pie Chart
```

{% hint style="success" %}
**Pro-Tip (Bir zumda diagramma yaratish):**
Jadval ichidagi istalgan katak ustiga kursor qo'ying va klaviaturadagi **`Alt + F1`** tugmalarini birga bosing! Excel jadvalingiz asosida eng mos keluvchi ustunli diagrammani o'sha varaqning o'zida bir zumda chizib beradi. Agar **`F11`** bossangiz, yangi alohida "Chart" varag'ida to'liq ekranli diagramma ochiladi!
{% endhint %}

### 2.2. Diagrammaning Asosiy Qismlari (Anatomiya)

1. **Chart Title (Diagramma sarlavhasi):** Grafik nima haqida ekanligini ifodalaydi (masalan: "2026-Yil 1-Chorak Savdo Natijalari").
2. **Data Series (Ma'lumotlar seriyasi):** Chizilgan ustunlar, chiziqlar yoki sektorlar.
3. **Legend (Afsona / Ranglar izohi):** Qaysi rang qaysi toifaga tegishli ekanligini tushuntiruvchi yo'riqnoma.
4. **Data Labels (Ma'lumot yorliqlari):** Ustun yoki sektor ustida aniq raqam yoki foizni ko'rsatib turuvchi yozuvlar.
5. **Axes (O'qlar):** Gorizontal o'q (X — kategoriyalar: oylar, ismlar) va Vertikal o'q (Y — sonlar, qiymatlar).

## 3. 💻 Bosqichma-bosqich Amaliy Mashg'ulot (Lab Task)

Ushbu amaliy mashg'ulotda siz kompaniyaning 4 choraklik moliyaviy daromadlari asosida Ustunli va Doiraviy diagrammalar qurasiz.

### Kerakli Resurslar:
* Microsoft Excel dasturi;
* Amaliy mashg'ulot shabloni.

### 📄 Amaliy Mashg'ulot Shabloni:
{% hint style="success" %}
**📄 Rasmiy Amaliy Mashg'ulot va Uy Vazifasi Shabloni (Google Sheets (Jadval)):**
Ushbu darsning barcha bosqichlarini bajarish, natijalar/hisobotlarni kiritish va uy vazifasini topshirish uchun quyidagi rasmiy shablondan foydalaning:
* 🌐 **Onlayn ko'rish va tahrirlash:** <a href="https://docs.google.com/spreadsheets/d/1oAOR96dWiKQkPvVVo3Chzqz7CAd_XLVcAkY6wSjVYyA/edit?usp=sharing" target="_blank" rel="noopener noreferrer">16-Mavzu: Microsoft Excel Diagrammalari — Shablonni ochish</a>
* 📥 **Shaxsiy Drive-ga nusxalash (Tavsiya etiladi):** <a href="https://docs.google.com/spreadsheets/d/1oAOR96dWiKQkPvVVo3Chzqz7CAd_XLVcAkY6wSjVYyA/copy" target="_blank" rel="noopener noreferrer">Nusxa yaratish (Make a copy)</a>
{% endhint %}

{% embed url="https://docs.google.com/spreadsheets/d/1oAOR96dWiKQkPvVVo3Chzqz7CAd_XLVcAkY6wSjVYyA/preview" %}

> *Eslatma: Shablondan nusxa oling va quyidagi 6 ta qadamni bajarib, hosil bo'lgan diagrammalarni unga joylang.*

### Bajarish Bosqichlari:

1. **1-Qadam:** Excel dasturida quyidagi 2 ustunli jadvalni kiriting:
   * `A1:B1`: Chorak | Savdo hajmi (mln so'm)
   * `A2:B2`: 1-Chorak | 450
   * `A3:B3`: 2-Chorak | 620
   * `A4:B4`: 3-Chorak | 580
   * `A5:B5`: 4-Chorak | 890
2. **2-Qadam (Ustunli diagramma yaratish):** `A1:B5` kataklarini to'liq belgilang. **Insert -> Charts -> Clustered Column (Oddiy ustunli)** tugmasini bosing.
3. **3-Qadam (Dizayn tanlash):** Diagramma ustiga bosing, yuqorida ochilgan **Chart Design** menyusidan o'zingizga yoqqan zamonaviy to'q rangli uslubni (Style) tanlang.
4. **4-Qadam (Doiraviy diagramma - Pie Chart):** Yana o'sha jadvalni belgilang, **Insert -> Charts -> 2-D Pie (Doiraviy)** ni tanlang.
5. **5-Qadam (Foizlarni ko'rsatish):** Doiraviy diagrammaning yuqori o'ng burchagidagi yashil `+` (Chart Elements) belgisini bosing, **Data Labels** qatoriga galochka qo'ying va uning yonidagi strelkadan **Outside End** yoki **Data Callout** ni tanlang (har bir bo'lak foizi ko'rinadi).
6. **6-Qadam:** Jadvaldagi 4-chorak sonini 890 dan `1200` ga o'zgartiring va ikkala diagramma ham avtomatik qayta chizilganini kuzatib, faylni `Moliyaviy_Diagrammalar.xlsx` qilib saqlang.

{% hint style="warning" %}
**Ehtiyot bo'ling:**
Diagramma uchun jadvalni belgilayotganda jami ("Total / Jami") qatorini HECH QACHON belgilangan sohaga qo'shib yubormang! Aks holda "Jami" ustuni qolgan barcha ustunlardan 2 barobar baland bo'lib, butun diagramma mutanosibligini buzib tashlaydi.
{% endhint %}

## 4. 🛠 Real Ish Vaziyati va Muammolarni Hal Qilish (Case-Study)

### Muammo:
Savdo bo'limi xodimi do'kondagi 35 xil mahsulotning sotilish ulushini tushuntirish uchun **Doiraviy (Pie Chart)** diagramma tanladi. Natijada doira 35 ta ingichka-ingichka rangli bo'lakchalarga bo'linib ketdi, harflar bir-birining ustiga minib qoldi va diagrammadan hech narsani tushunib bo'lmaydigan holatga keldi.

### Muammoning Kelib Chiqish Sababi:
Doiraviy diagramma inson ko'zi idrok qilishi uchun maksimal **5–7 ta bo'lakka** mo'ljallangan. 35 ta mahsulot uchun Pie Chart mutlaqo noto'g'ri tanlovdir.

### Bosqichma-bosqich Yechim:
1. Diagramma ustiga bosing va yuqori menyudan **Change Chart Type (Изменить тип диаграммы)** tugmasini bosing.
2. Diagramma turini Pie Chart dan **Bar Chart (Gorizontal chiziqli ustunlar)** yoki **Clustered Column** turiga almashtiring.
3. Jadvaldagi mahsulotlarni eng ko'p sotilganidan boshlab saralang (**Data -> Sort -> Descending**).
4. Natijada har bir mahsulot nomi chap tomonda chiroyli qator bo'lib, uning savdo hajmi esa gorizontal ustun sifatida aniq, o'qilishi juda oson va professional ko'rinishga keladi!

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz)

{% hint style="info" %}
**📝 Rasmiy Onlayn Test Sinovi (Google Forms — 15 ta saralangan savol, 100 ballik baholash):**
Ushbu dars bo'yicha olgan bilimlaringizni sinash uchun quyidagi rasmiy testni topshiring (15 ta saralangan test savoli, jami: 100 ball):
* 🔗 **Onlayn Testni Ochish (To'liq Ekranda):** <a href="https://docs.google.com/forms/d/e/1FAIpQLSfoX9Wf9a6QbtMWOjsPX5-I0VXMvSro9W7p6s09-29NLGrH1w/viewform" target="_blank" rel="noopener noreferrer">16-Mavzu: Microsoft Excel Diagrammalari — Testni Topshirish</a>
* 📊 **Kunlik Natijalar va Ballar Jadvali:** <a href="https://docs.google.com/spreadsheets/d/1uIwnctQ_Jp0U0aXD88nW2WmPch4O-hAI6_rcF7-282Y/edit" target="_blank" rel="noopener noreferrer">Google Sheets — Natijalar Jadvali</a>
{% endhint %}

{% embed url="https://docs.google.com/forms/d/e/1FAIpQLSfoX9Wf9a6QbtMWOjsPX5-I0VXMvSro9W7p6s09-29NLGrH1w/viewform" %}

## 6. 🏠 Mustaqil Amaliy Uyga Vazifa

### Topshiriq:
1. Microsoft Excel dasturida haftaning 7 kuni bo'yicha sarflangan internet trafigi (MB hisobida) jadvalini tuzing.
2. Ushbu jadval uchun chiroyli Chiziqli (Line) diagramma va Ustunli (Column) diagramma yarating.
3. Diagrammalarga sarlavha (Chart Title) bering va Data Labels (aniq MB qiymatlari)ni yoqing.
4. Natijani tahlil qilib, qaysi kuni eng ko'p internet ishlatilganini aniqlang.

**Topshirish formati:** Faylni `FIO_16-Mavzu_Diagrammalar.xlsx` nomi bilan platformaga yuklang.

# 06-Mavzu: Printer Bilan Ishlash va Sozlash

{% hint style="info" %}
**Dars maqsadi:** Zamonaviy printer turlari (Lazerli, Siyohli — Inkjet) ishlash prinsiplari, drayverlarni o'rnatish va sozlash, hujjatlarni professional chop etish (`Ctrl + P`), Print Queue (chop etish navbati)ni boshqarish hamda printer qotib qolishi bilan bog'liq texnik muammolarni mustaqil hal qilish.
{% endhint %}

### 🎯 Kutilayotgan Kompetensiyalar
* **Bilishingiz kerak:**
  * Lazerli (Laser) va Siyohli (Inkjet) printerlarning farqlari, sarf materiallari (Toner vs Kartrij).
  * Printer drayverining vazifasi va "Default printer" (Asosiy printer) mexanizmi.
  * Windows Print Spooler xizmatining chop etish navbatidagi roli.
* **Bajara olishingiz kerak:**
  * Printerni USB yoki lokal tarmoq (Wi-Fi/LAN) orqali kompyuterga ulash va tizimga tanitish.
  * Chop etish parametrlarini moslash: A4 formati, yo'nalish (Portrait/Landscape), ikki tomonlama chop etish (Duplex) va sahifalar diapazonini belgilash.
  * Chop etish navbatida qotib qolgan fayllarni bekor qilish (Cancel) va Spooler xizmatini qayta ishga tushirish.

---

## 🎬 1. Video Dars

{% hint style="info" %}
**Video darslik:** Printerlarni ulash, drayver o'rnatish va chop etish bo'yicha quyidagi videoni tomosha qiling:
{% endhint %}

[Iframe/Embed: 06-Mavzu Bo'yicha YouTube Video Dars Havolasi]

---

## 2. 📖 Chuqurlashtirilgan Nazariy Ma'ruza

### 2.1. Lazerli vs Siyohli (Inkjet) Printerlar

Ofis va xonadonlarda eng keng tarqalgan ikki xil printer texnologiyasi:

| Ko'rsatkich | Lazerli Printer (LaserJet) | Siyohli Printer (Inkjet) |
| :--- | :--- | :--- |
| **Bo'yoq turi** | Quruq kukunsimon modda — **Toner** | Suyuq siyoh — **Ink (CISS/SНПЧ)** |
| **Chop etish tezligi** | Juda yuqori (daqiqa 20–40 varaq) | O'rtacha (daqiqa 5–15 varaq) |
| **Asosiy yo'nalishi** | Matnli hujjatlar, shartnomalar, kitoblar | Rangli fotosuratlar, grafikalar, taqdimotlar |
| **Bo'yoqning qurishi** | Uzoq vaqt ishlatilmasa ham qurib qolmaydi | Uzoq vaqt ishlatilmasa boshchasi (head) qurib qoladi |
| **Bir varaq tannarxi** | Juda arzon | O'rtacha yoki qimmat |

```
[Chop Etish Jarayoni Mantiqi]
  Dastur (MS Word / PDF) ---> Ctrl + P buyrug'i
                                   |
                             Printer Drayveri (Ma'lumotni qurilma tiliga o'giradi)
                                   |
                             Windows Print Spooler (Chop etish navbati)
                                   |
                             Printer Xotirasi (RAM) ---> Qog'ozga tushirish
```

{% hint style="success" %}
**Pro-Tip (Default Printer belgilash):**
Agar kompyuteringizga bir nechta printer (masalan, ofisdagi jismoniy printer va PDF saqlovchi virtual printer) ulangan bo'lsa, eng ko'p ishlatiladiganini asosiy qilib belgilang:
`Win + I` -> **Bluetooth & devices -> Printers & scanners** -> Kerakli printerni tanlang -> **Set as default** tugmasini bosing. Endi `Ctrl + P` bosilganda har doim shu printer avtomatik tanlanadi!
{% endhint %}

### 2.2. Chop Etish Parametrlari (`Ctrl + P`)

Microsoft Word yoki boshqa dasturlarda `Ctrl + P` bosilganda quyidagi muhim parametrlar sozlanadi:

1. **Pages (Sahifalar):** Barcha sahifalarni emas, aniq kerakli sahifalarni kiritish mumkin:
   * `1-5` — 1-dan 5-gacha bo'lgan sahifalar;
   * `1, 3, 7` — faqat 1, 3 va 7-sahifalar;
   * `1-4, 8, 11-15` — aralash intervallar.
2. **Orientation (Sahifa yo'nalishi):**
   * *Portrait (Kitobiy)* — vertikal yo'nalish (standart arizalar va shartnomalar uchun).
   * *Landscape (Albomiy)* — gorizontal yo'nalish (keng jadvallar va chizmalar uchun).
3. **Collate (Tartiblash):** Agar 10 varaqli hujjatdan 3 nusxa chiqarayotgan bo'lsangiz:
   * *Collated (1,2,3... 1,2,3...)* — har bir nusxani alohida to'plam qilib chiqaradi.
   * *Uncollated (1,1,1... 2,2,2...)* — avval 1-sahifadan 3 ta, keyin 2-sahifadan 3 ta chiqaradi.

---

## 3. 💻 Bosqichma-bosqich Amaliy Mashg'ulot (Lab Task)

Ushbu amaliy mashg'ulotda siz kompyuterda mavjud printer sozlamalarini tahlil qilasiz va hujjatni virtual PDF printer orqali to'g'ri chop etishni mashq qilasiz.

### Kerakli Resurslar:
* Windows 10/11 o'rnatilgan kompyuter;
* Microsoft Word dasturi;
* O'rnatilgan "Microsoft Print to PDF" virtual printeri.

### 📄 Amaliy Mashg'ulot Shabloni:
{% hint style="success" %}
**📄 Rasmiy Amaliy Mashg'ulot va Uy Vazifasi Shabloni (Google Docs (Hujjat)):**
Ushbu darsning barcha bosqichlarini bajarish, natijalar/hisobotlarni kiritish va uy vazifasini topshirish uchun quyidagi rasmiy shablondan foydalaning:
* 🌐 **Onlayn ko'rish va tahrirlash:** [06-Mavzu: Printer Bilan Ishlash va Sozlash — Shablonni ochish](https://docs.google.com/document/d/159amdEc3kr4nbGYDfFw2lRneDQEaOkddxfU0t5V4f5g/edit?usp=sharing)
* 📥 **Shaxsiy Drive-ga nusxalash (Tavsiya etiladi):** [Nusxa yaratish (Make a copy)](https://docs.google.com/document/d/159amdEc3kr4nbGYDfFw2lRneDQEaOkddxfU0t5V4f5g/copy)
{% endhint %}

{% embed url="https://docs.google.com/document/d/159amdEc3kr4nbGYDfFw2lRneDQEaOkddxfU0t5V4f5g/preview" %}

> *Eslatma: Shablondan nusxa oling va quyidagi 6 ta qadam natijalarini hisobotga kiriting.*

### Bajarish Bosqichlari:

1. **1-Qadam:** `Win + I` bosing, **Bluetooth & devices -> Printers & scanners** bo'limiga kiring.
2. **2-Qadam:** Tizimda o'rnatilgan printerlar ro'yxatini ko'zdan kechiring. "Microsoft Print to PDF" printerini tanlang va **Open print queue** (Chop etish navbati) darchasini oching.
3. **3-Qadam:** Microsoft Word dasturida yangi hujjat oching va tasodifiy matn generatsiya qilish uchun `=rand(5,5)` yozib Enter bosing (5 ta xatboshi matn hosil bo'ladi).
4. **4-Qadam (Chop etish darchasi):** Klaviaturada `Ctrl + P` tugmalarini bosing.
5. **5-Qadam (Sozlamalar):**
   * Printer ro'yxatidan **Microsoft Print to PDF** ni tanlang;
   * Pages qatoriga faqat `1` deb yozing;
   * Orientation parametrini **Landscape** (Albomiy) qilib o'zgartiring va Print Preview'da qog'ozning gorizontal aylanganini kuzating.
6. **6-Qadam (Faylga saqlash):** **Print** tugmasini bosing, saqlash joyi sifatida `Mening_Hujjatlarim/` papkasini ko'rsatib, faylga `Chop_Etish_Sinovi.pdf` nomini bering.

{% hint style="warning" %}
**Ehtiyot bo'ling:**
Lazerli printer ichida qog'oz tiqilib (Paper Jam) qolsa, qog'ozni kuch bilan qarama-qarshi tomonga tortib yirtmang! Bu termoplyonka (Fuser) va rezina vallarni shikastlaydi. Har doim kartrijni chiqarib oling va qog'ozni uning harakat yo'nalishi bo'ylab ikki qo'llab asta-sekin torting.
{% endhint %}

---

## 4. 🛠 Real Ish Vaziyati va Muammolarni Hal Qilish (Case-Study)

### Muammo:
Ofisda xodim 100 betlik hisobotni chop etishga yubordi. Ammo 5-betda printerda qog'oz tugab qoldi. Xodim qog'oz soldi, lekin printer chop etishni davom ettirmadi va "Error — Printing" holatida qotib qoldi. Boshqa xodimlar yuborgan yangi hujjatlar ham chop bo'lmay, navbatda to'planib qoldi. Kompyuterni va printerni o'chirib yoqish natija bermadi.

### Muammoning Kelib Chiqish Sababi:
Windows tizimining **Print Spooler** xizmati keshida buzilgan chop etish fayli (`.spl` va `.shd`) tiqilib qolgan va navbatni bloklab qo'ygan.

### Bosqichma-bosqich Yechim:
1. `Win + R` bosing, `services.msc` deb yozing va Enter bosing (Xizmatlar darchasi ochiladi).
2. Ro'yxatdan **Print Spooler (Диспетчер печати)** xizmatini toping.
3. Ustiga o'ng tugmani bosib **Stop (Остановить)** buyrug'ini bering.
4. `Win + E` orqali quyidagi tizimli papkaga kiring:
   `C:\Windows\System32\spool\PRINTERS`
5. Ushbu papka ichidagi barcha vaqtinchalik tiqilib qolgan fayllarni belgilab, butunlay o'chirib tashlang (`Shift + Delete`).
6. Qaytadan Services darchasiga o'tib, **Print Spooler** ustiga o'ng tugmani bosing va **Start (Запустить)** qiling.
7. Printer navbati butunlay tozalanadi va qurilma yangi hujjatlarni normal qabul qila boshlaydi!

---

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz — 25 ta Savol, 100 Ball)

{% hint style="info" %}
**📝 Rasmiy Onlayn Test Sinovi (Google Forms — 25 ta savol, 100 ballik baholash):**
Ushbu dars bo'yicha olgan bilimlaringizni sinash uchun quyidagi rasmiy testni topshiring (Har bir to'g'ri javob 4 ball, jami: 100 ball):
* 🔗 **Onlayn Testni Ochish (To'liq Ekranda):** [06-Mavzu: Printer Bilan Ishlash va Sozlash — Testni Topshirish](https://docs.google.com/forms/d/e/1FAIpQLSfB6ph_u6BWJWUj7_UG1tAQlih9WXMoUwYo3JiDCXupNmJ43g/viewform)
* 📊 **Kunlik Natijalar va Ballar Jadvali:** [Google Sheets — Natijalar Jadvali](https://docs.google.com/spreadsheets/d/1bQZdeRGZYDQzj-ND03tUN_Gz5iOZQvoek6ZHD8YGz_4/edit)
{% endhint %}

{% embed url="https://docs.google.com/forms/d/e/1FAIpQLSfB6ph_u6BWJWUj7_UG1tAQlih9WXMoUwYo3JiDCXupNmJ43g/viewform" %}

---

## 6. 🏠 Mustaqil Amaliy Uyga Vazifa

### Topshiriq:
1. Microsoft Word dasturida o'zingiz haqingizda 2 sahifalik qisqacha ma'lumot (CV/Rezyume) yozing.
2. Chop etish sozlamalariga kirib (`Ctrl + P`), faqat 2-sahifani chop etish rejimiga sozlang.
3. Printerni "Microsoft Print to PDF" ga o'tkazib, uni kompyuteringizga PDF fayl qilib saqlang.
4. Chop etish navbati (Open queue) darchasini ochib skrinshot oling.

**Topshirish formati:** PDF natija fayli va skrinshotni `FIO_6-Mavzu_Printer.docx` shaklida platformaga yuklang.

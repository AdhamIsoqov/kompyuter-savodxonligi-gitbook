# 11-Mavzu: Microsoft Office Paketiga Kirish

{% hint style="info" %}
**Dars maqsadi:** Microsoft Office dasturlar to'plamining ekotizimi, har bir dasturning (Word, Excel, PowerPoint, Outlook, Access, OneNote) ixtisoslashuv sohasi, ofis dasturlarining versiyalari (Office 2019, 2021 va Microsoft 365) hamda zamonaviy XML asosidagi fayl formatlarini (`.docx`, `.xlsx`, `.pptx`) chuqur o'rganish.
{% endhint %}

### 🎯 Kutilayotgan Kompetensiyalar
* **Bilishingiz kerak:**
  * Har bir amaliy vazifa uchun to'g'ri Office dasturini tanlash mantig'i.
  * Standart `.doc`/`.xls` va zamonaviy `.docx`/`.xlsx` formatlari o'rtasidagi arxitekturaviy farq.
  * Microsoft 365 bulutli xizmati va oflayn dasturlar to'plami integratsiyasi.
* **Bajara olishingiz kerak:**
  * Kompyuterdagi Microsoft Office versiyasini va faollashtirish (Activation) holatini aniqlash.
  * Standart ofis shablonlaridan (Templates) foydalangan holda yangi hujjatlarni tezkor yaratish.
  * Hujjatlarni turli formatlarda (`.docx`, `.pdf`, `.txt`) eksport qilish.

---

## 🎬 1. Video Dars

{% hint style="info" %}
**Video darslik:** Microsoft Office dasturlari ekotizimi bilan tanishuv bo'yicha quyidagi videoni tomosha qiling:
{% endhint %}

[Iframe/Embed: 11-Mavzu Bo'yicha YouTube Video Dars Havolasi]

---

## 2. 📖 Chuqurlashtirilgan Nazariy Ma'ruza

### 2.1. Qaysi Ish Uchun Qaysi Dastur?

Microsoft Office — dunyodagi eng ommabop ofis ilovalari to'plamidir. Har bir dastur o'zining aniq yo'nalishiga ega:

| Dastur Nomi | Asosiy Vazifasi | Fayl Kengaytmasi | Real Hayotiy Qo'llanilishi |
| :--- | :--- | :--- | :--- |
| **Microsoft Word** | Matnli hujjatlar yaratish va formatlash | `.docx` | Ariza, buyruq, shartnoma, maqola, rezyume, kitob |
| **Microsoft Excel** | Elektron jadvallar va hisob-kitoblar | `.xlsx` | Buxgalteriya, maosh jadvali, moliyaviy tahlil, diagrammalar |
| **Microsoft PowerPoint** | Vizual slaydlar va taqdimotlar | `.pptx` | Darslar, ma'ruzalar, loyiha taqdimotlari, hisobotlar |
| **Microsoft Outlook** | Korporativ pochta va taqvim | `.pst`, `.ost` | Xizmat yozishmalari, uchrashuvlarni rejalashtirish |
| **Microsoft Access** | Relyatsion ma'lumotlar bazasi | `.accdb` | Katta hajmli ma'lumotlar ombori, so'rovlar (SQL), formalar |
| **Microsoft OneNote** | Raqamli yon daftarcha | `.one` | Tezkor eslatmalar, o'quv konspektlari, audio yozuvlar |

```
[Microsoft Office Ekotizimi]
      ├── Matn va Hujjatlar  =========> Microsoft Word (.docx)
      ├── Hisob-kitob va Sonlar ======> Microsoft Excel (.xlsx)
      ├── Ko'rgazma va Slaydlar ======> Microsoft PowerPoint (.pptx)
      └── Muloqot va Rejalar ========> Microsoft Outlook
```

{% hint style="success" %}
**Pro-Tip (Nima uchun oxirida "x" harfi bor?):**
Eski versiyalarda kengaytmalar `.doc`, `.xls`, `.ppt` bo'lgan bo'lsa, 2007-yildan boshlab oxiriga **"x"** harfi qo'shildi (`.docx`, `.xlsx`, `.pptx`). Bu **XML (OpenXML)** arxitekturasini bildiradi. Aslida har qanday `.docx` fayli — bu matnlar, rasmlar va shriftlar siqilgan ZIP-arxivdir! Bu fayllar hajmini 2-3 barobarga qisqartiradi va buzilgan taqdirda ham matnni oson tiklash imkonini beradi.
{% endhint %}

### 2.2. Oflayn Office vs Microsoft 365 (Bulutli)

* **Klassik Office (2016, 2019, 2021):** Bir marta sotib olinadi va o'rnatiladi. Yangi funksiyalar qo'shilmaydi, faqat xavfsizlik yangilanishlarini oladi.
* **Microsoft 365 (sobiq Office 365):** Oylik yoki yillik obuna tizimi. Doimiy ravishda eng so'nggi sun'iy intellekt (Copilot) funksiyalari qo'shilib boradi, 1 TB OneDrive bulutli xotira beradi va hujjat ustida bir vaqtning o'zida bir nechta xodim onlayn hamkorlikda ishlashi mumkin.

---

## 3. 💻 Bosqichma-bosqich Amaliy Mashg'ulot (Lab Task)

Ushbu amaliy mashg'ulotda siz kompyuteringizdagi Office paketining holatini tekshirasiz va professional tayyor shablon asosida birinchi hujjatni yaratasiz.

### Kerakli Resurslar:
* Kompyuter (Windows 10/11);
* Microsoft Office dasturlar to'plami.

### 📄 Amaliy Mashg'ulot Shabloni:
{% hint style="success" %}
**📄 Rasmiy Amaliy Mashg'ulot va Uy Vazifasi Shabloni (Google Docs (Hujjat)):**
Ushbu darsning barcha bosqichlarini bajarish, natijalar/hisobotlarni kiritish va uy vazifasini topshirish uchun quyidagi rasmiy shablondan foydalaning:
* 🌐 **Onlayn ko'rish va tahrirlash:** [11-Mavzu: Microsoft Office Paketiga Kirish — Shablonni ochish](https://docs.google.com/document/d/14Tu2cZOyq7zJqPbV1s0n1-r6jTS2zc3_5f73rulnUQ8/edit?usp=sharing)
* 📥 **Shaxsiy Drive-ga nusxalash (Tavsiya etiladi):** [Nusxa yaratish (Make a copy)](https://docs.google.com/document/d/14Tu2cZOyq7zJqPbV1s0n1-r6jTS2zc3_5f73rulnUQ8/copy)
{% endhint %}

{% embed url="https://docs.google.com/document/d/14Tu2cZOyq7zJqPbV1s0n1-r6jTS2zc3_5f73rulnUQ8/preview" %}

> *Eslatma: Shablondan nusxa oling va quyidagi 6 ta qadamni bajarib hisobotga joylang.*

### Bajarish Bosqichlari:

1. **1-Qadam:** Start menyusini oching va **Word** dasturini ishga tushiring.
2. **2-Qadam (Versiyani aniqlash):** Chap pastki burchakdagi **Account (Учетная запись)** bo'limiga kiring. "Product Information" qismida Office versiyasi (masalan: Microsoft Office 2019 Professional Plus) va litsenziya holatini aniqlab, skrinshot oling.
3. **3-Qadam (Shablon tanlash):** Bosh sahifaga qayting (**Home -> More templates / Другие шаблоны**). Qidiruv qatoriga "Resume" yoki "Rezyume" deb yozing.
4. **4-Qadam:** O'zingizga ma'qul kelgan rezyume shablonini tanlang va **Create (Создать)** tugmasini bosing.
5. **5-Qadam:** Shablon ichidagi ism-familiya, mutaxassislik va ma'lumotlarni o'zingizga moslab qisqacha o'zgartiring.
6. **6-Qadam (Saqlash va eksport):** Hujjatni `FIO_Rezyume.docx` nomi bilan saqlang (`Ctrl + S`), so'ng **File -> Export -> Create PDF/XPS** orqali PDF nusxasini ham hosil qiling.

{% hint style="warning" %}
**Ehtiyot bo'ling:**
Agar Office dasturingiz yuqori qismida qizil tasmada "Product Activation Failed" (Litsenziya muddati tugagan) xabari chiqsa, ko'p funksiyalar (matn tahrirlash, saqlash) bloklanib qoladi. Har doim qonuniy litsenziyadan foydalaning.
{% endhint %}

---

## 4. 🛠 Real Ish Vaziyati va Muammolarni Hal Qilish (Case-Study)

### Muammo:
Mijoz o'zining eski kompyuterida (Office 2003) tayyorlangan muhim hisobot faylini (`Hisobot.doc`) zamonaviy kompyuterda (Office 2021) ochdi. Hujjat yuqori sarlavhasida **[Compatibility Mode] (Режим ограниченной функциональности)** yozuvi chiqib qoldi. Natijada zamonaviy jadvallar, yangi formulalar va dizayn uslublarini kiritish bloklandi, mavjud shriftlar esa chalkashib ketdi.

### Muammoning Kelib Chiqish Sababi:
Fayl 20 yillik eski binar `.doc` formatida saqlangani uchun zamonaviy Word dasturi uni eski xatoliklardan himoyalash maqsadida cheklangan rejimda ochgan.

### Bosqichma-bosqich Yechim:
1. Word dasturida hujjat ochilgan holatda **File (Файл) -> Info (Сведения)** bo'limiga kiring.
2. Eng yuqoridagi **Convert (Преобразовать)** tugmasini bosing.
3. Tizim hujjatni zamonaviy XML arxitekturasiga (`.docx`) aylantirishini ma'lum qiladi — **OK** tugmasini bosing.
4. Hujjat bir zumda zamonaviy formatga o'tadi, cheklovlar yechiladi, fayl hajmi kichrayadi va barcha zamonaviy dizayn asboblari faollashadi.

---

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz — 25 ta Savol, 100 Ball)

{% hint style="info" %}
**📝 Rasmiy Onlayn Test Sinovi (Google Forms — 25 ta savol, 100 ballik baholash):**
Ushbu dars bo'yicha olgan bilimlaringizni sinash uchun quyidagi rasmiy testni topshiring (Har bir to'g'ri javob 4 ball, jami: 100 ball):
* 🔗 **Onlayn Testni Ochish (To'liq Ekranda):** [11-Mavzu: Microsoft Office Paketiga Kirish — Testni Topshirish](https://docs.google.com/forms/d/e/1FAIpQLScB2JiSccN78xpXw-QbEPLVilv3cyLqp8hpGsUHhGRfDsBp6w/viewform)
* 📊 **Kunlik Natijalar va Ballar Jadvali:** [Google Sheets — Natijalar Jadvali](https://docs.google.com/spreadsheets/d/1qNzEUe8nE08H6c3qFklLAFT7RdOTC8zZC8O9MCGgwRg/edit)
{% endhint %}

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLScB2JiSccN78xpXw-QbEPLVilv3cyLqp8hpGsUHhGRfDsBp6w/viewform?embedded=true" width="100%" height="800" frameborder="0" marginheight="0" marginwidth="0">Yuklanmoqda…</iframe>

---

### ✍️ 25 ta Rasmiy Test Savollari (Nazorat va O'z-o'zini Tekshirish):

Quyida ushbu dars bo'yicha tuzilgan barcha 25 ta rasmiy test savollari keltirilgan. Har bir savol 4 ta variantdan iborat bo'lib, to'g'ri javob belgilangan:

#### 1-Savol: Microsoft Office dasturlar paketiga qaysi asosiy dasturlar kiradi?
- [x] **A) Word, Excel, PowerPoint, Outlook** *(To'g'ri javob)*
- [ ] B) Photoshop, Premiere, After Effects
- [ ] C) AutoCAD, 3ds Max
- [ ] D) CorelDraw, Illustrator

#### 2-Savol: Office dasturlarining yuqori qismidagi tugmalar va menyular tasmasi nima deyiladi?
- [x] **A) Ribbon (Lenta)** *(To'g'ri javob)*
- [ ] B) Taskbar
- [ ] C) Scrollbar
- [ ] D) Status bar

#### 3-Savol: Tezkor kirish paneli (Quick Access Toolbar) qayerda joylashgan va vazifasi nima?
- [x] **A) Oynaning yuqori chap burchagida; eng ko'p ishlatiladigan buyruqlarni (Save, Undo) bir bosishda chaqiradi** *(To'g'ri javob)*
- [ ] B) Pastki o'ngda; vaqtni ko'rsatadi
- [ ] C) O'rtada; qidiradi
- [ ] D) Faqat menyu ochadi

#### 4-Savol: Word dasturida saqlangan zamonaviy fayllar qanday kengaytmaga ega bo'ladi?
- [x] **A) .docx** *(To'g'ri javob)*
- [ ] B) .doc
- [ ] C) .txt
- [ ] D) .rtf

#### 5-Savol: Excel elektron jadvallari qaysi kengaytma bilan saqlanadi?
- [x] **A) .xlsx** *(To'g'ri javob)*
- [ ] B) .xls
- [ ] C) .csv
- [ ] D) .dbf

#### 6-Savol: PowerPoint taqdimotlari qaysi formatda saqlanadi?
- [x] **A) .pptx** *(To'g'ri javob)*
- [ ] B) .ppt
- [ ] C) .pps
- [ ] D) .pot

#### 7-Savol: Hujjatni boshqa formatda yoki yangi nom bilan saqlash (Save As) klavishi qaysi?
- [x] **A) F12** *(To'g'ri javob)*
- [ ] B) F1
- [ ] C) Ctrl + S
- [ ] D) F5

#### 8-Savol: Hujjatni o'zgarishlar bilan tezkor saqlash (Save) kombinatsiyasi nima?
- [x] **A) Ctrl + S** *(To'g'ri javob)*
- [ ] B) Ctrl + P
- [ ] C) Ctrl + O
- [ ] D) Ctrl + N

#### 9-Savol: Yangi bo'sh hujjat yaratish (New Document) tugmasi qaysi?
- [x] **A) Ctrl + N** *(To'g'ri javob)*
- [ ] B) Ctrl + O
- [ ] C) Ctrl + W
- [ ] D) Ctrl + E

#### 10-Savol: Mavjud hujjatni ochish (Open) klaviatura birikmasi nima?
- [x] **A) Ctrl + O** *(To'g'ri javob)*
- [ ] B) Ctrl + P
- [ ] C) Ctrl + K
- [ ] D) Ctrl + D

#### 11-Savol: Hujjatni PDF formatida eksport qilishning asosiy afzalligi nima?
- [x] **A) Barcha qurilmalarda shrift va dizayn buzilmasdan bir xil ko'rinadi** *(To'g'ri javob)*
- [ ] B) Hajmi kattalashadi
- [ ] C) Uni o'zgartirib bo'lmaydi
- [ ] D) Rasmlar o'chadi

#### 12-Savol: Office dasturlarida 'AutoRecover' (Avtosaxlash) nima uchun kerak?
- [x] **A) Kutilmaganda kompyuter o'chganda hujjatning oxirgi holatini tiklash uchun** *(To'g'ri javob)*
- [ ] B) Viruslarni o'chirish uchun
- [ ] C) Faylni chop etish uchun
- [ ] D) Imloni tekshirish uchun

#### 13-Savol: Fayl menyusidagi 'Backstage' ko'rinishi qanday bo'limlarni o'z ichiga oladi?
- [x] **A) Info, Save, Save As, Print, Share, Export, Close** *(To'g'ri javob)*
- [ ] B) Faqat shriftlar
- [ ] C) Faqat jadvallar
- [ ] D) Faqat animatsiyalar

#### 14-Savol: Office shablonlari (Templates) nima maqsadda qo'llaniladi?
- [x] **A) Tayyor dizayn va tuzilmaga ega rezyume, hisobot yoki blankalarni tez yaratish uchun** *(To'g'ri javob)*
- [ ] B) Hujjatni qulflash uchun
- [ ] C) Ofisni o'chirish uchun
- [ ] D) Internetga ulanish uchun

#### 15-Savol: Microsoft 365 (Office 365) ning oddiy Office dan farqi nima?
- [x] **A) Bulutli obunaga asoslangan bo'lib, doimiy yangilanishlar va OneDrive integratsiyasini beradi** *(To'g'ri javob)*
- [ ] B) Faqat telefonda ishlaydi
- [ ] C) Faqat rasmlar chizadi
- [ ] D) Litsenziyasiz ishlaydi

#### 16-Savol: Hujjat oynasini yopish (Close Window) tugmasi qaysi?
- [x] **A) Ctrl + W** *(To'g'ri javob)*
- [ ] B) Ctrl + Q
- [ ] C) Alt + W
- [ ] D) Ctrl + Z

#### 17-Savol: Lentani (Ribbon) vaqtincha yashirish yoki ko'rsatish tugmasi qaysi?
- [x] **A) Ctrl + F1** *(To'g'ri javob)*
- [ ] B) Alt + F1
- [ ] C) F1
- [ ] D) Shift + F1

#### 18-Savol: Hujjatdagi barcha matn va ob'ektlarni belgilash qaysi tugma bilan bajariladi?
- [x] **A) Ctrl + A** *(To'g'ri javob)*
- [ ] B) Ctrl + S
- [ ] C) Ctrl + C
- [ ] D) Alt + A

#### 19-Savol: Hujjatda qidiruv (Find) darchasini ochish klavishi nima?
- [x] **A) Ctrl + F** *(To'g'ri javob)*
- [ ] B) Ctrl + H
- [ ] C) Ctrl + G
- [ ] D) Alt + F

#### 20-Savol: Matndagi so'zlarni boshqasiga almashtirish (Replace) qaysi birikma bilan chaqiriladi?
- [x] **A) Ctrl + H** *(To'g'ri javob)*
- [ ] B) Ctrl + R
- [ ] C) Ctrl + F
- [ ] D) Alt + H

#### 21-Savol: Hujjat masshtabini (Zoom) tezkor o'zgartirish qanday amalga oshiriladi?
- [x] **A) Ctrl tugmasini bosib turib sichqoncha g'ildiragini (Scroll) aylantirish** *(To'g'ri javob)*
- [ ] B) Shift + Scroll
- [ ] C) Alt + Scroll
- [ ] D) F5 bosish

#### 22-Savol: Hujjat xususiyatlarida (Document Properties) qanday ma'lumotlar saqlanadi?
- [x] **A) Muallif, yaratilgan sana, hajmi, sahifalar soni va kalit so'zlar** *(To'g'ri javob)*
- [ ] B) Faqat kompyuter nomi
- [ ] C) Faqat klaviatura turi
- [ ] D) Parollar

#### 23-Savol: Office dasturlarida clipboard (Almashish buferi) bir vaqtning o'zida nechta ob'ektni saqlay oladi?
- [x] **A) 24 tagacha** *(To'g'ri javob)*
- [ ] B) 1 ta
- [ ] C) 100 ta
- [ ] D) Cheksiz

#### 24-Savol: Hujjatni chop etishdan oldin ko'rish (Print Preview) qaysi tugmalar bilan ochiladi?
- [x] **A) Ctrl + F2 yoki Ctrl + P** *(To'g'ri javob)*
- [ ] B) Alt + P
- [ ] C) Shift + P
- [ ] D) F4

#### 25-Savol: Office dasturlaridan to'liq chiqish (Exit) tugmasi qaysi?
- [x] **A) Alt + F4** *(To'g'ri javob)*
- [ ] B) Ctrl + F4
- [ ] C) Shift + Esc
- [ ] D) Esc

---


## 6. 🏠 Mustaqil Amaliy Uyga Vazifa

### Topshiriq:
1. Kompyuteringizdagi Office dasturlari ro'yxatini va versiyasini ko'zdan kechiring.
2. Excel, Word va PowerPoint dasturlarining har birini bir marta ishga tushirib, ularning boshlang'ich interfeysini solishtiring.
3. Word dasturida mavjud shablonlar (Templates) asosida bitta xatboshi rasmiy xat (Letter) tayyorlang va `.docx` hamda `.pdf` shaklida saqlang.

**Topshirish formati:** Tayyorlangan fayl va skrinshotlarni `FIO_11-Mavzu_Office.docx` nomi bilan platformaga yuklang.

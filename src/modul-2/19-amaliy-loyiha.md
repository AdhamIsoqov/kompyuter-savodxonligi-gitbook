# 19-Mavzu: 2-Modul Amaliy Loyihasi: Kompleks Ofis Hujjatlari Paketi

{% hint style="info" %}
**Dars maqsadi:** 2-Modulda o'rganilgan uchta asosiy ofis dasturini — Microsoft Word (rasmiy xat/hisobot), Microsoft Excel (moliyaviy hisob-kitoblar va diagrammalar) hamda Microsoft PowerPoint (loyihaning 5–6 slaydli vizual taqdimoti) dasturlarini yagona real biznes loyihasi doirasida integratsiyalash va to'liq paket tayyorlash.
{% endhint %}

### 🎯 Kutilayotgan Kompetensiyalar
* **Bilishingiz kerak:**
  * Ofis dasturlari o'rtasida ma'lumotlar almashinuvi va dinamik bog'liqlik (OLE — Object Linking and Embedding).
  * Korxona hujjatlar aylanishi zanjiri: Hisob-kitob (Excel) -> Rasmiy hujjat (Word) -> Taqdimot (PowerPoint).
  * Hujjatlarni arxivlash, PDF ga eksport qilish va mijozga professional topshirish etikasi.
* **Bajara olishingiz kerak:**
  * Word dasturida rasmiy standartlarga javob beruvchi rasmiy loyiha taklifini formatlash.
  * Excelda `SUM`, `AVERAGE`, `IF` formulalari va dinamik diagrammaga ega moliyaviy smeta tuzish.
  * Exceldagi diagrammani PowerPoint taqdimotiga jonli havola (Paste Link) orqali ko'chirib, professional slayd-shou shakllantirish.

---

## 🎬 1. Video Dars

{% hint style="info" %}
**Video darslik:** 2-Modul amaliy loyihasini bajarish va dasturlar integratsiyasi bo'yicha quyidagi videoni tomosha qiling:
{% endhint %}

[Iframe/Embed: 19-Mavzu Bo'yicha YouTube Video Dars Havolasi]

---

## 2. 📖 Nazariy Integratsiya: Ofis Dasturlari Hamkorligi

Real ish faoliyatida hech bir ofis dasturi alohida ishlatilmaydi. Ular yagona mexanizm sifatida ishlaydi:

```
+-------------------------------------------------------------------------+
|                  2-MODUL KOMPLEKS BIZNES LOYIHASI                       |
+-------------------------------------------------------------------------+
|  1. Microsoft Excel:     2. Microsoft Word:       3. Microsoft          |
|                          (Tijoriy Taklif)         PowerPoint:           |
|  - Xarajatlar smetasi    - Rasmiy matn va ariza   - 5-6 slaydli loyiha  |
|  - SUM, AVERAGE, IF      - Formatlangan jadvallar - Excel diagrammasi   |
|  - Dinamik diagramma     - Avtomatik mundarija    - Transitions va Fade |
+-------------------------------------------------------------------------+
                                    │
                                    ▼
       [Yagona Loyiha Papkasi: Loyiha_2026_FIO/] ---> USB / PDF Export
```

{% hint style="success" %}
**Pro-Tip (Excel diagrammasini PowerPointga "jonli" ulash):**
Exceldagi diagrammani `Ctrl + C` qilib, PowerPointga shunchaki `Ctrl + V` qilsangiz, Excelda sonlar o'zgarganda slayd o'zgarmay qoladi.
Buning o'rniga PowerPointda: **Paste (Вставить) -> Paste Special (Специальная вставка) -> Paste Link (Связать)** ni tanlang! Endi Excelda 1 ta son o'zgarsa ham, PowerPoint taqdimotidagi diagramma o'z-o'zidan yangilanadi!
{% endhint %}

---

## 3. 💻 Bosqichma-bosqich Amaliy Mashg'ulot (Lab Task)

Ushbu loyihada siz "Kompaniya Kompyuter Parkini Yangilash" mavzusida to'liq 3 ta hujjatdan iborat to'plam tayyorlaysiz.

### Kerakli Resurslar:
* Microsoft Word, Excel va PowerPoint dasturlari;
* Amaliy loyiha topshiriq shabloni.

### 📄 Amaliy Mashg'ulot Shabloni:
{% hint style="success" %}
**📄 Rasmiy Amaliy Mashg'ulot va Uy Vazifasi Shabloni (Google Docs (Hujjat)):**
Ushbu darsning barcha bosqichlarini bajarish, natijalar/hisobotlarni kiritish va uy vazifasini topshirish uchun quyidagi rasmiy shablondan foydalaning:
* 🌐 **Onlayn ko'rish va tahrirlash:** [19-Mavzu: 2-Modul Amaliy Loyihasi — Shablonni ochish](https://docs.google.com/document/d/12cIhpUlo_1P9LR2-Z4iJ1EBhhAmsRRI3pI5eKmKZD5w/edit?usp=sharing)
* 📥 **Shaxsiy Drive-ga nusxalash (Tavsiya etiladi):** [Nusxa yaratish (Make a copy)](https://docs.google.com/document/d/12cIhpUlo_1P9LR2-Z4iJ1EBhhAmsRRI3pI5eKmKZD5w/copy)
{% endhint %}

{% embed url="https://docs.google.com/document/d/12cIhpUlo_1P9LR2-Z4iJ1EBhhAmsRRI3pI5eKmKZD5w/preview" %}

> *Eslatma: Shablondan nusxa oling va quyidagi 3 ta bosqich natijalarini to'liq bajaring.*

### Bajarish Bosqichlari:

#### 1-Bosqich: Microsoft Excel (Smeta tuzish)
1. Yangi Excel fayl ochib, 5 xil kompyuter qismlari (Protsessor, Ona plata, RAM, SSD, Quvvat bloki) narxi va sonini kiriting.
2. Jami summani hisoblash uchun ko'paytirish va pastida `=SUM(...)` formulasini yozing.
3. O'rtacha narxni `=AVERAGE(...)` orqali chiqaring.
4. Ushbu smeta asosida chiroyli **Ustunli (Column)** diagramma hosil qiling va faylni `01_Smeta.xlsx` qilib saqlang.

#### 2-Bosqich: Microsoft Word (Rasmiy hisobot tayyorlash)
1. Yangi Word fayl oching (Times New Roman, 14 pt, 1.15 interval, Justify).
2. Rahbariyat nomiga "Kompyuter parkini yangilash haqida" rasmiy bildirishnoma matnini yozing.
3. Exceldagi smeta jadvalini Word hujjati ichiga chiroyli qilib joylang va sarlavhasiga Header qo'shing.
4. Faylni `02_Bildirishnoma.docx` va `02_Bildirishnoma.pdf` shaklida saqlang.

#### 3-Bosqich: Microsoft PowerPoint (Rahbariyat uchun taqdimot)
1. 5 ta slayddan iborat taqdimot yarating:
   * *1-Slayd:* Titul (Loyiha nomi va muallif)
   * *2-Slayd:* Loyihaning maqsadi va muammolar
   * *3-Slayd:* Taklif etilayotgan yangi uskunalar ro'yxati (Bullets)
   * *4-Slayd:* Exceldan ko'chirilgan smeta diagrammasi (Grafik)
   * *5-Slayd:* Kutilayotgan samaradorlik va xulosa
2. Barcha slaydlarga Fade o'tishini bering va faylni `03_Taqdimot.pptx` qilib saqlang.

#### 4-Bosqich: Birlashtirish
* Ish stolida `Loyiha_Kompyuter_FIO` papkasini oching va barcha 3 ta faylni ushbu papkaga jamlang.

{% hint style="warning" %}
**Ehtiyot bo'ling:**
Word va PowerPoint hujjatlariga kiritilgan ma'lumotlar bilan Excel smetasidagi raqamlar bir-biriga 100% mos kelishi shart. Raqamlardagi nomuvofiqlik loyiha bahosining pasayishiga olib keladi.
{% endhint %}

---

## 4. 🛠 Real Ish Vaziyati va Muammolarni Hal Qilish (Case-Study)

### Muammo:
Katta yig'ilishda bosh muhandis loyiha taqdimotini namoyish qilayotgan paytda, bosh hisobchi: *"Ehtiyot qismlar narxi kecha 10% ga arzonlashdi, taqdimotdagi raqamlar eskiribdi"*, deb e'tiroz bildirdi. Bosh muhandis esa Exceldagi yangilangan fayldan raqamlarni qaytadan ko'chirib, slaydlarni tuzatish uchun 30 daqiqa yig'ilishni to'xtatishga majbur bo'ldi.

### Muammoning Kelib Chiqish Sababi:
Diagrammalar PowerPointga shunchaki statik rasm (Skrinshot) sifatida ko'chirilgan, dasturlar o'rtasidagi OLE (jonli havola) funksiyasidan foydalanilmagan.

### Bosqichma-bosqich Yechim:
1. Excelda narxlar o'zgarganda, PowerPointdagi diagramma ustiga sichqonchaning o'ng tugmasini bosing.
2. **Update Link (Обновить связь)** buyrug'ini tanlang.
3. PowerPointdagi barcha ustunlar, raqamlar va foizlar bor-yo'g'i **1 soniyada** Exceldagi yangi narxlarga avtomatik moslashadi, taqdimotni qaytadan yasash talab etilmaydi!

---

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz — 25 ta Savol, 100 Ball)

{% hint style="info" %}
**📝 Rasmiy Onlayn Test Sinovi (Google Forms — 25 ta savol, 100 ballik baholash):**
Ushbu dars bo'yicha olgan bilimlaringizni sinash uchun quyidagi rasmiy testni topshiring (Har bir to'g'ri javob 4 ball, jami: 100 ball):
* 🔗 **Onlayn Testni Ochish (To'liq Ekranda):** [19-Mavzu: 2-Modul Amaliy Loyihasi — Testni Topshirish](https://docs.google.com/forms/d/e/1FAIpQLSdRGSd1OWRb5plWdpDI8aXV5c2vfNAzmAyiJ_b_0BqIv3IW4w/viewform)
* 📊 **Kunlik Natijalar va Ballar Jadvali:** [Google Sheets — Natijalar Jadvali](https://docs.google.com/spreadsheets/d/1mF5dPEZHquy2gjxGAk4fy2WwuIbFbg0Ta9rxU6vHzEU/edit)
{% endhint %}

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSdRGSd1OWRb5plWdpDI8aXV5c2vfNAzmAyiJ_b_0BqIv3IW4w/viewform?embedded=true" width="100%" height="800" frameborder="0" marginheight="0" marginwidth="0">Yuklanmoqda…</iframe>

---

### ✍️ 25 ta Rasmiy Test Savollari (Nazorat va O'z-o'zini Tekshirish):

Quyida ushbu dars bo'yicha tuzilgan barcha 25 ta rasmiy test savollari keltirilgan. Har bir savol 4 ta variantdan iborat bo'lib, to'g'ri javob belgilangan:

#### 1-Savol: 2-Modul amaliy loyihasining asosiy vazifasi nimadan iborat?
- [x] **A) Word, Excel va PowerPoint dasturlarida o'zaro bog'liq kompleks korporativ loyihani tayyorlash** *(To'g'ri javob)*
- [ ] B) Faqat bitta matn terish
- [ ] C) Kino ko'rish
- [ ] D) Kompyuterni buzish

#### 2-Savol: Exceldagi dinamik diagrammani Word hujjatiga qanday joylashtirish eng to'g'ri hisoblanadi?
- [x] **A) Paste Special -> Paste Link (Bog'langan holda qo'yish: Excelda o'zgarsa, Wordda ham yangilanadi)** *(To'g'ri javob)*
- [ ] B) Oddiy skrinshot qilish
- [ ] C) Qayta qo'lda chizish
- [ ] D) Rasm qilib saqlab yuklash

#### 3-Savol: Korporativ biznes-reja yoki loyiha hujjati Wordda qaysi majburiy bo'limlardan iborat bo'ladi?
- [x] **A) Titul varag'i, Avtomatik mundarija, Kirish, Moliyaviy tahlil, Xulosa va Ilovalar** *(To'g'ri javob)*
- [ ] B) Faqat rasmlar
- [ ] C) Faqat bitta qator sarlavha
- [ ] D) Faqat jadvallar

#### 4-Savol: Loyiha moliyaviy hisob-kitoblarida qaysi ko'rsatkichlar Excelda hisoblanadi?
- [x] **A) Daromadlar, xarajatlar, sof foyda, rentabellik va o'rtacha qiymatlar** *(To'g'ri javob)*
- [ ] B) Faqat xodimlar soni
- [ ] C) Faqat sana
- [ ] D) Kompyuter narxi

#### 5-Savol: Loyihaning PowerPoint taqdimoti kimga mo'ljallangan bo'ladi?
- [x] **A) Investorlar va rahbariyatga loyiha g'oyasini qisqa va ta'sirchan yetkazish uchun** *(To'g'ri javob)*
- [ ] B) Faqat arxivda saqlash uchun
- [ ] C) Chop etish uchun
- [ ] D) O'chirish uchun

#### 6-Savol: Word hujjatida korxona logotipini barcha sahifalarda bir xil chiqarish qayerdan bajariladi?
- [x] **A) Header (Yuqori kolontitul) ichiga rasm joylash orqali** *(To'g'ri javob)*
- [ ] B) Har bir sahifaga alohida qo'yish
- [ ] C) Avtomatik mundarijaga
- [ ] D) Page Borderga

#### 7-Savol: Loyiha hujjatini chop etishga tayyorlashda qaysi ko'rsatkich standart me'yorda bo'lishi shart?
- [x] **A) Chap chekka (Left margin) kamida 2.5-3 sm (tikish uchun joy qoldirish)** *(To'g'ri javob)*
- [ ] B) Hamma tomon 0 sm
- [ ] C) Faqat o'ng tomon 5 sm
- [ ] D) Pastki tomon 10 sm

#### 8-Savol: Taqdimot slaydlari soni 10-12 tadan oshmasligi sababi nima?
- [x] **A) Auditoriyaning diqqati 15-20 daqiqadan so'ng susayishi va asosiy fikr yo'qolmasligi uchun** *(To'g'ri javob)*
- [ ] B) Xotira yetmasligi uchun
- [ ] C) Fayl ochilmasligi uchun
- [ ] D) Proyektor charchashi uchun

#### 9-Savol: Loyiha materiallarini hamkorlarga yuborishda qaysi format eng xavfsiz va qulay?
- [x] **A) PDF formati (barcha formatlashlar qat'iy saqlanadi)** *(To'g'ri javob)*
- [ ] B) DOCX o'zgartiriladigan
- [ ] C) TXT formati
- [ ] D) BMP rasmlar

#### 10-Savol: Excelda olingan moliyaviy natijalarni taqdimot slaydlarida qanday taqdim etish ma'qul?
- [x] **A) Murakkab ulkan jadvallar emas, balki asosiy raqamlar va ko'rgazmali diagrammalar orqali** *(To'g'ri javob)*
- [ ] B) 100 qatorli jadvalni skrinshot qilish
- [ ] C) Faqat matn yozish
- [ ] D) Raqamlarni yashirish

#### 11-Savol: Barcha uchala dasturda (Word, Excel, PPT) yagona korporativ uslubni ta'minlash nimaga asoslanadi?
- [x] **A) Yagona rang palitrasi, yagona shriftlar oilasi va korxona ramzidan foydalanish** *(To'g'ri javob)*
- [ ] B) Har xil ranglarni aralashtirish
- [ ] C) Faqat qora va oq qilish
- [ ] D) Format qilmaslik

#### 12-Savol: Wordda 'Heading 1' va 'Heading 2' uslublaridan foydalanishning yana bir afzalligi nima?
- [x] **A) Navigation Pane orqali hujjat bo'limlariga bir zumda o'tish imkoniyati** *(To'g'ri javob)*
- [ ] B) Faylni kichraytiradi
- [ ] C) Sahifani bo'yaydi
- [ ] D) Imloni tuzatadi

#### 13-Savol: Excel jadvalida ma'lumotlarni hisoblashda formulalarni dinamik saqlash nimani ta'minlaydi?
- [x] **A) Birlamchi narx yoki miqdor o'zgarganda barcha yakuniy jami summalar avtomatik qayta hisoblanadi** *(To'g'ri javob)*
- [ ] B) Xatoliklarni yashiradi
- [ ] C) Faqat bir marta hisoblaydi
- [ ] D) Katakni qulflaydi

#### 14-Savol: PowerPoint slaydlarida SmartArt ierarxiya diagrammasi nima uchun ishlatiladi?
- [x] **A) Korxona tashkiliy tuzilmasi va boshqaruv bo'g'inlarini ko'rsatish uchun** *(To'g'ri javob)*
- [ ] B) Pul hisoblash uchun
- [ ] C) Video ko'rish uchun
- [ ] D) Qo'shiq eshitish uchun

#### 15-Savol: Loyiha fayllari bitta umumiy papkaga qanday tartibda joylanadi?
- [x] **A) 01_Hisobot_Word.docx, 02_Moliya_Excel.xlsx, 03_Taqdimot_PPT.pptx** *(To'g'ri javob)*
- [ ] B) Nomsiz fayl 1, 2, 3
- [ ] C) Desktopga tartibsiz sochib
- [ ] D) Savatga tashlab

#### 16-Savol: Loyiha taqdimotida 'Elevator Pitch' qoidasi nima?
- [x] **A) Loyiha mohiyatini 1-2 daqiqa ichida qisqa, aniq va qiziqarli qilib tushuntirib bera olish** *(To'g'ri javob)*
- [ ] B) Liftda rasmga tushish
- [ ] C) Uzoq ma'ruza qilish
- [ ] D) Slaydni ko'paytirish

#### 17-Savol: Exceldagi formulalarni himoyalash va boshqalar o'zgartira olmasligi uchun nima qilinadi?
- [x] **A) Review -> Protect Sheet orqali parol bilan qulflash** *(To'g'ri javob)*
- [ ] B) Katakni yashirish
- [ ] C) Excelni o'chirish
- [ ] D) Faylni siqish

#### 18-Savol: Wordda jadvallarga avtomatik sarlavha va raqam berish (Caption) qaysi menyuda?
- [x] **A) References -> Insert Caption** *(To'g'ri javob)*
- [ ] B) Insert -> Table
- [ ] C) Home -> Styles
- [ ] D) Layout -> Borders

#### 19-Savol: PowerPoint slaydlarida rasmlar sifatini siqish (Compress Pictures) nima uchun kerak?
- [x] **A) Taqdimot fayli hajmini keskin kamaytirib, email orqali oson jo'natish uchun** *(To'g'ri javob)*
- [ ] B) Rasm rangini buzish uchun
- [ ] C) Slaydni sekinlashtirish uchun
- [ ] D) Faylni buzish uchun

#### 20-Savol: Loyihaning yakuniy taqdimotida qaysi slayd xulosa va harakatga chaqiriq (Call to Action) hisoblanadi?
- [x] **A) Yakuniy xulosa va aloqa ma'lumotlari slaydi** *(To'g'ri javob)*
- [ ] B) Titul slaydi
- [ ] C) Mundarija
- [ ] D) Bo'sh slayd

#### 21-Savol: Ofis dasturlarida tez-tez uchraydigan shrift buzilishi (shrift yo'qligi) qanday oldini olinadi?
- [x] **A) Save parametrlarida 'Embed fonts in the file' funksiyasini yoqish** *(To'g'ri javob)*
- [ ] B) Faylni nomini o'zgartirish
- [ ] C) Monitorni almashtirish
- [ ] D) Kompyuterni o'chirish

#### 22-Savol: Exceldagi moliyaviy ma'lumotlarni Wordga oddiy rasm qilib qo'yishning kamchiligi nima?
- [x] **A) Excelda hisob-kitoblar o'zgarganda Worddagi rasm yangilanmaydi va qayta nusxalash talab etiladi** *(To'g'ri javob)*
- [ ] B) Kamchiligi yo'q
- [ ] C) Fayl ochilmaydi
- [ ] D) Juda tez bo'ladi

#### 23-Savol: Word hujjatida Adabiyotlar ro'yxatini (Bibliography) avtomatik shakllantirish qaysi menyuda?
- [x] **A) References -> Bibliography** *(To'g'ri javob)*
- [ ] B) Review -> Proofing
- [ ] C) Insert -> Links
- [ ] D) Home -> Paragraph

#### 24-Savol: PowerPoint taqdimotini proyektorga uzatishda eng ishonchli ulanish qaysi?
- [x] **A) HDMI yoki DisplayPort raqamli kabellari orqali** *(To'g'ri javob)*
- [ ] B) Eski VGA orqali
- [ ] C) Faqat Bluetooth
- [ ] D) Audio kabel orqali

#### 25-Savol: 2-Modul loyihasining muvaffaqiyat mezoni qanday baholanadi?
- [x] **A) Hujjatlarning mukammal formati, to'g'ri formulalar va taqdimotning vizual jozibadorligi** *(To'g'ri javob)*
- [ ] B) Faqat sahifalar soni ko'pligi bilan
- [ ] C) Ranglar juda ko'pligi bilan
- [ ] D) Fayl og'irligi bilan

---


## 6. 🏠 Mustaqil Amaliy Loyiha Topshirig'i

### Topshiriq:
Ushbu darsning barcha 3 ta bosqichini (Excel smetasi, Word rasmiy hujjati, PowerPoint taqdimoti) o'z kompyuteringizda to'liq bajaring.
Yaratilgan `01_Smeta.xlsx`, `02_Bildirishnoma.docx`, `02_Bildirishnoma.pdf` va `03_Taqdimot.pptx` fayllarini bitta `Loyiha_FIO` papkasiga jamlang va uni ZIP arxiv qiling.

**Topshirish formati:** Tayyorlangan `Loyiha_FIO.zip` arxivini platformaga yuklang.

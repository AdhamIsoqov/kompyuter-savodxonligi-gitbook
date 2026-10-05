# 07-Mavzu: Skaner Bilan Ishlash va OCR Texnologiyalari

{% hint style="info" %}
**Dars maqsadi:** Qog'oz hujjatlarni raqamlashtirish, planshetli (Flatbed) va ADF (avtomatik oziqlantiruvchi) skanerlar bilan ishlash, optimal DPI (150/300/600) va rang rejimlarini tanlash, ko'p sahifali PDF formatini yaratish hamda OCR (optik matnni tanish) texnologiyasi orqali tasvirdan tahrirlanadigan matn ajratib olish ko'nikmalarini shakllantirish.
{% endhint %}

### 🎯 Kutilayotgan Kompetensiyalar
* **Bilishingiz kerak:**
  * Skanerlash aniqligi — DPI (Dots Per Inch) ning fayl sifati va hajmiga ta'siri.
  * PDF va JPG formatlarining hujjat aylanishidagi afzallik va kamchiliklari.
  * OCR (Optical Character Recognition) texnologiyasining ishlash mexanizmi.
* **Bajara olishingiz kerak:**
  * Windows Scan va ishlab chiqaruvchi dasturlari orqali Preview (oldindan ko'rish) va skanerlashni amalga oshirish.
  * 10–20 varaqli shartnomani bitta ko'p sahifali PDF faylga birlashtirib raqamlashtirish.
  * Skanerlangan rasmdagi matnni OCR vositalari (Google Docs / FineReader) yordamida tahrirlanadigan Word matniga aylantirish.

---

## 🎬 1. Video Dars

{% hint style="info" %}
**Video darslik:** Hujjatlarni professional skanerlash va OCR orqali matnga aylantirish bo'yicha quyidagi videoni tomosha qiling:
{% endhint %}

[Iframe/Embed: 07-Mavzu Bo'yicha YouTube Video Dars Havolasi]

---

## 2. 📖 Chuqurlashtirilgan Nazariy Ma'ruza

### 2.1. Skanerlashning Asosiy Parametrlari: DPI va Rang Rejimlari

Skanerlash sifati va hosil bo'ladigan fayl hajmi ikki asosiy omilga bog'liq:

| Parametr / Qiymat | Tavsiya etilgan soha | Fayl Hajmi | Xususiyati |
| :--- | :--- | :--- | :--- |
| **150 DPI** | Qoralamalar, tezkor ko'rib chiqish | Juda kichik (~200 KB) | Ekranda yaxshi ko'rinadi, lekin chop etish uchun xira |
| **300 DPI (Standart)** | Rasmiy hujjatlar, arizalar, shartnomalar | O'rtacha (~1–2 MB) | **Oltin standart:** Yuqori sifat va ixcham hajm muvozanati |
| **600+ DPI** | Fotosuratlar, arxiv hujjatlari, kichik shriftlar | Katta (10–50 MB) | Har bir mayda detalgacha aniq chiqadi |

#### Rang Rejimlari (Color Modes):
1. **Color (Rangli, 24-bit):** Rangli rasmlar, muhrlar va sertifikatlar uchun.
2. **Grayscale (Kulrang shkala, 8-bit):** Matn va oq-qora fotosuratlar uchun (rangli rejimga qaraganda 3 barobar yengil).
3. **Black & White / Line Art (1-bit):** Faqat sof qora matn va oq fon (fayl hajmi nihoyatda kichik bo'ladi).

```
[Skanerlash va Raqamlashtirish Arxitekturasi]
  Qog'oz Hujjat (A4)
        |
  [Skaner Optikasi: 300 DPI]
        |
  Preview (Oldindan ko'rish va chegaralarni to'g'rilash)
        |
        +---> Agar rasmli bo'lsa: [JPG format]
        |
        +---> Agar ko'p sahifali hujjat bo'lsa: [PDF format]
                    |
              OCR Dasturi (Google Docs / AI)
                    |
              Tahrirlanadigan Word Hujjati (.docx)
```

{% hint style="success" %}
**Pro-Tip (Ko'p sahifali PDF "Oltin Qoidasi"):**
Hech qachon 10 varaqli shartnomaning har bir betini alohida `skaner1.jpg`, `skaner2.jpg` qilib saqlamang! Skaner dasturida saqlash formati sifatida **PDF** ni tanlang va **"Combine into single file" (Bitta faylga birlashtirish)** bandini yoqing. Natijada barcha sahifalar bitta tartibli faylga aylanadi.
{% endhint %}

### 2.2. OCR (Optik Belgilarni Tanish) Texnologiyasi

Oddiy skanerlash natijasida kompyuter hujjatni shunchaki "rasm" (piksellar to'plami) deb qabul qiladi — undagi so'zlarni qidirib yoki nusxalab bo'lmaydi.

**OCR (Optical Character Recognition)** — bu rasm ichidagi harflar, so'zlar va jadvallarni tanib, ularni matnli formatga (`.docx`, `.txt`) aylantiruvchi dasturiy intellektdir. Zamonaviy OCR vositalari:
* Google Drive / Google Docs (bepul va o'zbek tilini yaxshi taniydi);
* ABBYY FineReader;
* Adobe Acrobat Pro;
* Zamonaviy AI neyrotarmoqlari.

---

## 3. 💻 Bosqichma-bosqich Amaliy Mashg'ulot (Lab Task)

Ushbu amaliy mashg'ulotda siz mavjud rasmdagi matnni Google Docs orqali bepul OCR qilib, tahrirlanadigan hujjatga aylantirishni o'rganasiz.

### Kerakli Resurslar:
* Kompyuter va internet brauzeri;
* Google hisobi (Google Drive);
* Skanerlangan yoki telefonda suratga olingan har qanday kitob sahifasi (`.jpg` yoki `.png`).

### 📄 Amaliy Mashg'ulot Shabloni:
[Iframe/Embed: 07-Mavzu Google Docs / MS Office Amaliy Mashq Shabloni Havolasi]

> *Eslatma: Shablondan nusxa oling va quyidagi 6 ta qadam orqali OCR qilingan matn natijasini hujjatga joylang.*

### Bajarish Bosqichlari:

1. **1-Qadam:** Telefoningiz yoki skaner orqali biror kitob sahifasini 300 DPI sifatda rasmga oling (`Matn_Namunasi.jpg`).
2. **2-Qadam:** Brauzeringizda **Google Drive** (`drive.google.com`) xizmatini oching.
3. **3-Qadam:** Yangi yuklash tugmasi orqali `Matn_Namunasi.jpg` faylini Google Drive-ga yuklang.
4. **4-Qadam (OCR sehrli buyrug'i):** Yuklangan rasm ustiga sichqonchaning o'ng tugmasini bosing:
   * **Open with (Открыть с помощью) -> Google Docs (Google Документы)** ni tanlang.
5. **5-Qadam:** Google Docs bir necha soniyada rasmni tahlil qiladi va hujjatning yuqori qismiga asl rasmni, pastki qismiga esa to'liq tahrirlanadigan matnni terib beradi!
6. **6-Qadam (Tahrirlash va saqlash):** Matndagi xatoliklarni to'g'rilang, Microsoft Word formati sifatida kompyuteringizga yuklab oling (**File -> Download -> Microsoft Word (.docx)**).

{% hint style="warning" %}
**Ehtiyot bo'ling:**
OCR dasturi matnni xatosiz tanishi uchun asl rasm qiyshiq bo'lmasligi, soya tushmagan bo'lishi va harflar xiralashmagan (aniq fokusda) bo'lishi shart!
{% endhint %}

---

## 4. 🛠 Real Ish Vaziyati va Muammolarni Hal Qilish (Case-Study)

### Muammo:
Kotibiyat xodimi 15 varaqli buyruqni skanerlab elektron pochta orqali vazirlikka yuborishi kerak edi. Xodim skanerni 1200 DPI va Color rejimida ishlatdi. Natijada har bir sahifaning hajmi 25 MB bo'lib, 15 ta sahifa jami **375 MB** hajmni tashkil qildi. Elektron pochta (Gmail) esa 25 MB dan katta fayllarni jo'natishni rad etdi.

### Muammoning Kelib Chiqish Sababi:
Hujjat turi matnli bo'lishiga qaramay, asossiz ravishda haddan tashqari yuqori DPI (1200) va rangli rejim tanlangan.

### Bosqichma-bosqich Yechim:
1. Skaner dasturi sozlamalariga kiring.
2. Rezolyutsiyani 1200 DPI dan rasmiy hujjatlar uchun optimal bo'lgan **300 DPI** ga tushiring.
3. Rang rejimini Color o'rniga **Grayscale (Kulrang)** yoki **Black & White** ga o'tkazing.
4. Saqlash formatini JPG emas, **Multi-page PDF (Ko'p sahifali PDF)** qilib belgilang.
5. Qayta skanerlanganda 15 betlik butun hujjat bor-yo'g'i **2.5 MB** hajmga ega bo'ldi va elektron pochtadan bir zumda muammosiz jo'natildi!

---

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz)

{% hint style="info" %}
**Onlayn Test:** 7-Mavzu bo'yicha olgan bilimlaringizni sinab ko'rish uchun quyidagi Google Forms testini topshiring:
{% endhint %}

[Iframe/Embed: 07-Mavzu Google Forms Rasmiy Test Havolasi]

### ✍️ O'z-o'zini Tekshirish Uchun Test Savollari:

#### Test 1: Oddiy ofis hujjatlarini (shartnoma, ariza) skanerlashda xalqaro standart bo'yicha qaysi DPI eng optimal hisoblanadi?
- ( ) A) 72 DPI
- ( ) B) 150 DPI
- (x) C) 300 DPI
- ( ) D) 2400 DPI
*Izoh: 300 DPI sifat va fayl hajmi o'rtasidagi eng mukammal mutanosiblikni ta'minlaydi.*

#### Test 2: Rasm shaklidagi skanerlangan matnlarni tahrirlanadigan Word formatiga aylantirish texnologiyasi nima deb ataladi?
- ( ) A) GPS
- (x) B) OCR (Optical Character Recognition)
- ( ) C) BIOS
- ( ) D) RAM
*Izoh: OCR — optik belgilarni tanish orqali piksellarni harflarga aylantiradi.*

#### Test 3: Ko'p sahifali (masalan, 10 betlik) rasmiy hujjatlarni bitta yaxlit faylda saqlash uchun qaysi format tanlanadi?
- ( ) A) `.mp3`
- ( ) B) `.jpg`
- (x) C) `.pdf`
- ( ) D) `.png`
*Izoh: PDF formati bir nechta sahifani bitta umumiy hujjatda saqlash va qulay varaqlash imkonini beradi.*

#### Test 4: ADF (Automatic Document Feeder) skaner qurilmasining oddiy planshetli skanerdan asosiy ustunligi nimada?
- ( ) A) Rangsiz skanerlaydi
- (x) B) 50–100 varaqli qog'ozlar dastasini avtomatik ravishda birin-ketin o'zi tortib olib skanerlaydi
- ( ) C) Faqat fotosuratlarni skanerlaydi
- ( ) D) Kompyutersiz ishlaydi
*Izoh: ADF operator qo'li bilan har bir varaqni almashtirmasdan, butun dasta qog'ozni avtomatlashtirilgan tarzda o'tkazadi.*

#### Test 5: Skaner oynasiga hujjat qanday holatda qo'yilishi shart?
- ( ) A) Matni yuqoriga qaragan holatda
- (x) B) Matnli yuzi pastga — shisha oynaga qaratilgan va burchakka tekislangan holda
- ( ) C) Qatlab qo'yilgan holda
- ( ) D) Farqi yo'q
*Izoh: Skaner optik moduli shisha ostidan nur taratib tasvir oladi, shuning uchun matn pastga qarashi kerak.*

### 🤔 O'ylantiruvchi Mantiqiy Savollar:
1. Nima uchun qog'oz hujjatlarni saqlashdan ko'ra ularni raqamlashtirib bulutli arxivda (Cloud) saqlash ancha xavfsiz va tejamkor?
2. Dastxat bilan (qo'lda) yozilgan xatlarni OCR dasturlari nega ba'zan xato yoki umuman taniy olmaydi?
3. Skaner oynasiga chang yoki barmoq izi tushsa, bu olingan fayl sifatiga qanday ta'sir ko'rsatadi?

---

## 6. 🏠 Mustaqil Amaliy Uyga Vazifa

### Topshiriq:
1. O'zingizga tegishli biror hujjatni (pasport nusxasi, diplom yoki kitob beti) smartfon yoki skaner orqali suratga oling.
2. Google Drive xizmatiga yuklab, Google Docs orqali OCR qiling.
3. Aniqlangan matnni Word dasturiga ko'chirib, shriftini `Times New Roman`, 14 pt, qator oralig'ini 1.15 qilib chiroyli formatlang.
4. Asl rasm va olingan Word matnini taqqoslab hisobot tayyorlang.

**Topshirish formati:** Tayyorlangan hisobotni `FIO_7-Mavzu_Skaner_OCR.docx` nomi bilan platformaga yuklang.

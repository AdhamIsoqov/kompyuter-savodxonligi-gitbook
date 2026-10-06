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
{% hint style="success" %}
**📄 Rasmiy Amaliy Mashg'ulot va Uy Vazifasi Shabloni (Google Docs (Hujjat)):**
Ushbu darsning barcha bosqichlarini bajarish, natijalar/hisobotlarni kiritish va uy vazifasini topshirish uchun quyidagi rasmiy shablondan foydalaning:
* 🌐 **Onlayn ko'rish va tahrirlash:** [07-Mavzu: Skaner Bilan Ishlash va OCR — Shablonni ochish](https://docs.google.com/document/d/1gZ0StVV2J_ca0jz80NRzVb--tD-KCZzztbbGPU5X6RM/edit?usp=sharing)
* 📥 **Shaxsiy Drive-ga nusxalash (Tavsiya etiladi):** [Nusxa yaratish (Make a copy)](https://docs.google.com/document/d/1gZ0StVV2J_ca0jz80NRzVb--tD-KCZzztbbGPU5X6RM/copy)
{% endhint %}

{% embed url="https://docs.google.com/document/d/1gZ0StVV2J_ca0jz80NRzVb--tD-KCZzztbbGPU5X6RM/preview" %}

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

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz — 25 ta Savol, 100 Ball)

{% hint style="info" %}
**📝 Rasmiy Onlayn Test Sinovi (Google Forms — 25 ta savol, 100 ballik baholash):**
Ushbu dars bo'yicha olgan bilimlaringizni sinash uchun quyidagi rasmiy testni topshiring (Har bir to'g'ri javob 4 ball, jami: 100 ball):
* 🔗 **Onlayn Testni Ochish (To'liq Ekranda):** [07-Mavzu: Skaner Bilan Ishlash va OCR — Testni Topshirish](https://docs.google.com/forms/d/e/1FAIpQLSf2Fn_aSEyeH49MCLC1PyOZdE2IynT0a5RJz9wlJ3FfFC6AFg/viewform)
* 📊 **Kunlik Natijalar va Ballar Jadvali:** [Google Sheets — Natijalar Jadvali](https://docs.google.com/spreadsheets/d/1h3YuO-hf_k4yEFfYAyxt93HCPyPs7W0xGaknxxKVoOY/edit)
{% endhint %}

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSf2Fn_aSEyeH49MCLC1PyOZdE2IynT0a5RJz9wlJ3FfFC6AFg/viewform?embedded=true" width="100%" height="800" frameborder="0" marginheight="0" marginwidth="0">Yuklanmoqda…</iframe>

---

### ✍️ 25 ta Rasmiy Test Savollari (Nazorat va O'z-o'zini Tekshirish):

Quyida ushbu dars bo'yicha tuzilgan barcha 25 ta rasmiy test savollari keltirilgan. Har bir savol 4 ta variantdan iborat bo'lib, to'g'ri javob belgilangan:

#### 1-Savol: Skaner qurilmasining asosiy vazifasi nima?
- [x] **A) Qog'ozdagi tasvir yoki matnni raqamli fayl shakliga o'tkazish** *(To'g'ri javob)*
- [ ] B) Matnni qog'ozga chop etish
- [ ] C) Kompyuterni internetga ulash
- [ ] D) Tovushni yozib olish

#### 2-Savol: OCR (Optical Character Recognition) texnologiyasi nima?
- [x] **A) Optik belgilarni tanib olish — skanerlangan rasmdagi matnni tahrirlanadigan matnga aylantirish** *(To'g'ri javob)*
- [ ] B) Rasmni rangini o'zgartirish
- [ ] C) Faylni arxivlash
- [ ] D) Videoni siqish

#### 3-Savol: Oddiy matnli hujjatlarni skanerlash uchun optimal ruxsat (DPI) qancha?
- [x] **A) 300 DPI** *(To'g'ri javob)*
- [ ] B) 72 DPI
- [ ] C) 1200 DPI
- [ ] D) 4800 DPI

#### 4-Savol: Skanerlashda TWAIN va WIA nima?
- [x] **A) Skaner va amaliy dasturlar o'rtasidagi standart drayver interfeyslari** *(To'g'ri javob)*
- [ ] B) Fayl kengaytmalari
- [ ] C) Rang modellari
- [ ] D) Kabel turlari

#### 5-Savol: Arxivlanadigan rasmiy hujjatlar uchun qaysi PDF formati tavsiya etiladi?
- [x] **A) PDF/A (Arxiv standarti)** *(To'g'ri javob)*
- [ ] B) PDF oddiy
- [ ] C) DOCX
- [ ] D) BMP

#### 6-Savol: ADF (Auto Document Feeder) skaneri nima uchun qulay?
- [x] **A) Ko'p sahifali hujjatlarni avtomatik ravishda ketma-ket skanerlash uchun** *(To'g'ri javob)*
- [ ] B) Faqat bitta rasm olish uchun
- [ ] C) Chop etish uchun
- [ ] D) Ranglarni to'g'rilash uchun

#### 7-Savol: Skanerlangan hujjatlarni eng kam sifat yo'qotishi bilan saqlaydigan format qaysi?
- [x] **A) TIFF va PNG** *(To'g'ri javob)*
- [ ] B) JPEG
- [ ] C) GIF
- [ ] D) ICO

#### 8-Savol: OCR dasturlariga qaysilar misol bo'ladi?
- [x] **A) ABBYY FineReader, Adobe Acrobat OCR, Google Keep OCR** *(To'g'ri javob)*
- [ ] B) VLC Player
- [ ] C) WinRAR
- [ ] D) Notepad

#### 9-Savol: Skanerlashda rang rejimlarining qanday turlari mavjud?
- [x] **A) Color (Rangli), Grayscale (Kulrang), Black & White (Oq-qora)** *(To'g'ri javob)*
- [ ] B) Ultra, High, Low
- [ ] C) Yorqin va Qorong'i
- [ ] D) Keng va Tor

#### 10-Savol: Qaysi rejimda skanerlangan hujjat fayl hajmi eng kichik bo'ladi?
- [x] **A) 1-bit Black & White (Oq-qora)** *(To'g'ri javob)*
- [ ] B) 24-bit True Color
- [ ] C) 8-bit Grayscale
- [ ] D) RGB

#### 11-Savol: Fotosuratlarni sifatli skanerlash uchun qanday DPI tavsiya qilinadi?
- [x] **A) 600–1200 DPI** *(To'g'ri javob)*
- [ ] B) 72 DPI
- [ ] C) 150 DPI
- [ ] D) 50 DPI

#### 12-Savol: Skaner oynasini (shishasini) qanday moddalar bilan tozalash mumkin?
- [x] **A) Spirtli maxsus shisha tozalagich va tuksiz yumshoq latta bilan** *(To'g'ri javob)*
- [ ] B) Abraziv kukunli tozalagich bilan
- [ ] C) Suv sepib cho'tka bilan
- [ ] D) Qog'oz bilan qirib

#### 13-Savol: Ko'p sahifali skanerlashda barcha varaqlarni bitta faylga jamlash formati qaysi?
- [x] **A) Multi-page PDF yoki TIFF** *(To'g'ri javob)*
- [ ] B) JPEG
- [ ] C) BMP
- [ ] D) PNG

#### 14-Savol: Windows tizimida o'rnatilgan standart skanerlash utilitasi nima deyiladi?
- [x] **A) Windows Fax and Scan (yoki Windows Scan)** *(To'g'ri javob)*
- [ ] B) Paint
- [ ] C) Calculator
- [ ] D) Camera

#### 15-Savol: Smartfonlar yordamida sifatli skanerlash ilovasi qaysi?
- [x] **A) CamScanner, Adobe Scan, Microsoft Lens** *(To'g'ri javob)*
- [ ] B) TikTok
- [ ] C) Instagram
- [ ] D) Telegram

#### 16-Savol: OCR dasturida tanib olish sifatini oshirish uchun nima talab etiladi?
- [x] **A) Asl hujjatning toza, tekis va yetarli aniqlikda (kamida 300 DPI) skanerlanganligi** *(To'g'ri javob)*
- [ ] B) Hujjat qorong'i bo'lishi
- [ ] C) Egri turishi
- [ ] D) Ranglari aralashganligi

#### 17-Savol: Skanerlashda 'Deskew' funksiyasi nima ishni bajaradi?
- [x] **A) Egri skanerlangan sahifani avtomatik ravishda to'g'rilab beradi** *(To'g'ri javob)*
- [ ] B) Faylni o'chiradi
- [ ] C) Rangini o'zgartiradi
- [ ] D) Matnni o'qiydi

#### 18-Savol: Skanerning optik o'lchami (Optical Resolution) interpolyatsiyadan nimasi bilan farq qiladi?
- [x] **A) Optik — apparat datchiklarining haqiqiy fizik aniqligi, interpolyatsiya — dasturiy hisoblangan nuqtalar** *(To'g'ri javob)*
- [ ] B) Optik dasturiy bo'ladi
- [ ] C) Farqi yo'q
- [ ] D) Interpolyatsiya aniqroq

#### 19-Savol: Planshetli (Flatbed) skanerning ustunligi nima?
- [x] **A) Kitob, jurnal va qalin hujjatlarni oynaga qo'yib skanerlash mumkinligi** *(To'g'ri javob)*
- [ ] B) Kichikligi
- [ ] C) Faqat chek skanerlashi
- [ ] D) Tezligi

#### 20-Savol: Skanerlash jarayonida nima uchun shisha qopqog'i yopilishi kerak?
- [x] **A) Tashqi yorug'lik tushib, tasvir sifatini buzmasligi va ko'zni qamashtirmasligi uchun** *(To'g'ri javob)*
- [ ] B) Skaner qizib ketmasligi uchun
- [ ] C) Qog'oz uchib ketmasligi uchun
- [ ] D) Elektrni tejash uchun

#### 21-Savol: Qaysi texnologiya skanerlashda yorug'lik sezgir element hisoblanadi?
- [x] **A) CIS (Contact Image Sensor) va CCD (Charge-Coupled Device)** *(To'g'ri javob)*
- [ ] B) LED va LCD
- [ ] C) CRT va OLED
- [ ] D) RAM va ROM

#### 22-Savol: Google Drive orqali OCR qanday amalga oshiriladi?
- [x] **A) Rasm yoki PDF ni Google Drive ga yuklab, 'Open with Google Docs' qilib ochish** *(To'g'ri javob)*
- [ ] B) Faylni ZIP qilish
- [ ] C) Faylni o'chirish
- [ ] D) Drive orqali yuborish

#### 23-Savol: Skaner kompyuterga ko'pincha qaysi interfeys orqali ulanadi?
- [x] **A) USB kabel yoki Wi-Fi/Ethernet tarmoq orqali** *(To'g'ri javob)*
- [ ] B) VGA orqali
- [ ] C) HDMI orqali
- [ ] D) Audio port orqali

#### 24-Savol: Qog'ozdagi shtrix-kod va QR-kodlarni o'quvchi qurilma qanday ishlaydi?
- [x] **A) Lazer yoki foto-datchik orqali kodni optik skanerlab, matnga o'giradi** *(To'g'ri javob)*
- [ ] B) Ovoz to'lqinlari orqali
- [ ] C) Magnit orqali
- [ ] D) Issiqlik orqali

#### 25-Savol: Skanerlangan matnni to'g'ridan-to'g'ri Word (DOCX) ga saqlash nima beradi?
- [x] **A) Matnni darhol tahrirlash va xatolarni to'g'rilash imkonini beradi** *(To'g'ri javob)*
- [ ] B) Hajmini kattalashtiradi
- [ ] C) Rasm sifatini buzadi
- [ ] D) Faylni qulflaydi

---


## 6. 🏠 Mustaqil Amaliy Uyga Vazifa

### Topshiriq:
1. O'zingizga tegishli biror hujjatni (pasport nusxasi, diplom yoki kitob beti) smartfon yoki skaner orqali suratga oling.
2. Google Drive xizmatiga yuklab, Google Docs orqali OCR qiling.
3. Aniqlangan matnni Word dasturiga ko'chirib, shriftini `Times New Roman`, 14 pt, qator oralig'ini 1.15 qilib chiroyli formatlang.
4. Asl rasm va olingan Word matnini taqqoslab hisobot tayyorlang.

**Topshirish formati:** Tayyorlangan hisobotni `FIO_7-Mavzu_Skaner_OCR.docx` nomi bilan platformaga yuklang.

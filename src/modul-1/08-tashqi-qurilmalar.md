# 08-Mavzu: Tashqi Qurilmalar va Axborot Tashuvchilar

{% hint style="info" %}
**Dars maqsadi:** Kompyuterga ulanadigan periferiya va tashqi saqlash qurilmalari (USB fleshkalar, tashqi HDD/SSD), video va audio interfeyslar (HDMI, DisplayPort), proyektorni ulash va ko'p ekranli rejimlar (`Win + P`), veb-kamera hamda audio kirish-chiqish tizimlarini professional sozlashni o'rganish.
{% endhint %}

### 🎯 Kutilayotgan Kompetensiyalar
* **Bilishingiz kerak:**
  * USB portlar evolyutsiyasi: USB 2.0 (qora), USB 3.0 (ko'k) va USB Type-C o'rtasidagi tezlik farqlari.
  * Tashqi HDD (mexanik) va tashqi SSD (flesh-xotira) afzallik va kamchiliklari.
  * Windows loyihalash (Projection) rejimlari: Duplicate, Extend, Second screen only.
* **Bajara olishingiz kerak:**
  * USB xotira tashuvchilarini ma'lumotlar yaxlitligini buzmasdan xavfsiz ajratish (Safely Remove Hardware).
  * `Win + P` yordamida proyektor yoki ikkinchi monitorni taqdimot va ishchi maydonni kengaytirish rejimlariga moslash.
  * Veb-kamera va mikrofon xavfsizlik ruxsatlarini (Privacy Settings) sozlash va diagnostika qilish.

---

## 🎬 1. Video Dars

{% hint style="info" %}
**Video darslik:** Tashqi qurilmalar, proyektor va multimedia vositalarini sozlash bo'yicha quyidagi videoni tomosha qiling:
{% endhint %}

[Iframe/Embed: 08-Mavzu Bo'yicha YouTube Video Dars Havolasi]

---

## 2. 📖 Chuqurlashtirilgan Nazariy Ma'ruza

### 2.1. USB Interfeyslari va Axborot Tashuvchilar

Kompyuter texnikasida tashqi qurilmalar asosan USB (Universal Serial Bus) portlari orqali ulanadi:

| Port Turi | Vizual Belgisi | Maksimal Nazariy Tezligi | Qo'llanilish Sohasi |
| :--- | :--- | :--- | :--- |
| **USB 2.0** | Qora rangli plastik ichlik | 480 Mbps (~35–40 MB/s) | Sichqoncha, klaviatura, oddiy printerlar |
| **USB 3.0 / 3.1** | Ko'k yoki qizil rangli ichlik, "SS" (SuperSpeed) | 5 Gbps – 10 Gbps (~450–600 MB/s)| Tashqi SSD, tezkor fleshkalar, veb-kameralar |
| **USB Type-C** | Oval shaklli, simmetrik (ikki tomonlama) | 10 Gbps – 40 Gbps (Thunderbolt) | Zamonaviy noutbuklar, smartfonlar, tashqi monitorlar |

```
[Tashqi Saqlash Qurilmalari Taqqoslanishi]
  ├── Tashqi HDD (Hard Disk) ---> Aylanuvchi magnit disklar, arzon, 1-5 TB, zarbaga nozik (~120 MB/s)
  └── Tashqi SSD (Solid State) --> Elektron mikrosxemalar, yengil, zarbaga chidamli, o'ta tez (~500-1050 MB/s)
```

{% hint style="success" %}
**Pro-Tip (Fleshkani xavfsiz ajratish):**
Fleshka yoki tashqi diskdan ma'lumot o'qilayotgan yoki unga fayl yozilayotgan vaqtda uni shunchaki sug'urib olish — fayl tizimining buzilishiga (`RAW` formatga o'tib qolishiga) va barcha ma'lumotlarning yo'qolishiga sabab bo'ladi!
Har doim System Tray dagi fleshka belgisini bosing va **"Safely Remove Hardware and Eject Media"** buyrug'ini tanlang.
{% endhint %}

### 2.2. Proyektor va Ikkinchi Ekran Boshqaruvi (`Win + P`)

HDMI yoki VGA kabel orqali tashqi monitor yoki proyektor ulanganda Windows klaviaturadagi `Win + P` tugmasi orqali 4 ta asosiy rejimni taqdim etadi:

```
+-------------------+     +-------------------+
|  1. PC Screen     |     |  Faqat noutbuk ekrani ishlaydi, tashqi ekran qora bo'ladi.
+-------------------+     +-------------------+
|  2. Duplicate     |     |  Noutbukdagi tasvir proyektorda AYNAN takrorlanadi (Taqdimotlar uchun!).
+-------------------+     +-------------------+
|  3. Extend        |     |  Ish stoli kengayadi: chapda Word, o'ngdagi proyektorda video ko'rsatish mumkin.
+-------------------+     +-------------------+
|  4. Second Screen |     |  Noutbuk ekrani o'chadi, faqat katta monitor yoki proyektor ishlaydi.
+-------------------+     +-------------------+
```

---

## 3. 💻 Bosqichma-bosqich Amaliy Mashg'ulot (Lab Task)

Ushbu amaliy mashg'ulotda siz kompyuteringizdagi audio va video multimedia qurilmalarining to'g'ri ishlashini diagnostika qilasiz.

### Kerakli Resurslar:
* Kompyuter (Windows 10/11);
* O'rnatilgan yoki tashqi veb-kamera va mikrofon/quloqchin;
* USB fleshka.

### 📄 Amaliy Mashg'ulot Shabloni:
{% hint style="success" %}
**📄 Rasmiy Amaliy Mashg'ulot va Uy Vazifasi Shabloni (Google Docs (Hujjat)):**
Ushbu darsning barcha bosqichlarini bajarish, natijalar/hisobotlarni kiritish va uy vazifasini topshirish uchun quyidagi rasmiy shablondan foydalaning:
* 🌐 **Onlayn ko'rish va tahrirlash:** [08-Mavzu: Tashqi Qurilmalar va Axborot Tashuvchilar — Shablonni ochish](https://docs.google.com/document/d/1Y_E6I3X7FwSofFV9x8qIwwcgOIKZ3XHVhRi8UukOooQ/edit?usp=sharing)
* 📥 **Shaxsiy Drive-ga nusxalash (Tavsiya etiladi):** [Nusxa yaratish (Make a copy)](https://docs.google.com/document/d/1Y_E6I3X7FwSofFV9x8qIwwcgOIKZ3XHVhRi8UukOooQ/copy)
{% endhint %}

{% embed url="https://docs.google.com/document/d/1Y_E6I3X7FwSofFV9x8qIwwcgOIKZ3XHVhRi8UukOooQ/preview" %}

> *Eslatma: Shablondan nusxa oling va diagnostika bosqichlari natijalarini to'ldiring.*

### Bajarish Bosqichlari:

1. **1-Qadam:** `Win + P` tugmalarini bosing va ekranning o'ng tomonida ochilgan loyihalash (Project) panelidagi 4 ta rejimni ko'zdan kechiring.
2. **2-Qadam:** Start menyusini oching, qidiruvga **Camera** deb yozing va dasturni ishga tushiring. Veb-kamera tasviri ravshanligini tekshiring.
3. **3-Qadam (Mikrofon sinovi):** `Win + I` bosing, **System -> Sound** bo'limiga o'ting. **Input (Kirish)** qismidagi mikrofon tanlanganini tekshiring va gapiring — indikator harakatlanishi kerak.
4. **4-Qadam (USB tekshiruvi):** USB fleshkangizni ko'k rangli (USB 3.0) portga ulang. File Explorer'da fleshka xotira hajmi va bo'sh joyini aniqlang.
5. **5-Qadam:** Fleshkaga o'quv faylini nusxalang (`Ctrl + C` / `Ctrl + V`).
6. **6-Qadam (Xavfsiz chiqarish):** Taskbar o'ng burchagidagi burchak strelkasini oching, USB belgisiga o'ng tugmani bosib **Eject (Извлечь)** buyrug'ini bering va "Safe to Remove Hardware" xabari chiqqach sug'urib oling.

{% hint style="warning" %}
**Ehtiyot bo'ling:**
Noutbuk yoki kompyuterning audio portiga (3.5 mm Mini-Jack) boshqa qattiq metall buyumlarni tiqmang. Shuningdek, HDMI kabelini kompyuter va televizor ishlab turgan vaqtda kuch bilan qiyshiq ulamang — bu videochip portining statik razryaddan kuyishiga sabab bo'lishi mumkin!
{% endhint %}

---

## 4. 🛠 Real Ish Vaziyati va Muammolarni Hal Qilish (Case-Study)

### Muammo:
Katta konferensiyada ma'ruzachi noutbukini HDMI kabel orqali katta zal proyektoriga uladi. Ammo zal proyektori ekranida "No Signal" (Signal yo'q) xatosi yonib turibdi, noutbuk esa proyektorni umuman ko'rmayapti. Taqdimot boshlanishiga 3 daqiqa vaqt qoldi.

### Muammoning Kelib Chiqish Sababi:
1) Noutbuk video signali tashqi portga uzatilmagan (rejim `PC screen only` da turibdi);
2) Proyektorning o'zida kirish signali manbasi (Input Source) noto'g'ri portga (masalan, HDMI 1 o'rniga HDMI 2 yoki VGA ga) sozlangan.

### Bosqichma-bosqich Yechim:
1. Klaviaturada zudlik bilan `Win + P` tugmalarini bosing va **Duplicate (Повторяющийся)** rejimini tanlang.
2. Agar signal chiqmasa, proyektor pultidagi yoki korpusidagi **Source / Input** tugmasini bosib, kabel ulangan aynan o'sha portni (masalan: `HDMI 1`) tanlang.
3. Agar tasvir nisbati buzilgan bo'lsa (`Win + I -> System -> Display`), Display resolution qismini proyektor qo'llab-quvvatlaydigan 1920x1080 yoki 1280x720 ga moslang.
4. Tasvir darhol katta ekranda paydo bo'ladi.

---

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz — 25 ta Savol, 100 Ball)

{% hint style="info" %}
**📝 Rasmiy Onlayn Test Sinovi (Google Forms — 25 ta savol, 100 ballik baholash):**
Ushbu dars bo'yicha olgan bilimlaringizni sinash uchun quyidagi rasmiy testni topshiring (Har bir to'g'ri javob 4 ball, jami: 100 ball):
* 🔗 **Onlayn Testni Ochish (To'liq Ekranda):** [08-Mavzu: Tashqi Qurilmalar va Axborot Tashuvchilar — Testni Topshirish](https://docs.google.com/forms/d/e/1FAIpQLScqpoLHSRHzx-3t2aP3YOOE0LawlWGeF1ZxDSJhBRNKovgtLA/viewform)
* 📊 **Kunlik Natijalar va Ballar Jadvali:** [Google Sheets — Natijalar Jadvali](https://docs.google.com/spreadsheets/d/1DWR7oghgreLxgmG9V_j0yK7uLLwRsQk9Dn2NpMXXpR8/edit)
{% endhint %}

{% embed url="https://docs.google.com/forms/d/e/1FAIpQLScqpoLHSRHzx-3t2aP3YOOE0LawlWGeF1ZxDSJhBRNKovgtLA/viewform" %}

---

## 6. 🏠 Mustaqil Amaliy Uyga Vazifa

### Topshiriq:
1. Kompyuteringizga ulangan tashqi qurilmalar (sichqoncha, klaviatura, fleshka, quloqchin) qaysi USB portlarga (USB 2.0 yoki USB 3.0) ulanganini vizual tekshiring.
2. `Win + P` menyusini ochib, uning barcha 4 ta rejimi vazifasini o'z so'zlaringiz bilan tushuntirib konspekt qiling.
3. Windows Camera dasturini ochib, veb-kamera tasviri va Sound sozlamalaridagi mikrofon faolligi aks etgan skrinshotni oling.

**Topshirish formati:** Bajarilgan topshiriqni `FIO_8-Mavzu_Qurilmalar.docx` nomi bilan platformaga yuklang.

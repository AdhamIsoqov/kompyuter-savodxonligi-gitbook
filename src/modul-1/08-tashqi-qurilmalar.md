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

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz)

{% hint style="info" %}
**Onlayn Test:** 8-Mavzu bo'yicha olgan bilimlaringizni sinab ko'rish uchun quyidagi Google Forms testini topshiring:
{% endhint %}

[Iframe/Embed: 08-Mavzu Google Forms Rasmiy Test Havolasi]

### ✍️ O'z-o'zini Tekshirish Uchun Test Savollari:

#### Test 1: Yuqori tezlikdagi zamonaviy USB 3.0 portlari odatda qanday rangdagi ichki plastik bilan ajralib turadi?
- ( ) A) Qora
- ( ) B) Oq
- (x) C) Ko'k (yoki qizil)
- ( ) D) Sariq
*Izoh: Ishlab chiqaruvchilar USB 3.0/3.1 SuperSpeed portlarini an'anaviy qora 2.0 dan ajratish uchun ko'k rangda ishlab chiqaradilar.*

#### Test 2: Windows tizimida ikkinchi monitor yoki proyektor ekran rejimlarini chaqiruvchi tezkor klaviatura yorlig'i qaysi?
- ( ) A) `Win + E`
- (x) B) `Win + P`
- ( ) C) `Alt + Tab`
- ( ) D) `Ctrl + P`
*Izoh: `Win + P` (Project) tashqi monitor va proyektorlar menyusini ochadi.*

#### Test 3: Taqdimot o'tkazishda kompyuter ekranidagi tasvir proyektorda xuddi o'zidek takrorlanishi uchun qaysi rejim tanlanadi?
- ( ) A) PC screen only
- (x) B) Duplicate (Dublyaj)
- ( ) C) Extend (Kengaytirish)
- ( ) D) Second screen only
*Izoh: Duplicate rejimi ikkala ekranda ham bir xil tasvirni namoyish qiladi.*

#### Test 4: Tashqi HDD (qattiq disk)ning tashqi SSD dan asosiy kamchiligi nimada?
- ( ) A) Hajmi juda kichik
- (x) B) Ichida aylanuvchi mexanik qismlar borligi sababli zarbalarga va silkinishga juda sezgir, tezligi pastroq
- ( ) C) USB orqali ulanmaydi
- ( ) D) Narxi juda qimmat
*Izoh: HDD mexanik magnit disk bo'lgani uchun tushib ketsa yoki qattiq silkinsa, o'qish kallagi diskni tirnab yuboradi.*

#### Test 5: USB fleshkani kompyuterdan sug'urishdan oldin nega "Safely Remove" qilish tavsiya etiladi?
- ( ) A) Kompyuter o'chib qolmasligi uchun
- (x) B) Keshdagi fayllar to'liq yozilib ulgurishi va fleshka fayl tizimi buzilmasligi uchun
- ( ) C) Internet tezligi tushib ketmasligi uchun
- ( ) D) Protsessorni sovitish uchun
*Izoh: Xavfsiz ajratish fleshkaga bo'lgan barcha yozish amallarini yakunlab, elektr quvvatini uzadi.*

### 🤔 O'ylantiruvchi Mantiqiy Savollar:
1. Nima uchun "Extend" (Kengaytirish) rejimi bir vaqtning o'zida ham video montaj qiluvchi, ham kod yozuvchi IT mutaxassislari uchun eng qulay hisoblanadi?
2. Agar fleshka hajmi 64 GB bo'lsa-yu, unga 5 GB lik bitta kinoni yozayotganda "Fayl juda katta" degan xatolik bersa, muammo nimada (FAT32 vs NTFS)?
3. Veb-kamera ishlamay qolganda dasturiy ruxsatlarni (Privacy & Security -> Camera) tekshirish nima uchun birinchi o'rinda turadi?

---

## 6. 🏠 Mustaqil Amaliy Uyga Vazifa

### Topshiriq:
1. Kompyuteringizga ulangan tashqi qurilmalar (sichqoncha, klaviatura, fleshka, quloqchin) qaysi USB portlarga (USB 2.0 yoki USB 3.0) ulanganini vizual tekshiring.
2. `Win + P` menyusini ochib, uning barcha 4 ta rejimi vazifasini o'z so'zlaringiz bilan tushuntirib konspekt qiling.
3. Windows Camera dasturini ochib, veb-kamera tasviri va Sound sozlamalaridagi mikrofon faolligi aks etgan skrinshotni oling.

**Topshirish formati:** Bajarilgan topshiriqni `FIO_8-Mavzu_Qurilmalar.docx` nomi bilan platformaga yuklang.

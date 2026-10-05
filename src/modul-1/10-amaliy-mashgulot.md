# 10-Mavzu: 1-Modul Bo'yicha Yakuniy Kompleks Amaliy Mashg'ulot

{% hint style="info" %}
**Dars maqsadi:** 1-Modulda o'rganilgan barcha nazariy va amaliy bilimlarni (texnika xavfsizligi, Windows boshqaruvi, fayllar daraxti, tizim sozlamalari, dasturlar dezinstallyatsiyasi, printer/skaner va profilaktika) yaxlit real amaliy keys doirasida qo'llash va kompleks ko'nikmalarni sinovdan o'tkazish.
{% endhint %}

### 🎯 Kutilayotgan Kompetensiyalar
* **Bilishingiz kerak:**
  * Kompyuter tizimining apparat va dasturiy barqarorligini ta'minlovchi barcha asosiy mezonlar.
  * Yangi ish o'rnini noldan professional darajada sozlash va tayyorlash reglamenti.
  * Hujjat aylanishining to'liq sikli: skanerlash -> tahrirlash -> chop etish.
* **Bajara olishingiz kerak:**
  * Yangi ishchi kompyuterni xavfsizlik va ergonomik talablarga mos tarzda ishga tushirish.
  * Standartlashtirilgan iyerarxik papkalar tizimini yaratish va xavfsizlik zaxirasini (Backup) shakllantirish.
  * Tizim parametrlarini optimallashtirish, kesh fayllarni tozalash va to'liq diagnostika hisobotini tayyorlash.

---

## 🎬 1. Video Dars

{% hint style="info" %}
**Video darslik:** 1-Modul yakuniy amaliy mashg'ulotini bajarish bo'yicha yo'riqnomani quyidagi videoda tomosha qiling:
{% endhint %}

[Iframe/Embed: 10-Mavzu Bo'yicha YouTube Video Dars Havolasi]

---

## 2. 📖 Nazariy Xulosa va Bilimlar Tizimi

1-Modul davomida siz kompyuter texnikasi montajchisi va ilg'or foydalanuvchisi uchun zarur bo'lgan poydevor ko'nikmalarni egalladingiz:

```
[1-MODUL INTEGRATSIYALASHGAN TIZIMI]
  ├── 1. Texnika Xavfsizligi (220V, ESD, Ergonomika)
  ├── 2. Windows Interfeysi (Desktop, Taskbar, Multitasking)
  ├── 3. Fayl Tizimi (Explorer, Ierarxiya, Qidiruv)
  ├── 4. Sozlamalar (Display, Til, Storage Sense)
  ├── 5. Dasturlar Boshqaruvi (Installer, Uninstall, Startup)
  ├── 6. Printer (Drayverlar, Spooler, Duplex chop etish)
  ├── 7. Skaner (300 DPI, Ko'p sahifali PDF, OCR)
  ├── 8. Tashqi Qurilmalar (USB 3.0, Win+P, Proyektor)
  └── 9. Texnik Xizmat (Termopasta, %temp%, cleanmgr, Antivirus)
```

{% hint style="success" %}
**Pro-Tip (Professional IT-Montajchi Qoidasi):**
Yangi kompyuter topshirilayotganda mijozga "tayyor" holat deb faqat Windows o'rnatilgan holat aytilmaydi. Professional montajchi har doim:
1) Barcha rasmiy drayverlarni o'rnatadi;
2) Arxivator (7-Zip) va PDF ko'ruvchi dasturlarni qo'yadi;
3) Storage Sense va Night light ni yoqadi;
4) Startup (Avtoyuklanish) ro'yxatini ortiqcha dasturlardan tozalaydi.
{% endhint %}

---

## 3. 💻 Bosqichma-bosqich Amaliy Mashg'ulot (Lab Task)

Ushbu amaliy imtihonda siz ofis xodimi uchun yangi kompyuterni to'liq ishchi holatga keltirish simulyatsiyasini bajarasiz.

### Kerakli Resurslar:
* Kompyuter (Windows 10/11);
* Matn muharriri (MS Word);
* Virtual printer (Microsoft Print to PDF);
* Yakuniy amaliyot shabloni.

### 📄 Amaliy Mashg'ulot Shabloni:
{% hint style="success" %}
**📄 Rasmiy Amaliy Mashg'ulot va Uy Vazifasi Shabloni (Google Docs (Hujjat)):**
Ushbu darsning barcha bosqichlarini bajarish, natijalar/hisobotlarni kiritish va uy vazifasini topshirish uchun quyidagi rasmiy shablondan foydalaning:
* 🌐 **Onlayn ko'rish va tahrirlash:** [10-Mavzu: 1-Modul Yakuniy Amaliy Mashg'uloti — Shablonni ochish](https://docs.google.com/document/d/12yo3XZFrbDO31VGfPbTnx3nxfE035Hv5CTr6DDFz3rk/edit?usp=sharing)
* 📥 **Shaxsiy Drive-ga nusxalash (Tavsiya etiladi):** [Nusxa yaratish (Make a copy)](https://docs.google.com/document/d/12yo3XZFrbDO31VGfPbTnx3nxfE035Hv5CTr6DDFz3rk/copy)
{% endhint %}

{% embed url="https://docs.google.com/document/d/12yo3XZFrbDO31VGfPbTnx3nxfE035Hv5CTr6DDFz3rk/preview" %}

> *Eslatma: Quyidagi 8 ta topshiriqni ketma-ket bajaring va har birining tasdiqlovchi skrinshotini shablonga joylang.*

### Bajarish Bosqichlari:

1. **1-Topshiriq (Tizim parametrlarini aniqlash):** `Win + R` bosing, `dxdiag` yozing va kompyuteringiz Protsessori, Operativ xotirasi (RAM) hamda Windows versiyasi aks etgan darchani skrinshot qiling.
2. **2-Topshiriq (Fayllar arxitekturasi):** Hujjatlar (Documents) papkasida `Korxona_2026` papkasini oching. Uning ichida `01_Buxgalteriya`, `02_Kadrlar`, `03_Arxiv` papkalarini yarating.
3. **3-Topshiriq (Hujjat tayyorlash):** Word dasturida yangi fayl ochib, "Ish o'rni xavfsizlik qoidalari" mavzusida 5 qatorli matn yozing va uni `01_Buxgalteriya/Xavfsizlik_Qoidalari.docx` nomi bilan saqlang.
4. **4-Topshiriq (Zaxira nusxalash - Backup):** Ushbu fayldan `Ctrl + C` orqali nusxa olib, `03_Arxiv` papkasiga `Xavfsizlik_Qoidalari_Zaxira.docx` nomi bilan joylashtiring (`Ctrl + V`).
5. **5-Topshiriq (Virtual chop etish):** Word hujjatini ochib, `Ctrl + P` bosing, Landscape yo'nalishini tanlang va "Microsoft Print to PDF" orqali `03_Arxiv/Hujjat_Chop_Etish.pdf` fayliga o'giring.
6. **6-Topshiriq (Ekran va qulaylik):** `Win + I -> System -> Display` orqali masshtab (Scale) va ekran o'lchami Recommended holatda ekanini tekshiring, tungi rejimni (Night light) yoqing.
7. **7-Topshiriq (Startup optimallashtirish):** `Ctrl + Shift + Esc` (Task Manager) ochib, Startup apps bo'limidagi barcha ikkinchi darajali dasturlarni "Disabled" holatiga o'tkazing.
8. **8-Topshiriq (Disk tozalash):** `cleanmgr` orqali C: diskidagi vaqtinchalik keraksiz fayllarni tozalang va yakuniy natijani hisobotga ilova qiling.

{% hint style="warning" %}
**Ehtiyot bo'ling:**
Yakuniy topshiriqni bajarishda fayllarni saqlash yo'llari va nomlariga qat'iy e'tibor bering. Noto'g'ri nomlangan yoki boshqa papkaga adashib saqlangan fayllar uchun ball berilmaydi.
{% endhint %}

---

## 4. 🛠 Real Ish Vaziyati va Muammolarni Hal Qilish (Case-Study)

### Muammo:
Kompaniyaga yangi xarid qilingan 10 dona kompyuter keltirildi. Ularni montajchi xodimlarga o'rnatib berdi. Bir hafta o'tgach, barcha xodimlardan quyidagi shikoyatlar tushdi:
1. Kompyuterlar yoqilishi 2–3 daqiqagacha cho'zilib ketmoqda;
2. C: diskida xotira qizil rangga kirib to'lib qolgan;
3. Monitorlarda shriftlar xira va ko'zni toliqtirmoqda;
4. Tarmoq printeriga yuborilgan hujjatlar chop bo'lmay qotib qolmoqda.

### Muammoning Kelib Chiqish Sababi:
Montajchi faqat Windows o'rnatib ketgan, lekin 1-modulda o'rganilgan standart profilaktika va optimallashtirish sozlamalarini (Startup tozalash, Storage Sense yoqish, ClearType/Scale to'g'rilash va Print Spooler sozlash) bajarmagan.

### Bosqichma-bosqich Yechim:
1. **Yuklanishni tezlashtirish:** Task Manager -> Startup apps ro'yxatidan avtomatik qo'shilib olgan barcha keraksiz dasturlarni o'chirish (Disabled qilish).
2. **Xotirani qutqarish:** `cleanmgr` tizim fayllarini tozalashni ishga tushirish hamda **Storage Sense** funksiyasini yoqib qo'yish.
3. **Ekran sifatini oshirish:** Settings -> Display bo'limida Native piksellar o'lchamini (masalan, 1920x1080) to'g'rilash va "Adjust ClearType text" vositasi orqali shriftlarni tekislash.
4. **Printerni tuzatish:** Print Spooler xizmatini tozalash va xodimlar uchun to'g'ri "Default Printer" ni tayinlash.

---

## 5. 📝 Bilimni Tekshirish (Google Forms 1-Modul Yakuniy Testi)

{% hint style="info" %}
**1-Modul Bo'yicha Yakuniy Attestatsiya Testi:** Quyidagi Google Forms testini topshirib, 1-modul bo'yicha olgan umumiy bilimlaringizni sinovdan o'tkazing:
{% endhint %}

[Iframe/Embed: 1-Modul Yakuniy Google Forms Attestatsiya Test Havolasi]

### ✍️ O'z-o'zini Tekshirish Uchun Test Savollari:

#### Test 1: Yangi kompyuterda Windows o'rnatilgandan so'ng birinchi navbatda nima qilinishi shart?
- ( ) A) Kompyuterga darhol 10 ta o'yin o'rnatish
- (x) B) Tizim apparat drayverlarini to'liq o'rnatish va Windows xavfsizlik yangilanishlarini tekshirish
- ( ) C) Monitorni o'chirib qo'yish
- ( ) D) C: diskini formatlash
*Izoh: Drayverlarsiz kompyuterning videokartasi, tarmog'i, ovozi va protsessori to'liq quvvat bilan ishlay olmaydi.*

#### Test 2: Klaviaturadagi `Win + D` yorlig'ining vazifasi nima?
- ( ) A) Dasturni o'chirib yuborish
- (x) B) Barcha ochiq oynalarni minimallashtirib, bir zumda Ish stolini (Desktop) ko'rsatish
- ( ) C) Faylni nusxalash
- ( ) D) Kompyuterni o'chirish
*Izoh: `Win + D` ish stolini tezkor ko'rish va oynalarni boshqarishning eng samarali yorlig'idir.*

#### Test 3: Hujjatlarni skanerlashda optik belgilarni tahrirlanadigan Word matniga aylantiruvchi texnologiya nima?
- ( ) A) RAM
- ( ) B) GPU
- (x) C) OCR (Optical Character Recognition)
- ( ) D) USB
*Izoh: OCR rasm ichidagi matnni taniy oladigan yagona texnologiyadir.*

#### Test 4: Lazerli printerda qog'oz tiqilib qolganda (Paper Jam) qanday yo'l tutiladi?
- ( ) A) Printerni pichoq bilan ochish
- (x) B) Printerni elektrdan uzib, kartrijni chiqarish va qog'ozni uning harakat yo'nalishi bo'ylab ehtiyotkorlik bilan tortib olish
- ( ) C) Qog'ozni teskari tomonga kuch bilan yulqib tortish
- ( ) D) Qog'oz ustiga suv quyish
*Izoh: Kuch bilan teskari tortish printerning nozik rezina roliklari va termoplyonkasini yirtib yuboradi.*

#### Test 5: Protsessor va sovutgich radiatori orasidagi termopastani necha vaqtda almashtirish tavsiya etiladi?
- ( ) A) Har kuni
- ( ) B) Har 10 yilda bir marta
- (x) C) Har 1–2 yilda kamida bir marta
- ( ) D) Umuman almashtirilmaydi
*Izoh: 1–2 yil ichida termopasta quriydi va issiqlik o'tkazuvchanlik xususiyatini yo'qotadi.*

### 🤔 O'ylantiruvchi Mantiqiy Savollar:
1. Nima uchun har qanday tashkilotda har haftalik ma'lumotlar zaxirasi (Backup) olinishi shart?
2. Agar biror xodim kompyuteriga doimiy ravishda fleshka ulab ishlasa, qanday kiberxavfsizlik xatarlari yuzaga kelishi mumkin?
3. Kompyuter foydalanuvchisining ish unumdorligiga to'g'ri sozlangan ish stoli va klaviatura yorliqlari qanday ta'sir ko'rsatadi?

---

## 6. 🏠 Mustaqil Yakuniy Loyiha Vazifasi

### Topshiriq:
Ushbu darsning "Bosqichma-bosqich Amaliy Mashg'ulot" bo'limidagi barcha 8 ta topshiriqni o'z kompyuteringizda to'liq bajaring.
Har bir bosqichning skrinshotlarini tartib bilan joylab, **"1-Modul Yakuniy Amaliy Ish Hisoboti"** nomli mukammal hujjat tayyorlang.

**Topshirish formati:** Tayyorlangan keng qamrovli hisobotni `FIO_10-Mavzu_Yakuniy_Loyiha.docx` nomi bilan platformaga yuklang.

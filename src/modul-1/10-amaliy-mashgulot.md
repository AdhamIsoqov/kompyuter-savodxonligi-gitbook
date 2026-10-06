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

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz — 25 ta Savol, 100 Ball)

{% hint style="info" %}
**📝 Rasmiy Onlayn Test Sinovi (Google Forms — 25 ta savol, 100 ballik baholash):**
Ushbu dars bo'yicha olgan bilimlaringizni sinash uchun quyidagi rasmiy testni topshiring (Har bir to'g'ri javob 4 ball, jami: 100 ball):
* 🔗 **Onlayn Testni Ochish (To'liq Ekranda):** [10-Mavzu: 1-Modul Yakuniy Amaliy Mashg'uloti — Testni Topshirish](https://docs.google.com/forms/d/e/1FAIpQLSdDkkw241_B_mHq5lFRx19QodQDDPl4dthx_bFVzg-nvheuPg/viewform)
* 📊 **Kunlik Natijalar va Ballar Jadvali:** [Google Sheets — Natijalar Jadvali](https://docs.google.com/spreadsheets/d/1gsMkbVASQgQyaZlCmBPnKuHuT59XaarDbsqxoakHOGM/edit)
{% endhint %}

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSdDkkw241_B_mHq5lFRx19QodQDDPl4dthx_bFVzg-nvheuPg/viewform?embedded=true" width="100%" height="800" frameborder="0" marginheight="0" marginwidth="0">Yuklanmoqda…</iframe>

---

### ✍️ 25 ta Rasmiy Test Savollari (Nazorat va O'z-o'zini Tekshirish):

Quyida ushbu dars bo'yicha tuzilgan barcha 25 ta rasmiy test savollari keltirilgan. Har bir savol 4 ta variantdan iborat bo'lib, to'g'ri javob belgilangan:

#### 1-Savol: Yangi yig'ilgan kompyuterni birinchi marta yoqishdan oldin nima tekshiriladi?
- [x] **A) Barcha quvvat kabellari (24-pin, 8-pin CPU, GPU) va kulerlar to'g'ri ulanganligi** *(To'g'ri javob)*
- [ ] B) Internet ulanganligi
- [ ] C) Faqat sichqoncha
- [ ] D) Monitor rangi

#### 2-Savol: Windows 11 o'rnatish uchun yuklanuvchi fleshka (Bootable USB) qaysi dasturda yaratiladi?
- [x] **A) Rufus, Ventoy, Media Creation Tool** *(To'g'ri javob)*
- [ ] B) WinRAR
- [ ] C) Photoshop
- [ ] D) WordPad

#### 3-Savol: Windows 11 o'rnatish uchun qanday apparat talabi mavjud?
- [x] **A) TPM 2.0 va Secure Boot qo'llab-quvvatlashi** *(To'g'ri javob)*
- [ ] B) Faqat HDD disk
- [ ] C) CD-ROM mavjudligi
- [ ] D) Floppi disk

#### 4-Savol: Yuklanuvchi fleshkani ishga tushirish uchun kompyuter yoqilganda qaysi menyu ochiladi?
- [x] **A) Boot Menu (F12, F11, F8)** *(To'g'ri javob)*
- [ ] B) Ctrl + Alt + Del
- [ ] C) Alt + F4
- [ ] D) Shift + Enter

#### 5-Savol: GPT bo'limlar jadvali (Partition style) qaysi BIOS rejimiga mos keladi?
- [x] **A) UEFI** *(To'g'ri javob)*
- [ ] B) Legacy BIOS
- [ ] C) MS-DOS
- [ ] D) FreeDOS

#### 6-Savol: MBR bo'limlar jadvali qaysi cheklovga ega?
- [x] **A) Disk hajmi maksimal 2 TB va ko'pi bilan 4 ta asosiy bo'lim** *(To'g'ri javob)*
- [ ] B) Cheklovi yo'q
- [ ] C) Faqat 100 GB
- [ ] D) Faqat SSD da ishlaydi

#### 7-Savol: Windows o'rnatilgandan so'ng birinchi navbatda qanday dasturiy ta'minot o'rnatiladi?
- [x] **A) Ona plata chipset drayveri va tarmoq/video drayverlari** *(To'g'ri javob)*
- [ ] B) O'yinlar
- [ ] C) Telegram
- [ ] D) Ofis dasturlari

#### 8-Savol: Videokarta drayverini qayerdan yuklab olish eng xavfsiz hisoblanadi?
- [x] **A) Ishlab chiqaruvchining rasmiy saytidan (NVIDIA, AMD, Intel)** *(To'g'ri javob)*
- [ ] B) Noma'lum forumlardan
- [ ] C) Torrentdan
- [ ] D) Telegram kanallardan

#### 9-Savol: Qurilmalar drayveri to'liq o'rnatilganligini qayerdan tekshirish mumkin?
- [x] **A) Device Manager (devmgmt.msc) da sariq belgilar yo'qligini ko'rish orqali** *(To'g'ri javob)*
- [ ] B) Taskbar orqali
- [ ] C) Calculator orqali
- [ ] D) Desktop orqali

#### 10-Savol: Kompyuter yangi yig'ilganda diskni C: va D: qismlarga bo'lish qayerdan bajariladi?
- [x] **A) Windows o'rnatish jarayonida yoki Disk Management orqali** *(To'g'ri javob)*
- [ ] B) Brauzerda
- [ ] C) Notepadda
- [ ] D) BIOS da

#### 11-Savol: Tizim barqarorligini tekshirish uchun qanday stress-test dasturi qo'llaniladi?
- [x] **A) AIDA64 System Stability Test, FurMark, Cinebench** *(To'g'ri javob)*
- [ ] B) Paint
- [ ] C) Chrome
- [ ] D) Solitaire

#### 12-Savol: Videokarta uchun FurMark testi qaysi ko'rsatkichni sinaydi?
- [x] **A) Grafik protsessorning maksimal yuklama ostidagi harorati va quvvat barqarorligini** *(To'g'ri javob)*
- [ ] B) Ovoz balandligini
- [ ] C) Klaviatura tugmalarini
- [ ] D) Wi-Fi tezligini

#### 13-Savol: Tizimni dastlabki sozlashda qaysi foydalanuvchi hisobidan foydalanish tavsiya etiladi?
- [x] **A) Lokal hisob yoki Microsoft akkaunt** *(To'g'ri javob)*
- [ ] B) Faqat Guest (Mehmon)
- [ ] C) Hisobsiz
- [ ] D) Parolsiz ochiq tarmoq

#### 14-Savol: Kompyuter yig'ilganda quvvat manbaining (PSU) qora va yashil simlarini birlashtirish nima qiladi?
- [x] **A) Quvvat blokini ona platasiz alohida ishga tushirish (test qilish) imkonini beradi** *(To'g'ri javob)*
- [ ] B) Portlatadi
- [ ] C) O'chiradi
- [ ] D) Qizdiradi

#### 15-Savol: RAM modullari ikkita bo'lsa, ikki kanalli (Dual-channel) rejim uchun qaysi slotlarga qo'yiladi?
- [x] **A) Odatda 2 va 4-slotlarga (A2 va B2)** *(To'g'ri javob)*
- [ ] B) 1 va 2-slotlarga
- [ ] C) Faqat 1-slotga
- [ ] D) Farqi yo'q

#### 16-Savol: Ninite xizmati nima vazifani bajaradi?
- [x] **A) Bir vaqtning o'zida bir nechta asosiy bepul dasturlarni avtomatik o'rnatish paketi** *(To'g'ri javob)*
- [ ] B) Windowsni buzish
- [ ] C) Kompyuterni o'chirish
- [ ] D) Virus yozish

#### 17-Savol: Yangi kompyuterda fayllarni zaxiralash (System Restore Point) nima uchun kerak?
- [x] **A) Kelajakda tizim ishdan chiqqanda kompyuterni dastlabki soz holatiga qaytarish uchun** *(To'g'ri javob)*
- [ ] B) Diskni to'ldirish uchun
- [ ] C) Tezlikni pasaytirish uchun
- [ ] D) Fayllarni yashirish uchun

#### 18-Savol: Windows Update barcha yangilanishlarni o'rnatgach, nima qilish shart?
- [x] **A) Kompyuterni qayta yuklash (Restart)** *(To'g'ri javob)*
- [ ] B) Kompyuterni o'chirib qo'yish
- [ ] C) Drayverlarni o'chirish
- [ ] D) Hech narsa

#### 19-Savol: Ona platadagi XMP / DOCP profili nima vazifani bajaradi?
- [x] **A) Operativ xotirani (RAM) ishlab chiqaruvchi belgilagan maksimal zavod chastotasida ishlatish** *(To'g'ri javob)*
- [ ] B) Protsessorni sekinlashtirish
- [ ] C) Ekranni o'chirish
- [ ] D) Ventilyatorni to'xtatish

#### 20-Savol: Kompyuter yig'ishda kabel menejmenti (Cable Management) nimasi bilan muhim?
- [x] **A) Korpus ichida havo aylanishini yaxshilaydi va estetik tartib yaratadi** *(To'g'ri javob)*
- [ ] B) Elektrni tejaydi
- [ ] C) Kabelni ko'paytiradi
- [ ] D) Faqat go'zallik uchun

#### 21-Savol: Fleshkadan Windows o'rnatishda 'Disk 0 Unallocated Space' nimani bildiradi?
- [x] **A) Hali bo'linmagan toza disk maydoni** *(To'g'ri javob)*
- [ ] B) Disk to'la ekanligini
- [ ] C) Disk buzilganligini
- [ ] D) Fleshka ekanligini

#### 22-Savol: Tizim sozlamalarida 'Fast Startup' (Tez yuklanish) nimaga asoslanadi?
- [x] **A) Tizim yadrosini gibrid kutish holatida diskka saqlab, keyingi safar tez ochadi** *(To'g'ri javob)*
- [ ] B) Protsessorni qizdiradi
- [ ] C) Xotirani o'chiradi
- [ ] D) Internetni yoqadi

#### 23-Savol: Kompyuter tarmoqqa ulanganini tekshirish uchun konsolda qaysi buyruq yoziladi?
- [x] **A) ping 8.8.8.8** *(To'g'ri javob)*
- [ ] B) exit
- [ ] C) cls
- [ ] D) echo

#### 24-Savol: Kompyuterning IP manzilini bilish uchun qaysi buyruq ishlatiladi?
- [x] **A) ipconfig** *(To'g'ri javob)*
- [ ] B) msinfo
- [ ] C) dxdiag
- [ ] D) tasklist

#### 25-Savol: 1-Modul bo'yicha to'liq tayyorlangan kompyuterning yakuniy holati qanday bo'lishi lozim?
- [x] **A) Drayverlari o'rnatilgan, testlardan o'tgan, harorati me'yorda va asosiy dasturlar bilan ta'minlangan** *(To'g'ri javob)*
- [ ] B) Faqat Windows o'rnatilgan bo'lsa yetarli
- [ ] C) Kabel chalkash bo'lsa ham mayli
- [ ] D) Internet ishlamasa ham bo'ladi

---


## 6. 🏠 Mustaqil Yakuniy Loyiha Vazifasi

### Topshiriq:
Ushbu darsning "Bosqichma-bosqich Amaliy Mashg'ulot" bo'limidagi barcha 8 ta topshiriqni o'z kompyuteringizda to'liq bajaring.
Har bir bosqichning skrinshotlarini tartib bilan joylab, **"1-Modul Yakuniy Amaliy Ish Hisoboti"** nomli mukammal hujjat tayyorlang.

**Topshirish formati:** Tayyorlangan keng qamrovli hisobotni `FIO_10-Mavzu_Yakuniy_Loyiha.docx` nomi bilan platformaga yuklang.

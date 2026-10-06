# 02-Mavzu: Windows Operatsion Tizimi va Ishchi Muhit Bilan Tanishuv

{% hint style="info" %}
**Dars maqsadi:** Windows operatsion tizimining asosiy boshqaruv mexanizmlari, Desktop (Ish stoli), Start menyusi, Taskbar (Vazifalar paneli), oynalar bilan ishlash arxitekturasi va ko'p vazifalilik (Multitasking) rejimini hamda klaviatura yorliqlarini professional darajada o'zlashtirish.
{% endhint %}

### 🎯 Kutilayotgan Kompetensiyalar
* **Bilishingiz kerak:**
  * Operatsion tizimning vazifasi: apparat va dasturiy ta'minot o'rtasidagi ko'prik.
  * Obyektlar iyerarxiyasi: haqiqiy fayl, papka va yorliq (Shortcut) o'rtasidagi farqlar.
  * Windows 10/11 interfeysi tuzilishi: Desktop, Start, Taskbar, System Tray va Action Center.
* **Bajara olishingiz kerak:**
  * Oynalarni samarali boshqarish: Snap Layouts (ekranni 2 yoki 4 qismga bo'lib yonma-yon joylashtirish).
  * Multitasking rejimida `Alt + Tab` va `Win + Tab` (Task View) orqali tezkor almashish.
  * Kerakli dasturlar uchun tezkor yorliqlar (Shortcuts) yaratish va Taskbar'ga biriktirish (Pin qilish).

---

## 🎬 1. Video Dars

{% hint style="info" %}
**Video ko'rsatma:** Darsni o'zlashtirishdan oldin Windows interfeysi va tezkor boshqaruv bo'yicha video qo'llanmani tomosha qiling:
{% endhint %}

[Iframe/Embed: 02-Mavzu Bo'yicha Video Dars (YouTube / Google Drive Havolasi)]

---

## 2. 📖 Chuqurlashtirilgan Nazariy Ma'ruza

### 2.1. Desktop (Ish Stoli) va Obyektlar Turlari

Desktop — Windows operatsion tizimi yuklangandan so'ng foydalanuvchi qarshisida ochiladigan asosiy grafik ish maydonidir. Kompyuter bilan barcha amallar va dasturlarni ishga tushirish aynan shu yerdan boshlanadi.

| Obyekt Turi | Belgisi / Xususiyati | Asosiy Vazifasi | O'chirilganda nima bo'ladi? |
| :--- | :--- | :--- | :--- |
| **Haqiqiy Fayl** | `.docx`, `.xlsx`, `.jpg` va h.k. | Ma'lumotlarni o'zida saqlaydi | Fayl savatga (Recycle Bin) tushadi, ichidagi ma'lumot o'chadi |
| **Papka (Folder)** | Odatda sariq rangli jild ko'rinishida | Fayllar va boshqa papkalarni tartiblash konteyneri | Papka va uning ichidagi barcha fayllar savatga tushadi |
| **Yorliq (Shortcut)** | Pastki chap burchagida kichik ko'k strelka belgisi bor | Asl dastur yoki faylga ishora qiluvchi yo'l ko'rsatkich | Faqat yo'l ko'rsatkich o'chadi, asl dastur yoki fayl saqlanib qoladi |

{% hint style="success" %}
**Pro-Tip (Yorliq yaratish):**
Istalgan dastur yoki faylni ish stoliga yorliq qilish uchun obyekt ustiga sichqonchaning o'ng tugmasini bosing:
* Windows 10 da: **Отправить (Send to) -> Рабочий стол (создать ярлык)**.
* Windows 11 da: **Show more options -> Send to -> Desktop (create shortcut)**.
{% endhint %}

### 2.2. Start Menyusi va Taskbar (Vazifalar Paneli)

* **Start Menyusi (Boshqaruv markazi):** Kompyuterga o'rnatilgan barcha dasturlar katalogi, qidiruv (Search) tizimi, foydalanuvchi profili va quvvat boshqaruvi (O'chirish, qayta yoqish, uyqu rejimi) shu yerda joylashgan.
* **Taskbar (Vazifalar paneli):** Ekranning pastki qismida joylashgan panel. U 3 qismdan iborat:
  1. *Chap tomon (Windows 10) / Markaz (Windows 11):* Start tugmasi, qidiruv va doimiy biriktirilgan (Pinned) dasturlar.
  2. *O'rta qism:* Ayni damda ochiq turgan faol oynalar ro'yxati.
  3. *O'ng tomon (System Tray):* Internet ulanishi, ovoz balandligi, til paneli, batareya holati, sana/vaqt va bildirishnomalar markazi.

### 2.3. Oynalar Boshqaruvi va Ko'p Vazifalilik (Multitasking)

Windows tizimida har bir dastur o'z oynasida ishlaydi. Har bir oynaning yuqori o'ng burchagida 3 ta standart tugma mavjud:
1. `—` (**Minimize**): Oynani yopmasdan Taskbarga tushirib qo'yish.
2. `🗖` / `🗗` (**Maximize / Restore**): Oynani butun ekranga yoyish yoki avvalgi o'lchamiga qaytarish.
3. `✕` (**Close**): Dastur oynasini to'liq yopish (o'zgarishlar saqlanmagan bo'lsa, tizim ogohlantiradi).

```
+-------------------------------------------------------------------+
|  [Dastur Nomi]                                      [-]  [口]  [X]|
+-------------------------------------------------------------------+
|                                                                   |
|   1-Oyna: Microsoft Word                 2-Oyna: Internet Brauzer |
|   (Matn yozish va tahrirlash)            (Ma'lumot qidirish)      |
|                                                                   |
|   [ Win + Chap Strelka ]                 [ Win + O'ng Strelka ]   |
+-------------------------------------------------------------------+
| [Start] [Word] [Browser]                                [10:00 AM]|
+-------------------------------------------------------------------+
```

### ⌨️ Mavzuning Eng Muhim Tezkor Klaviatura Yorliqlari:

| Yorliq | Funksiyasi | Nima uchun muhim? |
| :--- | :--- | :--- |
| `Win + D` | Barcha ochiq oynalarni yashirib, Ish stolini (Desktop) ko'rsatish | Ekrandagi oynalar ko'payib ketganda bir zumda ish stoliga o'tish |
| `Alt + Tab` | Ochiq dasturlar va oynalar orasida tezkor almashish | Sichqonchasiz multitasking rejimida ishlash |
| `Win + E` | Fayl boshqaruvchisini (File Explorer) ochish | Kerakli papka va disklarga darhol kirish |
| `Win + Chap / O'ng` | Faol oynani ekranning chap yoki o'ng yarmiga mahkamlash (Snap) | Bir vaqtda ikkita dasturni yonma-yon solishtirib ishlash |
| `Win + L` | Kompyuterni bir soniyada bloklash (Lock) | Ish joyidan ketayotganda begona shaxslardan xavfsizlanish |
| `Alt + F4` | Faol oynani darhol yopish (ish stoli ochiq bo'lsa, o'chirish menyusi) | Ishni tez yakunlash |

---

## 3. 💻 Bosqichma-bosqich Amaliy Mashg'ulot (Lab Task)

Ushbu amaliy topshiriqda siz Windows tizimida ko'p vazifali ish muhitini to'g'ri tashkil qilishni va oynalarni boshqarishni mashq qilasiz.

### Kerakli Resurslar:
* Windows 10 yoki Windows 11 o'rnatilgan kompyuter;
* Matn muharriri (WordPad yoki MS Word);
* Internet brauzeri (Google Chrome yoki Edge).

### 📄 Amaliy Mashq Shabloni (Google Docs / MS Office):
{% hint style="success" %}
**📄 Rasmiy Amaliy Mashg'ulot va Uy Vazifasi Shabloni (Google Docs (Hujjat)):**
Ushbu darsning barcha bosqichlarini bajarish, natijalar/hisobotlarni kiritish va uy vazifasini topshirish uchun quyidagi rasmiy shablondan foydalaning:
* 🌐 **Onlayn ko'rish va tahrirlash:** [02-Mavzu: Kompyuter Bilan Tanishuv va Arxitektura — Shablonni ochish](https://docs.google.com/document/d/1NPICLKBxLSTfZ7K0BTVTB_BkTIuYj2_b87wwip__bRc/edit?usp=sharing)
* 📥 **Shaxsiy Drive-ga nusxalash (Tavsiya etiladi):** [Nusxa yaratish (Make a copy)](https://docs.google.com/document/d/1NPICLKBxLSTfZ7K0BTVTB_BkTIuYj2_b87wwip__bRc/copy)
{% endhint %}

{% embed url="https://docs.google.com/document/d/1NPICLKBxLSTfZ7K0BTVTB_BkTIuYj2_b87wwip__bRc/preview" %}

> *Eslatma: Shablondan nusxa oling va quyidagi qadamlarni bajarish davomida ekranni suratga olib (skrinshot) hisobotga joylang.*

### Bajarish Bosqichlari:

1. **1-Qadam:** Klaviaturada `Win + E` tugmalarini bosib File Explorer oynasini oching.
2. **2-Qadam:** Brauzeringizni (Chrome yoki Edge) ishga tushiring.
3. **3-Qadam:** Istalgan matn muharririni (masalan, Word yoki Notepad) oching.
4. **4-Qadam (Snap funksiyasi):** Matn muharriri oynasi faol bo'lgan holda `Win + Chap Strelka` tugmasini bosing (oyna ekranning chap yarmiga tekislanadi).
5. **5-Qadam:** O'ng tomonda paydo bo'lgan oynalar ro'yxatidan Brauzer oynasini tanlang (oyna ekranning o'ng yarmiga tekislanadi).
6. **6-Qadam (Multitasking almashinuvi):** `Alt + Tab` tugmalarini bosing va qo'lingizni `Alt` tugmasidan uzmagan holda `Tab` ni bosib oynalar bo'ylab harakatlaning. Kerakli oyna ustida to'xtang.
7. **7-Qadam (Taskbar Pin):** Start menyusini oching, kalkulyator (`Calculator`) dasturini toping, ustiga sichqonchaning o'ng tugmasini bosib **Pin to taskbar** (Закрепить на панели задач) buyrug'ini tanlang.
8. **8-Qadam (Tezkor tozalash):** Klaviaturada `Win + D` tugmasini bosing — barcha oynalar minimallashtirilib, Ish stoli ochiladi. Qayta `Win + D` bosib oynalarni joyiga qaytaring.

{% hint style="warning" %}
**Ehtiyot bo'ling:**
Ish stolidagi tartibsizlik (yuzlab fayllar va o'rnatish paketlarining Desktop'da saqlanishi) kompyuter yuklanish tezligini sekinlashtiradi. Fayllarni doimo maxsus papkalarga (`Hujjatlar`, `Rasmlar` yoki alohida D: diskka) saqlang!
{% endhint %}

---

## 4. 🛠 Real Ish Vaziyati va Muammolarni Hal Qilish (Case-Study)

### Muammo:
Foydalanuvchi bir nechta og'ir dasturlar bilan ishlayotgan paytda to'satdan pastki Taskbar (Vazifalar paneli) yo'qolib qoldi yoki qotib qolib, sichqoncha bosilishiga javob bermay qo'ydi. Start tugmasi ham ochilmayapti. Foydalanuvchi kompyuterni tugmasidan majburiy o'chirishga (Hard reset) tayyorlanmoqda, ammo saqlanmagan muhim hujjatlar bor.

### Muammoning Kelib Chiqish Sababi:
Windows tizimining asosiy grafik qobig'i bo'lgan `explorer.exe` (Windows Explorer) jarayoni vaqtinchalik xotira to'lib qolishi yoki tizim kutilmagan xatoga uchrashi sababli to'xtab qolgan.

### Bosqichma-bosqich Yechim:
Kompyuterni majburiy o'chirish shart emas! Jarayonni tezkor qayta ishga tushirish yetarli:
1. Klaviaturada to'g'ridan-to'g'ri `Ctrl + Shift + Esc` tugmalarini bosing (Vazifalar boshqaruvchisi — Task Manager ochiladi).
2. Dasturlar ro'yxatidan **Windows Explorer (Проводник)** ni toping.
3. Uning ustiga sichqonchaning o'ng tugmasini bosing va **Restart (Перезапустить)** buyrug'ini tanlang.
4. Agar ro'yxatda topilmasa, yuqori menyudan **Run new task (Запустить новую задачу)** tugmasini bosing, qatorga `explorer.exe` deb yozing va Enter bosing.
5. Taskbar va Ish stoli 2 soniyada qayta tiklanadi, barcha ochilgan hujjatlar o'z o'rnida saqlanib qoladi!

---

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz — 25 ta Savol, 100 Ball)

{% hint style="info" %}
**📝 Rasmiy Onlayn Test Sinovi (Google Forms — 25 ta savol, 100 ballik baholash):**
Ushbu dars bo'yicha olgan bilimlaringizni sinash uchun quyidagi rasmiy testni topshiring (Har bir to'g'ri javob 4 ball, jami: 100 ball):
* 🔗 **Onlayn Testni Ochish (To'liq Ekranda):** [02-Mavzu: Kompyuter Bilan Tanishuv va Arxitektura — Testni Topshirish](https://docs.google.com/forms/d/e/1FAIpQLSdGnfgZuyJ28Q1AX7s9Wbf6wsnr6XbJSzfAcOZ4Nr-1qdkOoQ/viewform)
* 📊 **Kunlik Natijalar va Ballar Jadvali:** [Google Sheets — Natijalar Jadvali](https://docs.google.com/spreadsheets/d/1CJKc9BWxdpEkuw9QFsNxGL1Kcqzn7vMS53cAKvCeoRY/edit)
{% endhint %}

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSdGnfgZuyJ28Q1AX7s9Wbf6wsnr6XbJSzfAcOZ4Nr-1qdkOoQ/viewform?embedded=true" width="100%" height="800" frameborder="0" marginheight="0" marginwidth="0">Yuklanmoqda…</iframe>

---

### ✍️ 25 ta Rasmiy Test Savollari (Nazorat va O'z-o'zini Tekshirish):

Quyida ushbu dars bo'yicha tuzilgan barcha 25 ta rasmiy test savollari keltirilgan. Har bir savol 4 ta variantdan iborat bo'lib, to'g'ri javob belgilangan:

#### 1-Savol: Kompyuterning asosiy 'miyasi' hisoblangan qurilma qaysi?
- [x] **A) Protsessor (CPU)** *(To'g'ri javob)*
- [ ] B) Operativ xotira (RAM)
- [ ] C) Qattiq disk (HDD)
- [ ] D) Videokarta (GPU)

#### 2-Savol: CPU ning kesh xotirasi (Cache) qaysi pog'onalarga bo'linadi?
- [x] **A) L1, L2, L3** *(To'g'ri javob)*
- [ ] B) A, B, C
- [ ] C) Primary, Secondary
- [ ] D) Flash va Dynamic

#### 3-Savol: Kompyuter o'chirilganda undagi barcha ma'lumotlar o'chib ketadigan xotira qaysi?
- [x] **A) RAM (Operativ xotira)** *(To'g'ri javob)*
- [ ] B) ROM (Doimiy xotira)
- [ ] C) SSD
- [ ] D) HDD

#### 4-Savol: NVMe M.2 SSD disklarining odatiy SATA SSD dan asosiy afzalligi nima?
- [x] **A) O'qish va yozish tezligi ancha yuqori (PCIe shinasi orqali)** *(To'g'ri javob)*
- [ ] B) Hajmi kichikligi va arzonligi
- [ ] C) Elektr toki sarflamasligi
- [ ] D) Mexanik aylanuvchi diski borligi

#### 5-Savol: Ona plata (Motherboard) ning asosiy vazifasi nima?
- [x] **A) Barcha apparat qismlarini o'zaro bog'lash va axborot almashinuvini ta'minlash** *(To'g'ri javob)*
- [ ] B) Faqat quvvat yetkazish
- [ ] C) Tasvirni monitorda ko'rsatish
- [ ] D) Dasturlarni saqlash

#### 6-Savol: 80 PLUS sertifikati quvvat blokining (PSU) qaysi ko'rsatkichini bildiradi?
- [x] **A) Foydali ish koeffitsiyenti (kamida 80% energiya samaradorligi)** *(To'g'ri javob)*
- [ ] B) Vatt miqdori 800W ekanligini
- [ ] C) Kafolat muddati 80 oyni
- [ ] D) Kabel uzunligini

#### 7-Savol: Grafik protsessorning (GPU) asosiy vazifasi nima?
- [x] **A) Grafik va videolarni qayta ishlash, tasvirni ekranga uzatish** *(To'g'ri javob)*
- [ ] B) Internetni ulash
- [ ] C) Fayllarni arxivlash
- [ ] D) Tovush chiqarish

#### 8-Savol: BIOS/UEFI dasturi kompyuterning qaysi qismida saqlanadi?
- [x] **A) Ona platadagi ROM (Doimiy xotira) mikrosxemasida** *(To'g'ri javob)*
- [ ] B) Qattiq diskda
- [ ] C) RAM da
- [ ] D) Videokartada

#### 9-Savol: Windows tizimida apparat ta'minoti haqida to'liq axborot beruvchi dastur qaysi?
- [x] **A) dxdiag va msinfo32** *(To'g'ri javob)*
- [ ] B) notepad
- [ ] C) calc
- [ ] D) paint

#### 10-Savol: Protsessor chastotasi qaysi birlikda o'lchanadi?
- [x] **A) Gigagers (GHz)** *(To'g'ri javob)*
- [ ] B) Gigabayt (GB)
- [ ] C) Vatt (W)
- [ ] D) Piksel (px)

#### 11-Savol: DDR5 xotirasining DDR4 dan asosiy farqi nima?
- [x] **A) Yuqori o'tkazuvchanlik tezligi va quvvat tejamkorligi** *(To'g'ri javob)*
- [ ] B) Faqat noutbuklarga tushishi
- [ ] C) Hajmi kichikligi
- [ ] D) Narxi arzonligi

#### 12-Savol: Kompyuterning termopastasi nima vazifani bajaradi?
- [x] **A) Protsessor va kuler orasidagi issiqlik o'tkazuvchanligini yaxshilaydi** *(To'g'ri javob)*
- [ ] B) Qismlarni bir-biriga yopishtiradi
- [ ] C) Elektr tokini o'tkazadi
- [ ] D) Changdan himoya qiladi

#### 13-Savol: Zamonaviy shaxsiy kompyuterlar uchun eng ko'p tarqalgan form-faktor qaysi?
- [x] **A) ATX / Micro-ATX** *(To'g'ri javob)*
- [ ] B) BTX
- [ ] C) Mini-PC
- [ ] D) Server Blade

#### 14-Savol: Protsessorning ko'p yadroliligi (Multi-core) nimaga xizmat qiladi?
- [x] **A) Bir vaqtning o'zida bir nechta vazifalarni parallel bajarishga** *(To'g'ri javob)*
- [ ] B) Faqat bitta dasturni tezroq ochishga
- [ ] C) Elektrni ko'p sarflashga
- [ ] D) Xotira hajmini oshirishga

#### 15-Savol: Doimiy xotira qurilmasi (HDD) qanday mexanizmga asoslangan?
- [x] **A) Magnit disk va mexanik o'quvchi boshcha** *(To'g'ri javob)*
- [ ] B) Flesh yarimo'tkazgich mikrosxema
- [ ] C) Optik lazer nuri
- [ ] D) Kondensatorlar to'plami

#### 16-Savol: Vazifalar boshqaruvchisini (Task Manager) ochish uchun qaysi klavishlar bosiladi?
- [x] **A) Ctrl + Shift + Esc** *(To'g'ri javob)*
- [ ] B) Ctrl + Alt + F4
- [ ] C) Win + R
- [ ] D) Alt + Shift

#### 17-Savol: Chipset nima?
- [x] **A) Ona platadagi CPU, xotira va tashqi qurilmalar aloqasini boshqaruvchi mikrosxemalar to'plami** *(To'g'ri javob)*
- [ ] B) Kuler ventilyatori
- [ ] C) Monitor kabeli
- [ ] D) Protsessor qopqog'i

#### 18-Savol: PCIe (PCI Express) slotlariga qaysi qurilmalar ulanadi?
- [x] **A) Videokarta, NVMe adapter va tarmoq kartalari** *(To'g'ri javob)*
- [ ] B) Faqat sichqoncha
- [ ] C) Monitor kabeli
- [ ] D) Quvvat bloki

#### 19-Savol: 1 Gigabayt necha Megabaytga teng?
- [x] **A) 1024 MB** *(To'g'ri javob)*
- [ ] B) 1000 MB
- [ ] C) 512 MB
- [ ] D) 2048 MB

#### 20-Savol: Tizim bloki sovutish tizimining qanday turlari mavjud?
- [x] **A) Havo (Air) va Suyuqlik (Water/Liquid) sovutish** *(To'g'ri javob)*
- [ ] B) Quyoshli va shamolli
- [ ] C) Faqat muzli
- [ ] D) Statik va passivsiz

#### 21-Savol: Integratsiyalashgan (Integrated) videokarta qayerda joylashgan bo'ladi?
- [x] **A) Protsessor yoki ona plata mikrosxemasi ichida** *(To'g'ri javob)*
- [ ] B) Alohida kengaytma platasida
- [ ] C) Monitorda
- [ ] D) Quvvat blokida

#### 22-Savol: SATA 3 interfeysining maksimal nazariy o'tkazish tezligi qancha?
- [x] **A) 6 Gb/s (taxminan 550-600 MB/s)** *(To'g'ri javob)*
- [ ] B) 1 Gb/s
- [ ] C) 100 MB/s
- [ ] D) 10 Gb/s

#### 23-Savol: Kompyuter quvvat tugmasi bosilganda birinchi bo'lib qaysi jarayon ishga tushadi?
- [x] **A) POST (Power-On Self-Test) tekshiruvi** *(To'g'ri javob)*
- [ ] B) Windows yuklanishi
- [ ] C) Brauzer ochilishi
- [ ] D) Antivirus tekshiruvi

#### 24-Savol: Qaysi xotira tezligi jihatidan eng yuqori hisoblanadi?
- [x] **A) Protsessor registrlari va L1 kesh** *(To'g'ri javob)*
- [ ] B) RAM
- [ ] C) NVMe SSD
- [ ] D) SATA HDD

#### 25-Savol: Kompyuterda 'Run' (Bajarish) darchasini chaqirish qaysi tugma orqali amalga oshiriladi?
- [x] **A) Win + R** *(To'g'ri javob)*
- [ ] B) Win + P
- [ ] C) Win + X
- [ ] D) Ctrl + R

---


## 6. 🏠 Mustaqil Amaliy Uyga Vazifa

### Topshiriq:
1. Ish stolingizda yangi `Mening_Ishim` nomli papka yarating.
2. Sevimli brauzeringiz va matn muharriringiz uchun Ish stolida yorliq (Shortcut) hosil qiling.
3. Klaviaturadagi `Win + Strelka` yordamida ekranni ikkiga bo'lib, chap tomonda brauzer, o'ng tomonda matn muharririni joylashtiring.
4. Ekranni skrinshot qiling (`Win + Shift + S` yoki `PrtScn` tugmasi bilan).
5. Skrinshotni va yuqoridagi 3 ta mantiqiy savol javobini bitta hujjatga jamlang.

**Topshirish formati:** Tayyorlangan hisobotni `FIO_2-Mavzu_Windows.docx` nomi bilan platformaga yuklang.

# 02-Mavzu: Windows Operatsion Tizimi va Ishchi Muhit Bilan Tanishuv

Birinchi darsimizda biz kompyuter xonasida xavfsiz ishlash qoidalarini o'rgandik — elektr xavfsizligi, ergonomika va raqamli gigiyena talablarini puxta o'zlashtirib oldik. Endi esa xavfsiz muhitimizda o'tirgancha, kompyuterning "miyasi" bo'lgan **operatsion tizim** bilan yaqindan tanishamiz.

Kompyuterni yoqdingiz va ekranda ish stoli (Desktop) paydo bo'ldi. Xo'sh, bu qanday sodir bo'ladi? Kim fayllarni boshqaradi, dasturlarni ishga tushiradi va tarmoqqa ulanadi? Bularning barchasini **Windows Operatsion Tizimi** amalga oshiradi. Bu tizimni bilmasdan turib, kompyuterni professional darajada boshqarib bo'lmaydi.

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

## 🎬 1. Video Dars

{% hint style="info" %}
**Video ko'rsatma:** Darsni o'zlashtirishdan oldin Windows interfeysi va tezkor boshqaruv bo'yicha video qo'llanmani tomosha qiling:
{% endhint %}

[Iframe/Embed: 02-Mavzu Bo'yicha Video Dars (YouTube / Google Drive Havolasi)]

## 2. 📖 Chuqurlashtirilgan Nazariy Ma'ruza

### 2.0. Operatsion Tizim Nima va Nima Uchun Kerak?

Tasavvur qiling: kompyuter — bu kuchli, ammo "til bilmaydigan" mexanizm. Protsessor, xotira, disk va klaviatura o'zlari bir-biri bilan muloqot qila olmaydi. **Operatsion tizim (OS)** — bu barcha qurilmalarni bir tizimga birlashtiruvchi, siz bilan kompyuter o'rtasida "tarjimon" vazifasini bajaruvchi maxsus dasturiy muhitdir.

```
[Siz (Foydalanuvchi)]
        ↕  (grafik interfeys orqali)
[Windows Operatsion Tizimi]
   ↕ Drayverllar orqali      ↕ Fayl tizimi orqali
[Apparat qurilmalari]    [Disk va fayllar]
  (Protsessor, RAM,       (Hujjatlar, Rasmlar,
   Klaviatura, Monitor)    Dasturlar)
```

Windows dunyodagi eng ommabop operatsion tizim bo'lib, bugungi kunda barcha shaxsiy kompyuterlarning 70% dan ortiq qismida ishlatiladi. Windows XP, Vista, 7, 8, 10 va hozirgi Windows 11 — bularning barchasi Microsoft korporatsiyasi tomonidan ishlab chiqilgan bir oilaning avlodlaridir.

> **Muhim farq:** *Windows 10* va *Windows 11* — ikkalasi ham Microsoft Windows oilasiga mansub. Windows 11 yangi, chiroyliroq dizayn va yaxshilangan xavfsizlik tizimiga ega. Ammo ish prinsipi bir xil — siz ikkala tizimda ham bir xil ko'nikmalar bilan ishlaysiz.

### 2.1. Desktop (Ish Stoli) va Obyektlar Turlari

Desktop — Windows operatsion tizimi yuklangandan so'ng foydalanuvchi qarshisida ochiladigan asosiy grafik ish maydonidir. Kompyuter bilan barcha amallar va dasturlarni ishga tushirish aynan shu yerdan boshlanadi.

Ish stolida turli xil obyektlar joylashishi mumkin. Ularning farqlarini bilmaslik juda ko'p muammolarga olib keladi — masalan, "yorliqni o'chirdim, dastur ham yo'qoldi" degan noto'g'ri tushuncha:

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

{% hint style="info" %}
**Windows 11 yangiligi:** Windows 10 da Start tugmasi chapda, Windows 11 da markazda joylashgan. Buni eski usulga qaytarish uchun: `Taskbar Settings -> Taskbar behaviors -> Taskbar alignment -> Left` deb o'rnating.
{% endhint %}

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

**Snap Layouts (Windows 11):** Maximize tugmasi ustiga sichqonchani olib borsangiz, ekranni 2, 3 yoki 4 qismga bo'lishning tayyor shablonlari paydo bo'ladi. Bu ayniqsa katta monitorlarda samaradorlikni sezilarli oshiradi. Windows 10 da esa `Win + Strelka` tugmalari orqali xuddi shunday natijaga erishish mumkin.

### ⌨️ Mavzuning Eng Muhim Tezkor Klaviatura Yorliqlari:

| Yorliq | Funksiyasi | Nima uchun muhim? |
| :--- | :--- | :--- |
| `Win + D` | Barcha ochiq oynalarni yashirib, Ish stolini (Desktop) ko'rsatish | Ekrandagi oynalar ko'payib ketganda bir zumda ish stoliga o'tish |
| `Alt + Tab` | Ochiq dasturlar va oynalar orasida tezkor almashish | Sichqonchasiz multitasking rejimida ishlash |
| `Win + E` | Fayl boshqaruvchisini (File Explorer) ochish | Kerakli papka va disklarga darhol kirish |
| `Win + Chap / O'ng` | Faol oynani ekranning chap yoki o'ng yarmiga mahkamlash (Snap) | Bir vaqtda ikkita dasturni yonma-yon solishtirib ishlash |
| `Win + L` | Kompyuterni bir soniyada bloklash (Lock) | Ish joyidan ketayotganda begona shaxslardan xavfsizlanish |
| `Alt + F4` | Faol oynani darhol yopish (ish stoli ochiq bo'lsa, o'chirish menyusi) | Ishni tez yakunlash |

> **Oldingi darsdan eslatma:** 1-darsimizda `Win + L` klaviatura yorlig'ini xavfsizlik qoidalarida o'rgangan edik — ish joyidan ketganda kompyuterni bloklash. Ko'ryapsizmi, bilimlar bir-biriga bog'lanib boradi!

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
* 🌐 **Onlayn ko'rish va tahrirlash:** <a href="https://docs.google.com/document/d/1NPICLKBxLSTfZ7K0BTVTB_BkTIuYj2_b87wwip__bRc/edit?usp=sharing" target="_blank" rel="noopener noreferrer">02-Mavzu: Kompyuter Bilan Tanishuv va Arxitektura — Shablonni ochish</a>
* 📥 **Shaxsiy Drive-ga nusxalash (Tavsiya etiladi):** <a href="https://docs.google.com/document/d/1NPICLKBxLSTfZ7K0BTVTB_BkTIuYj2_b87wwip__bRc/copy" target="_blank" rel="noopener noreferrer">Nusxa yaratish (Make a copy)</a>
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

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz)

{% hint style="info" %}
**📝 Rasmiy Onlayn Test Sinovi (Google Forms — 15 ta saralangan savol, 100 ballik baholash):**
Ushbu dars bo'yicha olgan bilimlaringizni sinash uchun quyidagi rasmiy testni topshiring (15 ta saralangan test savoli, jami: 100 ball):
* 🔗 **Onlayn Testni Ochish (To'liq Ekranda):** <a href="https://docs.google.com/forms/d/e/1FAIpQLSdGnfgZuyJ28Q1AX7s9Wbf6wsnr6XbJSzfAcOZ4Nr-1qdkOoQ/viewform" target="_blank" rel="noopener noreferrer">02-Mavzu: Kompyuter Bilan Tanishuv va Arxitektura — Testni Topshirish</a>
* 📊 **Kunlik Natijalar va Ballar Jadvali:** <a href="https://docs.google.com/spreadsheets/d/1CJKc9BWxdpEkuw9QFsNxGL1Kcqzn7vMS53cAKvCeoRY/edit" target="_blank" rel="noopener noreferrer">Google Sheets — Natijalar Jadvali</a>
{% endhint %}

{% embed url="https://docs.google.com/forms/d/e/1FAIpQLSdGnfgZuyJ28Q1AX7s9Wbf6wsnr6XbJSzfAcOZ4Nr-1qdkOoQ/viewform" %}

## 6. 🏠 Mustaqil Amaliy Uyga Vazifa

### Topshiriq:
1. Ish stolingizda yangi `Mening_Ishim` nomli papka yarating.
2. Sevimli brauzeringiz va matn muharriringiz uchun Ish stolida yorliq (Shortcut) hosil qiling.
3. Klaviaturadagi `Win + Strelka` yordamida ekranni ikkiga bo'lib, chap tomonda brauzer, o'ng tomonda matn muharririni joylashtiring.
4. Ekranni skrinshot qiling (`Win + Shift + S` yoki `PrtScn` tugmasi bilan).
5. Skrinshotni va yuqoridagi 3 ta mantiqiy savol javobini bitta hujjatga jamlang.

**Topshirish formati:** Tayyorlangan hisobotni `FIO_2-Mavzu_Windows.docx` nomi bilan platformaga yuklang.

---

> **Keyingi dars anonsi:**
> *Keyingi 3-darsimizda kompyuterdagi fayllar va papkalar bilan professional ishlashni o'rganamiz: fayl tizimi tuzilishi, Copy va Cut amallarining farqlari, savatdan faylni tiklash va wildcard yordamida kengaytirilgan qidiruv usullari!*

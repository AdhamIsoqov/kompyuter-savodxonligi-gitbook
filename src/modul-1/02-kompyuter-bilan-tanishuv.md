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
[Iframe/Embed: 02-Mavzu Amaliy Mashg'ulot Shabloni - Google Docs / MS Word Online]

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

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz)

{% hint style="info" %}
**Onlayn Test:** 2-Mavzu bo'yicha olgan bilimlaringizni sinab ko'rish uchun quyidagi Google Forms testini topshiring:
{% endhint %}

[Iframe/Embed: 02-Mavzu Google Forms Rasmiy Test Havolasi]

### ✍️ O'z-o'zini Tekshirish Uchun Test Savollari:

#### Test 1: Desktop'dagi yorliq (Shortcut) faylidan uning nima belgisi orqali ajratib olinadi?
- ( ) A) Yorliq nomi har doim qizil rangda bo'ladi
- (x) B) Yorliq ikonkasining pastki chap burchagida kichik strelka belgisi bo'ladi
- ( ) C) Yorliq faylining hajmi har doim 1 GB dan katta bo'ladi
- ( ) D) Yorliqni o'chirib bo'lmaydi
*Izoh: Yorliq bu asl faylga ishora qiluvchi yo'l ko'rsatkich bo'lib, uning belgisida burilgan kichik strelka bo'ladi.*

#### Test 2: Barcha ochiq oynalarni bir zumda minimallashtirib, Ish stolini ochish tugmasi qaysi?
- ( ) A) `Ctrl + Alt + Delete`
- (x) B) `Win + D`
- ( ) C) `Shift + Esc`
- ( ) D) `Alt + F4`
*Izoh: `Win + D` (Desktop) barcha ochiq oynalarni yashiradi yoki qayta tiklaydi.*

#### Test 3: Agar Desktop'dagi yorliq (Shortcut) o'chirib tashlansa, asosiy dastur nima bo'ladi?
- ( ) A) Asosiy dastur ham to'liq o'chib ketadi
- (x) B) Asosiy dastur saqlanib qoladi, faqat unga yo'naltiruvchi havola o'chadi
- ( ) C) Windows operatsion tizimi ishdan chiqadi
- ( ) D) Kompyuter qayta ishga tushadi
*Izoh: Yorliq faqat havola hisoblanadi. Uni o'chirish asl dastur yoki faylga ta'sir qilmaydi.*

#### Test 4: Ochiq dasturlar va oynalar orasida sichqonchasiz tezkor almashish uchun qaysi tugmalar ishlatiladi?
- ( ) A) `Ctrl + S`
- ( ) B) `Win + L`
- (x) C) `Alt + Tab`
- ( ) D) `Ctrl + P`
*Izoh: `Alt + Tab` multitasking jarayonida eng ko'p qo'llaniladigan oynalar almashish yorlig'idir.*

#### Test 5: Ekranning pastki o'ng burchagidagi soat, internet va ovoz belgilari joylashgan hudud nima deb ataladi?
- ( ) A) Start Menu
- (x) B) System Tray (Tizim lagani)
- ( ) C) Recycle Bin
- ( ) D) Control Panel
*Izoh: Taskbar'ning o'ng tomonidagi fon xizmatlari va sozlamalari ko'rinadigan joy System Tray deb nomlanadi.*

### 🤔 O'ylantiruvchi Mantiqiy Savollar:
1. Nima uchun katta hajmdagi video yoki arxiv fayllarni to'g'ridan-to'g'ri Ish stolida (C: disk profilida) saqlash tavsiya etilmaydi?
2. `Alt + F4` bilan `Win + D` o'rtasidagi asosiy farq nimada?
3. Agar kompyuteringizda 20 ta oyna ochiq bo'lsa, bu kompyuterning qaysi apparat resursiga ko'proq yuklama beradi (CPU, RAM yoki SSD)?

---

## 6. 🏠 Mustaqil Amaliy Uyga Vazifa

### Topshiriq:
1. Ish stolingizda yangi `Mening_Ishim` nomli papka yarating.
2. Sevimli brauzeringiz va matn muharriringiz uchun Ish stolida yorliq (Shortcut) hosil qiling.
3. Klaviaturadagi `Win + Strelka` yordamida ekranni ikkiga bo'lib, chap tomonda brauzer, o'ng tomonda matn muharririni joylashtiring.
4. Ekranni skrinshot qiling (`Win + Shift + S` yoki `PrtScn` tugmasi bilan).
5. Skrinshotni va yuqoridagi 3 ta mantiqiy savol javobini bitta hujjatga jamlang.

**Topshirish formati:** Tayyorlangan hisobotni `FIO_2-Mavzu_Windows.docx` nomi bilan platformaga yuklang.

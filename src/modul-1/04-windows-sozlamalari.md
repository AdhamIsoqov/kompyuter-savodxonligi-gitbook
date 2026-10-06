# 04-Mavzu: Windows Sozlamalari va Boshqaruv Paneli

{% hint style="info" %}
**Dars maqsadi:** Windows 10 va Windows 11 operatsion tizimining tizimli parametrlarini boshqarish, yangi "Sozlamalar" (Settings) interfeysi va an'anaviy "Boshqaruv paneli" (Control Panel) bilan professional ishlash, ekran, ovoz, xotira (Storage Sense), til va klaviatura parametrlarini moslashtirish ko'nikmalarini egallash.
{% endhint %}

### 🎯 Kutilayotgan Kompetensiyalar
* **Bilishingiz kerak:**
  * Yangi "Settings" (`Win + I`) va klassik "Control Panel" o'rtasidagi arxitekturaviy farqlar.
  * Tizim xotirasini optimallashtirish vositalari (Storage Sense va Disk Cleanup).
  * Ko'p tilli muhitda klaviatura drayverlari va til paketlarini o'rnatish tartibi.
* **Bajara olishingiz kerak:**
  * Displey piksellar aniqligi (Resolution), masshtabi (Scaling) va yangilanish tezligini (Hz) sozlash.
  * Klaviaturada tillar almashish yorliqlarini (`Alt + Shift` / `Win + Space`) to'g'ri moslash.
  * Tizimning qorong'i (Dark mode) va tungi yorug'lik (Night light) rejimlarini o'rnatish.

---

## 🎬 1. Video Dars

{% hint style="info" %}
**Video darslik:** Quyidagi pleer orqali mavzuni video formatda o'rganing:
{% endhint %}

[Iframe/Embed: 04-Mavzu Bo'yicha YouTube Video Dars Havolasi]

---

## 2. 📖 Chuqurlashtirilgan Nazariy Ma'ruza

### 2.1. Settings (Sozlamalar) vs Control Panel (Boshqaruv Paneli)

Windows tizimida parametrlarni o'zgartirish uchun ikkita asosiy platforma mavjud. Microsoft asta-sekin eski boshqaruv panelini yangi zamonaviy sozlamalar ilovasiga ko'chirmoqda.

| Parametr | Sozlamalar — Settings (`Win + I`) | Boshqaruv Paneli — Control Panel (`control`) |
| :--- | :--- | :--- |
| **Interfeys turi** | Zamonaviy, sensorli ekranlarga mos (UWP/WinUI) | Klassik Windows (Win32) uslubi |
| **Boshqaruv chuqurligi** | Kundalik foydalanuvchi sozlamalari | Chuqur administrativ va apparat darajadagi boshqaruv |
| **Ochish usuli** | `Win + I` tugmasi yoki Start menyusidagi tishli g'ildirakcha | `Win + R` -> `control` yozish orqali |
| **Asosiy bo'limlari** | System, Personalization, Apps, Accounts, Network | Hardware and Sound, Administrative Tools, Power Options |

```
[Windows Sozlamalari Boshqaruvi]
   ├── Settings (Win + I)
   │     ├── System (Ekran, Ovoz, Xotira, Quvvat)
   │     ├── Personalization (Fon, Mavzu, Qorong'i rejim)
   │     ├── Time & Language (Til, Soat, Klaviatura)
   │     └── Windows Update (Tizim yangilanishlari)
   └── Control Panel (control)
         ├── Device Manager (Apparat drayverlari)
         ├── Power Options (Kuchaytirilgan quvvat rejimi)
         └── Programs and Features (Klassik dasturlar boshqaruvi)
```

{% hint style="success" %}
**Pro-Tip ("God Mode" — Maxfiy Boshqaruv Paneli):**
Windows'dagi 200 dan ortiq barcha yashirin sozlamalarni bitta papkaga jamlash mumkin! Ish stolida yangi papka yarating va uning nomini aynan quyidagicha o'zgartiring:
`GodMode.{ED7BA470-8E54-465E-825C-99712043E01C}`
Enter bosing — papka boshqaruv paneli belgisiga aylanadi va ichida barcha tizim sozlamalari yagona ro'yxatda ochiladi!
{% endhint %}

### 2.2. Ekran va Vizual Qulaylik Sozlamalari

* **Resolution (Ekran o'lchami):** Monitorning tabiiy piksellar soniga (masalan: 1920x1080 Full HD) mos bo'lishi shart. Agar noto'g'ri tanlansa, tasvir cho'zilib yoki xiralashib qoladi.
* **Scale and Layout (Masshtab):** Noutbuklarda piktogrammalar va matnlarni ko'zga qulay qilish uchun masshtab odatda 125% yoki 100% qilib o'rnatiladi.
* **Night Light (Tungi rejim):** Monitorning ko'k nurlanish spektrini kamaytirib, issiq (sarg'ish) rangga o'tkazadi. Bu kechki payt ishlaganda ko'zning toliqishini 70% ga kamaytiradi.

### 2.3. Xotirani Tozalash (Storage Sense)

Windows 10/11 da **Storage Sense** tizimi mavjud bo'lib, u foydalanuvchi aralashuvisiz quyidagi amallarni avtomatik bajaradi:
1. Vaqtinchalik tizim fayllarini (`%temp%`) tozalash.
2. Savatda (Recycle Bin) 30 kundan ortiq qolib ketgan keraksiz fayllarni avtomatik o'chirish.
3. "Yuklab olinganlar" (Downloads) papkasidagi foydalanilmayotgan eski o'rnatish fayllarini tozalash.

---

## 3. 💻 Bosqichma-bosqich Amaliy Mashg'ulot (Lab Task)

Ushbu mashg'ulotda siz kompyuteringiz xotirasini optimallashtirasiz va ishchi muhitni shaxsiylashtirasiz.

### Kerakli Resurslar:
* Windows 10 yoki 11 o'rnatilgan kompyuter;
* Settings va Control Panel vositalari.

### 📄 Amaliy Mashg'ulot Shabloni:
{% hint style="success" %}
**📄 Rasmiy Amaliy Mashg'ulot va Uy Vazifasi Shabloni (Google Docs (Hujjat)):**
Ushbu darsning barcha bosqichlarini bajarish, natijalar/hisobotlarni kiritish va uy vazifasini topshirish uchun quyidagi rasmiy shablondan foydalaning:
* 🌐 **Onlayn ko'rish va tahrirlash:** [04-Mavzu: Windows Sozlamalari va Boshqaruv Paneli — Shablonni ochish](https://docs.google.com/document/d/15BPfYjSgKEZBzQKdEuacwfxToPYEgkuI0x4MBJCRehw/edit?usp=sharing)
* 📥 **Shaxsiy Drive-ga nusxalash (Tavsiya etiladi):** [Nusxa yaratish (Make a copy)](https://docs.google.com/document/d/15BPfYjSgKEZBzQKdEuacwfxToPYEgkuI0x4MBJCRehw/copy)
{% endhint %}

{% embed url="https://docs.google.com/document/d/15BPfYjSgKEZBzQKdEuacwfxToPYEgkuI0x4MBJCRehw/preview" %}

> *Eslatma: Shablondan nusxa oling va amallarni bajarish davomida olingan skrinshotlarni kiritib boring.*

### Bajarish Bosqichlari:

1. **1-Qadam:** Klaviaturada `Win + I` tugmalarini bosib **Settings** darchasini oching.
2. **2-Qadam:** **System -> Display** bo'limiga o'ting. Ekran o'lchami (Display resolution) tavsiya etilgan (Recommended) holatda ekanligini tekshiring.
3. **3-Qadam:** **Night light** parametrini yoqing va uning intensivligini o'zingizga qulay holatga moslang.
4. **4-Qadam (Storage Sense faollashtirish):** **System -> Storage** bo'limiga kiring. **Storage Sense** tugmachasini "On" holatiga o'tkazing va "Configure Storage Sense" orqali tozalash davriyligini "Every month" (Har oy) qilib belgilang.
5. **5-Qadam (Til qo'shish):** **Time & Language -> Language & Region** bo'limiga o'ting. Agar ro'yxatda bo'lmasa, "Add a language" tugmasini bosib "O'zbek (Lotin)" tilini qo'shing.
6. **6-Qadam (Klassik panel):** `Win + R` bosing, qatorga `control` deb yozing va Enter bosing. Yuqori o'ng burchakdagi "View by" parametrini "Large icons" holatiga o'tkazib, klassik vositalarni ko'zdan kechiring.

{% hint style="warning" %}
**Ehtiyot bo'ling:**
Control Panel ichidagi **Administrative Tools** yoki **Device Manager** bo'limidagi noma'lum apparat drayverlarini sababsiz o'chirmang (Disable qilmang). Bu ovoz, internet yoki klaviaturaning ishlamay qolishiga olib kelishi mumkin!
{% endhint %}

---

## 4. 🛠 Real Ish Vaziyati va Muammolarni Hal Qilish (Case-Study)

### Muammo:
Ofis foydalanuvchisi kompyuteriga yangi monitor uladi. Ammo ekrandagi barcha harflar, jadvallar va dasturlar ikonkalari haddan tashqari mayda bo'lib qoldi, matnlarni o'qish qiyinlashdi. Foydalanuvchi ekranni kattalashtirish uchun ekran o'lchamini (Resolution) 1920x1080 dan 1280x720 ga tushirdi, natijada butun tasvir xira va sifatsiz ko'rinishga kelib qoldi.

### Muammoning Kelib Chiqish Sababi:
Ekran o'lchamini (Resolution) pasaytirish xato yondashuvdir, chunki zamonaviy LCD monitorlar faqat o'zining tabiiy (Native) pikselida aniq tasvir beradi. Mayda elementlar muammosi **Masshtab (Display Scaling)** orqali yechilishi kerak.

### Bosqichma-bosqich Yechim:
1. `Win + I` orqali **Settings -> System -> Display** bo'limiga kiring.
2. Display resolution qatorini monitorni tabiiy o'lchamiga — **1920x1080 (Recommended)** ga qaytaring (tasvir tiniqligi tiklanadi).
3. Yuqoriroqda joylashgan **Scale (Masshtab)** parametrini oching.
4. Qiymatni 100% dan **125%** yoki **150%** ga oshiring.
5. Natijada ekrandagi piktogrammalar va harflar kattalashadi, shu bilan birga tasvirning tiniqligi va piksellar sifati 100% saqlanib qoladi.

---

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz — 25 ta Savol, 100 Ball)

{% hint style="info" %}
**📝 Rasmiy Onlayn Test Sinovi (Google Forms — 25 ta savol, 100 ballik baholash):**
Ushbu dars bo'yicha olgan bilimlaringizni sinash uchun quyidagi rasmiy testni topshiring (Har bir to'g'ri javob 4 ball, jami: 100 ball):
* 🔗 **Onlayn Testni Ochish (To'liq Ekranda):** [04-Mavzu: Windows Sozlamalari va Boshqaruv Paneli — Testni Topshirish](https://docs.google.com/forms/d/e/1FAIpQLSeWvsAsC3nwiEKQW3fk_SwRcUYWzjYBYilIzUNkXYyYlFct6g/viewform)
* 📊 **Kunlik Natijalar va Ballar Jadvali:** [Google Sheets — Natijalar Jadvali](https://docs.google.com/spreadsheets/d/178FyY11NDfHTqZsxeGGK6JlSiaaosXGTWiiOSDVrhxs/edit)
{% endhint %}

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSeWvsAsC3nwiEKQW3fk_SwRcUYWzjYBYilIzUNkXYyYlFct6g/viewform?embedded=true" width="100%" height="800" frameborder="0" marginheight="0" marginwidth="0">Yuklanmoqda…</iframe>

---

### ✍️ 25 ta Rasmiy Test Savollari (Nazorat va O'z-o'zini Tekshirish):

Quyida ushbu dars bo'yicha tuzilgan barcha 25 ta rasmiy test savollari keltirilgan. Har bir savol 4 ta variantdan iborat bo'lib, to'g'ri javob belgilangan:

#### 1-Savol: Windows 11 da 'Boshqaruv paneli'ni (Control Panel) tezkor ochish usuli qaysi?
- [x] **A) Win + R bosib, control deb yozish** *(To'g'ri javob)*
- [ ] B) F1 bosish
- [ ] C) Ctrl + P
- [ ] D) Win + C

#### 2-Savol: Ekran masshtabi va o'lchamini o'zgartirish qaysi bo'limda joylashgan?
- [x] **A) System -> Display** *(To'g'ri javob)*
- [ ] B) Personalization -> Colors
- [ ] C) Network & Internet
- [ ] D) Apps

#### 3-Savol: Virtual xotira (Paging file / Файл подкачки) nima uchun kerak?
- [x] **A) RAM yetishmaganda qattiq diskdan qo'shimcha xotira sifatida foydalanish uchun** *(To'g'ri javob)*
- [ ] B) Internetni tezlashtirish uchun
- [ ] C) Fayllarni arxivlash uchun
- [ ] D) Ekranni yorqin qilish uchun

#### 4-Savol: Kompyuterdagi xizmatlar (Services) oynasini ochish buyrug'i qaysi?
- [x] **A) services.msc** *(To'g'ri javob)*
- [ ] B) dxdiag
- [ ] C) cleanmgr
- [ ] D) regedit

#### 5-Savol: Windows da yangi foydalanuvchi hisobini (User Account) qo'shish qayerdan bajariladi?
- [x] **A) Settings -> Accounts** *(To'g'ri javob)*
- [ ] B) Settings -> System
- [ ] C) Control Panel -> Fonts
- [ ] D) Taskbar sozlamalaridan

#### 6-Savol: Klaviaturadagi kiritish tillari orasida almashish qaysi tugmalar bilan amalga oshadi?
- [x] **A) Alt + Shift yoki Win + Space** *(To'g'ri javob)*
- [ ] B) Ctrl + Shift + Esc
- [ ] C) Ctrl + Tab
- [ ] D) Alt + F4

#### 7-Savol: Kompyuter ekrani zudlik bilan qulflanishi (Lock screen) uchun qaysi tugma bosiladi?
- [x] **A) Win + L** *(To'g'ri javob)*
- [ ] B) Win + D
- [ ] C) Alt + L
- [ ] D) Ctrl + L

#### 8-Savol: Ochiq barcha oynalarni bir vaqtda pasaytirib, Ish stolini ochish qaysi tugma?
- [x] **A) Win + D** *(To'g'ri javob)*
- [ ] B) Win + M
- [ ] C) Alt + D
- [ ] D) Ctrl + D

#### 9-Savol: Disklarni boshqarish (Disk Management) utilitasini ochish buyrug'i nima?
- [x] **A) diskmgmt.msc** *(To'g'ri javob)*
- [ ] B) devmgmt.msc
- [ ] C) compmgmt.msc
- [ ] D) gpedit.msc

#### 10-Savol: Qurilmalar menejerini (Device Manager) ochish buyrug'i qaysi?
- [x] **A) devmgmt.msc** *(To'g'ri javob)*
- [ ] B) taskmgr
- [ ] C) appwiz.cpl
- [ ] D) ncpa.cpl

#### 11-Savol: Windows tizimida reyestr tahrirchisini (Registry Editor) qaysi buyruq ochadi?
- [x] **A) regedit** *(To'g'ri javob)*
- [ ] B) cmd
- [ ] C) powershell
- [ ] D) msconfig

#### 12-Savol: Tizim konfiguratsiyasi (System Configuration) oynasi qaysi buyruq bilan chaqiriladi?
- [x] **A) msconfig** *(To'g'ri javob)*
- [ ] B) sysdm.cpl
- [ ] C) config.exe
- [ ] D) winver

#### 13-Savol: Windows versiyasini tekshirish uchun 'Run' ga nima deb yoziladi?
- [x] **A) winver** *(To'g'ri javob)*
- [ ] B) ver
- [ ] C) osver
- [ ] D) info

#### 14-Savol: Windows Defender xavfsizlik devori (Firewall) ning asosiy vazifasi nima?
- [x] **A) Kiruvchi va chiquvchi tarmoq trafigini nazorat qilish va xavflardan himoyalash** *(To'g'ri javob)*
- [ ] B) Fayllarni o'chirish
- [ ] C) Viruslarni yaratish
- [ ] D) Diskni tozalash

#### 15-Savol: Vazifalar panelini (Taskbar) yashirish yoki sozlash qaysi menyuda joylashgan?
- [x] **A) Settings -> Personalization -> Taskbar** *(To'g'ri javob)*
- [ ] B) Settings -> Network
- [ ] C) Control Panel -> Sound
- [ ] D) System -> About

#### 16-Savol: Kompyuterning uyqu rejimiga (Sleep mode) o'tish vaqtini qayerdan sozlash mumkin?
- [x] **A) System -> Power & battery (Screen and sleep)** *(To'g'ri javob)*
- [ ] B) Display -> Color profile
- [ ] C) Network -> Proxy
- [ ] D) Apps -> Default apps

#### 17-Savol: Sana va vaqtni internet bilan avtomatik sinxronlash qaysi bo'limda?
- [x] **A) Time & language -> Date & time** *(To'g'ri javob)*
- [ ] B) Personalization -> Fonts
- [ ] C) Accessibility
- [ ] D) Privacy & security

#### 18-Savol: Windows da ovoz sozlamalarini boshqarish qayerda joylashgan?
- [x] **A) System -> Sound** *(To'g'ri javob)*
- [ ] B) Apps -> Installed apps
- [ ] C) Network
- [ ] D) Accounts

#### 19-Savol: Bildirishnomalar (Notifications) va 'Fokuslanish' (Focus assist) qayerdan boshqariladi?
- [x] **A) System -> Notifications / Focus** *(To'g'ri javob)*
- [ ] B) Personalization
- [ ] C) Bluetooth & devices
- [ ] D) Gaming

#### 20-Savol: Windows 11 da mavzularni (Themes, Dark/Light mode) o'zgartirish qaysi bo'limda?
- [x] **A) Settings -> Personalization -> Colors / Themes** *(To'g'ri javob)*
- [ ] B) System -> Storage
- [ ] C) Network
- [ ] D) Accounts

#### 21-Savol: O'rnatilgan dasturlar ro'yxatini ko'rish va o'chirish uchun 'Run' buyrug'i qaysi?
- [x] **A) appwiz.cpl** *(To'g'ri javob)*
- [ ] B) ncpa.cpl
- [ ] C) firewall.cpl
- [ ] D) main.cpl

#### 22-Savol: Sichqoncha kursori tezligini va ko'rinishini qayerdan sozlash mumkin?
- [x] **A) Bluetooth & devices -> Mouse (yoki main.cpl)** *(To'g'ri javob)*
- [ ] B) Personalization -> Start
- [ ] C) System -> Recovery
- [ ] D) Time & language

#### 23-Savol: Kompyuter haqida asosiy ma'lumotlarni ko'rish bo'limi qaysi?
- [x] **A) Settings -> System -> About** *(To'g'ri javob)*
- [ ] B) Settings -> Privacy
- [ ] C) Settings -> Update
- [ ] D) Control Panel -> Clock

#### 24-Savol: Windows Update (Yangilanishlar) bo'limining asosiy vazifasi nima?
- [x] **A) Xavfsizlik yamoqlari va tizim yangilanishlarini o'rnatish** *(To'g'ri javob)*
- [ ] B) Fayllarni tozalash
- [ ] C) Internetni o'chirish
- [ ] D) Diskni formatlash

#### 25-Savol: Ochiq oynalarni almashlab ko'rish (Task View) uchun qaysi tugma ishlatiladi?
- [x] **A) Win + Tab** *(To'g'ri javob)*
- [ ] B) Alt + Shift
- [ ] C) Ctrl + Shift
- [ ] D) Win + Space

---


## 6. 🏠 Mustaqil Amaliy Uyga Vazifa

### Topshiriq:
1. Shaxsiy kompyuteringizda **Settings -> System -> Storage** bo'limini oching va diskdagi bo'sh va band joy nisbatini tahlil qiling.
2. Vaqtinchalik fayllar (Temporary files) bo'limiga kirib, tizim keraksiz deb topgan fayllarni (kesh, eski yangilanishlar) tozalamasdan oldin va tozalagandan keyingi hajmini qayd eting.
3. Ish stoli fonini va rang mavzusini (Dark/Light mode) o'zingizga qulay holatga moslang.
4. Barcha bosqichlarning skrinshotlarini yagona hujjatga jamlang.

**Topshirish formati:** Bajarilgan ish hisobotini `FIO_4-Mavzu_Sozlamalar.docx` nomi bilan platformaga yuklang.

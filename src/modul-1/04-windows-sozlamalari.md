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
[Iframe/Embed: 04-Mavzu Google Docs / MS Office Amaliy Mashq Shabloni Havolasi]

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

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz)

{% hint style="info" %}
**Onlayn Test:** Ushbu dars bo'yicha bilimlaringizni sinash uchun quyidagi rasmiy Google Forms testini topshiring:
{% endhint %}

[Iframe/Embed: 04-Mavzu Google Forms Rasmiy Test Havolasi]

### ✍️ O'z-o'zini Tekshirish Uchun Test Savollari:

#### Test 1: Windows 10/11 da "Sozlamalar" (Settings) darchasini tezkor chaqiruvchi klaviatura yorlig'i qaysi?
- ( ) A) `Win + S`
- (x) B) `Win + I`
- ( ) C) `Win + R`
- ( ) D) `Ctrl + Shift + S`
*Izoh: `Win + I` kombinatsiyasi operatsion tizimning zamonaviy sozlamalar ilovasini darhol ishga tushiradi.*

#### Test 2: Monitor tasvirining ravshanligini buzmagan holda matn va ikonkalar hajmini kattalashtirish uchun qaysi parametr o'zgartiriladi?
- ( ) A) Display Resolution
- (x) B) Scale (Masshtab)
- ( ) C) Refresh Rate (Hz)
- ( ) D) Orientation
*Izoh: Scale parametri piksellar o'lchamini o'zgartirmay, grafik obyektlarni proporsional kattalashtirib beradi.*

#### Test 3: Windows tizimida qoldiq kesh fayllarni va savatdagi eski ma'lumotlarni avtomatik tozalovchi funksiya nima deb ataladi?
- ( ) A) Windows Defender
- ( ) B) Task Scheduler
- (x) C) Storage Sense (Xotira nazorati)
- ( ) D) Quick Assist
*Izoh: Storage Sense diskda bo'sh joy kamayganda yoki belgilangan vaqtda vaqtinchalik keraksiz fayllarni o'zi tozalaydi.*

#### Test 4: Windows-da klaviatura kirish tillari orasida tezkor almashish uchun qaysi tugmalar ishlatiladi?
- (x) A) `Alt + Shift` yoki `Win + Space`
- ( ) B) `Ctrl + Tab`
- ( ) C) `Shift + Esc`
- ( ) D) `Alt + Enter`
*Izoh: Windows muhitida tillar `Win + Bo'shliq (Space)` yoki `Alt + Shift` orqali almashtiriladi.*

#### Test 5: "Night light" (Tungi yorug'lik) funksiyasining inson salomatligi uchun asosiy foydasi nimada?
- ( ) A) Kompyuter quvvat sarfini 50% ga tejaydi
- (x) B) Ko'zga zararli ko'k nurlanishni kamaytirib, ko'rish quvvatini va uyqu gormonini asraydi
- ( ) C) Internet tezligini oshiradi
- ( ) D) Protsessorni sovitishga yordam beradi
*Izoh: Ekrandan tarqaladigan ko'k spektr ko'z to'r pardasini charchatadi; tungi rejim uni issiq ranglar bilan yumshatadi.*

### 🤔 O'ylantiruvchi Mantiqiy Savollar:
1. Nima uchun Microsoft kompaniyasi Boshqaruv panelini (Control Panel) birdaniga butunlay yo'q qilib yubormasdan, bosqichma-bosqich Settings-ga o'tkazmoqda?
2. Agar kompyuterda O'zbek tili klaviaturasi o'rnatilgan bo'lsa, `O'` va `G'` harflarini yozish uchun qaysi tugmalardan foydalaniladi?
3. Kompyuter ekrani yangilanish tezligi (Refresh Rate — 60Hz, 120Hz, 144Hz) inson ko'zining toliqishiga qanday ta'sir qiladi?

---

## 6. 🏠 Mustaqil Amaliy Uyga Vazifa

### Topshiriq:
1. Shaxsiy kompyuteringizda **Settings -> System -> Storage** bo'limini oching va diskdagi bo'sh va band joy nisbatini tahlil qiling.
2. Vaqtinchalik fayllar (Temporary files) bo'limiga kirib, tizim keraksiz deb topgan fayllarni (kesh, eski yangilanishlar) tozalamasdan oldin va tozalagandan keyingi hajmini qayd eting.
3. Ish stoli fonini va rang mavzusini (Dark/Light mode) o'zingizga qulay holatga moslang.
4. Barcha bosqichlarning skrinshotlarini yagona hujjatga jamlang.

**Topshirish formati:** Bajarilgan ish hisobotini `FIO_4-Mavzu_Sozlamalar.docx` nomi bilan platformaga yuklang.

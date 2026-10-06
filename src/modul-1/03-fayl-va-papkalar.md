# 03-Mavzu: Fayl va Papkalar Bilan Ishlash

{% hint style="info" %}
**Dars maqsadi:** Windows fayl tizimi tuzilishi, File Explorer vositasida fayl va papkalarni professional boshqarish, iyerarxik kataloglar yaratish, fayllarni nusxalash (Copy), ko'chirish (Cut), savat (Recycle Bin) xavfsizligi va kengaytirilgan qidiruv filtrlarini to'liq o'zlashtirish.
{% endhint %}

### 🎯 Kutilayotgan Kompetensiyalar
* **Bilishingiz kerak:**
  * Fayl va papkaning fundamental farqlari hamda mashhur fayl kengaytmalari (`.docx`, `.xlsx`, `.pptx`, `.pdf`, `.zip`, `.exe`).
  * `Copy` (nusxalash) va `Cut` (ko'chirish) amallarining ishlash mexanizmi.
  * Oddiy o'chirish (`Delete`) va butunlay yo'q qilish (`Shift + Delete`) oqibatlari.
* **Bajara olishingiz kerak:**
  * File Explorer'da ko'p bosqichli iyerarxik papkalar daraxtini yaratish.
  * Fayllar nomini tezkor o'zgartirish (`F2`), guruhlab tanlash (`Ctrl + A`, `Shift + Click`, `Ctrl + Click`).
  * Wildcard belgisi (`*`) orqali formati bo'yicha tezkor qidiruvni amalga oshirish (masalan: `*.xlsx`).

---

## 🎬 1. Video Dars

{% hint style="info" %}
**Video ko'rsatma:** Darsni o'zlashtirishdan oldin File Explorer va fayllarni tartibga solish bo'yicha video darsni tomosha qiling:
{% endhint %}

[Iframe/Embed: 03-Mavzu Bo'yicha Video Dars (YouTube / Google Drive Havolasi)]

---

## 2. 📖 Chuqurlashtirilgan Nazariy Ma'ruza

### 2.1. Fayl Tizimi Tushunchasi va File Explorer

Kompyuterdagi barcha axborotlar fayllar ko'rinishida saqlanadi. Windows tizimida ma'lumotlarni tartibli boshqarish uchun **File Explorer (Проводник)** asosiy dastur hisoblanadi. Uni ochishning eng tez yo'li — `Win + E` tugmalari kombinatsiyasidir.

```
[Mening Kompyuterim (This PC)]
   ├── Mahalli Disk (C:)  --> Operatsion tizim va dasturlar
   └── Mahalli Disk (D:)  --> Foydalanuvchi ma'lumotlari va arxivlar
         └── [Loyiha_2026] (Asosiy papka)
               ├── [Hujjatlar]  --> .docx, .pdf fayllar
               ├── [Jadvallar]  --> .xlsx hisobotlar
               └── [Taqdimotlar]--> .pptx slaydlar
```

### 2.2. Copy (Nusxalash) vs Cut (Ko'chirish)

Fayllarni boshqarishda eng ko'p ishlatiladigan va yangi boshlovchilar tez-tez adashtiradigan ikki asosiy amal taqqoslanishi:

| Xususiyati | Nusxalash — COPY (`Ctrl + C`) | Ko'chirish — CUT (`Ctrl + X`) |
| :--- | :--- | :--- |
| **Asl nusxasi** | Asl joyida saqlanib qoladi | Asl joyidan o'chiriladi |
| **Yangi joydagi natija** | Yangi joyda uning ikkinchi nusxasi paydo bo'ladi | Yangi joyga ko'chib o'tadi |
| **Xotirada egallagan joyi**| 2 barobarga ortadi (ikkita alohida fayl) | O'zgarmaydi (bitta fayl bo'lib qoladi) |
| **Vizual ko'rinishi** | Fayl belgisi o'zgarmaydi | `Ctrl + X` bosilgach, fayl belgisi yarim shaffof (xira) bo'ladi |

{% hint style="success" %}
**Pro-Tip (Fayllarni guruhlab belgilash):**
* `Ctrl + A` — Papka ichidagi barcha fayllarni bir zumda belgilash.
* `Shift + Strelka` — Ketma-ket joylashgan fayllar blokini birgalikda tanlash.
* `Ctrl + Sichqoncha chap tugmasi` — Har xil joyda turgan fayllarni donalab (tanlab-tanlab) belgilash.
{% endhint %}

### 2.3. O'chirish Mexanizmi va Recycle Bin (Savat)

Kompyuterda fayllarni o'chirish ikki xil usulda amalga oshiriladi:

1. **Vaqtinchalik o'chirish (`Delete`):** Fayl diskdan yo'qolmaydi, balki operatsion tizimning maxsus himoya qutisi — **Recycle Bin (Savat)** ga tushadi. Agar fayl adashib o'chirilgan bo'lsa, Savatga kirib, fayl ustiga sichqonchaning o'ng tugmasini bosib **Restore (Восстановить)** buyrug'ini tanlash orqali uni o'z joyiga qaytarish mumkin.
2. **Butunlay yo'q qilish (`Shift + Delete`):** Fayl savatga tushmasdan disk sektorlaridan to'g'ridan-to'g'ri o'chiriladi. Ushbu buyruqni berishda nihoyatda ehtiyotkor bo'lish zarur!

### 2.4. File Explorer Qidiruv Tizimi va Wildcards (`*`)

Agar kompyuteringizda minglab fayllar orasidan keraklisini topa olmasangiz, File Explorer qidiruv qatoriga maxsus filtrlarni kiritishingiz mumkin:
* `Hisobot` — Nomi ichida "Hisobot" so'zi qatnashgan barcha fayllarni topadi.
* `*.docx` — Barcha Microsoft Word hujjatlarini qidiradi.
* `*.xlsx` — Barcha Excel jadvallarini qidiradi.
* `Hujjat_2026_*.pdf` — "Hujjat_2026_" bilan boshlanuvchi barcha PDF fayllarni topadi.

---

## 3. 💻 Bosqichma-bosqich Amaliy Mashg'ulot (Lab Task)

Ushbu amaliy mashg'ulotda siz professional iyerarxik kataloglar strukturasini mustaqil qurasiz va fayllar oqimini tartiblaysiz.

### Kerakli Resurslar:
* Kompyuter (Windows 10/11);
* File Explorer dasturi;
* Amaliy topshiriq shabloni.

### 📄 Amaliy Mashq Shabloni (Google Docs / MS Office):
{% hint style="success" %}
**📄 Rasmiy Amaliy Mashg'ulot va Uy Vazifasi Shabloni (Google Docs (Hujjat)):**
Ushbu darsning barcha bosqichlarini bajarish, natijalar/hisobotlarni kiritish va uy vazifasini topshirish uchun quyidagi rasmiy shablondan foydalaning:
* 🌐 **Onlayn ko'rish va tahrirlash:** [03-Mavzu: Fayl va Papkalar Bilan Ishlash — Shablonni ochish](https://docs.google.com/document/d/1Z0ih8BLr3txSa1UzvLMUHPbW4IDHi1Mm4y1k4jNPp24/edit?usp=sharing)
* 📥 **Shaxsiy Drive-ga nusxalash (Tavsiya etiladi):** [Nusxa yaratish (Make a copy)](https://docs.google.com/document/d/1Z0ih8BLr3txSa1UzvLMUHPbW4IDHi1Mm4y1k4jNPp24/copy)
{% endhint %}

{% embed url="https://docs.google.com/document/d/1Z0ih8BLr3txSa1UzvLMUHPbW4IDHi1Mm4y1k4jNPp24/preview" %}

> *Eslatma: Shablondan nusxa oling va quyidagi amallarni bajargach, fayllar daraxti skrinshotini unga ilova qiling.*

### Bajarish Bosqichlari:

1. **1-Qadam:** `Win + E` tugmalari bilan File Explorer dasturini oching va **Hujjatlar (Documents)** jildiga kiring.
2. **2-Qadam:** Bo'sh joyga o'ng tugmani bosib, yangi papka yarating va unga `Mening_Arxivim` deb nom bering (yoki `Ctrl + Shift + N` tezkor tugmasini bosing).
3. **3-Qadam:** `Mening_Arxivim` papkasi ichiga kiring va uning ichida 3 ta alohida ichki papka yarating:
   * `01_Matnlar`
   * `02_Jadvallar`
   * `03_Media`
4. **4-Qadam:** `01_Matnlar` papkasi ichida yangi matnli fayl oching (O'ng tugma -> **New -> Text Document**) va unga `Reja_2026.txt` nomini bering.
5. **5-Qadam (Nomini o'zgartirish):** Ushbu faylni tanlang va klaviaturadagi `F2` tugmasini bosing. Nomini `Yillik_Reja_2026.txt` ga o'zgartirib Enter bosing.
6. **6-Qadam (Nusxalash - Copy):** Ushbu fayl ustida `Ctrl + C` tugmasini bosing, so'ng `02_Jadvallar` papkasiga o'tib `Ctrl + V` bosing (fayl ikkala papkada ham mavjud bo'ladi).
7. **7-Qadam (Ko'chirish - Cut):** `02_Jadvallar` papkasidagi faylni `Ctrl + X` qiling va `03_Media` papkasiga o'tib `Ctrl + V` bosing (fayl jadvallar papkasidan o'chib, media papkasiga ko'chadi).
8. **8-Qadam (Qidiruv):** `Mening_Arxivim` papkasining yuqori o'ng burchagidagi qidiruv qatoriga `*.txt` deb yozing va qidiruv natijalarini kuzating.

{% hint style="warning" %}
**Ehtiyot bo'ling:**
Hech qachon tizimli `C:\Windows` yoki `C:\Program Files` papkalari ichidagi fayllarni bilmasdan o'chirmang yoki nomini o'zgartirmang! Bu operatsion tizimning ishdan chiqishiga (Blue Screen of Death — BSOD) olib kelishi mumkin.
{% endhint %}

---

## 4. 🛠 Real Ish Vaziyati va Muammolarni Hal Qilish (Case-Study)

### Muammo:
Buxgalteriya xodimi muhim oylik hisobot hujjati ustida 4 soat ishlagach, uni xato bilan boshqa papkaga ko'chirib yubordi yoki bexosdan klaviaturadagi `Delete` tugmasini bosib o'chirib yubordi. Xodim sarosimada, kompyuterda fayl joylashgan joyda hujjat yo'q.

### Muammoning Kelib Chiqish Sababi:
Fayl tasodifan o'chirilgan (Savatga tushgan) yoki noto'g'ri sichqoncha harakati oqibatida qo'shni papkaga sudrab yuborilgan (Drag & Drop xatosi).

### Bosqichma-bosqich Yechim:
1. **Zudlik bilan bekor qilish:** Agar hodisa hozirgina yuz bergan bo'lsa, File Explorer'da `Ctrl + Z` tugmasini bosing (oxirgi noto'g'ri ko'chirish yoki o'chirish amali darhol bekor qilinadi).
2. **Savatni (Recycle Bin) tekshirish:** Agar vaqt o'tgan bo'lsa, Ish stolidagi **Recycle Bin** ikonkasini oching.
3. Qidiruv qatoriga fayl nomini yozing yoki sanasi bo'yicha saralang.
4. Topilgan fayl ustiga sichqonchaning o'ng tugmasini bosib **Restore (Восстановить)** buyrug'ini tanlang. Fayl o'z asl o'rniga tiklanadi.
5. Agar savatda bo'lmasa, `Win + E` orqali butun `D:` disk bo'ylab `*.xlsx` yoki hisobot nomi bo'yicha umumiy qidiruv bering.

---

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz — 25 ta Savol, 100 Ball)

{% hint style="info" %}
**📝 Rasmiy Onlayn Test Sinovi (Google Forms — 25 ta savol, 100 ballik baholash):**
Ushbu dars bo'yicha olgan bilimlaringizni sinash uchun quyidagi rasmiy testni topshiring (Har bir to'g'ri javob 4 ball, jami: 100 ball):
* 🔗 **Onlayn Testni Ochish (To'liq Ekranda):** [03-Mavzu: Fayl va Papkalar Bilan Ishlash — Testni Topshirish](https://docs.google.com/forms/d/e/1FAIpQLSen2YqcHQmESi-k6UH_MAkq0VOcFxYxwQfFrDPJGDrnGfY0Aw/viewform)
* 📊 **Kunlik Natijalar va Ballar Jadvali:** [Google Sheets — Natijalar Jadvali](https://docs.google.com/spreadsheets/d/1Np11QGlCCmBFE6sNmQjaenFKccGy_-5RQMHMDbxyq6k/edit)
{% endhint %}

{% embed url="https://docs.google.com/forms/d/e/1FAIpQLSen2YqcHQmESi-k6UH_MAkq0VOcFxYxwQfFrDPJGDrnGfY0Aw/viewform" %}

---

## 6. 🏠 Mustaqil Amaliy Uyga Vazifa

### Topshiriq:
1. Kompyuteringizning `D:` yoki `C:\Hujjatlar` bo'limida o'zingizning shaxsiy yoki o'qish yo'nalishingiz bo'yicha kamida 3 pog'onali iyerarxik papkalar tizimini yarating.
2. Har bir papkaga kamida bittadan matnli (`.txt` yoki `.docx`) mashq fayli joylang.
3. Klaviaturadagi `Ctrl + Shift + N`, `F2`, `Ctrl + C`, `Ctrl + V` va `Ctrl + X` tugmalaridan foydalanish jarayonini sinab ko'ring.
4. Yaratilgan papkalar daraxtini File Explorer chap panelida daraxt ko'rinishida ochib, to'liq skrinshot oling.

**Topshirish formati:** Skrinshot va 3 ta mantiqiy savolga berilgan javoblarni `FIO_3-Mavzu_Fayllar.docx` faylida tayyorlab tizimga yuklang.

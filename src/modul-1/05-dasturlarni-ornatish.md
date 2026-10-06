# 05-Mavzu: Dasturlarni O'rnatish va Boshqarish

{% hint style="info" %}
**Dars maqsadi:** Windows muhitida amaliy dasturiy ta'minotni to'g'ri va xavfsiz o'rnatish, Installer (`.exe`, `.msi`) va Portable dasturlar farqlarini o'rganish, dasturlarni to'laqonli o'chirish (Uninstall), avtoyuklanishni (Startup) nazorat qilish hamda keraksiz reklama dasturlari (Adware/PUP)dan himoyalanish.
{% endhint %}

### 🎯 Kutilayotgan Kompetensiyalar
* **Bilishingiz kerak:**
  * O'rnatish paketlari formatlari (`.exe`, `.msi`, `.zip`) va ularning arxitekturasi.
  * Tizim xavfsizlik filtri — UAC (User Account Control) ning vazifasi.
  * Oddiy o'chirish (Delete) va to'g'ri dezinstallyatsiya (Uninstall) o'rtasidagi farq.
* **Bajara olishingiz kerak:**
  * O'rnatish jarayonida yashirin reklama dasturlari (Adware) belgilarini aniqlash va ularni rad etish.
  * Kompyuterdan keraksiz dasturlarni Settings va Control Panel orqali qoldiqsiz o'chirish.
  * Windows yuklanishini tezlashtirish uchun Task Manager orqali Startup (Avtoyuklanish) ro'yxatini tozalash.

---

## 🎬 1. Video Dars

{% hint style="info" %}
**Video darslik:** Dasturlarni xavfsiz o'rnatish va boshqarish bo'yicha quyidagi videoni tomosha qiling:
{% endhint %}

[Iframe/Embed: 05-Mavzu Bo'yicha YouTube Video Dars Havolasi]

---

## 2. 📖 Chuqurlashtirilgan Nazariy Ma'ruza

### 2.1. Installer vs Portable Dasturlar

Dasturiy ta'minot foydalanuvchilarga ikki asosiy shaklda yetkazib beriladi:

| Ko'rsatkich | Installer Dastur (`.exe`, `.msi`) | Portable (Ko'chma) Dastur |
| :--- | :--- | :--- |
| **O'rnatish jarayoni** | Tizimga to'liq o'rnatishni talab qiladi | O'rnatish shart emas, papkadan to'g'ridan-to'g'ri ishlaydi |
| **Tizim integratsiyasi** | Windows reyestriga (`Registry`) yoziladi, Start va Taskbarga ulanadi | Reyestrga yozilmaydi, tizim sozlamalariga ta'sir qilmaydi |
| **O'chirish usuli** | Maxsus `Uninstall` vositasi orqali to'liq o'chiriladi | Shunchaki dastur papkasini o'chirib tashlash kifoya |
| **Foydalanish qulayligi** | Katta ofis paketlari, professional dasturlar va o'yinlar | Fleshkadan istalgan begona kompyuterda iz qoldirmay ishlash |

```
[O'rnatish Jarayoni Ketma-ketligi]
  1. Installer (.exe) yuklanadi
        |
  2. UAC (User Account Control) ruxsati beriladi (Yes)
        |
  3. License Agreement (Litsenziya shartlari qabul qilinadi)
        |
  4. Joylashuv tanlanadi (Standart: C:\Program Files\)
        |
  5. DIQQAT: Qo'shimcha taklif qilinayotgan reklama dasturlari belgisi olib tashlanadi!
        |
  6. Fayllar nusxalanadi va tizimga integratsiya bo'ladi
```

{% hint style="success" %}
**Pro-Tip (Xavfsiz o'rnatish "Oltin Qoidasi"):**
Dastur o'rnatayotganda hech qachon shoshilib faqat "Next -> Next -> Next" tugmalarini bosmang! Ko'pincha bepul dasturlar ichiga qo'shimcha brauzerlar, keraksiz tozalovchi vositalar yoki qidiruv tizimlari (masalan, Yandex Bar, McAfee, Chromium) yashiringan bo'ladi. Har doim **"Custom Installation" (Maxsus o'rnatish)** bandini tanlab, ortiqcha belgilarni (checkbox) olib tashlang.
{% endhint %}

### 2.2. Dasturlarni To'g'ri O'chirish (Uninstall)

Ko'pchilik yangi boshlovchilar qiladigan eng katta xato — `C:\Program Files` papkasiga kirib, dastur papkasini `Delete` bilan savatga tashlashdir. 

**Nima uchun papkani shunchaki o'chirish xato?**
* Dastur Windows xizmatlarida (Services) va tizim reyestrida (Registry) qolib ketadi;
* Kompyuter har yoqilganda o'chib ketgan faylni qidirib xatolik beradi;
* Tizim diskida "axlat" fayllar to'planib boradi.

**To'g'ri o'chirish yo'li:**
* **1-usul:** `Win + I` -> **Apps -> Installed apps** -> Dastur yonidagi uch nuqtani bosib **Uninstall** tanlash.
* **2-usul:** `Win + R` -> `appwiz.cpl` yozib Enter bosish (Klassik Programs and Features darchasi ochiladi) -> Ro'yxatdan tanlab **Uninstall** qilish.

### 2.3. Kompyuter Yuklanishini Tezlashtirish (Startup Apps)

Kompyuter yoqilganda uning sekin ochilishining 80% sababi — orqa fonda ishga tushadigan ko'p sonli dasturlardir (Telegram, Spotify, Skype, Torrent, turli yangilovchilar).

* Klaviaturada `Ctrl + Shift + Esc` tugmasini bosing (Task Manager).
* **Startup apps (Автозагрузка)** bo'limiga o'ting.
* Kundalik kerak bo'lmagan dasturlar ustiga sichqonchaning o'ng tugmasini bosib **Disable (Отключить)** qiling. Bu ularni o'chirmaydi, faqat kompyuter yoqilganda o'z-o'zidan ishga tushishini to'xtatadi.

---

## 3. 💻 Bosqichma-bosqich Amaliy Mashg'ulot (Lab Task)

Ushbu amaliy mashg'ulotda siz kompyuteringizdagi keraksiz dasturlarni aniqlab, ularni to'g'ri o'chirasiz va avtoyuklanishni optimallashtirasiz.

### Kerakli Resurslar:
* Kompyuter (Windows 10/11);
* Task Manager va Installed Apps bo'limlari;
* O'quv mashqi uchun bepul utilita (masalan, 7-Zip yoki Notepad++ rasmiy saytidan).

### 📄 Amaliy Mashg'ulot Shabloni:
{% hint style="success" %}
**📄 Rasmiy Amaliy Mashg'ulot va Uy Vazifasi Shabloni (Google Docs (Hujjat)):**
Ushbu darsning barcha bosqichlarini bajarish, natijalar/hisobotlarni kiritish va uy vazifasini topshirish uchun quyidagi rasmiy shablondan foydalaning:
* 🌐 **Onlayn ko'rish va tahrirlash:** [05-Mavzu: Dasturlarni O'rnatish va Boshqarish — Shablonni ochish](https://docs.google.com/document/d/1Zg8xWTv4tMk9hqSYWEoSQtjd7LjexLI5LXSYQfrIKwc/edit?usp=sharing)
* 📥 **Shaxsiy Drive-ga nusxalash (Tavsiya etiladi):** [Nusxa yaratish (Make a copy)](https://docs.google.com/document/d/1Zg8xWTv4tMk9hqSYWEoSQtjd7LjexLI5LXSYQfrIKwc/copy)
{% endhint %}

{% embed url="https://docs.google.com/document/d/1Zg8xWTv4tMk9hqSYWEoSQtjd7LjexLI5LXSYQfrIKwc/preview" %}

> *Eslatma: Shablondan nusxa oling va quyidagi 6 ta qadam natijalarini skrinshotlar bilan hujjatga to'ldiring.*

### Bajarish Bosqichlari:

1. **1-Qadam:** `Ctrl + Shift + Esc` tugmalarini bosib Task Manager darchasini oching.
2. **2-Qadam:** **Startup apps** bo'limiga o'ting. Har bir dasturning "Startup impact" (Yuklanishga ta'siri: High, Medium, Low) ustunini tahlil qiling.
3. **3-Qadam:** Kompyuter yoqilganda zudlik bilan kerak bo'lmagan dasturlarni (masalan, o'yin do'konlari, messenjerlar) o'ng tugma bilan **Disable** holatiga o'tkazing.
4. **4-Qadam:** Rasmiy `7-zip.org` saytidan eng so'nggi 64-bitli arxivator dasturini yuklab oling.
5. **5-Qadam:** Yuklangan faylni ishga tushiring, o'rnatish yo'li `C:\Program Files\7-Zip\` ekanligini ko'zdan kechirib **Install** tugmasini bosing.
6. **6-Qadam (Dezinstallyatsiya nazorati):** `Win + R` bosing, `appwiz.cpl` buyrug'ini yozib ro'yxatda yangi o'rnatilgan dastur paydo bo'lganini tekshiring.

{% hint style="warning" %}
**Ehtiyot bo'ling:**
Hech qachon Microsoft Visual C++ Redistributable, DirectX, Realtek Audio yoki videokarta (NVIDIA/AMD/Intel) drayverlarini "Programs and Features" ro'yxatidan o'chirib yubormang! Bu tizimning to'g'ri ishlashi uchun hayotiy muhim komponentlardir.
{% endhint %}

---

## 4. 🛠 Real Ish Vaziyati va Muammolarni Hal Qilish (Case-Study)

### Muammo:
Foydalanuvchi internetdan o'ziga kerakli bir bepul dasturni yuklab o'rnatdi. O'rnatish tugagach, brauzerda o'z-o'zidan turli begona reklama saytlari ochila boshladi, asosiy qidiruv tizimi begona noma'lum saytga o'zgarib ketdi, kompyuter esa haddan tashqari sekin ishlay boshladi.

### Muammoning Kelib Chiqish Sababi:
Foydalanuvchi o'rnatish vaqtida shartlarni o'qimay "Next" ni bosgan va dastur ichiga qo'shib berilgan **PUP (Potentially Unwanted Program / Ehtimoliy keraksiz dastur)** hamda brauzer kengaytmasini (Adware) o'rnatib qo'ygan.

### Bosqichma-bosqich Yechim:
1. `Win + R` bosing va `appwiz.cpl` deb yozing.
2. Dasturlar ro'yxatini **Installed On (O'rnatilgan sana)** ustuni bo'yicha saralang (oxirgi sanadagilar eng yuqoriga chiqadi).
3. Aynan o'sha kuni ruxsatsiz o'rnatilgan barcha shubhali dasturlarni birma-bir **Uninstall** qiling.
4. Brauzerni oching, sozlamalar bo'limidan **Extensions (Kengaytmalar)** ro'yxatiga kiring va notanish reklama plaginlarini butunlay o'chiring.
5. Brauzerning asosiy qidiruv tizimini qaytadan Google yoki Yandex ga to'g'rilang.

---

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz — 25 ta Savol, 100 Ball)

{% hint style="info" %}
**📝 Rasmiy Onlayn Test Sinovi (Google Forms — 25 ta savol, 100 ballik baholash):**
Ushbu dars bo'yicha olgan bilimlaringizni sinash uchun quyidagi rasmiy testni topshiring (Har bir to'g'ri javob 4 ball, jami: 100 ball):
* 🔗 **Onlayn Testni Ochish (To'liq Ekranda):** [05-Mavzu: Dasturlarni O'rnatish va Boshqarish — Testni Topshirish](https://docs.google.com/forms/d/e/1FAIpQLSfs3sOkMVwZgV3nWJ_I-SFt5P45P_GzCF6r3BJ0jC3TBFbwaA/viewform)
* 📊 **Kunlik Natijalar va Ballar Jadvali:** [Google Sheets — Natijalar Jadvali](https://docs.google.com/spreadsheets/d/1FX4XxxVK4ZCCNtahGmUyto20hP0CkZ6V0AlVHMeG6lA/edit)
{% endhint %}

{% embed url="https://docs.google.com/forms/d/e/1FAIpQLSfs3sOkMVwZgV3nWJ_I-SFt5P45P_GzCF6r3BJ0jC3TBFbwaA/viewform" %}

---

## 6. 🏠 Mustaqil Amaliy Uyga Vazifa

### Topshiriq:
1. Kompyuteringizdagi o'rnatilgan dasturlar ro'yxatini (`Win + I -> Apps`) ko'zdan kechiring.
2. Oxirgi 6 oy davomida umuman ishlatilmagan kamida 1 ta keraksiz dasturni toping va uni qoidaga muvofiq to'liq o'chiring.
3. Task Manager'dagi avtoyuklanish (Startup) ro'yxatidan kamida 2 ta ikkinchi darajali dasturni "Disable" qiling.
4. Kompyuterni qayta ishga tushirib (Restart), yuklanish tezligi o'zgarganini his eting va barcha bosqichlarni hisobotga yozing.

**Topshirish formati:** Bajarilgan ish natijalarini `FIO_5-Mavzu_Dasturlar.docx` faylida tayyorlab platformaga yuklang.

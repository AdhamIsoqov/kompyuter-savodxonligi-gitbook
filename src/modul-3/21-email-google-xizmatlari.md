# 21-Mavzu: Elektron Pochta Madaniyati va Google Workspace Xizmatlari

Assalomu alaykum! Kasbtech Akademiyasining Kompyuter savodxonligi kursidagi 21-darsimizga xush kelibsiz.

Oldingi 20-darsimizda biz global internet tarmog'ining ishlash mexanizmlari, xavfsiz HTTPS protokoli hamda veb-brauzerlar va Google qidiruv tizimidan unumli foydalanishni o'rgangan edik. Endi esa veb-brauzerdan shunchaki ma'lumot izlash uchun emas, balki professional biznes va korporativ aloqa vositasi sifatida foydalanishni boshlaymiz.

Zamonaviy ish dunyosida har qanday rasmiy shartnoma, taklif yoki hisobot messenjerlar (Telegram, WhatsApp) orqali emas, balki yuridik kuchga ega bo'lgan **elektron pochta (Email)** orqali yuboriladi. Shuningdek, ma'lumotlarni fleshkada olib yurish o'rniga **Google Drive** bulutli xotirasida saqlash va jamoa bo'lib bir vaqtning o'zida bitta hujjat ustida ishlash zamonaviy raqamli madaniyatning ajralmas qismidir.

Kelgusi 22-darsimizda esa bugun o'rganiladigan Google hisobimiz orqali eng so'nggi Sun'iy Intellekt (AI) tizimlari — ChatGPT, Google Gemini va onlayn dizayn vositalaridan amaliy foydalanishga o'tamiz.

{% hint style="info" %}
**Dars maqsadi:** Zamonaviy korporativ elektron pochta (Gmail) madaniyati, xat yozish etiketi (To, Cc, Bcc, Subject), 25 MB dan katta fayllarni yuborish, Google Drive bulutli xotirasi, Google Docs/Sheets vositalarida jamoaviy onlayn hamkorlik (Co-authoring), versiyalar tarixi (Version history) hamda kirish huquqlarini (Viewer, Commenter, Editor) xavfsiz boshqarish ko'nikmalarini egallash.
{% endhint %}

### 🎯 Kutilayotgan Kompetensiyalar
* **Bilishingiz kerak:**
  * Elektron pochta va messenjerlar o'rtasidagi huquqiy hamda amaliy farq.
  * Rasmiy yozishmalarda `To` (Kimgadir), `Cc` (Nusxa) va `Bcc` (Yashirin nusxa) qatorlarining vazifasi.
  * Elektron pochtada fayl biriktirish cheklovi (25 MB) va uni Google Drive orqali yechish mexanizmi.
  * Bulutli fayllarni ulashishda ruxsatlar darajasi (Viewer, Commenter, Editor).
* **Bajara olishingiz kerak:**
  * Gmail'da rasmiy xat yozish, mavzu (Subject) kiritish va professional avtomatik imzo (Signature) o'rnatish.
  * Google Drive'ga fayllar yuklash, papkalar ochish va havola (Link sharing) orqali xavfsiz ulashish.
  * Google Docs va Sheets xizmatlarida boshqa foydalanuvchilar bilan real vaqtda birgalikda hujjat tahrirlash.
  * Hujjatdagi o'zgarishlarni bekor qilish uchun versiyalar tarixidan (Version history) foydalanish.

## 🎬 1. Video Dars

{% hint style="info" %}
**Video darslik:** Gmail va Google Workspace (Drive, Docs, Sheets) imkoniyatlari bo'yicha quyidagi videoni tomosha qiling:
{% endhint %}

[Iframe/Embed: 21-Mavzu Bo'yicha YouTube Video Dars Havolasi]

## 2. 📖 Chuqurlashtirilgan Nazariy Ma'ruza

### 2.1. Elektron Pochta va Korporativ Etiket

Elektron pochta (Email) — bu shunchaki muloqot vositasi emas, balki qonuniy va rasmiy isbot kuchiga ega bo'lgan korporativ yozishma hisoblanadi. Telegram kabi messenjerlarda yuborilgan xabarni istalgan tomon o'chirib yuborishi mumkin, pochtadagi xatlar esa yillar davomida arxivda saqlanadi.

Rasmiy xat jo'natishda quyidagi maydonlarning aniq vazifasi bor:

| Maydon Nomi | To'liq Ma'nosi | Vazifasi va Qoidasi | Qabul qiluvchilar ko'radimi? |
| :--- | :--- | :--- | :--- |
| **To (Kimgadir)** | Asosiy qabul qiluvchi | Xat bevosita tegishli bo'lgan va javob berishi talab etiladigan shaxs | Barcha qabul qiluvchilar ko'radi |
| **Cc (Nusxa)** | Carbon Copy | Xatdan xabardor bo'lib turishi kerak bo'lgan nazoratchilar (masalan: bo'lim boshlig'i) | Barcha qabul qiluvchilar ko'radi |
| **Bcc (Yashirin)**| Blind Carbon Copy | Xat nusxasi yuboriladi, lekin boshqa hech kim uning manzilini ko'rmaydi | **To'liq maxfiy qoladi** |

```
[Rasmiy Elektron Xat Tuzilmasi (Anatomiyasi)]
  To: rahbar@korxona.uz
  Subject: [Loyiha 2026] Oylik smeta hisoboti hujjati topshirilishi haqida
  ------------------------------------------------------------------
  Hurmatli Akrom Shokirovich! (Rasmiy salomlashish)
  
  Ushbu xatga 2026-yil 1-chorak bo'yicha tayyorlangan kompyuter parki
  smetasi hisobotini ilova qilmoqdaman. (Asosiy maqsad)
  
  Iltimos, ilovadagi hujjat bilan tanishib chiqib, o'z fikringizni
  bildirsangiz.
  
  Ilova: Smeta_Hisoboti.pdf (1.8 MB)
  
  Hurmat bilan,
  Alisher Valiyev, Kompyuter mutaxassisi (Avtomatik imzo)
  Tel: +998 90 123 45 67
```

### 2.2. Fayl Biriktirish (Attachment) va 25 MB Cheklovi

Elektron pochtada to'g'ridan-to'g'ri biriktirib yuborish mumkin bo'lgan maksimal hajm — **25 MB** hisoblanadi. Agar fayl hajmi (masalan, yuqori sifatli video taqdimot yoki katta arxiv) 25 MB dan oshsa:
* Gmail xatga to'g'ridan-to'g'ri fayl yuklash o'rniga, uni avtomatik tarzda sizning **Google Drive** bulutingizga yuklaydi;
* Xat matniga esa o'sha faylning xavfsiz havolasini (Link) kiritib beradi.

### 2.3. Google Drive va Bulutli Hamkorlik Ruxsatlari

Google har bir ro'yxatdan o'tgan foydalanuvchiga **15 GB bepul bulutli xotira** ajratadi. Ushbu xotirada nafaqat fayllarni saqlash, balki **Google Docs** (Word analogi), **Google Sheets** (Excel analogi) va **Google Slides** (PowerPoint analogi) yordamida brauzerning o'zida dastur o'rnatmasdan ishlash mumkin.

Bulutdagi fayllarni boshqa foydalanuvchilarga ulashishda (Share) quyidagi 3 ta qat'iy daraja mavjud:
1. **Viewer (Ko'ruvchi):** Foydalanuvchi faylni faqat o'qiy oladi, nusxa olishi mumkin, ammo birorta ham harfni o'zgartira olmaydi.
2. **Commenter (Izohlovchi):** Foydalanuvchi asosiy matnga zarar yetkaza olmaydi, lekin matn chetiga savol va takliflarini izoh (Comment) sifatida qoldiradi.
3. **Editor (Tahrirlovchi):** Hujjatni to'liq o'zgartirish, o'chirish va yangi matn kiritish huquqiga ega bo'ladi (faqat ishonchli hamkorlarga beriladi).

{% hint style="success" %}
**Pro-Tip (Xatni bekor qilish — Undo Send):**
Xatni jo'natish tugmasini bosishingiz bilan fayl biriktirishni unutganingiz yoki xatoni payqab qoldingizmi? Gmail sozlamalarida **"Undo Send" (Yuborishni bekor qilish)** vaqtini 30 soniyaga qilib belgilang! Xat jo'natilgach, ekranning pastida 30 soniya davomida "Undo" tugmasi turadi — uni bosib, xatni qaytarib olib tahrirlashingiz mumkin.
{% endhint %}

## 3. 💻 Bosqichma-bosqich Amaliy Mashg'ulot (Lab Task)

Ushbu mashg'ulotda siz Google Drive-da jamoaviy papka ochasiz va Google Docs orqali onlayn hamkorlikda hujjat tahrirlashni bajarasiz.

### Kerakli Resurslar:
* Kompyuter va internet;
* Shaxsiy Google akkaunt (Gmail).

### 📄 Amaliy Mashg'ulot Shabloni:
{% hint style="success" %}
**📄 Rasmiy Amaliy Mashg'ulot va Uy Vazifasi Shabloni (Google Docs (Hujjat)):**
Ushbu darsning barcha bosqichlarini bajarish, natijalar/hisobotlarni kiritish va uy vazifasini topshirish uchun quyidagi rasmiy shablondan foydalaning:
* 🌐 **Onlayn ko'rish va tahrirlash:** <a href="https://docs.google.com/document/d/1GGfT-qTKMjnnQn5Ki1PYN9tO3D_HVDZSnaLHapX7CaU/edit?usp=sharing" target="_blank" rel="noopener noreferrer">21-Mavzu: Elektron Pochta va Google Xizmatlari — Shablonni ochish</a>
* 📥 **Shaxsiy Drive-ga nusxalash (Tavsiya etiladi):** <a href="https://docs.google.com/document/d/1GGfT-qTKMjnnQn5Ki1PYN9tO3D_HVDZSnaLHapX7CaU/copy" target="_blank" rel="noopener noreferrer">Nusxa yaratish (Make a copy)</a>
{% endhint %}

{% embed url="https://docs.google.com/document/d/1GGfT-qTKMjnnQn5Ki1PYN9tO3D_HVDZSnaLHapX7CaU/preview" %}

> *Eslatma: Shablondan nusxa oling va quyidagi 6 ta qadam orqali bulutli fayllarni sozlang.*

### Bajarish Bosqichlari:

1. **1-Qadam:** Brauzeringizda **Google Drive** (`drive.google.com`) ga kiring.
2. **2-Qadam (Papka ochish):** **New -> New folder** tugmasini bosing va papkaga `Oquv_Loyiha_2026` deb nom bering.
3. **3-Qadam (Google Docs yaratish):** Papka ichiga kiring, **New -> Google Docs** tugmasini bosing. Hujjat sarlavhasiga "Jamoaviy Hamkorlik Rejasi" deb nom bering va 3 qator matn kiriting.
4. **4-Qadam (Avtomatik saqlanish):** E'tibor bering, Google Docs da `Ctrl + S` bosish shart emas — har bir harf kiritilishi bilan yuqorida "Saving -> Saved to Drive" deb o'zi saqlanib boradi.
5. **5-Qadam (Havolani ulashish - Share):** Yuqori o'ng burchakdagi **Share (Поделиться)** tugmasini bosing. "General access" qismini **"Anyone with the link" (Havolaga ega har qanday foydalanuvchi)** ga o'zgartiring va huquqini **Viewer** qilib belgilang.
6. **6-Qadam (Gmail orqali xat tayyorlash):** Gmail (`mail.google.com`) ga o'ting, **Compose** bosing, To qatoriga sherigingiz pochtasini, Subject qatoriga "Loyiha hujjati havolasi" deb yozing va Google Docs havolasini xat ichiga joylang.

{% hint style="warning" %}
**Ehtiyot bo'ling:**
Hech qachon ommaviy internet guruhlariga (Telegram kanallar, guruhlar) Google Drive fayllarining havolasini **Editor (Tahrirlovchi)** huquqi bilan tarqatmang! Aks holda istalgan notanish shaxs hujjatingizdagi barcha ma'lumotlarni o'chirib yoki buzib ketishi mumkin.
{% endhint %}

## 4. 🛠 Real Ish Vaziyati va Muammolarni Hal Qilish (Case-Study)

### Muammo:
Kompaniya rahbari 100 ta turli korxonalarga tijoriy taklif xati yubordi. Kotib barcha 100 ta rahbarning elektron pochtasini ochiq `To:` (Kimgadir) maydoniga bitta qator qilib kiritib jo'natdi. Natijada barcha 100 ta mijoz bir-birining shaxsiy elektron pochtasini ko'rib qoldi, raqobatchi kompaniyalar esa bundan foydalanib mijozlar bazasini o'g'irladi. Kompaniya katta moliyaviy va obro' zarariga uchradi.

### Muammoning Kelib Chiqish Sababi:
Ommaviy bir xil xatlar tarqatilganda kiberxavfsizlik va maxfiylik vositasi bo'lgan **Bcc (Yashirin nusxa)** dan foydalanilmagan.

### Bosqichma-bosqich Yechim:
1. Ommaviy xat yuborishda `To:` maydoniga faqat o'zingizning pochtangizni yozing.
2. Xat oynasining o'ng tomonidagi **Bcc (Скрытая копия)** tugmasini bosing.
3. Barcha 100 ta mijozning elektron pochtalarini aynan **Bcc** qatoriga kiriting.
4. Xat barcha 100 kishiga alohida-alohida yetib boradi va har bir mijoz faqat o'ziga xat kelgan deb hisoblaydi, qolgan 99 kishining manzillari butunlay maxfiy qoladi!

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz)

{% hint style="info" %}
**📝 Rasmiy Onlayn Test Sinovi (Google Forms — 15 ta saralangan savol, 100 ballik baholash):**
Ushbu dars bo'yicha olgan bilimlaringizni sinash uchun quyidagi rasmiy testni topshiring (15 ta saralangan test savoli, jami: 100 ball):
* 🔗 **Onlayn Testni Ochish (To'liq Ekranda):** <a href="https://docs.google.com/forms/d/e/1FAIpQLSePXwQecCPaEjEeHmWaVvbnBiGuQ8cHYA0DZMEsnJ2Pix3F3Q/viewform" target="_blank" rel="noopener noreferrer">21-Mavzu: Elektron Pochta va Google Xizmatlari — Testni Topshirish</a>
* 📊 **Kunlik Natijalar va Ballar Jadvali:** <a href="https://docs.google.com/spreadsheets/d/1nAfH2Fx2zstB1UVq_tzz4ynmm9h7-NbDNMJLYqrv1YE/edit" target="_blank" rel="noopener noreferrer">Google Sheets — Natijalar Jadvali</a>
{% endhint %}

{% embed url="https://docs.google.com/forms/d/e/1FAIpQLSePXwQecCPaEjEeHmWaVvbnBiGuQ8cHYA0DZMEsnJ2Pix3F3Q/viewform" %}

## 6. 🏠 Mustaqil Amaliy Uyga Vazifa

### Topshiriq:
1. Shaxsiy Google Drive xizmatingizda yangi `Mening_Bulutim` nomli papka oching.
2. Unga bitta rasm va bitta Word faylini kompyuteringizdan yuklang.
3. Yangi Google Docs hujjati yaratib, o'zingizning qisqacha rezyumeyingizni yozing.
4. Hujjat havolasini "Anyone with the link -> Viewer" qilib oching va o'sha havolani hisobot fayliga joylang.

**Topshirish formati:** Bajarilgan ish hisobotini `FIO_21-Mavzu_Google_Xizmatlari.docx` nomi bilan platformaga yuklang.

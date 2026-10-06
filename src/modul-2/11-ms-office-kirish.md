# 11-Mavzu: Microsoft Office Paketiga Kirish

{% hint style="info" %}
**Dars maqsadi:** Microsoft Office dasturlar to'plamining ekotizimi, har bir dasturning (Word, Excel, PowerPoint, Outlook, Access, OneNote) ixtisoslashuv sohasi, ofis dasturlarining versiyalari (Office 2019, 2021 va Microsoft 365) hamda zamonaviy XML asosidagi fayl formatlarini (`.docx`, `.xlsx`, `.pptx`) chuqur o'rganish.
{% endhint %}

### 🎯 Kutilayotgan Kompetensiyalar
* **Bilishingiz kerak:**
  * Har bir amaliy vazifa uchun to'g'ri Office dasturini tanlash mantig'i.
  * Standart `.doc`/`.xls` va zamonaviy `.docx`/`.xlsx` formatlari o'rtasidagi arxitekturaviy farq.
  * Microsoft 365 bulutli xizmati va oflayn dasturlar to'plami integratsiyasi.
* **Bajara olishingiz kerak:**
  * Kompyuterdagi Microsoft Office versiyasini va faollashtirish (Activation) holatini aniqlash.
  * Standart ofis shablonlaridan (Templates) foydalangan holda yangi hujjatlarni tezkor yaratish.
  * Hujjatlarni turli formatlarda (`.docx`, `.pdf`, `.txt`) eksport qilish.

---

## 🎬 1. Video Dars

{% hint style="info" %}
**Video darslik:** Microsoft Office dasturlari ekotizimi bilan tanishuv bo'yicha quyidagi videoni tomosha qiling:
{% endhint %}

[Iframe/Embed: 11-Mavzu Bo'yicha YouTube Video Dars Havolasi]

---

## 2. 📖 Chuqurlashtirilgan Nazariy Ma'ruza

### 2.1. Qaysi Ish Uchun Qaysi Dastur?

Microsoft Office — dunyodagi eng ommabop ofis ilovalari to'plamidir. Har bir dastur o'zining aniq yo'nalishiga ega:

| Dastur Nomi | Asosiy Vazifasi | Fayl Kengaytmasi | Real Hayotiy Qo'llanilishi |
| :--- | :--- | :--- | :--- |
| **Microsoft Word** | Matnli hujjatlar yaratish va formatlash | `.docx` | Ariza, buyruq, shartnoma, maqola, rezyume, kitob |
| **Microsoft Excel** | Elektron jadvallar va hisob-kitoblar | `.xlsx` | Buxgalteriya, maosh jadvali, moliyaviy tahlil, diagrammalar |
| **Microsoft PowerPoint** | Vizual slaydlar va taqdimotlar | `.pptx` | Darslar, ma'ruzalar, loyiha taqdimotlari, hisobotlar |
| **Microsoft Outlook** | Korporativ pochta va taqvim | `.pst`, `.ost` | Xizmat yozishmalari, uchrashuvlarni rejalashtirish |
| **Microsoft Access** | Relyatsion ma'lumotlar bazasi | `.accdb` | Katta hajmli ma'lumotlar ombori, so'rovlar (SQL), formalar |
| **Microsoft OneNote** | Raqamli yon daftarcha | `.one` | Tezkor eslatmalar, o'quv konspektlari, audio yozuvlar |

```
[Microsoft Office Ekotizimi]
      ├── Matn va Hujjatlar  =========> Microsoft Word (.docx)
      ├── Hisob-kitob va Sonlar ======> Microsoft Excel (.xlsx)
      ├── Ko'rgazma va Slaydlar ======> Microsoft PowerPoint (.pptx)
      └── Muloqot va Rejalar ========> Microsoft Outlook
```

{% hint style="success" %}
**Pro-Tip (Nima uchun oxirida "x" harfi bor?):**
Eski versiyalarda kengaytmalar `.doc`, `.xls`, `.ppt` bo'lgan bo'lsa, 2007-yildan boshlab oxiriga **"x"** harfi qo'shildi (`.docx`, `.xlsx`, `.pptx`). Bu **XML (OpenXML)** arxitekturasini bildiradi. Aslida har qanday `.docx` fayli — bu matnlar, rasmlar va shriftlar siqilgan ZIP-arxivdir! Bu fayllar hajmini 2-3 barobarga qisqartiradi va buzilgan taqdirda ham matnni oson tiklash imkonini beradi.
{% endhint %}

### 2.2. Oflayn Office vs Microsoft 365 (Bulutli)

* **Klassik Office (2016, 2019, 2021):** Bir marta sotib olinadi va o'rnatiladi. Yangi funksiyalar qo'shilmaydi, faqat xavfsizlik yangilanishlarini oladi.
* **Microsoft 365 (sobiq Office 365):** Oylik yoki yillik obuna tizimi. Doimiy ravishda eng so'nggi sun'iy intellekt (Copilot) funksiyalari qo'shilib boradi, 1 TB OneDrive bulutli xotira beradi va hujjat ustida bir vaqtning o'zida bir nechta xodim onlayn hamkorlikda ishlashi mumkin.

---

## 3. 💻 Bosqichma-bosqich Amaliy Mashg'ulot (Lab Task)

Ushbu amaliy mashg'ulotda siz kompyuteringizdagi Office paketining holatini tekshirasiz va professional tayyor shablon asosida birinchi hujjatni yaratasiz.

### Kerakli Resurslar:
* Kompyuter (Windows 10/11);
* Microsoft Office dasturlar to'plami.

### 📄 Amaliy Mashg'ulot Shabloni:
{% hint style="success" %}
**📄 Rasmiy Amaliy Mashg'ulot va Uy Vazifasi Shabloni (Google Docs (Hujjat)):**
Ushbu darsning barcha bosqichlarini bajarish, natijalar/hisobotlarni kiritish va uy vazifasini topshirish uchun quyidagi rasmiy shablondan foydalaning:
* 🌐 **Onlayn ko'rish va tahrirlash:** <a href="https://docs.google.com/document/d/14Tu2cZOyq7zJqPbV1s0n1-r6jTS2zc3_5f73rulnUQ8/edit?usp=sharing" target="_blank" rel="noopener noreferrer">11-Mavzu: Microsoft Office Paketiga Kirish — Shablonni ochish</a>
* 📥 **Shaxsiy Drive-ga nusxalash (Tavsiya etiladi):** <a href="https://docs.google.com/document/d/14Tu2cZOyq7zJqPbV1s0n1-r6jTS2zc3_5f73rulnUQ8/copy" target="_blank" rel="noopener noreferrer">Nusxa yaratish (Make a copy)</a>
{% endhint %}

{% embed url="https://docs.google.com/document/d/14Tu2cZOyq7zJqPbV1s0n1-r6jTS2zc3_5f73rulnUQ8/preview" %}

> *Eslatma: Shablondan nusxa oling va quyidagi 6 ta qadamni bajarib hisobotga joylang.*

### Bajarish Bosqichlari:

1. **1-Qadam:** Start menyusini oching va **Word** dasturini ishga tushiring.
2. **2-Qadam (Versiyani aniqlash):** Chap pastki burchakdagi **Account (Учетная запись)** bo'limiga kiring. "Product Information" qismida Office versiyasi (masalan: Microsoft Office 2019 Professional Plus) va litsenziya holatini aniqlab, skrinshot oling.
3. **3-Qadam (Shablon tanlash):** Bosh sahifaga qayting (**Home -> More templates / Другие шаблоны**). Qidiruv qatoriga "Resume" yoki "Rezyume" deb yozing.
4. **4-Qadam:** O'zingizga ma'qul kelgan rezyume shablonini tanlang va **Create (Создать)** tugmasini bosing.
5. **5-Qadam:** Shablon ichidagi ism-familiya, mutaxassislik va ma'lumotlarni o'zingizga moslab qisqacha o'zgartiring.
6. **6-Qadam (Saqlash va eksport):** Hujjatni `FIO_Rezyume.docx` nomi bilan saqlang (`Ctrl + S`), so'ng **File -> Export -> Create PDF/XPS** orqali PDF nusxasini ham hosil qiling.

{% hint style="warning" %}
**Ehtiyot bo'ling:**
Agar Office dasturingiz yuqori qismida qizil tasmada "Product Activation Failed" (Litsenziya muddati tugagan) xabari chiqsa, ko'p funksiyalar (matn tahrirlash, saqlash) bloklanib qoladi. Har doim qonuniy litsenziyadan foydalaning.
{% endhint %}

---

## 4. 🛠 Real Ish Vaziyati va Muammolarni Hal Qilish (Case-Study)

### Muammo:
Mijoz o'zining eski kompyuterida (Office 2003) tayyorlangan muhim hisobot faylini (`Hisobot.doc`) zamonaviy kompyuterda (Office 2021) ochdi. Hujjat yuqori sarlavhasida **[Compatibility Mode] (Режим ограниченной функциональности)** yozuvi chiqib qoldi. Natijada zamonaviy jadvallar, yangi formulalar va dizayn uslublarini kiritish bloklandi, mavjud shriftlar esa chalkashib ketdi.

### Muammoning Kelib Chiqish Sababi:
Fayl 20 yillik eski binar `.doc` formatida saqlangani uchun zamonaviy Word dasturi uni eski xatoliklardan himoyalash maqsadida cheklangan rejimda ochgan.

### Bosqichma-bosqich Yechim:
1. Word dasturida hujjat ochilgan holatda **File (Файл) -> Info (Сведения)** bo'limiga kiring.
2. Eng yuqoridagi **Convert (Преобразовать)** tugmasini bosing.
3. Tizim hujjatni zamonaviy XML arxitekturasiga (`.docx`) aylantirishini ma'lum qiladi — **OK** tugmasini bosing.
4. Hujjat bir zumda zamonaviy formatga o'tadi, cheklovlar yechiladi, fayl hajmi kichrayadi va barcha zamonaviy dizayn asboblari faollashadi.

---

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz — 25 ta Savol, 100 Ball)

{% hint style="info" %}
**📝 Rasmiy Onlayn Test Sinovi (Google Forms — 25 ta savol, 100 ballik baholash):**
Ushbu dars bo'yicha olgan bilimlaringizni sinash uchun quyidagi rasmiy testni topshiring (Har bir to'g'ri javob 4 ball, jami: 100 ball):
* 🔗 **Onlayn Testni Ochish (To'liq Ekranda):** <a href="https://docs.google.com/forms/d/e/1FAIpQLScB2JiSccN78xpXw-QbEPLVilv3cyLqp8hpGsUHhGRfDsBp6w/viewform" target="_blank" rel="noopener noreferrer">11-Mavzu: Microsoft Office Paketiga Kirish — Testni Topshirish</a>
* 📊 **Kunlik Natijalar va Ballar Jadvali:** <a href="https://docs.google.com/spreadsheets/d/1qNzEUe8nE08H6c3qFklLAFT7RdOTC8zZC8O9MCGgwRg/edit" target="_blank" rel="noopener noreferrer">Google Sheets — Natijalar Jadvali</a>
{% endhint %}

{% embed url="https://docs.google.com/forms/d/e/1FAIpQLScB2JiSccN78xpXw-QbEPLVilv3cyLqp8hpGsUHhGRfDsBp6w/viewform" %}

---

## 6. 🏠 Mustaqil Amaliy Uyga Vazifa

### Topshiriq:
1. Kompyuteringizdagi Office dasturlari ro'yxatini va versiyasini ko'zdan kechiring.
2. Excel, Word va PowerPoint dasturlarining har birini bir marta ishga tushirib, ularning boshlang'ich interfeysini solishtiring.
3. Word dasturida mavjud shablonlar (Templates) asosida bitta xatboshi rasmiy xat (Letter) tayyorlang va `.docx` hamda `.pdf` shaklida saqlang.

**Topshirish formati:** Tayyorlangan fayl va skrinshotlarni `FIO_11-Mavzu_Office.docx` nomi bilan platformaga yuklang.

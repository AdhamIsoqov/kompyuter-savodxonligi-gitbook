# 19-Mavzu: 2-Modul Amaliy Loyihasi: Kompleks Ofis Hujjatlari Paketi

{% hint style="info" %}
**Dars maqsadi:** 2-Modulda o'rganilgan uchta asosiy ofis dasturini — Microsoft Word (rasmiy xat/hisobot), Microsoft Excel (moliyaviy hisob-kitoblar va diagrammalar) hamda Microsoft PowerPoint (loyihaning 5–6 slaydli vizual taqdimoti) dasturlarini yagona real biznes loyihasi doirasida integratsiyalash va to'liq paket tayyorlash.
{% endhint %}

### 🎯 Kutilayotgan Kompetensiyalar
* **Bilishingiz kerak:**
  * Ofis dasturlari o'rtasida ma'lumotlar almashinuvi va dinamik bog'liqlik (OLE — Object Linking and Embedding).
  * Korxona hujjatlar aylanishi zanjiri: Hisob-kitob (Excel) -> Rasmiy hujjat (Word) -> Taqdimot (PowerPoint).
  * Hujjatlarni arxivlash, PDF ga eksport qilish va mijozga professional topshirish etikasi.
* **Bajara olishingiz kerak:**
  * Word dasturida rasmiy standartlarga javob beruvchi rasmiy loyiha taklifini formatlash.
  * Excelda `SUM`, `AVERAGE`, `IF` formulalari va dinamik diagrammaga ega moliyaviy smeta tuzish.
  * Exceldagi diagrammani PowerPoint taqdimotiga jonli havola (Paste Link) orqali ko'chirib, professional slayd-shou shakllantirish.

---

## 🎬 1. Video Dars

{% hint style="info" %}
**Video darslik:** 2-Modul amaliy loyihasini bajarish va dasturlar integratsiyasi bo'yicha quyidagi videoni tomosha qiling:
{% endhint %}

[Iframe/Embed: 19-Mavzu Bo'yicha YouTube Video Dars Havolasi]

---

## 2. 📖 Nazariy Integratsiya: Ofis Dasturlari Hamkorligi

Real ish faoliyatida hech bir ofis dasturi alohida ishlatilmaydi. Ular yagona mexanizm sifatida ishlaydi:

```
+-------------------------------------------------------------------------+
|                  2-MODUL KOMPLEKS BIZNES LOYIHASI                       |
+-------------------------------------------------------------------------+
|  1. Microsoft Excel:     2. Microsoft Word:       3. Microsoft          |
|                          (Tijoriy Taklif)         PowerPoint:           |
|  - Xarajatlar smetasi    - Rasmiy matn va ariza   - 5-6 slaydli loyiha  |
|  - SUM, AVERAGE, IF      - Formatlangan jadvallar - Excel diagrammasi   |
|  - Dinamik diagramma     - Avtomatik mundarija    - Transitions va Fade |
+-------------------------------------------------------------------------+
                                    │
                                    ▼
       [Yagona Loyiha Papkasi: Loyiha_2026_FIO/] ---> USB / PDF Export
```

{% hint style="success" %}
**Pro-Tip (Excel diagrammasini PowerPointga "jonli" ulash):**
Exceldagi diagrammani `Ctrl + C` qilib, PowerPointga shunchaki `Ctrl + V` qilsangiz, Excelda sonlar o'zgarganda slayd o'zgarmay qoladi.
Buning o'rniga PowerPointda: **Paste (Вставить) -> Paste Special (Специальная вставка) -> Paste Link (Связать)** ni tanlang! Endi Excelda 1 ta son o'zgarsa ham, PowerPoint taqdimotidagi diagramma o'z-o'zidan yangilanadi!
{% endhint %}

---

## 3. 💻 Bosqichma-bosqich Amaliy Mashg'ulot (Lab Task)

Ushbu loyihada siz "Kompaniya Kompyuter Parkini Yangilash" mavzusida to'liq 3 ta hujjatdan iborat to'plam tayyorlaysiz.

### Kerakli Resurslar:
* Microsoft Word, Excel va PowerPoint dasturlari;
* Amaliy loyiha topshiriq shabloni.

### 📄 Amaliy Mashg'ulot Shabloni:
{% hint style="success" %}
**📄 Rasmiy Amaliy Mashg'ulot va Uy Vazifasi Shabloni (Google Docs (Hujjat)):**
Ushbu darsning barcha bosqichlarini bajarish, natijalar/hisobotlarni kiritish va uy vazifasini topshirish uchun quyidagi rasmiy shablondan foydalaning:
* 🌐 **Onlayn ko'rish va tahrirlash:** [19-Mavzu: 2-Modul Amaliy Loyihasi — Shablonni ochish](https://docs.google.com/document/d/12cIhpUlo_1P9LR2-Z4iJ1EBhhAmsRRI3pI5eKmKZD5w/edit?usp=sharing)
* 📥 **Shaxsiy Drive-ga nusxalash (Tavsiya etiladi):** [Nusxa yaratish (Make a copy)](https://docs.google.com/document/d/12cIhpUlo_1P9LR2-Z4iJ1EBhhAmsRRI3pI5eKmKZD5w/copy)
{% endhint %}

{% embed url="https://docs.google.com/document/d/12cIhpUlo_1P9LR2-Z4iJ1EBhhAmsRRI3pI5eKmKZD5w/preview" %}

> *Eslatma: Shablondan nusxa oling va quyidagi 3 ta bosqich natijalarini to'liq bajaring.*

### Bajarish Bosqichlari:

#### 1-Bosqich: Microsoft Excel (Smeta tuzish)
1. Yangi Excel fayl ochib, 5 xil kompyuter qismlari (Protsessor, Ona plata, RAM, SSD, Quvvat bloki) narxi va sonini kiriting.
2. Jami summani hisoblash uchun ko'paytirish va pastida `=SUM(...)` formulasini yozing.
3. O'rtacha narxni `=AVERAGE(...)` orqali chiqaring.
4. Ushbu smeta asosida chiroyli **Ustunli (Column)** diagramma hosil qiling va faylni `01_Smeta.xlsx` qilib saqlang.

#### 2-Bosqich: Microsoft Word (Rasmiy hisobot tayyorlash)
1. Yangi Word fayl oching (Times New Roman, 14 pt, 1.15 interval, Justify).
2. Rahbariyat nomiga "Kompyuter parkini yangilash haqida" rasmiy bildirishnoma matnini yozing.
3. Exceldagi smeta jadvalini Word hujjati ichiga chiroyli qilib joylang va sarlavhasiga Header qo'shing.
4. Faylni `02_Bildirishnoma.docx` va `02_Bildirishnoma.pdf` shaklida saqlang.

#### 3-Bosqich: Microsoft PowerPoint (Rahbariyat uchun taqdimot)
1. 5 ta slayddan iborat taqdimot yarating:
   * *1-Slayd:* Titul (Loyiha nomi va muallif)
   * *2-Slayd:* Loyihaning maqsadi va muammolar
   * *3-Slayd:* Taklif etilayotgan yangi uskunalar ro'yxati (Bullets)
   * *4-Slayd:* Exceldan ko'chirilgan smeta diagrammasi (Grafik)
   * *5-Slayd:* Kutilayotgan samaradorlik va xulosa
2. Barcha slaydlarga Fade o'tishini bering va faylni `03_Taqdimot.pptx` qilib saqlang.

#### 4-Bosqich: Birlashtirish
* Ish stolida `Loyiha_Kompyuter_FIO` papkasini oching va barcha 3 ta faylni ushbu papkaga jamlang.

{% hint style="warning" %}
**Ehtiyot bo'ling:**
Word va PowerPoint hujjatlariga kiritilgan ma'lumotlar bilan Excel smetasidagi raqamlar bir-biriga 100% mos kelishi shart. Raqamlardagi nomuvofiqlik loyiha bahosining pasayishiga olib keladi.
{% endhint %}

---

## 4. 🛠 Real Ish Vaziyati va Muammolarni Hal Qilish (Case-Study)

### Muammo:
Katta yig'ilishda bosh muhandis loyiha taqdimotini namoyish qilayotgan paytda, bosh hisobchi: *"Ehtiyot qismlar narxi kecha 10% ga arzonlashdi, taqdimotdagi raqamlar eskiribdi"*, deb e'tiroz bildirdi. Bosh muhandis esa Exceldagi yangilangan fayldan raqamlarni qaytadan ko'chirib, slaydlarni tuzatish uchun 30 daqiqa yig'ilishni to'xtatishga majbur bo'ldi.

### Muammoning Kelib Chiqish Sababi:
Diagrammalar PowerPointga shunchaki statik rasm (Skrinshot) sifatida ko'chirilgan, dasturlar o'rtasidagi OLE (jonli havola) funksiyasidan foydalanilmagan.

### Bosqichma-bosqich Yechim:
1. Excelda narxlar o'zgarganda, PowerPointdagi diagramma ustiga sichqonchaning o'ng tugmasini bosing.
2. **Update Link (Обновить связь)** buyrug'ini tanlang.
3. PowerPointdagi barcha ustunlar, raqamlar va foizlar bor-yo'g'i **1 soniyada** Exceldagi yangi narxlarga avtomatik moslashadi, taqdimotni qaytadan yasash talab etilmaydi!

---

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz)

{% hint style="info" %}
**Onlayn Test:** 2-Modul amaliy loyihasi bo'yicha olgan bilimlaringizni sinab ko'rish uchun quyidagi Google Forms testini topshiring:
{% endhint %}

{% hint style="info" %}
**📝 Rasmiy Bilimni Tekshirish Testi (Google Forms — 25 ta savol, 100 ballik baholash):**
Ushbu dars bo'yicha bilimlaringizni sinash uchun quyidagi 25 ta savoldan iborat rasmiy testni topshiring (Har bir to'g'ri javob 4 ball, jami: 100 ball):
* 🔗 **Testni to'liq ekranda ochish:** [19-Mavzu: 2-Modul Amaliy Loyihasi — Testni topshirish](https://docs.google.com/forms/d/e/1FAIpQLSdRGSd1OWRb5plWdpDI8aXV5c2vfNAzmAyiJ_b_0BqIv3IW4w/viewform)
* 📊 **Natijalar va ballar jadvali:** [Google Sheets — Natijalar Jadvali](https://docs.google.com/spreadsheets/d/1mF5dPEZHquy2gjxGAk4fy2WwuIbFbg0Ta9rxU6vHzEU/edit)
{% endhint %}

{% embed url="https://docs.google.com/forms/d/e/1FAIpQLSdRGSd1OWRb5plWdpDI8aXV5c2vfNAzmAyiJ_b_0BqIv3IW4w/viewform" %}

### ✍️ O'z-o'zini Tekshirish Uchun Test Savollari:

#### Test 1: Excel jadvali va diagrammasini PowerPointga o'zgarishlar avtomatik yangilanadigan qilib ko'chirish qaysi buyruq orqali bajariladi?
- ( ) A) Oddiy `Ctrl + V`
- (x) B) Paste Special -> Paste Link (Maxsus qo'yish -> Bog'lash)
- ( ) C) Skrinshot orqali
- ( ) D) Save As orqali
*Izoh: Paste Link ikki fayl o'rtasida jonli OLE ko'prigini o'rnatadi.*

#### Test 2: Rasmiy hisobot hujjatining boshqa kompyuterlarda shrifitlari buzilmasdan, aynan bir xil ochilishini kafolatlovchi yakuniy eksport formati qaysi?
- ( ) A) `.txt`
- (x) B) `.pdf`
- ( ) C) `.dotx`
- ( ) D) `.rtf`
*Izoh: PDF fayllar har qanday qurilma va operatsion tizimda o'zgarmas qotirilgan formatda ochiladi.*

#### Test 3: Word dasturida tayyorlangan hisobot ichiga Excel elektron jadvalini kiritish uchun qaysi menyudan foydalaniladi?
- ( ) A) Home -> Styles
- (x) B) Insert -> Table -> Excel Spreadsheet (yoki Object)
- ( ) C) Design -> Watermark
- ( ) D) References -> Citations
*Izoh: Insert orqali to'g'ridan-to'g'ri Word ichida Excel jadval modulini ishlatish mumkin.*

#### Test 4: PowerPoint taqdimotida auditoriya diqqatini chalg'itmaslik uchun slaydlar soni va matn qanday bo'lishi maqbul?
- ( ) A) Har bir slaydda 50 qatordan matn bo'lishi kerak
- (x) B) 5–6 ta ixcham slayd, asosiy e'tibor diagramma va kalit so'zlarga qaratilgan bo'lishi kerak
- ( ) C) 100 ta slayd bo'lishi kerak
- ( ) D) Faqat qora fonda bo'lishi kerak
*Izoh: Loyiha taqdimotida lakonik, tushunarli va vizual diagrammalarga boy slaydlar eng samarali hisoblanadi.*

#### Test 5: Excel smetasidagi barcha qismlar narxlarining umumiy yig'indisini hisoblovchi standart formula qaysi?
- ( ) A) `=COUNT(...)`
- (x) B) `=SUM(...)`
- ( ) C) `=MAX(...)`
- ( ) D) `=IF(...)`
*Izoh: Smeta xarajatlarining umumiy jamini `SUM` formulasi chiqaradi.*

### 🤔 O'ylantiruvchi Mantiqiy Savollar:
1. Nima uchun yirik loyihalarni topshirishda mijozga barcha fayllarni bitta tartibli papkaga jamlab, ZIP arxiv holatida yuborish professional etika hisoblanadi?
2. Agar Excel fayl kompyuterda boshqa joyga ko'chirilsa, PowerPointdagi "Paste Link" bilan ulangan diagramma nima bo'ladi?
3. Word hujjatini chop etishdan oldin PDF formatiga o'tkazib tekshirish foydalanuvchini qanday kutilmagan xatoliklardan asraydi?

---

## 6. 🏠 Mustaqil Amaliy Loyiha Topshirig'i

### Topshiriq:
Ushbu darsning barcha 3 ta bosqichini (Excel smetasi, Word rasmiy hujjati, PowerPoint taqdimoti) o'z kompyuteringizda to'liq bajaring.
Yaratilgan `01_Smeta.xlsx`, `02_Bildirishnoma.docx`, `02_Bildirishnoma.pdf` va `03_Taqdimot.pptx` fayllarini bitta `Loyiha_FIO` papkasiga jamlang va uni ZIP arxiv qiling.

**Topshirish formati:** Tayyorlangan `Loyiha_FIO.zip` arxivini platformaga yuklang.

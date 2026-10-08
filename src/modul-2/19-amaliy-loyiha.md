# 19-Mavzu: 2-Modul Amaliy Loyihasi: Kompleks Ofis Hujjatlari Paketi

Assalomu alaykum! Kasbtech Akademiyasining Kompyuter savodxonligi kursidagi 19-darsimizga xush kelibsiz.

Ushbu dars — 2-Modulimizning ("Microsoft Office Dasturlari") eng muhim amaliy cho'qqisi hisoblanadi. 11-darsdan to 18-darsgacha biz zamonaviy ofisning uchta ustuni — **Word (matn va rasmiy blanklar)**, **Excel (formulalar, jadvallar va tahliliy diagrammalar)** hamda **PowerPoint (dinamik slaydlar va taqdimotlar)** bilan bosqichma-bosqich tanishdik.

Haqiqiy biznes muhitida yoki davlat tashkilotlarida hech qaysi dastur alohida ajratilgan holda ishlatilmaydi. Har qanday jiddiy loyiha moliya va hisob-kitob (Excel), rasmiy hisobot va xat (Word) hamda rahbariyatga namoyish etish (PowerPoint) zanjirini o'z ichiga oladi. Bugungi darsda biz barcha o'rgangan bilimlarimizni umumlashtirib, professional va yaxlit hujjatlar paketini tayyorlaymiz.

Kelgusi 3-Modulimizda (20-dars) esa ushbu fayllarni internet tarmog'i orqali xavfsiz almashish, Google bulutli xizmatlari va eng so'nggi Sun'iy Intellekt (AI) texnologiyalaridan amaliy foydalanish olamiga qadam qo'yamiz.

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
  * Loyiha fayllarini bitta tizimli papkaga jamlab, ZIP formatida arxivlash (3-dars ko'nikmasi).

## 🎬 1. Video Dars

{% hint style="info" %}
**Video darslik:** 2-Modul amaliy loyihasini bajarish va dasturlar integratsiyasi bo'yicha quyidagi videoni tomosha qiling:
{% endhint %}

[Iframe/Embed: 19-Mavzu Bo'yicha YouTube Video Dars Havolasi]

## 2. 📖 Chuqurlashtirilgan Nazariy Ma'ruza

### 2.1. OLE (Object Linking and Embedding) Texnologiyasi

Real ish faoliyatida ma'lumotlar bir dasturdan ikkinchisiga ko'chib yuradi. Microsoft kompaniyasi ushbu dasturlar o'rtasida ma'lumot almashish uchun **OLE** tizimini yaratgan:

* **Embedding (Ichiga joylash):** Obyekt shunchaki nusxalanadi (masalan, Word ichida Excel jadvali paydo bo'ladi, lekin asl fayl bilan aloqa uziladi).
* **Linking (Jonli havola bog'lash):** Obyekt ikkinchi dasturga havola orqali ulanadi. Asl Excel faylidagi raqam o'zgarishi bilan Word va PowerPointdagi grafiklar avtomatik yangilanadi.

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
       [Yagona Loyiha Papkasi: Loyiha_2026_FIO/] ---> ZIP / PDF Export
```

### 2.2. Hujjatlarni Standartlashtirish va Eksport Etikasi

Loyiha tayyorlanganda mijozga yoki rahbariyatga xom `.docx` yoki `.xlsx` fayllarni yuborish ba'zan xavflidir — boshqa kompyuterda shriftlar buzilishi yoki formulalar adashib o'chib ketishi mumkin.

Shuning uchun quyidagi qoidalarga qat'iy amal qilinadi:
1. **Yakuniy hisobot — har doim PDF:** Matnli hujjat o'zgarmas holatda bo'lishi uchun **PDF (Portable Document Format)** shaklida eksport qilinadi (`F12` -> Save as type: PDF).
2. **Namoyish uchun `.ppsx` formati:** Taqdimot taqdim etilganda tahrirlash darchasi emas, bir zumda to'liq ekranda ochiladigan PowerPoint Show (`.ppsx`) ishlatiladi.
3. **Arxivlash tartibi:** Barcha 3 xil hujjatlar 3-darsda o'rganganimizdek maxsus nomlash qoidasi bilan bitta papkaga yig'iladi va ZIP formatida siqiladi.

{% hint style="success" %}
**Pro-Tip (Excel diagrammasini PowerPointga "jonli" ulash):**
Exceldagi diagrammani `Ctrl + C` qilib, PowerPointga shunchaki `Ctrl + V` qilsangiz, Excelda sonlar o'zgarganda slayd o'zgarmay qoladi.
Buning o'rniga PowerPointda: **Paste (Вставить) -> Paste Special (Специальная вставка) -> Paste Link (Связать)** ni tanlang! Endi Excelda 1 ta son o'zgarsa ham, PowerPoint taqdimotidagi diagramma o'z-o'zidan yangilanadi!
{% endhint %}

## 3. 💻 Bosqichma-bosqich Amaliy Mashg'ulot (Lab Task)

Ushbu loyihada siz "Kompaniya Kompyuter Parkini Yangilash" mavzusida to'liq 3 ta hujjatdan iborat to'plam tayyorlaysiz.

### Kerakli Resurslar:
* Microsoft Word, Excel va PowerPoint dasturlari;
* Amaliy loyiha topshiriq shabloni.

### 📄 Amaliy Mashg'ulot Shabloni:
{% hint style="success" %}
**📄 Rasmiy Amaliy Mashg'ulot va Uy Vazifasi Shabloni (Google Docs (Hujjat)):**
Ushbu darsning barcha bosqichlarini bajarish, natijalar/hisobotlarni kiritish va uy vazifasini topshirish uchun quyidagi rasmiy shablondan foydalaning:
* 🌐 **Onlayn ko'rish va tahrirlash:** <a href="https://docs.google.com/document/d/12cIhpUlo_1P9LR2-Z4iJ1EBhhAmsRRI3pI5eKmKZD5w/edit?usp=sharing" target="_blank" rel="noopener noreferrer">19-Mavzu: 2-Modul Amaliy Loyihasi — Shablonni ochish</a>
* 📥 **Shaxsiy Drive-ga nusxalash (Tavsiya etiladi):** <a href="https://docs.google.com/document/d/12cIhpUlo_1P9LR2-Z4iJ1EBhhAmsRRI3pI5eKmKZD5w/copy" target="_blank" rel="noopener noreferrer">Nusxa yaratish (Make a copy)</a>
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

## 4. 🛠 Real Ish Vaziyati va Muammolarni Hal Qilish (Case-Study)

### Muammo:
Katta yig'ilishda bosh muhandis loyiha taqdimotini namoyish qilayotgan paytda, bosh hisobchi: *"Ehtiyot qismlar narxi kecha 10% ga arzonlashdi, taqdimotdagi raqamlar eskiribdi"*, deb e'tiroz bildirdi. Bosh muhandis esa Exceldagi yangilangan fayldan raqamlarni qaytadan ko'chirib, slaydlarni tuzatish uchun 30 daqiqa yig'ilishni to'xtatishga majbur bo'ldi.

### Muammoning Kelib Chiqish Sababi:
Diagrammalar PowerPointga shunchaki statik rasm (Skrinshot) sifatida ko'chirilgan, dasturlar o'rtasidagi OLE (jonli havola) funksiyasidan foydalanilmagan.

### Bosqichma-bosqich Yechim:
1. Excelda narxlar o'zgarganda, PowerPointdagi diagramma ustiga sichqonchaning o'ng tugmasini bosing.
2. **Update Link (Обновить связь)** buyrug'ini tanlang.
3. PowerPointdagi barcha ustunlar, raqamlar va foizlar bor-yo'g'i **1 soniyada** Exceldagi yangi narxlarga avtomatik moslashadi, taqdimotni qaytadan yasash talab etilmaydi!

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz)

{% hint style="info" %}
**📝 Rasmiy Onlayn Test Sinovi (Google Forms — 15 ta saralangan savol, 100 ballik baholash):**
Ushbu dars bo'yicha olgan bilimlaringizni sinash uchun quyidagi rasmiy testni topshiring (15 ta saralangan test savoli, jami: 100 ball):
* 🔗 **Onlayn Testni Ochish (To'liq Ekranda):** <a href="https://docs.google.com/forms/d/e/1FAIpQLSdRGSd1OWRb5plWdpDI8aXV5c2vfNAzmAyiJ_b_0BqIv3IW4w/viewform" target="_blank" rel="noopener noreferrer">19-Mavzu: 2-Modul Amaliy Loyihasi — Testni Topshirish</a>
* 📊 **Kunlik Natijalar va Ballar Jadvali:** <a href="https://docs.google.com/spreadsheets/d/1mF5dPEZHquy2gjxGAk4fy2WwuIbFbg0Ta9rxU6vHzEU/edit" target="_blank" rel="noopener noreferrer">Google Sheets — Natijalar Jadvali</a>
{% endhint %}

{% embed url="https://docs.google.com/forms/d/e/1FAIpQLSdRGSd1OWRb5plWdpDI8aXV5c2vfNAzmAyiJ_b_0BqIv3IW4w/viewform" %}

## 6. 🏠 Mustaqil Amaliy Loyiha Topshirig'i

### Topshiriq:
Ushbu darsning barcha 3 ta bosqichini (Excel smetasi, Word rasmiy hujjati, PowerPoint taqdimoti) o'z kompyuteringizda to'liq bajaring.
Yaratilgan `01_Smeta.xlsx`, `02_Bildirishnoma.docx`, `02_Bildirishnoma.pdf` va `03_Taqdimot.pptx` fayllarini bitta `Loyiha_FIO` papkasiga jamlang va uni ZIP arxiv qiling.

**Topshirish formati:** Tayyorlangan `Loyiha_FIO.zip` arxivini platformaga yuklang.

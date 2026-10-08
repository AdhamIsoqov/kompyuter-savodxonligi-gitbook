# 13-Mavzu: Microsoft Word Kengaytirilgan Imkoniyatlari: Jadvallar, Grafik Obyektlar va Mundarija

12-darsimizda rasmiy hujjat formatlashning asosiy qoidalarini — shrift, tekislash, xatboshi va qatorlar oralig'ini o'rgandik. Endi Word'ning kuchli tomoni bo'lgan murakkab imkoniyatlarini — jadvallar, grafikalar va avtomatik mundarijani o'rganish vaqti keldi.

Katta hujjatlar — dissertatsiyalar, yillik hisobotlar, loyihalar — faqat formatlangan matndan iborat emas. Ularda jadvallar, sxemalar, rasmlar va mundarija bo'ladi. Bu elementlarni professional tarzda kiritish bilmasangiz, hujjat tartibizdek ko'rinmaydi. Bugungi darsda Word'ning haqiqiy kuchini ko'rasiz!

{% hint style="info" %}
**Dars maqsadi:** Word hujjatlarida murakkab jadvallarni loyihalash (kataklarni birlashtirish, formatlash), rasmlarni joylash va matn bilan o'rash (Wrap Text), SmartArt orqali tashkiliy blok-sxemalar chizish, kolontitullar (Header/Footer), sahifa raqamlari hamda avtomatik mundarija (Table of Contents) yaratish ko'nikmalarini egallash.
{% endhint %}

### 🎯 Kutilayotgan Kompetensiyalar
* **Bilishingiz kerak:**
  * Jadvallarda kataklarni birlashtirish (Merge) va bo'lish (Split) texnologiyasi.
  * Rasmlarni matn bilan uyg'unlashtirish usullari (In Line with Text, Square, Behind/In Front of Text).
  * Uslublar (Styles: Heading 1, Heading 2) va avtomatik mundarija o'rtasidagi bog'liqlik.
* **Bajara olishingiz kerak:**
  * Chegaralari va fon ranglari moslangan professional jadval tuzish.
  * SmartArt grafik vositasi orqali korxona tuzilmasi yoki ish jarayoni sxemasini chizish.
  * Titul (birinchi) sahifasida raqam ko'rinmaydigan qilib sahifa raqamlarini (Page Numbers) o'rnatish va bitta tugma bilan avtomatik mundarija generatsiya qilish.

## 🎬 1. Video Dars

{% hint style="info" %}
**Video darslik:** Word dasturida jadvallar, grafikalar va avtomatik mundarija yaratish bo'yicha quyidagi videoni tomosha qiling:
{% endhint %}

[Iframe/Embed: 13-Mavzu Bo'yicha YouTube Video Dars Havolasi]

## 2. 📖 Chuqurlashtirilgan Nazariy Ma'ruza

### 2.1. Jadvallar Bilan Professional Ishlash

Jadvallar — hisobotlar va tahliliy ma'lumotlarni ixcham ko'rsatishning asosiy vositasidir. 14-darsimizda Excel jadvallari bilan tanishamiz, lekin ba'zi jadvallar hujjat ichida — Word'da bo'lgani maqbul:

```
+-------------------------------------------------------------+
|              KORXONA HODIMLARI RO'YXATI (Merge Cells)       |
+----+--------------------+---------------+-------------------+
| T/r| F.I.O.             | Lavozimi      | Maoshi (so'm)     |
+----+--------------------+---------------+-------------------+
| 1  | Karimova Dilnoza   | Bosh hisobchi | 8 500 000         |
| 2  | Aliyev Bobur       | Tizim admini  | 9 000 000         |
+----+--------------------+---------------+-------------------+
```

* **Merge Cells (Kataklarni birlashtirish):** Bir nechta katakni belgilab, o'ng tugma orqali yagona keng katakka aylantirish (umumiy sarlavhalar uchun).
* **AutoFit (Avtomatik moslash):** Jadval sahifa hoshiyalaridan chiqib ketmasligi uchun: **Layout -> AutoFit -> AutoFit to Window**.
* **Repeat Header Rows (Sarlavha qatorini takrorlash):** Agar jadval 10 sahifaga cho'zilsa, har bir yangi sahifa boshida jadval ustun nomlari avtomatik qayta chiqadi!

{% hint style="success" %}
**Pro-Tip (Rasm matnni buzib yubormasligi uchun):**
Wordga rasm qo'yganda u ko'pincha matnni surib, sahifani buzib yuboradi. Buning oldini olish uchun rasm ustiga bosing, uning yonida paydo bo'lgan kichik kamalakcha belgisini (**Layout Options**) oching va **Square (Maydon bo'ylab)** yoki **Tight (Zich)** parametrini tanlang. Endi rasmni sahifaning istalgan joyiga erkin surishingiz mumkin, matn esa uning atrofida chiroyli aylanib o'tadi!
{% endhint %}

### 2.2. SmartArt — Grafik Sxemalar Yaratish

SmartArt — tezkor grafik sxema va diagrammalar yaratish vositasi. Oddiy matnni vizual blok-sxemaga aylantiradi:

```
[SmartArt Asosiy Kategoriyalar]
  ├── List (Ro'yxat)        → Oddiy ma'lumot ro'yxatlari
  ├── Process (Jarayon)     → Qadamlarni ko'rsatuvchi oqim sxemasi
  ├── Hierarchy (Iyerarxiya)→ Tashkiliy tuzilma (Direktor→Menejer→Xodim)
  ├── Relationship (Bog'liq)→ Elementlar o'rtasidagi munosabat
  └── Matrix (Matritsa)     → To'rt kvadrantli tahlil
```

Insert → SmartArt → kerakli kategoriya → shablon tanlash → matn kiritish. 5 daqiqada professional diagramma tayyor!

### 2.3. Avtomatik Mundarija (Table of Contents)

Ko'pchilik foydalanuvchilar xato qilib mundarijani qo'lda — nuqtalar qo'yib yozib chiqadilar. Bu sahifalar o'zgarganda xatoliklarga olib keladi.

> **12-darsdan eslatma:** Sarlavha formatlashni o'rgandik — qalin va markazda. Endi bu sarlavhalarni `Heading 1` uslubida belgilab, avtomatik mundarijaga ulash vaqti keldi!

**Avtomatik mundarija yaratishning 3 qadami:**
1. Hujjatdagi har bir katta sarlavhani belgilab, Bosh sahifadagi **Heading 1 (Заголовок 1)** uslubiga o'tkazing.
2. Ichki kichik sarlavhalarni **Heading 2 (Заголовок 2)** ga o'tkazing.
3. Hujjat boshiga (yoki oxiriga) o'tib: **References (Ссылки) -> Table of Contents (Оглавление)** ni bosing. Mundarija sahifa raqamlari bilan bir soniyada avtomatik shakllanadi!

## 3. 💻 Bosqichma-bosqich Amaliy Mashg'ulot (Lab Task)

Ushbu amaliy mashg'ulotda siz jadvallar, SmartArt va avtomatik mundarijadan iborat 3 sahifalik ixcham hisobot tayyorlaysiz.

### Kerakli Resurslar:
* Microsoft Word dasturi;
* Amaliy mashg'ulot shabloni.

### 📄 Amaliy Mashg'ulot Shabloni:
{% hint style="success" %}
**📄 Rasmiy Amaliy Mashg'ulot va Uy Vazifasi Shabloni (Google Docs (Hujjat)):**
Ushbu darsning barcha bosqichlarini bajarish, natijalar/hisobotlarni kiritish va uy vazifasini topshirish uchun quyidagi rasmiy shablondan foydalaning:
* 🌐 **Onlayn ko'rish va tahrirlash:** <a href="https://docs.google.com/document/d/1NmOu9spVeVgOvZX57MIq2ho7jcnh87gSEoNb-ydoqAk/edit?usp=sharing" target="_blank" rel="noopener noreferrer">13-Mavzu: Microsoft Word Kengaytirilgan Imkoniyatlari — Shablonni ochish</a>
* 📥 **Shaxsiy Drive-ga nusxalash (Tavsiya etiladi):** <a href="https://docs.google.com/document/d/1NmOu9spVeVgOvZX57MIq2ho7jcnh87gSEoNb-ydoqAk/copy" target="_blank" rel="noopener noreferrer">Nusxa yaratish (Make a copy)</a>
{% endhint %}

{% embed url="https://docs.google.com/document/d/1NmOu9spVeVgOvZX57MIq2ho7jcnh87gSEoNb-ydoqAk/preview" %}

> *Eslatma: Shablondan nusxa oling va quyidagi 6 ta qadamni bajarib hisobotga joylang.*

### Bajarish Bosqichlari:

1. **1-Qadam:** Yangi Word hujjati oching. **Insert -> Page Number -> Bottom of Page (Plain Number 2)** orqali pastki markazga sahifa raqamini qo'ying.
2. **2-Qadam (Titul sahifasini tozalash):** Header & Footer menyusidan **Different First Page (Особый колонтитул для первой страницы)** bandiga galochka qo'ying (birinchi sahifadan raqam yo'qoladi, 2-sahifadan boshlab 2, 3... deb davom etadi).
3. **3-Qadam (Jadval yasash):** 2-sahifaga o'ting, **Insert -> Table** orqali 4x4 o'lchamli jadval chizing. Birinchi qatorni belgilab, **Merge Cells** qiling va "2026-Yil Ish Rejasi" deb nomlang.
4. **4-Qadam (SmartArt diagramma):** 3-sahifaga o'ting, **Insert -> SmartArt -> Hierarchy (Iyerarxiya)** bo'limidan tashkiliy tuzilma shablonini tanlang (Direktor -> Menejer -> Mutaxassis) va to'ldiring.
5. **5-Qadam (Sarlavhalarga uslub berish):** 2-sahifadagi sarlavhaga **Heading 1**, 3-sahifadagi sarlavhaga ham **Heading 1** uslubini bering.
6. **6-Qadam (Mundarija generatsiyasi):** 1-sahifaga qayting, **References -> Table of Contents -> Automatic Table 1** ni bosing. Tayyor mundarija paydo bo'lganini ko'ring va faylni `Hisobot_Mundarija.docx` qilib saqlang.

{% hint style="warning" %}
**Ehtiyot bo'ling:**
Mundarija yaratilgandan so'ng hujjat matniga biror o'zgartirish kiritsangiz yoki yangi sahifalar qo'shilsa, mundarija ustiga sichqonchaning o'ng tugmasini bosib **Update Field -> Update entire table (Обновить целиком)** buyrug'ini berishni unutmang!
{% endhint %}

## 4. 🛠 Real Ish Vaziyati va Muammolarni Hal Qilish (Case-Study)

### Muammo:
Magistrant 80 betlik dissertatsiya yozdi va mundarijani qo'lda har bir betga qarab nuqta bosib yozib chiqdi. Himoyadan oldin ilmiy rahbar ishning boshiga 3 bet yangi matn kiritishni talab qildi. Natijada dissertatsiyaning barcha 80 betidagi mavzular 3 sahifaga surilib ketdi va qo'lda yozilgan butun mundarijadagi raqamlar xato bo'lib qoldi. Qayta sanab chiqish uchun 1 kun vaqt talab etiladi.

### Muammoning Kelib Chiqish Sababi:
Hujjatda Wordning avtomatlashtirilgan uslublari (Styles: Heading 1, Heading 2) va avtomatik mundarija funksiyasidan foydalanilmagan.

### Bosqichma-bosqich Yechim:
1. Qo'lda yozilgan xato mundarijani butunlay o'chirib tashlang.
2. Hujjat bo'ylab har bir bob va fasl sarlavhasini tanlab, tezkor tarzda **Heading 1** (Boblar) va **Heading 2** (Paragraflar) uslubiga o'tkazing (bu bor-yo'g'i 5 daqiqa oladi).
3. Tituldan keyingi bo'sh sahifaga o'tib, **References -> Table of Contents -> Automatic Table** tugmasini bosing.
4. Barcha 80 sahifalik boblar va ularning to'g'ri yangi sahifa raqamlari 2 soniyada ideal holatda qayta tiklanadi!

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz)

{% hint style="info" %}
**📝 Rasmiy Onlayn Test Sinovi (Google Forms — 15 ta saralangan savol, 100 ballik baholash):**
Ushbu dars bo'yicha olgan bilimlaringizni sinash uchun quyidagi rasmiy testni topshiring (15 ta saralangan test savoli, jami: 100 ball):
* 🔗 **Onlayn Testni Ochish (To'liq Ekranda):** <a href="https://docs.google.com/forms/d/e/1FAIpQLSen0OyBOSvYYLeYqIg8vUy_NvZlbmDildZNnbOUEYMvTF-1CQ/viewform" target="_blank" rel="noopener noreferrer">13-Mavzu: Microsoft Word Kengaytirilgan Imkoniyatlari — Testni Topshirish</a>
* 📊 **Kunlik Natijalar va Ballar Jadvali:** <a href="https://docs.google.com/spreadsheets/d/1m_kH9VlBLMT9KBXVaiULVTu6fF94SYPqNv7FmBL1F0I/edit" target="_blank" rel="noopener noreferrer">Google Sheets — Natijalar Jadvali</a>
{% endhint %}

{% embed url="https://docs.google.com/forms/d/e/1FAIpQLSen0OyBOSvYYLeYqIg8vUy_NvZlbmDildZNnbOUEYMvTF-1CQ/viewform" %}

## 6. 🏠 Mustaqil Amaliy Uyga Vazifa

### Topshiriq:
1. Microsoft Word dasturida kamida 3 sahifalik "Mening shaxsiy loyiham" nomli hujjat tayyorlang.
2. Hujjat ichiga 1 ta birlashtirilgan katakli jadval, 1 ta matn bilan o'ralgan (Square) rasm va 1 ta SmartArt iyerarxik sxemasi joylang.
3. Sarlavhalarga Heading 1 va Heading 2 uslublarini berib, birinchi sahifaga avtomatik mundarija joylashtiring.
4. Birinchi sahifada raqam ko'rinmaydigan qilib pastki sahifa raqamlarini o'rnating.

**Topshirish formati:** Hujjatni `FIO_13-Mavzu_Word_Kengaytirilgan.docx` nomi bilan platformaga yuklang.

---

> **Keyingi dars anonsi:**
> *Keyingi 14-darsimizda Microsoft Office to'plamining ikkinchi quvvatli dasturi — Excel bilan tanishamiz. Katak koordinatalari, ma'lumot turlari, AutoFill sehrli dastagi va professional jadval dizayni!*

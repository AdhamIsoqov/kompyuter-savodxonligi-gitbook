# 14-Mavzu: Microsoft Excel Asoslari: Kataklar, Ma'lumot Turlari va Jadval Dizayni

{% hint style="info" %}
**Dars maqsadi:** Microsoft Excel elektron jadval dasturining arxitekturasi, kataklar koordinata tizimi (Name Box), Formula Bar, ma'lumot turlari (matn, son, sana, valyuta), AutoFill (avtomatik to'ldirish markeri) imkoniyatlari hamda professional jadval formatlash ko'nikmalarini egallash.
{% endhint %}

### 🎯 Kutilayotgan Kompetensiyalar
* **Bilishingiz kerak:**
  * Excel'da matn va sonli ma'lumotlarning tekislanish qoidasi (matn chapga, sonlar avtomatik o'ngga tekislanadi).
  * Katak manzili tuzilishi (Ustun harfi + Satr raqami: masalan `B4`).
  * Katakdagi `###` xatolik belgisi nimani anglatishi.
* **Bajara olishingiz kerak:**
  * AutoFill dastagi yordamida ketma-ketliklarni (1, 2, 3... yoki haftaning kunlari) 1 soniyada avtomatik to'ldirish.
  * Ustun va satr kengliklarini ma'lumot hajmiga avtomatik moslash (AutoFit).
  * Kataklarni birlashtirish (Merge & Center), matnni o'rash (Wrap Text) va chegaralar (All Borders) chizish.

---

## 🎬 1. Video Dars

{% hint style="info" %}
**Video darslik:** Excel interfeysi va birinchi jadvalni yaratish bo'yicha quyidagi videoni tomosha qiling:
{% endhint %}

[Iframe/Embed: 14-Mavzu Bo'yicha YouTube Video Dars Havolasi]

---

## 2. 📖 Chuqurlashtirilgan Nazariy Ma'ruza

### 2.1. Excel Interfeysi va Koordinata Tizimi

Excel ish kitobi (Workbook) alohida varaqlardan (Sheets) iborat. Har bir varaq 1 048 576 ta satr va 16 384 ta ustundan tashkil topgan ulkan kataklar to'ridir.

```
       A            B            C            D
   +------------+------------+------------+------------+
 1 | Name Box   | Formula Bar: [ fx ]                  |
   +------------+------------+------------+------------+
 2 | T/r        | Mahsulot   | Narxi      | Miqdori    |
   +------------+------------+------------+------------+
 3 | 1          | Monitor    | 1 800 000  | 5          | <--- Katak (Cell C3)
   +------------+------------+------------+------------+
```

* **Name Box (Nomlar maydoni):** Ayni damda kursor turgan katak manzilini (masalan: `C3`) ko'rsatadi.
* **Formula Bar (Formulalar satri):** Katak ichidagi asl qiymat yoki formulani ko'rish va tahrirlash uchun xizmat qiladi.

### 2.2. Ma'lumot Turlari va Formatlash

| Ma'lumot Turi | Qoidasi | Misol | Ko'rinishi |
| :--- | :--- | :--- | :--- |
| **Matn (Text)** | Avtomatik ravishda katakning **chap tomoniga** tekislanadi | `Toshkent`, `Dastur` | Chapda |
| **Son (Number)** | Avtomatik ravishda katakning **o'ng tomoniga** tekislanadi | `150000`, `25.5` | O'ngda |
| **Sana (Date)** | Tizim kalendari bo'yicha saqlanadi | `05.10.2026` | O'ngda |
| **Valyuta (Currency)** | Son oxiriga pul birligi va razryad bo'shlig'i qo'shadi | `1 800 000 so'm` | O'ngda |

{% hint style="success" %}
**Pro-Tip (AutoFill sehrli dastagi):**
1 dan 100 gacha raqamlarni qo'lda terib o'tirmang!
`A1` katakka `1`, `A2` katakka `2` deb yozing. Ikkala katakni belgilang va belgilangan sohaning pastki o'ng burchagidagi kichik qora nuqtachadan (AutoFill Handle) ushlab pastga torting. Excel qolgan barcha raqamlarni avtomatik to'ldirib beradi! Bu hafta kunlari (Dushanba, Seshanba...) va oylar (Yanvar, Fevral...) uchun ham ishlaydi.
{% endhint %}

### 2.3. Wrap Text va Merge & Center

* **Wrap Text (Matnni o'rash):** Agar katakdagi sarlavha juda uzun bo'lsa, ustunni haddan tashqari kengaytirmasdan, matnni bir katak ichida 2-3 qatorga tushirib beradi.
* **Merge & Center:** Bir nechta katakni birlashtirib, sarlavhani jadval o'rtasiga joylashtiradi.

---

## 3. 💻 Bosqichma-bosqich Amaliy Mashg'ulot (Lab Task)

Ushbu mashg'ulotda siz korxona omboridagi kompyuter ehtiyot qismlari hisobi jadvalini tayyorlaysiz.

### Kerakli Resurslar:
* Microsoft Excel dasturi;
* Amaliy mashg'ulot shabloni.

### 📄 Amaliy Mashg'ulot Shabloni:
{% hint style="success" %}
**📄 Rasmiy Amaliy Mashg'ulot va Uy Vazifasi Shabloni (Google Sheets (Jadval)):**
Ushbu darsning barcha bosqichlarini bajarish, natijalar/hisobotlarni kiritish va uy vazifasini topshirish uchun quyidagi rasmiy shablondan foydalaning:
* 🌐 **Onlayn ko'rish va tahrirlash:** [14-Mavzu: Microsoft Excel Asoslari — Shablonni ochish](https://docs.google.com/spreadsheets/d/1lnWVjQzzTAilMCAjbXkGEK-YDSRxPFZDarsyi3KDmn8/edit?usp=sharing)
* 📥 **Shaxsiy Drive-ga nusxalash (Tavsiya etiladi):** [Nusxa yaratish (Make a copy)](https://docs.google.com/spreadsheets/d/1lnWVjQzzTAilMCAjbXkGEK-YDSRxPFZDarsyi3KDmn8/copy)
{% endhint %}

{% embed url="https://docs.google.com/spreadsheets/d/1lnWVjQzzTAilMCAjbXkGEK-YDSRxPFZDarsyi3KDmn8/preview" %}

> *Eslatma: Shablondan nusxa oling va quyidagi 6 ta qadam orqali jadvalni to'ldiring.*

### Bajarish Bosqichlari:

1. **1-Qadam:** Excel dasturida yangi bo'sh ish kitobi oching (**Blank workbook**).
2. **2-Qadam (Birlashtirilgan sarlavha):** `A1:E1` kataklarini belgilang, Bosh sahifadan **Merge & Center** tugmasini bosing va "KOMPYUTER QISMLARI OMBORI" deb yozing (Shrift: 14 pt, Qalin, fon rangi ochiq kulrang).
3. **3-Qadam (Ustun nomlari):** 2-qatordagi kataklarga quyidagi sarlavhalarni kiriting:
   * `A2`: T/r
   * `B2`: Qism nomi
   * `C2`: Narxi (so'm)
   * `D2`: Miqdori (dona)
   * `E2`: Holati
4. **4-Qadam (AutoFill orqali raqamlash):** `A3` ga `1`, `A4` ga `2` yozing va pastki dastakni tortib 5 tagacha raqamlang.
5. **5-Qadam (Ma'lumotlarni to'ldirish):** Qismlar nomini kiriting (SSD 512GB, RAM 16GB, Ona plata, Quvvat bloki, Kuler).
6. **6-Qadam (AutoFit va Chegaralar):** Butun jadvalni belgilang (`Ctrl + A`), **Borders -> All Borders** qilib to'r chiziqlarini yoqing. Ustunlar orasidagi chiziqqa ikki marta bosib **AutoFit** qiling va faylni `Ombor_Hisobi.xlsx` qilib saqlang.

{% hint style="warning" %}
**Ehtiyot bo'ling:**
Raqamlarni kiritayotganda probel bilan `150 000` deb yozmang! Probel qo'yilsa, Excel uni "matn" deb qabul qiladi va kelgusida bu sonlar ustida formulalar bilan hisob-kitob qilib bo'lmaydi. Sonni to'g'ridan-to'g'ri `150000` deb kiriting, oraliq bo'shliqni esa Number panelidagi `Comma Style` (Vergul belgisi) orqali chiqaring.
{% endhint %}

---

## 4. 🛠 Real Ish Vaziyati va Muammolarni Hal Qilish (Case-Study)

### Muammo:
Kassir Excel jadvaliga xodimlarning maoshlarini kiritdi. Ammo oxirgi xodimning maoshi katagida sonlar o'rniga `#######` (panjaralar) belgisi chiqib qoldi. Kassir sonlar o'chib ketdi deb o'ylab, katakni qayta-qayta terdi, ammo panjara belgisi yo'qolmadi.

### Muammoning Kelib Chiqish Sababi:
Excelda `###` belgisi xatolik emas! Bu shunchaki katak ichidagi son yoki sana ustun kengligiga sig'may qolganini bildiradi. Excel matndan farqli ravishda sonlarni chala ko'rsatishdan himoyalangan (chunki xodim 10 000 000 maosh olgan bo'lsa, ustun torligi sababli 10 000 ko'rinib qolsa, katta moliyaviy xatolik bo'ladi).

### Bosqichma-bosqich Yechim:
1. Sichqoncha kursorini o'sha ustunning yuqori harfli chegarasiga (masalan, C va D ustunlari o'rtasidagi ajratuvchi chiziqqa) olib boring.
2. Kursor ikki tomonlama qora strelka shakliga kiradi.
3. Sichqonchaning chap tugmasini ketma-ket **ikki marta bosing (Double-click)**.
4. Ustun avtomatik ravishda kengayadi (**AutoFit**) va yashiringan haqiqiy sonlar darhol to'liq ko'rinadi!

---

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz — 25 ta Savol, 100 Ball)

{% hint style="info" %}
**📝 Rasmiy Onlayn Test Sinovi (Google Forms — 25 ta savol, 100 ballik baholash):**
Ushbu dars bo'yicha olgan bilimlaringizni sinash uchun quyidagi rasmiy testni topshiring (Har bir to'g'ri javob 4 ball, jami: 100 ball):
* 🔗 **Onlayn Testni Ochish (To'liq Ekranda):** [14-Mavzu: Microsoft Excel Asoslari — Testni Topshirish](https://docs.google.com/forms/d/e/1FAIpQLSewIddDjssMWgxXPf0PB8GG1tZdj2ryWjeqXYuRwfOM7eEJ2A/viewform)
* 📊 **Kunlik Natijalar va Ballar Jadvali:** [Google Sheets — Natijalar Jadvali](https://docs.google.com/spreadsheets/d/1XXQNzCeUfqK-fCOqmlueOOSEuWP-0ml87JK99iYKWB8/edit)
{% endhint %}

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSewIddDjssMWgxXPf0PB8GG1tZdj2ryWjeqXYuRwfOM7eEJ2A/viewform?embedded=true" width="100%" height="800" frameborder="0" marginheight="0" marginwidth="0">Yuklanmoqda…</iframe>

---

### ✍️ 25 ta Rasmiy Test Savollari (Nazorat va O'z-o'zini Tekshirish):

Quyida ushbu dars bo'yicha tuzilgan barcha 25 ta rasmiy test savollari keltirilgan. Har bir savol 4 ta variantdan iborat bo'lib, to'g'ri javob belgilangan:

#### 1-Savol: Excel dasturida qatorlar (Rows) va ustunlar (Columns) qanday belgilanadi?
- [x] **A) Ustunlar lotin harflari bilan (A, B, C), qatorlar sonlar bilan (1, 2, 3)** *(To'g'ri javob)*
- [ ] B) Ustunlar sonlar bilan, qatorlar harflar bilan
- [ ] C) Ikkalasi ham sonlar bilan
- [ ] D) Ikkalasi ham harflar bilan

#### 2-Savol: Katakcha manzili (Cell Address) qanday ifodalanadi?
- [x] **A) Ustun harfi va qator soni (masalan: B4, C10)** *(To'g'ri javob)*
- [ ] B) Qator soni va ustun harfi (masalan: 4B)
- [ ] C) Faqat raqam
- [ ] D) Faqat harf

#### 3-Savol: Katakchaga kiritilgan matnli ma'lumot odatda qaysi tomonga tekislanadi?
- [x] **A) Chap tomonga** *(To'g'ri javob)*
- [ ] B) O'ng tomonga
- [ ] C) O'rtaga
- [ ] D) Pastga

#### 4-Savol: Katakchaga kiritilgan raqamli (sonli) ma'lumot qaysi tomonga tekislanadi?
- [x] **A) O'ng tomonga** *(To'g'ri javob)*
- [ ] B) Chap tomonga
- [ ] C) O'rtaga
- [ ] D) Tepaga

#### 5-Savol: AutoFill (Avtomatik to'ldirish) dastagi katakchaning qayerida joylashgan?
- [x] **A) Katakchaning pastki o'ng burchagidagi kichik qora nuqtada** *(To'g'ri javob)*
- [ ] B) Yuqori chapda
- [ ] C) O'rtada
- [ ] D) Pastki chapda

#### 6-Savol: Katakchalarni birlashtirib o'rtaga tekislash buyrug'i nima?
- [x] **A) Merge & Center** *(To'g'ri javob)*
- [ ] B) Wrap Text
- [ ] C) AutoFit
- [ ] D) Format Cells

#### 7-Savol: Katakdagi uzun matnni pastki qatorga ko'chirish (Wrap Text) nima qiladi?
- [x] **A) Ustun kengligini o'zgartirmasdan, matnni katak ichida ko'p qatorli qilib ko'rsatadi** *(To'g'ri javob)*
- [ ] B) Katakni kengaytiradi
- [ ] C) Matnni o'chiradi
- [ ] D) Katakni bo'ladi

#### 8-Savol: Katakchani tahrirlash (Edit Cell) rejimiga o'tish uchun qaysi klavish bosiladi?
- [x] **A) F2** *(To'g'ri javob)*
- [ ] B) F1
- [ ] C) F4
- [ ] D) F5

#### 9-Savol: Yangi ish varag'i (Sheet) qo'shishning tezkor klaviatura birikmasi qaysi?
- [x] **A) Shift + F11** *(To'g'ri javob)*
- [ ] B) Ctrl + N
- [ ] C) Alt + N
- [ ] D) Ctrl + Shift + S

#### 10-Savol: Varaqlar (Sheets) orasida tezkor almashish klavishlari qaysilar?
- [x] **A) Ctrl + PageDown va Ctrl + PageUp** *(To'g'ri javob)*
- [ ] B) Alt + Tab
- [ ] C) Ctrl + Tab
- [ ] D) Shift + Tab

#### 11-Savol: Ustun yoki qator sarlavhalarini skroll qilganda qotirib qo'yish (Freeze Panes) qayerda?
- [x] **A) View -> Freeze Panes** *(To'g'ri javob)*
- [ ] B) Home -> Format
- [ ] C) Data -> Sort
- [ ] D) Page Layout -> Margins

#### 12-Savol: Ustun kengligini matn uzunligiga avtomatik moslash (AutoFit Column Width) qanday bajariladi?
- [x] **A) Ustun harflari orasidagi chiziqqa ikki marta sichqoncha bilan bosish** *(To'g'ri javob)*
- [ ] B) Ctrl + A
- [ ] C) F2 bosish
- [ ] D) Enter bosish

#### 13-Savol: Barcha kataklarga to'r chiziqlarini (All Borders) qo'yish qaysi bo'limda?
- [x] **A) Home -> Font -> Borders** *(To'g'ri javob)*
- [ ] B) Insert -> Shapes
- [ ] C) View -> Gridlines
- [ ] D) Data -> Data Tools

#### 14-Savol: Katakchaga joriy sanani tezkor kiritish kombinatsiyasi nima?
- [x] **A) Ctrl + ; (nuqta-vergul)** *(To'g'ri javob)*
- [ ] B) Ctrl + Shift + :
- [ ] C) Alt + D
- [ ] D) F5

#### 15-Savol: Katakchaga joriy vaqtni tezkor kiritish qaysi birikma bilan bajariladi?
- [x] **A) Ctrl + Shift + ; (ikki nuqta)** *(To'g'ri javob)*
- [ ] B) Ctrl + ;
- [ ] C) Alt + T
- [ ] D) F9

#### 16-Savol: Excel katagida ### belgisi paydo bo'lishining sababi nima?
- [x] **A) Ustun kengligi son yoki sanani to'liq ko'rsatish uchun torlik qilyapti** *(To'g'ri javob)*
- [ ] B) Formulada xato bor
- [ ] C) Katak o'chirilgan
- [ ] D) Virus tushgan

#### 17-Savol: Katakchaning formatini o'zgartirish darchasi (Format Cells) qaysi klavishlar bilan ochiladi?
- [x] **A) Ctrl + 1** *(To'g'ri javob)*
- [ ] B) Ctrl + F
- [ ] C) Alt + 1
- [ ] D) Shift + 1

#### 18-Savol: Excel da pul birligi (Valyuta) formatini tezkor berish kombinatsiyasi nima?
- [x] **A) Ctrl + Shift + $ (yoki 4)** *(To'g'ri javob)*
- [ ] B) Ctrl + Shift + %
- [ ] C) Ctrl + Shift + #
- [ ] D) Alt + $

#### 19-Savol: Foiz (Percent) formatiga o'tkazish qaysi tugma bilan bajariladi?
- [x] **A) Ctrl + Shift + % (yoki 5)** *(To'g'ri javob)*
- [ ] B) Ctrl + P
- [ ] C) Alt + %
- [ ] D) Shift + %

#### 20-Savol: Katakcha ichida yangi satrga tushish (Alt+Enter) nima qiladi?
- [x] **A) Bitta katak ichida matnni yangi qatordan davom ettiradi** *(To'g'ri javob)*
- [ ] B) Keyingi katakka o'tadi
- [ ] C) Katakni tozalaydi
- [ ] D) Jadvalni yopadi

#### 21-Savol: Butun ustunni belgilash uchun qaysi klavishlar birikmasi bosiladi?
- [x] **A) Ctrl + Space** *(To'g'ri javob)*
- [ ] B) Shift + Space
- [ ] C) Alt + Space
- [ ] D) Ctrl + A

#### 22-Savol: Butun qatorni to'liq belgilash uchun qaysi birikma bosiladi?
- [x] **A) Shift + Space** *(To'g'ri javob)*
- [ ] B) Ctrl + Space
- [ ] C) Alt + Space
- [ ] D) Tab

#### 23-Savol: Excel da formulalar satri (Formula Bar) nima uchun xizmat qiladi?
- [x] **A) Belgilangan katakdagi haqiqiy formula yoki matnni ko'rish va tahrirlash uchun** *(To'g'ri javob)*
- [ ] B) Faqat natijani ko'rsatish uchun
- [ ] C) Xotirani ko'rsatish uchun
- [ ] D) Faylni saqlash uchun

#### 24-Savol: Katakchani tanlab Delete tugmasi bosilsa nima o'chadi?
- [x] **A) Faqat katak ichidagi ma'lumot (formati va chegarasi qoladi)** *(To'g'ri javob)*
- [ ] B) Katakning o'zi butunlay yo'qoladi
- [ ] C) Butun ustun o'chadi
- [ ] D) Hech narsa o'chmaydi

#### 25-Savol: Katakchaning formati, rangi va chegarasini butunlay tozalash qayerdan bajariladi?
- [x] **A) Home -> Editing -> Clear -> Clear All** *(To'g'ri javob)*
- [ ] B) Delete bosish
- [ ] C) Backspace bosish
- [ ] D) Ctrl + Z

---


## 6. 🏠 Mustaqil Amaliy Uyga Vazifa

### Topshiriq:
1. Microsoft Excel dasturida yangi fayl oching.
2. 5 ta talabaning F.I.Sh, 3 ta fan bo'yicha olgan baholari (85, 90, 78...) va yakuniy ballari ustunlaridan iborat chiroyli formatlangan jadval tuzing.
3. Jadval sarlavhasini Merge & Center orqali birlashtiring va All Borders chegaralarini o'rnating.
4. AutoFill orqali talabalar tartib raqamini (1 dan 5 gacha) shakllantiring.

**Topshirish formati:** Jadvalni `FIO_14-Mavzu_Excel_Asoslari.xlsx` nomi bilan saqlab platformaga yuklang.

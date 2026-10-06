# 15-Mavzu: Microsoft Excel Formulalari va Funksiyalari

{% hint style="info" %}
**Dars maqsadi:** Excel formulasining sintaksisi (`=`), nisbiy va mutlaq katak havolalari (`$A$1`, `F4`), asosiy matematik va statistik funksiyalar (`SUM`, `AVERAGE`, `MAX`, `MIN`, `COUNT`), shartli mantiqiy funksiya (`IF`) hamda formulalardagi xatoliklarni (`#DIV/0!`, `#VALUE!`, `#NAME?`, `#REF!`) tahlil qilish va tuzatish.
{% endhint %}

### 🎯 Kutilayotgan Kompetensiyalar
* **Bilishingiz kerak:**
  * Excel'da barcha formulalar nima sababdan `=` (tenglik) belgisi bilan boshlanishi.
  * Nisbiy havola (`A1`) va mutlaq/o'zgarmas havola (`$A$1`) o'rtasidagi farq.
  * Standart Excel xatolik kodlarining ma'nolari.
* **Bajara olishingiz kerak:**
  * Bir nechta kataklar yig'indisini (`SUM`), o'rtacha qiymatini (`AVERAGE`), eng katta/kichik ko'rsatkichini (`MAX`/`MIN`) hisoblash.
  * Mantiqiy `IF` funksiyasi yordamida avtomatlashtirilgan baholash yoki holat aniqlash shartlarini tuzish.
  * Formulalarni AutoFill dastagi yordamida yuzlab qatorlarga bir zumda nusxalash.

---

## 🎬 1. Video Dars

{% hint style="info" %}
**Video darslik:** Excel formulalari va avtomatlashtirilgan hisob-kitoblar bo'yicha quyidagi videoni tomosha qiling:
{% endhint %}

[Iframe/Embed: 15-Mavzu Bo'yicha YouTube Video Dars Havolasi]

---

## 2. 📖 Chuqurlashtirilgan Nazariy Ma'ruza

### 2.1. Formula Sintaksisi va Arifmetik Amallar

Excelda har qanday hisob-kitob qat'iyan `=` belgisi bilan boshlanadi. Agar tenglik qo'yilmasa, Excel kiritilgan yozuvni oddiy "matn" deb hisoblaydi.

```
       = B2 * C2
       ▲  ▲  ▲  ▲
       │  │  │  └─ 2-Katak koordinatasi
       │  │  └──── Arifmetik amal (Ko'paytirish)
       │  └─────── 1-Katak koordinatasi
       └────────── Formulani boshlovchi belgi
```

* **Qo'shish:** `=A1 + B1`
* **Ayirish:** `=A1 - B1`
* **Ko'paytirish:** `=A1 * B1`
* **Bo'lish:** `=A1 / B1`
* **Darajaga ko'tarish:** `=A1 ^ 2`

### 2.2. Asosiy Funksiyalar Kutubxonasi

Funksiyalar — bu Excel tomonidan oldindan tayyorlab qo'yilgan maxsus hisoblash formulalaridir:

| Funksiya Nomi | Vazifasi | Formula Namunasi | Tushuntirishi |
| :--- | :--- | :--- | :--- |
| **`SUM`** | Diapazondagi barcha sonlar yig'indisini hisoblaydi | `=SUM(B2:B10)` | B2 dan B10 gacha bo'lgan barcha sonlarni qo'shadi |
| **`AVERAGE`** | O'rtacha arifmetik qiymatni topadi | `=AVERAGE(C2:C10)` | Sonlar yig'indisini ularning soniga bo'ladi |
| **`MAX`** | Eng katta sonni aniqlaydi | `=MAX(D2:D10)` | Ro'yxatdagi eng yuqori ko'rsatkichni topadi |
| **`MIN`** | Eng kichik sonni aniqlaydi | `=MIN(D2:D10)` | Ro'yxatdagi eng past ko'rsatkichni topadi |
| **`COUNT`** | Sonli kataklar sonini sanaydi | `=COUNT(A2:A10)` | Diapazonda nechta katakda son borligini hisoblaydi |
| **`IF`** | Shartni tekshirib, 2 xil natija qaytaradi | `=IF(E2>=60; "O'tdi"; "Yiqildi")` | Agar E2>=60 bo'lsa "O'tdi", aks holda "Yiqildi" |

{% hint style="success" %}
**Pro-Tip (F4 — Katakni "Qulflash" / Absolyut havola):**
Formulani pastga nusxalaganda barcha katak manzillari ham pastga suriladi (`B2` -> `B3` -> `B4`). Ammo agar siz barcha qatorlarni yagona o'zgarmas katakka (masalan, valyuta kursi turgan `$D$1` ga) ko'paytirmoqchi bo'lsangiz, katak manzilini yozgach klaviaturadagi **`F4`** tugmasini bosing! Katak `$D$1` ko'rinishiga keladi va formulani qayerga tortmang, o'zgarmay qotib turadi!
{% endhint %}

### 2.3. Exceldagi Keng Tarqalgan Xatoliklar

| Xatolik Kodi | Sababi | Qanday tuzatiladi? |
| :--- | :--- | :--- |
| **`#DIV/0!`** | Formulada son nolga yoki bo'sh katakka bo'lingan | Bo'luvchi katakda 0 yo'qligini tekshiring |
| **`#VALUE!`** | Arifmetik amalda son o'rniga matn ishtirok etgan | Matnli kataklarni tekshirib, sonli qiymatga keltiring |
| **`#NAME?`** | Funksiya nomi xato yozilgan (masalan: `=SUMM(...)`) | Funksiya nomini to'g'ri yozing (`=SUM(...)`) |
| **`#REF!`** | Formulada ko'rsatilgan katak yoki ustun o'chirib yuborilgan | `Ctrl + Z` bosing yoki formulaga to'g'ri katakni qayta ko'rsating |

---

## 3. 💻 Bosqichma-bosqich Amaliy Mashg'ulot (Lab Task)

Ushbu amaliy mashg'ulotda siz o'quv markazi talabalarining yakuniy imtihon ballarini avtomatlashtirilgan tarzda hisoblab chiquvchi jadval yaratasiz.

### Kerakli Resurslar:
* Microsoft Excel dasturi;
* Amaliy mashg'ulot shabloni.

### 📄 Amaliy Mashg'ulot Shabloni:
{% hint style="success" %}
**📄 Rasmiy Amaliy Mashg'ulot va Uy Vazifasi Shabloni (Google Sheets (Jadval)):**
Ushbu darsning barcha bosqichlarini bajarish, natijalar/hisobotlarni kiritish va uy vazifasini topshirish uchun quyidagi rasmiy shablondan foydalaning:
* 🌐 **Onlayn ko'rish va tahrirlash:** [15-Mavzu: Microsoft Excel Formulalari va Funksiyalari — Shablonni ochish](https://docs.google.com/spreadsheets/d/1KV61Xl2yennGNgE125YJrkJDmwTdVWjErLDFIQqzvd0/edit?usp=sharing)
* 📥 **Shaxsiy Drive-ga nusxalash (Tavsiya etiladi):** [Nusxa yaratish (Make a copy)](https://docs.google.com/spreadsheets/d/1KV61Xl2yennGNgE125YJrkJDmwTdVWjErLDFIQqzvd0/copy)
{% endhint %}

{% embed url="https://docs.google.com/spreadsheets/d/1KV61Xl2yennGNgE125YJrkJDmwTdVWjErLDFIQqzvd0/preview" %}

> *Eslatma: Shablondan nusxa oling va quyidagi 6 ta qadam orqali barcha formulalarni kiritib chiqing.*

### Bajarish Bosqichlari:

1. **1-Qadam:** Excel dasturida yangi jadval tuzing:
   * `A2:A6` ustuniga 5 ta talaba ismini yozing;
   * `B2:B6` ustuniga 1-oraliq ballarini (60 dan 100 gacha);
   * `C2:C6` ustuniga 2-oraliq ballarini kiriting.
2. **2-Qadam (Jami ball - SUM):** `D2` katakka kiring va formulani yozing:
   `=SUM(B2:C2)`
   Enter bosing va formulani pastki qatorlarga AutoFill dastagi bilan torting.
3. **3-Qadam (O'rtacha ball - AVERAGE):** `E2` katakka kiring va formulani yozing:
   `=AVERAGE(B2:C2)`
   Enter bosing va pastga nusxalang.
4. **4-Qadam (Shartli holat - IF):** `F2` katakka kiring va shartli formulani yozing:
   `=IF(E2>=70, "O'tdi", "Yiqildi")`
   Enter bosing va pastga nusxalang (70 dan yuqori bo'lganlar avtomatik "O'tdi" chiqadi).
5. **5-Qadam (Statistik ko'rsatkichlar):**
   * Jadval ostidagi bir bo'sh katakka eng yuqori ballni topish uchun: `=MAX(D2:D6)`
   * Eng past ballni topish uchun: `=MIN(D2:D6)`
6. **6-Qadam:** Barcha formulalar ishlaganini ko'zdan kechirib, faylni `Talabalar_Baholari.xlsx` nomi bilan saqlang.

{% hint style="warning" %}
**Ehtiyot bo'ling:**
Funksiyalar ichidagi parametrlarni ajratishda Windows mintaqaviy sozlamalariga qarab nuqta-vergul (`;`) yoki vergul (`,`) ishlatiladi. Agar `=IF(E2>=70, ...)` xato bersa, vergul o'rniga nuqta-vergul qo'yib ko'ring: `=IF(E2>=70; ...)`.
{% endhint %}

---

## 4. 🛠 Real Ish Vaziyati va Muammolarni Hal Qilish (Case-Study)

### Muammo:
Savdo do'koni menejeri 100 ta tovarning AQSH dollaridagi narxini o'zbek so'miga aylantirish uchun formula yozdi: `=B2 * $D$1` (bu yerda `D1` katakda dollar kursi: 12 800 so'm turibdi). Menejer formulani birinchi qatorda to'g'ri hisobladi, ammo AutoFill bilan pastga tortganda barcha qolgan 99 ta tovarda qiymat `0` so'm bo'lib chiqdi!

### Muammoning Kelib Chiqish Sababi:
Menejer kursorni tortishdan oldin kurs turgan `D1` katakka **`F4` (dollar belgilarini)** qo'ymagan. Natijada pastga tortganda formula `=B3*D2`, `=B4*D3` bo'lib pastga siljib ketgan, `D2`, `D3` kataklar esa bo'sh bo'lgani uchun natija 0 chiqqan.

### Bosqichma-bosqich Yechim:
1. `C2` katakdagi formulani oching.
2. `D1` manzili ustiga kursor qo'yib, klaviaturadagi **`F4`** tugmasini bosing.
3. Formula `=B2 * $D$1` ko'rinishiga keladi.
4. AutoFill dastagini pastga torting — endi barcha 100 ta tovar narxi to'g'ri o'zgarmas kursga (`$D$1`) ko'paytirilib, to'g'ri hisoblab beriladi!

---

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz — 25 ta Savol, 100 Ball)

{% hint style="info" %}
**📝 Rasmiy Onlayn Test Sinovi (Google Forms — 25 ta savol, 100 ballik baholash):**
Ushbu dars bo'yicha olgan bilimlaringizni sinash uchun quyidagi rasmiy testni topshiring (Har bir to'g'ri javob 4 ball, jami: 100 ball):
* 🔗 **Onlayn Testni Ochish (To'liq Ekranda):** [15-Mavzu: Microsoft Excel Formulalari va Funksiyalari — Testni Topshirish](https://docs.google.com/forms/d/e/1FAIpQLSegi35-Ai6rcjQfK2VQg3s8P3dj2w9P575z4bXdhGT0b_BWIQ/viewform)
* 📊 **Kunlik Natijalar va Ballar Jadvali:** [Google Sheets — Natijalar Jadvali](https://docs.google.com/spreadsheets/d/1mvFnPN7Y5FMK8auZ1PKIg4JluDnZfvx4oZqR2rSdLj4/edit)
{% endhint %}

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSegi35-Ai6rcjQfK2VQg3s8P3dj2w9P575z4bXdhGT0b_BWIQ/viewform?embedded=true" width="100%" height="800" frameborder="0" marginheight="0" marginwidth="0">Yuklanmoqda…</iframe>

---

### ✍️ 25 ta Rasmiy Test Savollari (Nazorat va O'z-o'zini Tekshirish):

Quyida ushbu dars bo'yicha tuzilgan barcha 25 ta rasmiy test savollari keltirilgan. Har bir savol 4 ta variantdan iborat bo'lib, to'g'ri javob belgilangan:

#### 1-Savol: Excel dasturida har qanday formula qaysi belgi bilan boshlanishi shart?
- [x] **A) = (tenglik)** *(To'g'ri javob)*
- [ ] B) +
- [ ] C) @
- [ ] D) #

#### 2-Savol: Berilgan kataklar oralig'idagi sonlar yig'indisini hisoblovchi funksiya qaysi?
- [x] **A) SUM** *(To'g'ri javob)*
- [ ] B) AVERAGE
- [ ] C) COUNT
- [ ] D) TOTAL

#### 3-Savol: Sonlarning o'rta arifmetik qiymatini hisoblovchi funksiya nima deyiladi?
- [x] **A) AVERAGE** *(To'g'ri javob)*
- [ ] B) SUM
- [ ] C) MEDIAN
- [ ] D) MEAN

#### 4-Savol: Berilgan diapazondagi faqat sonli kataklar sonini hisoblovchi funksiya qaysi?
- [x] **A) COUNT** *(To'g'ri javob)*
- [ ] B) COUNTA
- [ ] C) COUNTBLANK
- [ ] D) SUM

#### 5-Savol: Bo'sh bo'lmagan (matn yoki son bor) barcha kataklarni sanovchi funksiya nima?
- [x] **A) COUNTA** *(To'g'ri javob)*
- [ ] B) COUNT
- [ ] C) COUNTIF
- [ ] D) SUMIF

#### 6-Savol: Kataklar oralig'idagi eng katta sonni topuvchi funksiya qaysi?
- [x] **A) MAX** *(To'g'ri javob)*
- [ ] B) MIN
- [ ] C) LARGE
- [ ] D) TOP

#### 7-Savol: Kataklar oralig'idagi eng kichik sonni aniqlovchi funksiya nima?
- [x] **A) MIN** *(To'g'ri javob)*
- [ ] B) MAX
- [ ] C) SMALL
- [ ] D) BOTTOM

#### 8-Savol: Mutlaq manzil (Absolute Reference) yaratish uchun katak harfi va soni oldiga qaysi belgi qo'yiladi?
- [x] **A) $ (masalan: $A$1)** *(To'g'ri javob)*
- [ ] B) #
- [ ] C) %
- [ ] D) &

#### 9-Savol: Formulada katak manzilini nisbiydan mutlaqqa o'tkazuvchi klavish qaysi?
- [x] **A) F4** *(To'g'ri javob)*
- [ ] B) F2
- [ ] C) F5
- [ ] D) F9

#### 10-Savol: Mantiqiy shart tekshiruvchi asosiy funksiya qaysi?
- [x] **A) IF (AGAR)** *(To'g'ri javob)*
- [ ] B) AND
- [ ] C) OR
- [ ] D) NOT

#### 11-Savol: =IF(A1>=60; "O'tdi"; "Yiqildi") formulasi A1=75 bo'lganda qanday natija qaytaradi?
- [x] **A) O'tdi** *(To'g'ri javob)*
- [ ] B) Yiqildi
- [ ] C) Xato
- [ ] D) 60

#### 12-Savol: Shartga mos keluvchi kataklarni sanash funksiyasi nima deb ataladi?
- [x] **A) COUNTIF** *(To'g'ri javob)*
- [ ] B) SUMIF
- [ ] C) COUNT
- [ ] D) IFCOUNT

#### 13-Savol: Faqat ma'lum bir shartni qanoatlantiruvchi kataklar yig'indisini hisoblovchi funksiya qaysi?
- [x] **A) SUMIF** *(To'g'ri javob)*
- [ ] B) COUNTIF
- [ ] C) AVERAGEIF
- [ ] D) SUM

#### 14-Savol: Excel da sonni nolga bo'lishga uringanda qanday xatolik xabari chiqadi?
- [x] **A) #DIV/0!** *(To'g'ri javob)*
- [ ] B) #VALUE!
- [ ] C) #N/A
- [ ] D) #NAME?

#### 15-Savol: Formulada kiritilgan funksiya nomi noto'g'ri yozilsa, qanday xato chiqadi?
- [x] **A) #NAME?** *(To'g'ri javob)*
- [ ] B) #REF!
- [ ] C) #VALUE!
- [ ] D) #NULL!

#### 16-Savol: Formulada murojaat qilingan katak o'chirib yuborilsa, qanday xato paydo bo'ladi?
- [x] **A) #REF!** *(To'g'ri javob)*
- [ ] B) #NUM!
- [ ] C) #DIV/0!
- [ ] D) #N/A

#### 17-Savol: Matnlarni o'zaro birlashtirish uchun qaysi operator ishlatiladi?
- [x] **A) & (amper sand)** *(To'g'ri javob)*
- [ ] B) +
- [ ] C) *
- [ ] D) ^

#### 18-Savol: Jadvalning birinchi ustunidan qidirib, mos qatordagi ma'lumotni olib keluvchi mashhur funksiya qaysi?
- [x] **A) VLOOKUP (PROR)** *(To'g'ri javob)*
- [ ] B) HLOOKUP
- [ ] C) INDEX
- [ ] D) MATCH

#### 19-Savol: Zamonaviy Excel da VLOOKUP o'rniga kelgan ancha moslashuvchan funksiya qaysi?
- [x] **A) XLOOKUP** *(To'g'ri javob)*
- [ ] B) LOOKUP
- [ ] C) FIND
- [ ] D) SEARCH

#### 20-Savol: Sonni darajaga ko'tarish matematik belgisi qaysi?
- [x] **A) ^ (masalan: 2^3 = 8)** *(To'g'ri javob)*
- [ ] B) *
- [ ] C) **
- [ ] D) %

#### 21-Savol: Ikkita yoki undan ortiq shart bir vaqtda bajarilishi talab etilganda qaysi funksiya ishlatiladi?
- [x] **A) AND (VA)** *(To'g'ri javob)*
- [ ] B) OR (YOKI)
- [ ] C) NOT
- [ ] D) XOR

#### 22-Savol: Bir nechta shartdan kamida bittasi bajarilsa kifoya bo'lganda qaysi funksiya qo'llaniladi?
- [x] **A) OR (YOKI)** *(To'g'ri javob)*
- [ ] B) AND
- [ ] C) NOT
- [ ] D) IF

#### 23-Savol: Sonning kvadrat ildizini hisoblovchi funksiya nima deyiladi?
- [x] **A) SQRT** *(To'g'ri javob)*
- [ ] B) ROOT
- [ ] C) POWER
- [ ] D) SQR

#### 24-Savol: Matndagi harflar sonini hisoblovchi funksiya qaysi?
- [x] **A) LEN (DLSTR)** *(To'g'ri javob)*
- [ ] B) COUNT
- [ ] C) TEXT
- [ ] D) SUM

#### 25-Savol: Formulalarni hisoblashni majburiy qayta yangilash klavishi qaysi?
- [x] **A) F9** *(To'g'ri javob)*
- [ ] B) F5
- [ ] C) F7
- [ ] D) F2

---


## 6. 🏠 Mustaqil Amaliy Uyga Vazifa

### Topshiriq:
1. Microsoft Excel dasturida yangi fayl oching.
2. Oila oylik xarajatlari bo'yicha jadval tuzing (Kommunal, Oziq-ovqat, Transport, Internet, Kiyim-kechak).
3. `SUM` yordamida jami xarajatni, `AVERAGE` orqali o'rtacha xarajatni, `MAX` va `MIN` orqali eng katta va eng kichik xarajatlarni hisoblang.
4. `IF` funksiyasi yordamida agar jami xarajat 5 000 000 dan oshsa "Tejamkorlik zarur", aks holda "Me'yorda" degan natijani chiqaring.

**Topshirish formati:** Jadvalni `FIO_15-Mavzu_Excel_Formulalari.xlsx` nomi bilan saqlab platformaga yuklang.

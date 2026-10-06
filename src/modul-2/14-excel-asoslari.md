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

## 🎬 1. Video Dars

{% hint style="info" %}
**Video darslik:** Excel interfeysi va birinchi jadvalni yaratish bo'yicha quyidagi videoni tomosha qiling:
{% endhint %}

[Iframe/Embed: 14-Mavzu Bo'yicha YouTube Video Dars Havolasi]

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

## 3. 💻 Bosqichma-bosqich Amaliy Mashg'ulot (Lab Task)

Ushbu mashg'ulotda siz korxona omboridagi kompyuter ehtiyot qismlari hisobi jadvalini tayyorlaysiz.

### Kerakli Resurslar:
* Microsoft Excel dasturi;
* Amaliy mashg'ulot shabloni.

### 📄 Amaliy Mashg'ulot Shabloni:
{% hint style="success" %}
**📄 Rasmiy Amaliy Mashg'ulot va Uy Vazifasi Shabloni (Google Sheets (Jadval)):**
Ushbu darsning barcha bosqichlarini bajarish, natijalar/hisobotlarni kiritish va uy vazifasini topshirish uchun quyidagi rasmiy shablondan foydalaning:
* 🌐 **Onlayn ko'rish va tahrirlash:** <a href="https://docs.google.com/spreadsheets/d/1lnWVjQzzTAilMCAjbXkGEK-YDSRxPFZDarsyi3KDmn8/edit?usp=sharing" target="_blank" rel="noopener noreferrer">14-Mavzu: Microsoft Excel Asoslari — Shablonni ochish</a>
* 📥 **Shaxsiy Drive-ga nusxalash (Tavsiya etiladi):** <a href="https://docs.google.com/spreadsheets/d/1lnWVjQzzTAilMCAjbXkGEK-YDSRxPFZDarsyi3KDmn8/copy" target="_blank" rel="noopener noreferrer">Nusxa yaratish (Make a copy)</a>
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

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz)

{% hint style="info" %}
**📝 Rasmiy Onlayn Test Sinovi (Google Forms — 25 ta savol, 100 ballik baholash):**
Ushbu dars bo'yicha olgan bilimlaringizni sinash uchun quyidagi rasmiy testni topshiring (Har bir to'g'ri javob 4 ball, jami: 100 ball):
* 🔗 **Onlayn Testni Ochish (To'liq Ekranda):** <a href="https://docs.google.com/forms/d/e/1FAIpQLSewIddDjssMWgxXPf0PB8GG1tZdj2ryWjeqXYuRwfOM7eEJ2A/viewform" target="_blank" rel="noopener noreferrer">14-Mavzu: Microsoft Excel Asoslari — Testni Topshirish</a>
* 📊 **Kunlik Natijalar va Ballar Jadvali:** <a href="https://docs.google.com/spreadsheets/d/1XXQNzCeUfqK-fCOqmlueOOSEuWP-0ml87JK99iYKWB8/edit" target="_blank" rel="noopener noreferrer">Google Sheets — Natijalar Jadvali</a>
{% endhint %}

{% embed url="https://docs.google.com/forms/d/e/1FAIpQLSewIddDjssMWgxXPf0PB8GG1tZdj2ryWjeqXYuRwfOM7eEJ2A/viewform" %}

## 6. 🏠 Mustaqil Amaliy Uyga Vazifa

### Topshiriq:
1. Microsoft Excel dasturida yangi fayl oching.
2. 5 ta talabaning F.I.Sh, 3 ta fan bo'yicha olgan baholari (85, 90, 78...) va yakuniy ballari ustunlaridan iborat chiroyli formatlangan jadval tuzing.
3. Jadval sarlavhasini Merge & Center orqali birlashtiring va All Borders chegaralarini o'rnating.
4. AutoFill orqali talabalar tartib raqamini (1 dan 5 gacha) shakllantiring.

**Topshirish formati:** Jadvalni `FIO_14-Mavzu_Excel_Asoslari.xlsx` nomi bilan saqlab platformaga yuklang.

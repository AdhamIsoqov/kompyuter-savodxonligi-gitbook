# 09-Mavzu: Kompyuterga Texnik Xizmat Ko'rsatish va Profilaktika

{% hint style="info" %}
**Dars maqsadi:** Kompyuter tizim blokiga apparat (changdan tozalash, termopasta almashtirish, kulerlar diagnostikasi) va dasturiy (Disk Cleanup, vaqtinchalik `%temp%` fayllarni tozalash, SSD TRIM / HDD defragmentatsiya, Windows Defender tekshiruvi) xizmat ko'rsatish texnologiyalarini professional darajada egallash.
{% endhint %}

### 🎯 Kutilayotgan Kompetensiyalar
* **Bilishingiz kerak:**
  * Kompyuter qizib ketishi (Overheating) va termal himoya (Thermal Throttling) sabablari.
  * Termopasta (Thermal Paste) vazifasi va uni almashtirish davriyligi (yiliga 1–2 marta).
  * SSD disklarda defragmentatsiya o'rniga nima uchun faqat TRIM (Optimize) buyrug'i berilishi.
* **Bajara olishingiz kerak:**
  * Tizim blokini changdan xavfsiz tozalash va sovutish radiatorlarini ko'zdan kechirish.
  * `cleanmgr` (Disk Cleanup) va `%temp%` buyruqlari yordamida diskdan gigabaytlab axlat fayllarni xavfsiz tozalash.
  * Windows Security orqali to'liq antivirus diagnostikasini o'tkazish.

## 🎬 1. Video Dars

{% hint style="info" %}
**Video darslik:** Tizim blokini changdan tozalash va dasturiy optimallashtirish bo'yicha quyidagi videoni tomosha qiling:
{% endhint %}

[Iframe/Embed: 09-Mavzu Bo'yicha YouTube Video Dars Havolasi]

## 2. 📖 Chuqurlashtirilgan Nazariy Ma'ruza

### 2.1. Apparat Profilaktikasi: Sovutish Tizimi va Termopasta

Kompyuter protsessori (CPU) va videokartasi (GPU) yuqori yuklamada 70°C – 85°C gacha qiziydi. Ularning issiqligini radiatorga uzatish uchun maxsus kremniy-metall birikmali pasta — **Termopasta** ishlatiladi.

| Profilaktika Bosqichi | Davriyligi | Ishlatiladigan Asboblar | Kutiladigan Natija |
| :--- | :--- | :--- | :--- |
| **Changdan tozalash** | Har 3–6 oyda | Siqilgan havo balloni, antistatik yumshoq cho'tka | Ventilyatsiya tiklanadi, kulerlar shovqini pasayadi |
| **Termopastani almashtirish** | Har 1–2 yilda | Izopropil spirti, quruq salfetka, yangi termopasta (masalan, MX-4) | Protsessor harorati 15–25°C ga tushadi |
| **Kulerlarni moylash** | Shovqin chiqqanda | Maxsus sintetik silikon moy | Ventilyator aylanishi ravonlashadi |

```
[Issiqlik Uzatish Zanjiri]
  [Protsessor Kristall (CPU)] ---> [Yupqa Termopasta Qatlami] ---> [Mis/Alyuminiy Radiator] ---> [Kuler Ventilyatori (Havoga chiqarish)]
```

{% hint style="success" %}
**Pro-Tip (Termopasta surtish qoidasi):**
"Qancha ko'p surtsam, shuncha yaxshi soviydi" degan tushuncha mutlaqo xatodir! Termopasta faqat metall yuzalar orasidagi mikroskopik havo g'ovaklarini to'ldirish uchun xizmat qiladi. Qalin surtilsa, u issiqlikni o'tkazmaydigan to'siqqa aylanadi. Protsessor o'rtasiga bitta no'xat donasidek (yoki guruch donasidek) tomizib, radiatorni tekis bosish kifoya!
{% endhint %}

### 2.2. Dasturiy Profilaktika: Diskni Kesh Fayllardan Tozalash

Vaqt o'tishi bilan Windows tizimida dasturlar va brauzerlarning vaqtinchalik fayllari (Temp) to'planib, 10–30 GB gacha joyni egallab oladi:

1. **`%temp%` katalogi:** `Win + R` bosing, `%temp%` deb yozing va Enter bosing. Bu foydalanuvchi ilovalarining vaqtinchalik keshidir. Ichidagi barcha fayllarni `Ctrl + A` va `Shift + Delete` orqali bemalol o'chirishingiz mumkin.
2. **Disk Cleanup vositasi:** `Win + R` -> `cleanmgr` deb yozing. C: diskini tanlang va "Clean up system files" (Tizim fayllarini tozalash) tugmasini bosing (eski Windows yangilanishlari va xatolik hisobotlari tozalanadi).

### 2.3. HDD Defragmentatsiya vs SSD TRIM (Optimizatsiya)

* **HDD (Magnit disklar):** Fayllar diskning turli burchaklariga bo'linib (fragmentatsiyalashib) yoziladi. Mexanik o'qish kallagi tez harakatlanishi uchun ularni yonma-yon tartiblash — **Defragmentatsiya** talab etiladi (oyiga 1 marta).
* **SSD (Flesh disklar):** SSD disklarni HECH QACHON defragmentatsiya qilish mumkin emas! Bu ularning yozish resursini (TBW) tez tugatib yuboradi. SSD disklar uchun Windows faqat **TRIM (Optimizatsiya)** buyrug'ini yuboradi.

## 3. 💻 Bosqichma-bosqich Amaliy Mashg'ulot (Lab Task)

Ushbu mashg'ulotda siz kompyuteringiz xotirasi va xavfsizligini to'liq profilaktika qilasiz.

### Kerakli Resurslar:
* Windows 10/11 kompyuter;
* `cleanmgr` va Windows Security utilitalari.

### 📄 Amaliy Mashg'ulot Shabloni:
{% hint style="success" %}
**📄 Rasmiy Amaliy Mashg'ulot va Uy Vazifasi Shabloni (Google Docs (Hujjat)):**
Ushbu darsning barcha bosqichlarini bajarish, natijalar/hisobotlarni kiritish va uy vazifasini topshirish uchun quyidagi rasmiy shablondan foydalaning:
* 🌐 **Onlayn ko'rish va tahrirlash:** <a href="https://docs.google.com/document/d/1SYGC5cpNusvTmzjwFisoA1KEskKltMCp6UnQUIj_PvY/edit?usp=sharing" target="_blank" rel="noopener noreferrer">09-Mavzu: Kompyuterga Texnik Xizmat Ko'rsatish — Shablonni ochish</a>
* 📥 **Shaxsiy Drive-ga nusxalash (Tavsiya etiladi):** <a href="https://docs.google.com/document/d/1SYGC5cpNusvTmzjwFisoA1KEskKltMCp6UnQUIj_PvY/copy" target="_blank" rel="noopener noreferrer">Nusxa yaratish (Make a copy)</a>
{% endhint %}

{% embed url="https://docs.google.com/document/d/1SYGC5cpNusvTmzjwFisoA1KEskKltMCp6UnQUIj_PvY/preview" %}

> *Eslatma: Shablondan nusxa oling va tozalashgacha hamda tozalashdan keyingi bo'sh joy parametrlarini qayd eting.*

### Bajarish Bosqichlari:

1. **1-Qadam:** `Win + E` orqali "This PC" (Mening kompyuterim) bo'limini oching va C: diskidagi bo'sh joy miqdorini yozib oling.
2. **2-Qadam:** `Win + R` bosing, `%temp%` deb yozing va Enter bosing. Barcha fayllarni tanlab (`Ctrl + A`), `Shift + Delete` bilan o'chiring (band fayllar chiqsa, "Skip" bosing).
3. **3-Qadam:** `Win + R` bosing, `temp` deb yozing va tizim keshini ham xuddi shunday tozalang.
4. **4-Qadam (Disk Cleanup):** `Win + R` orqali `cleanmgr` buyrug'ini ishga tushiring. Keraksiz deb topilgan barcha katakchalarga (Temporary files, Thumbnails, Recycle Bin) galochka qo'yib **OK** bosing.
5. **5-Qadam (Diskni optimallashtirish):** Start qidiruviga **Defragment and Optimize Drives** deb yozing va dasturni oching. Diskingiz SSD yoki HDD ekanligini aniqlab, **Optimize** tugmasini bosing.
6. **6-Qadam (Antivirus sinovi):** Start qidiruviga **Windows Security** deb yozing. **Virus & threat protection** bo'limiga kiring va **Quick scan (Tezkor tekshiruv)** tugmasini bosing.

{% hint style="warning" %}
**Ehtiyot bo'ling:**
Tizim blokini kompressor yoki changyutgich bilan tozalayotganda ventilyator (kuler) pichoqlarini barmog'ingiz yoki qalam bilan ushlab turing! Yuqori bosimli havo ventilyatorni haddan tashqari tez aylantirib, uning motorida teskari tok (generator effekti) hosil qilishi va ona platadagi mikrosxemani kuydirishi mumkin.
{% endhint %}

## 4. 🛠 Real Ish Vaziyati va Muammolarni Hal Qilish (Case-Study)

### Muammo:
Foydalanuvchi kompyuterida Word yoki brauzerda ishlayotganda hammasi yaxshi, ammo video montaj dasturini yoki og'ir dasturni ishga tushirishi bilan 10-15 daqiqa o'tib kompyuter ichidagi ventilyator juda baland g'uvillab ovoz chiqaradi, dasturlar qota boshlaydi va to'satdan kompyuter o'z-o'zidan butunlay o'chib qoladi. Qayta yoqish uchun 5 daqiqa kutishga to'g'ri keladi.

### Muammoning Kelib Chiqish Sababi:
Protsessor radiatorining panjaralari kigizsimon chang qatlami bilan to'silib qolgan, termopasta esa 3 yildan buyon almashtirilmaganligi sababli toshdek qotib, quruq bo'rga aylanib qolgan. Protsessor harorati 95°C dan oshib ketgach, ona plataning avariya tizimi protsessorni yonib ketishdan saqlash uchun quvvatni majburiy o'chirgan (**Thermal Shutdown**).

### Bosqichma-bosqich Yechim:
1. Kompyuterning quvvat simini uzing va tizim blokining yon qopqog'ini oching.
2. Protsessor kulerini ehtiyotkorlik bilan yechib oling.
3. Radiator panjaralaridagi changlarni cho'tka va changyutgich bilan tozalang.
4. Eski qotib qolgan termopastani spirtli salfetka bilan protsessor va radiator tagidan butunlay artib tozalang.
5. Protsessor markaziga bir tomchi sifatli yangi termopasta tomizing.
6. Kulerni qayta o'rnatib, qisqichlarini mustahkam qotiring.
7. Kompyuterni yoqing va haroratni kuzatuvchi dastur (masalan, HWMonitor) orqali tekshiring — yuklama ostidagi harorat 65°C dan oshmaydi va kompyuter boshqa o'chmaydi!

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz)

{% hint style="info" %}
**📝 Rasmiy Onlayn Test Sinovi (Google Forms — 15 ta saralangan savol, 100 ballik baholash):**
Ushbu dars bo'yicha olgan bilimlaringizni sinash uchun quyidagi rasmiy testni topshiring (15 ta saralangan test savoli, jami: 100 ball):
* 🔗 **Onlayn Testni Ochish (To'liq Ekranda):** <a href="https://docs.google.com/forms/d/e/1FAIpQLSeyP9v04D6XYO30O8yL8rJCHanAWKiWQpvgSRNN2oXQ_pTlMw/viewform" target="_blank" rel="noopener noreferrer">09-Mavzu: Kompyuterga Texnik Xizmat Ko'rsatish — Testni Topshirish</a>
* 📊 **Kunlik Natijalar va Ballar Jadvali:** <a href="https://docs.google.com/spreadsheets/d/1ABSV6HKIylv6cvnMrHUGsTlUBTU-VfXmdHzzXQg99Vw/edit" target="_blank" rel="noopener noreferrer">Google Sheets — Natijalar Jadvali</a>
{% endhint %}

{% embed url="https://docs.google.com/forms/d/e/1FAIpQLSeyP9v04D6XYO30O8yL8rJCHanAWKiWQpvgSRNN2oXQ_pTlMw/viewform" %}

## 6. 🏠 Mustaqil Amaliy Uyga Vazifa

### Topshiriq:
1. Kompyuteringizda `cleanmgr` utilitasini ishga tushiring va tizimli fayllarni tozalash (Clean up system files) tekshiruvini bajaring.
2. Windows Security orqali kompyuterni tezkor tekshiruvdan (Quick Scan) o'tkazing va xavfsizlik hisobotini oching.
3. Tizim blokining tashqi ventilyatsiya teshiklarini va noutbuk tag qismini changdan tozalash bo'yicha profilaktika rejasini yozing.
4. Bajarilgan amallarning skrinshotlarini yagona hujjatga jamlang.

**Topshirish formati:** Hisobotni `FIO_9-Mavzu_Profilaktika.docx` nomi bilan platformaga yuklang.

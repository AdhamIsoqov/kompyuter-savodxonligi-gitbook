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

---

## 🎬 1. Video Dars

{% hint style="info" %}
**Video darslik:** Tizim blokini changdan tozalash va dasturiy optimallashtirish bo'yicha quyidagi videoni tomosha qiling:
{% endhint %}

[Iframe/Embed: 09-Mavzu Bo'yicha YouTube Video Dars Havolasi]

---

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

---

## 3. 💻 Bosqichma-bosqich Amaliy Mashg'ulot (Lab Task)

Ushbu mashg'ulotda siz kompyuteringiz xotirasi va xavfsizligini to'liq profilaktika qilasiz.

### Kerakli Resurslar:
* Windows 10/11 kompyuter;
* `cleanmgr` va Windows Security utilitalari.

### 📄 Amaliy Mashg'ulot Shabloni:
{% hint style="success" %}
**📄 Rasmiy Amaliy Mashg'ulot va Uy Vazifasi Shabloni (Google Docs (Hujjat)):**
Ushbu darsning barcha bosqichlarini bajarish, natijalar/hisobotlarni kiritish va uy vazifasini topshirish uchun quyidagi rasmiy shablondan foydalaning:
* 🌐 **Onlayn ko'rish va tahrirlash:** [09-Mavzu: Kompyuterga Texnik Xizmat Ko'rsatish — Shablonni ochish](https://docs.google.com/document/d/1SYGC5cpNusvTmzjwFisoA1KEskKltMCp6UnQUIj_PvY/edit?usp=sharing)
* 📥 **Shaxsiy Drive-ga nusxalash (Tavsiya etiladi):** [Nusxa yaratish (Make a copy)](https://docs.google.com/document/d/1SYGC5cpNusvTmzjwFisoA1KEskKltMCp6UnQUIj_PvY/copy)
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

---

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

---

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz — 25 ta Savol, 100 Ball)

{% hint style="info" %}
**📝 Rasmiy Onlayn Test Sinovi (Google Forms — 25 ta savol, 100 ballik baholash):**
Ushbu dars bo'yicha olgan bilimlaringizni sinash uchun quyidagi rasmiy testni topshiring (Har bir to'g'ri javob 4 ball, jami: 100 ball):
* 🔗 **Onlayn Testni Ochish (To'liq Ekranda):** [09-Mavzu: Kompyuterga Texnik Xizmat Ko'rsatish — Testni Topshirish](https://docs.google.com/forms/d/e/1FAIpQLSeyP9v04D6XYO30O8yL8rJCHanAWKiWQpvgSRNN2oXQ_pTlMw/viewform)
* 📊 **Kunlik Natijalar va Ballar Jadvali:** [Google Sheets — Natijalar Jadvali](https://docs.google.com/spreadsheets/d/1ABSV6HKIylv6cvnMrHUGsTlUBTU-VfXmdHzzXQg99Vw/edit)
{% endhint %}

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSeyP9v04D6XYO30O8yL8rJCHanAWKiWQpvgSRNN2oXQ_pTlMw/viewform?embedded=true" width="100%" height="800" frameborder="0" marginheight="0" marginwidth="0">Yuklanmoqda…</iframe>

---

### ✍️ 25 ta Rasmiy Test Savollari (Nazorat va O'z-o'zini Tekshirish):

Quyida ushbu dars bo'yicha tuzilgan barcha 25 ta rasmiy test savollari keltirilgan. Har bir savol 4 ta variantdan iborat bo'lib, to'g'ri javob belgilangan:

#### 1-Savol: Kompyuter changdan qancha vaqtda tozalanib turilishi tavsiya etiladi?
- [x] **A) Kamida har 6–12 oyda bir marta** *(To'g'ri javob)*
- [ ] B) 10 yilda bir marta
- [ ] C) Har kuni
- [ ] D) Tozalash shart emas

#### 2-Savol: Protsessor harorati odatiy ish holatida (Idle) necha darajadan oshmasligi kerak?
- [x] **A) 35–50 °C** *(To'g'ri javob)*
- [ ] B) 85–95 °C
- [ ] C) 10–15 °C
- [ ] D) 100–120 °C

#### 3-Savol: Protsessor yuklama ostida (Stress test / Gaming) maksimal qancha qizishi xavfsiz hisoblanadi?
- [x] **A) 70–80 °C (90 °C dan oshmasligi lozim)** *(To'g'ri javob)*
- [ ] B) 120–150 °C
- [ ] C) 25 °C
- [ ] D) 200 °C

#### 4-Savol: Kompyuter qismlarining harorati va zo'riqishini kuzatuvchi mashhur utilita qaysi?
- [x] **A) HWMonitor, AIDA64, Core Temp** *(To'g'ri javob)*
- [ ] B) Notepad
- [ ] C) Paint
- [ ] D) Calculator

#### 5-Savol: Termopastani almashtirish davriyligi qanday?
- [x] **A) Har 1–2 yilda bir marta** *(To'g'ri javob)*
- [ ] B) Har hafta
- [ ] C) Hech qachon almashtirilmaydi
- [ ] D) 10 kunda bir

#### 6-Savol: SSD disklarda defragmentatsiya o'tkazish nima sababdan tavsiya etilmaydi?
- [x] **A) U SSD ning flesh-kataklari yozish resursini tez tugatadi va foydasi yo'q** *(To'g'ri javob)*
- [ ] B) SSD ni sekinlashtiradi
- [ ] C) Fayllarni o'chiradi
- [ ] D) Virus yuqtiradi

#### 7-Savol: SSD disklarni optimallashtirish uchun qaysi texnologiya qo'llaniladi?
- [x] **A) TRIM buyrug'i** *(To'g'ri javob)*
- [ ] B) Defrag
- [ ] C) Scandisk
- [ ] D) Format

#### 8-Savol: HDD diskning sog'lig'i va ishonchliligini baholash tizimi nima deyiladi?
- [x] **A) S.M.A.R.T. diagnostikasi** *(To'g'ri javob)*
- [ ] B) POST
- [ ] C) BIOS
- [ ] D) RAM Test

#### 9-Savol: Windows da diskdagi vaqtinchalik va keraksiz fayllarni tozalovchi standart vosita qaysi?
- [x] **A) Disk Cleanup (cleanmgr)** *(To'g'ri javob)*
- [ ] B) Disk Defragmenter
- [ ] C) Paint
- [ ] D) Task Manager

#### 10-Savol: Throttling (Trottling) nima?
- [x] **A) Qizib ketganda protsessorning o'zini kuyishdan asrash uchun chastotasini pasaytirishi** *(To'g'ri javob)*
- [ ] B) Kompyuterni tezlashtirish
- [ ] C) Ovozni o'chirish
- [ ] D) Internetni uzish

#### 11-Savol: Ona platadagi CR2032 'tabletka' batareykaning vazifasi nima?
- [x] **A) Kompyuter o'chganda BIOS sozlamalari va soatni quvvatlab turish** *(To'g'ri javob)*
- [ ] B) Monitorni yoqish
- [ ] C) Protsessorni sovutish
- [ ] D) Fayllarni saqlash

#### 12-Savol: Kompyuter ichini changdan tozalashda changyutgichdan nima uchun ehtiyot bo'lish kerak?
- [x] **A) Statik elektr toki (ESD) hosil qilib, nozik mikrosxemalarni kuydirishi mumkin** *(To'g'ri javob)*
- [ ] B) Shovqin chiqaradi
- [ ] C) Quvvat sarflaydi
- [ ] D) Kabel uziladi

#### 13-Savol: Kuler ventilyatorlari qattiq g'uvillab shovqin qilsa, qanday chora ko'riladi?
- [x] **A) Changdan tozalash va podshipnikiga maxsus moy (silikon moy) tomizish** *(To'g'ri javob)*
- [ ] B) Suv sepish
- [ ] C) Ventilyatorni sindirish
- [ ] D) Hajmini kichraytirish

#### 14-Savol: Eski termopastani protsessor sirtidan tozalash uchun nima ishlatiladi?
- [x] **A) Izopropil spirti yoki quruq mikrofibra latta** *(To'g'ri javob)*
- [ ] B) Suvli sovun
- [ ] C) Pichoq bilan qirish
- [ ] D) Aseton

#### 15-Savol: Tizim bloki ichida havo oqimi qanday yo'naltirilishi lozim?
- [x] **A) Old va pastdan sovuq havo kiradi, orqa va yuqoridan issiq havo chiqariladi** *(To'g'ri javob)*
- [ ] B) Barcha ventilyatorlar ichkariga puflashi kerak
- [ ] C) Barchasi tashqariga puflashi kerak
- [ ] D) Havo oqimi ahamiyatsiz

#### 16-Savol: Kompyuter yuklama ostida birdan o'chib qolsa, asosiy sabab nima bo'lishi mumkin?
- [x] **A) Protsessor yoki videokartaning haddan tashqari qizib ketishi (Overheating) yoki quvvat bloki yetishmovchiligi** *(To'g'ri javob)*
- [ ] B) Klaviatura kirligi
- [ ] C) Sichqoncha tezligi
- [ ] D) Internet yo'qligi

#### 17-Savol: Windows da tizim fayllari butunligini tekshirish va tuzatish konsol buyrug'i qaysi?
- [x] **A) sfc /scannow** *(To'g'ri javob)*
- [ ] B) format c:
- [ ] C) ping google.com
- [ ] D) dir /s

#### 18-Savol: Qattiq disk xatolarini tekshirish va tuzatish buyrug'i nima?
- [x] **A) chkdsk C: /f /r** *(To'g'ri javob)*
- [ ] B) cleanmgr
- [ ] C) ipconfig
- [ ] D) shutdown

#### 19-Savol: Oddiy qalam o'chirg'ichi (rezinka) kompyuter ta'mirlashda qayerda asqotadi?
- [x] **A) RAM va videokarta oltin kontakt tishchalaridagi oksidlanishni xavfsiz tozalashda** *(To'g'ri javob)*
- [ ] B) Termopastani artishda
- [ ] C) Changni artishda
- [ ] D) Ekran tirnalishini yo'qotishda

#### 20-Savol: Tizimning ko'k ekrani (BSOD - Blue Screen of Death) odatda nima sababdan chiqadi?
- [x] **A) Kritik apparat nosozligi (RAM, SSD) yoki drayverlar to'qnashuvi** *(To'g'ri javob)*
- [ ] B) Brauzer ko'pligi
- [ ] C) Video formati
- [ ] D) Musiqa hajmi

#### 21-Savol: Quvvat blokidagi elektrolitik kondensatorlarning shishib qolishi nima oqibatga olib keladi?
- [x] **A) Kuchlanish beqarorlashib, kompyuter o'chib-yonishi yoki yonmasligiga** *(To'g'ri javob)*
- [ ] B) Kompyuter tezlashishiga
- [ ] C) Sovuq havo chiqishiga
- [ ] D) Internet to'xtashiga

#### 22-Savol: MemTest86 dasturi nima vazifani bajaradi?
- [x] **A) Operativ xotira (RAM) modullarining xatolarini chuqur tekshiradi** *(To'g'ri javob)*
- [ ] B) Qattiq diskni formatlaydi
- [ ] C) Windows o'rnatadi
- [ ] D) Parolni tiklaydi

#### 23-Savol: Kompyuter yoqilganda 1 ta qisqa signal (Beep code) nimani bildiradi?
- [x] **A) POST tekshiruvi muvaffaqiyatli o'tdi, barcha qismlar soz** *(To'g'ri javob)*
- [ ] B) Protsessor buzildi
- [ ] C) RAM yo'q
- [ ] D) Quvvat yo'q

#### 24-Savol: Noutbuk sovutish panellari (Cooling pad) qanday yordam beradi?
- [x] **A) Noutbuk ostiga qo'shimcha havo haydab, haroratni 3-7 darajaga tushiradi** *(To'g'ri javob)*
- [ ] B) Batareyani to'ldiradi
- [ ] C) Klaviatura tozalaydi
- [ ] D) Ekranni yorqin qiladi

#### 25-Savol: Kompyuterni qayta o'rnatishdan (Reinstall) oldin ma'lumotlarni qayerga nusxalash shart?
- [x] **A) Tashqi diskka, fleshkaga yoki bulutli xotiraga (Backup)** *(To'g'ri javob)*
- [ ] B) Savatga (Recycle bin)
- [ ] C) Temp papkasiga
- [ ] D) Monitorga

---


## 6. 🏠 Mustaqil Amaliy Uyga Vazifa

### Topshiriq:
1. Kompyuteringizda `cleanmgr` utilitasini ishga tushiring va tizimli fayllarni tozalash (Clean up system files) tekshiruvini bajaring.
2. Windows Security orqali kompyuterni tezkor tekshiruvdan (Quick Scan) o'tkazing va xavfsizlik hisobotini oching.
3. Tizim blokining tashqi ventilyatsiya teshiklarini va noutbuk tag qismini changdan tozalash bo'yicha profilaktika rejasini yozing.
4. Bajarilgan amallarning skrinshotlarini yagona hujjatga jamlang.

**Topshirish formati:** Hisobotni `FIO_9-Mavzu_Profilaktika.docx` nomi bilan platformaga yuklang.

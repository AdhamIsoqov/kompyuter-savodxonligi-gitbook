# 20-Mavzu: Internet Arxitekturasi, Brauzerlar va Samarali Qidiruv Usullari

Assalomu alaykum! Kasbtech Akademiyasining Kompyuter savodxonligi kursidagi 20-darsimizga xush kelibsiz.

Bugungi darsdan boshlab biz mutlaqo yangi va nihoyatda hayajonli bosqich — **3-Modul: "Internet, Bulutli Xizmatlar va Sun'iy Intellekt Vositalari"** olamiga qadam qo'yamiz.

Oldingi 2-modulda biz shaxsiy kompyuterimiz ichida Microsoft Word, Excel va PowerPoint vositasida to'liq professional hujjatlar yaratishni o'rgandik. Endi esa lokal kompyuter doirasidan tashqariga chiqib, millionlab kompyuterlarni o'zaro bog'lab turuvchi global axborot maydoni — **Internet** bilan tanishamiz.

Internetda milliardlab ma'lumotlar mavjud, biroq ularning ichidan kerakli, to'g'ri va xavfsiz axborotni bir zumda topa olish — zamonaviy mutaxassisning eng qimmatli ko'nikmalaridan biridir. Ushbu darsda biz veb-brauzerlar bilan ishlash madaniyati, xavfsizlik protokollari va Google qidiruvining professional "sehrli" operatorlarini o'rganamiz.

Kelgusi 21-darsimizda esa bugun o'rganiladigan brauzer imkoniyatlaridan foydalanib, rasmiy elektron pochta (Gmail) yozishmalari hamda Google Drive bulutli xotirasida jamoaviy ishlashni yo'lga qo'yamiz.

{% hint style="info" %}
**Dars maqsadi:** Global internet tarmog'ining ishlash prinsiplari (Klient-Server modeli, DNS, IP), xavfsiz ulanish protokollari (HTTP vs HTTPS), zamonaviy veb-brauzerlar (Google Chrome, Microsoft Edge) imkoniyatlari, maxfiy rejim (Incognito), Google qidiruv tizimining ilg'or mantiqiy operatorlari (`site:`, `filetype:`, `"..."`, `-`) hamda internetdagi axborotlarning ishonchliligini baholash (Fact-checking) ko'nikmalarini egallash.
{% endhint %}

### 🎯 Kutilayotgan Kompetensiyalar
* **Bilishingiz kerak:**
  * Internet qanday ishlashi: Klient-Server modeli, IP-manzil va DNS tushunchalari.
  * HTTP va HTTPS (xavfsiz shifrlangan qulf belgisi) protokollari o'rtasidagi farq.
  * Brauzer keshi (Cache), Cookie fayllari va Inkognito rejimining maxfiylikdagi asl o'rni.
  * Google qidiruv operatorlari sintaksisi va axborot ishonchliligini tekshirish mezonlari.
* **Bajara olishingiz kerak:**
  * Brauzerda sahifalarni (Tabs) boshqarish, xatcho'plar (Bookmarks) yaratish va tarixni tozalash (`Ctrl + Shift + Delete`).
  * Yopilib ketgan sahifalarni darhol qayta tiklash (`Ctrl + Shift + T`).
  * Ilg'or qidiruv operatorlari yordamida internetdan faqat rasmiy davlat saytlaridan (`site:gov.uz`) yoki faqat PDF kitoblarni (`filetype:pdf`) soniyalar ichida topish.
  * Soxta (fishing) havolalarni haqiqiy domenlardan vizual ajrata olish.

## 🎬 1. Video Dars

{% hint style="info" %}
**Video darslik:** Brauzerlar bilan professional ishlash va Google qidiruv sirlari bo'yicha quyidagi videoni tomosha qiling:
{% endhint %}

[Iframe/Embed: 20-Mavzu Bo'yicha YouTube Video Dars Havolasi]

## 2. 📖 Chuqurlashtirilgan Nazariy Ma'ruza

### 2.1. Internet Arxitekturasi: Klient-Server, IP va DNS

Internet — butun dunyo bo'ylab joylashgan millionlab serverlar, kompyuterlar va mobil qurilmalarni birlashtiruvchi global axborot tarmog'idir.

1. **Klient-Server modeli:**
   * **Klient (Mijoz):** Sizning kompyuteringiz yoki telefoningiz (ma'lumot so'rovchi tomon).
   * **Server:** Ma'lumotlarni kechayu-kunduz saqlab, internetga uzatib turuvchi yuqori quvvatli kompyuter.
2. **IP-manzil va DNS (Domen Nomlari Tizimi):**
   * Har bir qurilma internetda o'zining raqamli pasporti — **IP-manziliga** ega (masalan: `142.250.185.206`).
   * Insonlar uchun bu kabi murakkab raqamlarni yodlab qolish juda noqulay. Shu sababli **DNS (Domain Name System)** ishlab chiqilgan. DNS — internetning "telefon kitobi" bo'lib, `google.com` kabi so'zlarni serverning raqamli IP-manziliga bir zumda aylantirib beradi.

```
[Foydalanuvchi: google.com yozdi] 
              │
              ▼
   [DNS Server: IP ni aniqlaydi (142.250.185.206)]
              │
              ▼
    [Veb-Server: Sahifani foydalanuvchiga uzatadi]
              │
              ▼
    [Brauzer: Ekranda chiroyli veb-sahifani chizib beradi]
```

### 2.2. HTTP va HTTPS: Xavfsiz Aloqa Protokollari

Brauzer satriga qaraganingizda har bir sayt manzili boshida protokol ko'rsatiladi:
* **HTTP (HyperText Transfer Protocol):** Ma'lumotlar ochiq matn ko'rinishida uzatiladi. Agar siz ochiq Wi-Fi tarmog'ida HTTP saytga parol kiritsangiz, oraliqdagi har qanday tajovuzkor uni tutib olishi mumkin.
* **HTTPS (HyperText Transfer Protocol Secure):** Ma'lumotlar zamonaviy **SSL/TLS** shifrlash kalitlari bilan himoyalanadi. Brauzer manzilida yashil yoki qora **Qulf belgisi** ko'rinadi. Bank saytlari, elektron pochtalar va barcha rasmiy xizmatlar faqat HTTPS orqali ishlashi shart!

### 2.3. Brauzer Muhiti: Kesh (Cache) va Cookie Fayllari

Brauzer (Google Chrome, Microsoft Edge, Mozilla Firefox) — internetdagi HTML, CSS va JavaScript kodlarini inson tushunadigan vizual interfeysga aylantiruvchi dasturdir.

* **Kesh (Cache):** Saytdagi rasmlar, logotiplar va dizayn elementlari kompyuter xotirasiga vaqtincha saqlab olinadi. Natijada saytga ikkinchi marta kirganingizda u qaytadan yuklanmasdan, juda tez ochiladi.
* **Cookie (Kuki):** Sizning saytdagi tanlovlaringiz (til sozlamalari, savatchadagi tovarlar, tizimga kirish sessiyasi) saqlanadigan kichik matnli fayllar.

### 2.4. Brauzerda Ishlashning Tezkor Klaviatura Yorliqlari

Professional foydalanuvchi brauzerda har bir amal uchun sichqonchani qidirmaydi, balki klaviatura yorliqlaridan unumli foydalanadi:

| Klaviatura Yorlig'i | Vazifasi | Amaliy Ahamiyati |
| :--- | :--- | :--- |
| `Ctrl + T` | Yangi bo'sh sahifa (Tab) ochish | Ishni to'xtatmasdan boshqa saytga o'tish |
| `Ctrl + W` | Joriy ochiq sahifani darhol yopish | Ortiqcha sahifalarni tez yopish |
| `Ctrl + Shift + T` | **Tasodifan yopib yuborilgan oxirgi sahifani qayta tiklash** | "Hayot qutqaruvchi" eng muhim yorliq! |
| `Ctrl + D` | Sahifani xatcho'plarga (Bookmarks) saqlash | Muhim sayt manzilini yo'qotib qo'ymaslik |
| `Ctrl + H` | Ko'rilgan sahifalar tarixini (History) ochish | O'tgan haftada o'qilgan maqolani topish |
| `Ctrl + J` | Yuklab olingan fayllar (Downloads) panelini ochish | Yuklangan faylni darhol papkadan ko'rish |
| `Ctrl + Shift + N` | Maxfiy oyna (Incognito / InPrivate) ochish | Begona kompyuterda iz qoldirmaslik |
| `Ctrl + Shift + Delete` | Kesh va brauzer tarixini tozalash oynasini ochish | Xotirani bo'shatish va xavfsizlikni ta'minlash |

{% hint style="success" %}
**Pro-Tip (Incognito rejimining asl haqiqati):**
Inkognito rejimi sizni internetda butunlay "anonim xaker" qilib qo'ymaydi! U faqat lokal kompyuter doirasida ishlaydi: oynani yopganingizdan so'ng qaysi saytlarga kirganingiz tarixi, kiritilgan parollar va cookie fayllari o'sha kompyuter xotirasida saqlanib qolmaydi. Bu begona kompyuterda yoki mehmonda shaxsiy pochtangizga kirishda juda qulaydir.
{% endhint %}

### 2.5. Professional Google Qidiruv Operatorlari

Oddiy odamlar Google qidiruviga "Men noutbuk sotib olmoqchiman qayerda arzon" kabi uzun jumlalarni yozishadi va yuzlab foydasiz reklamalarga duch kelishadi. Professional foydalanuvchilar esa qidiruv operatorlaridan foydalanib, aniq natijaga erishadilar:

```
[Ilg'or Qidiruv Operatorlari Mantiqi]
  1. "Kompyuter savodxonligi"  ===> Aniq shu ibora qatnashgan sahifalarni topadi
  2. Mehnat kodeksi filetype:pdf => Faqat .PDF kitob fayllarini yuklab beradi
  3. Qaror site:lex.uz           => Faqat rasmiy lex.uz sayti ichidan qidiradi
  4. Noutbuk sotib olish -kredit  => "kredit" so'zi qatnashgan reklamalarni chiqarib tashlaydi
```

* **Qo'shtirnoq `"..."`:** Belgilangan so'zlar aynan shu tartibda ketma-ket kelgan veb-sahifalarni qidiradi (aniq fraza).
* **`site:sayt_manzili`:** Qidiruvni faqat aniq bitta veb-sayt yoki milliy domen hududi bilan cheklaydi (masalan: `Prezident qarori site:lex.uz` yoki `qabul site:gov.uz`).
* **`filetype:kengaytma`:** Faqat ma'lum bir formatdagi tayyor fayllarni qidiradi (`filetype:pdf`, `filetype:docx`, `filetype:xlsx`, `filetype:pptx`).
* **Minus belgisi `-`:** Qidiruv natijasidan istalmagan kalit so'zlarni butunlay chiqarib tashlaydi (masalan: `smartfon narxi -reklama`).
* **Mantiqiy operator `OR` (yoki):** Bir vaqtning o'zida ikkita muqobil variantdan birini qidirish (masalan: `Python OR JavaScript kurslari`).

## 3. 💻 Bosqichma-bosqich Amaliy Mashg'ulot (Lab Task)

Ushbu amaliy mashg'ulotda siz Google qidiruv operatorlari yordamida rasmiy davlat qonunchiligi hujjatini bir zumda topishni mashq qilasiz.

### Kerakli Resurslar:
* Kompyuter va internet aloqasi;
* Brauzer (Google Chrome yoki Microsoft Edge).

### 📄 Amaliy Mashg'ulot Shabloni:
{% hint style="success" %}
**📄 Rasmiy Amaliy Mashg'ulot va Uy Vazifasi Shabloni (Google Docs (Hujjat)):**
Ushbu darsning barcha bosqichlarini bajarish, natijalar/hisobotlarni kiritish va uy vazifasini topshirish uchun quyidagi rasmiy shablondan foydalaning:
* 🌐 **Onlayn ko'rish va tahrirlash:** <a href="https://docs.google.com/document/d/1qP08ol8vRIRu5qLNdtFUj9StJng2MLue-eWIfsgNQYY/edit?usp=sharing" target="_blank" rel="noopener noreferrer">20-Mavzu: Internet va Qidiruv Tizimlari — Shablonni ochish</a>
* 📥 **Shaxsiy Drive-ga nusxalash (Tavsiya etiladi):** <a href="https://docs.google.com/document/d/1qP08ol8vRIRu5qLNdtFUj9StJng2MLue-eWIfsgNQYY/copy" target="_blank" rel="noopener noreferrer">Nusxa yaratish (Make a copy)</a>
{% endhint %}

{% embed url="https://docs.google.com/document/d/1qP08ol8vRIRu5qLNdtFUj9StJng2MLue-eWIfsgNQYY/preview" %}

> *Eslatma: Shablondan nusxa oling va quyidagi qidiruv amallari skrinshotlarini unga kiriting.*

### Bajarish Bosqichlari:

1. **1-Qadam:** Brauzeringizni oching va `Ctrl + T` orqali yangi oyna oching.
2. **2-Qadam:** Google qidiruv satriga aynan quyidagi so'rovni kiriting:
   `"Kiberxavfsizlik to'g'risida" site:lex.uz filetype:pdf`
3. **3-Qadam:** Qidiruv natijalarini kuzating — ro'yxatda birorta ham reklama sayti chiqmaydi, faqat `lex.uz` portalidagi rasmiy qonun hujjati PDF formatda chiqadi.
4. **4-Qadam (Xatcho'pga saqlash):** Saytni oching va `Ctrl + D` tugmalarini bosib, "Bookmarks bar" (Xatcho'plar paneli)ga saqlang.
5. **5-Qadam (Yopiq tabni tiklash mashqi):** Ushbu sahifani `Ctrl + W` bilan yoping. So'ng zudlik bilan `Ctrl + Shift + T` tugmalarini bosing — yopilgan sahifa darhol qayta ochiladi!
6. **6-Qadam (Maxfiy rejim):** Klaviaturada `Ctrl + Shift + N` bosing va InPrivate / Incognito darchasini ochib, uning xususiyatlarini o'rganing.

{% hint style="warning" %}
**Ehtiyot bo'ling:**
Sayt manzilidagi xavfsizlik qulfi belgisiga doimo e'tibor bering! Agar brauzer manzilida **"Not Secure" (Xavfli)** yozuvi chiqsa yoki qizil chiziq tortilgan bo'lsa, bunday saytlarga hech qachon shaxsiy plastik karta ma'lumotlaringizni yoki parollaringizni kiritmang!
{% endhint %}

## 4. 🛠 Real Ish Vaziyati va Muammolarni Hal Qilish (Case-Study)

### Muammo:
Ofis xodimi internetdan korxona uchun yangi "Namunaviy Mehnat Shartnomasi" shablonini qidirdi. Qidiruvda chiqqan birinchi chiroyli reklamali saytga kirib, "Hujjatni yuklab olish" tugmasini bosdi. Natijada kompyuterga Word hujjati o'rniga `Shartnoma.docx.exe` nomli fayl yuklandi. Xodim uni ochganida kompyuterdagi barcha fayllar shifrlanib (Ransomware virusi), ekran bloklanib qoldi.

### Muammoning Kelib Chiqish Sababi:
Xodim internet qidiruv natijalariga tanqidiy qaramagan, rasmiy manba o'rniga virusli pirat saytga kirgan va fayl kengaytmasi `.docx` emas, `.exe` (zararli dastur) ekanligiga e'tibor bermagan.

### Bosqichma-bosqich Yechim:
1. Hech qachon shubhali yuklash tugmalariga (katta qizil "Download / Скачать") ishonmang.
2. Rasmiy qonuniy hujjatlar faqat davlat portallaridan (`lex.uz`, `gov.uz`) yuklanishi kerak.
3. To'g'ri qidiruv so'rovi quyidagicha bo'lishi shart edi:
   `namunaviy mehnat shartnomasi site:gov.uz` yoki `filetype:docx`
4. Yuklangan fayl kengaytmasini har doim tekshiring: agar hujjat nomi oxirida `.exe` yoki `.vbs` tursa, uni aslo ishga tushirmasdan darhol o'chirib tashlash (`Shift + Delete`) shart!

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz)

{% hint style="info" %}
**📝 Rasmiy Onlayn Test Sinovi (Google Forms — 15 ta saralangan savol, 100 ballik baholash):**
Ushbu dars bo'yicha olgan bilimlaringizni sinash uchun quyidagi rasmiy testni topshiring (15 ta saralangan test savoli, jami: 100 ball):
* 🔗 **Onlayn Testni Ochish (To'liq Ekranda):** <a href="https://docs.google.com/forms/d/e/1FAIpQLSeUy_Ha4irUbVPA1hJ2vplU6gpzWitHORAKQChM9P_WLT6vlQ/viewform" target="_blank" rel="noopener noreferrer">20-Mavzu: Internet va Qidiruv Tizimlari — Testni Topshirish</a>
* 📊 **Kunlik Natijalar va Ballar Jadvali:** <a href="https://docs.google.com/spreadsheets/d/1e6cB0YStabEYK15YbJlnzTfnCAZWd4ZsWG_tjbcDT8c/edit" target="_blank" rel="noopener noreferrer">Google Sheets — Natijalar Jadvali</a>
{% endhint %}

{% embed url="https://docs.google.com/forms/d/e/1FAIpQLSeUy_Ha4irUbVPA1hJ2vplU6gpzWitHORAKQChM9P_WLT6vlQ/viewform" %}

## 6. 🏠 Mustaqil Amaliy Uyga Vazifa

### Topshiriq:
1. Google qidiruv tizimida `filetype:pdf site:gov.uz` operatorlari ishtirokida kompyuter texnologiyalariga oid bitta rasmiy davlat qarorini toping.
2. Brauzeringizda ushbu sahifani xatcho'plar paneliga (Bookmarks) qo'shing.
3. `Ctrl + Shift + Delete` oynasini ochib, brauzer keshini tozalash darchasini skrinshot qiling.

**Topshirish formati:** Bajarilgan topshiriq skrinshotlarini `FIO_20-Mavzu_Internet_Qidiruv.docx` shaklida platformaga yuklang.

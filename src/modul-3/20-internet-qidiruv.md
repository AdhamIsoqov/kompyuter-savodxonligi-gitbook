# 20-Mavzu: Internet Arxitekturasi, Brauzerlar va Samarali Qidiruv Usullari

{% hint style="info" %}
**Dars maqsadi:** Global internet tarmog'ining ishlash prinsiplari, zamonaviy brauzerlar (Google Chrome, Microsoft Edge) imkoniyatlari, maxfiy rejim (Incognito), Google qidiruv tizimining ilg'or mantiqiy operatorlari (`site:`, `filetype:`, `"..."`, `-`) hamda internetdagi axborotlarning ishonchliligini (fact-checking) baholashni o'rganish.
{% endhint %}

### 🎯 Kutilayotgan Kompetensiyalar
* **Bilishingiz kerak:**
  * HTTP va HTTPS (xavfsiz shifrlangan qulf belgisi) protokollari farqi.
  * Brauzer keshi (Cache), Cookie fayllari va Inkognito rejimining maxfiylikdagi o'rni.
  * Google qidiruv operatorlari sintaksisi.
* **Bajara olishingiz kerak:**
  * Brauzerda teglarni (Tabs) boshqarish, xatcho'plar (Bookmarks) yaratish va tarixni tozalash (`Ctrl + Shift + Delete`).
  * Ilg'or qidiruv operatorlari yordamida internetdan faqat rasmiy davlat saytlaridan (`site:gov.uz`) yoki faqat PDF kitoblarni (`filetype:pdf`) topish.
  * Soxta (fishing) havolalarni haqiqiy domenlardan vizual ajrata olish.

## 🎬 1. Video Dars

{% hint style="info" %}
**Video darslik:** Brauzerlar bilan professional ishlash va Google qidiruv sirlari bo'yicha quyidagi videoni tomosha qiling:
{% endhint %}

[Iframe/Embed: 20-Mavzu Bo'yicha YouTube Video Dars Havolasi]

## 2. 📖 Chuqurlashtirilgan Nazariy Ma'ruza

### 2.1. Brauzer Muhiti va Tezkor Boshqaruv

Brauzer — internetdagi HTML, CSS va JavaScript kodlarini inson tushunadigan vizual veb-sahifaga aylantirib beruvchi dasturdir.

| Klaviatura Yorlig'i | Vazifasi | Nima uchun juda qulay? |
| :--- | :--- | :--- |
| `Ctrl + T` | Yangi bo'sh oyna (Tab) ochish | Dasturdan chiqmasdan boshqa saytni ochish |
| `Ctrl + W` | Joriy ochiq tabni yopish | Keraksiz sahifani tez yopish |
| `Ctrl + Shift + T` | Tasodifan yopib yuborilgan oxirgi tabni qayta ochish | **"Hayot qutqaruvchi" yorliq!** |
| `Ctrl + D` | Saytni xatcho'plarga (Bookmarks/Favorites) saqlash | Muhim saytni yo'qotib qo'ymaslik |
| `Ctrl + H` | Ko'rilgan saytlar tarixini (History) ochish | Bir necha kun oldin ochilgan saytni topish |
| `Ctrl + J` | Yuklab olingan fayllar (Downloads) ro'yxatini ochish | Yuklangan faylni darhol papkada ko'rish |
| `Ctrl + Shift + N` | Maxfiy (Incognito / InPrivate) oynani ochish | Kesh va tarixdan iz qoldirmaslik |

{% hint style="success" %}
**Pro-Tip (Incognito rejimining asl haqiqati):**
Inkognito rejimi sizni internetda butunlay "ko'rinmas" yoki "anonim xaker" qilib qo'ymaydi! U faqat kompyuteringiz ichida ishlaydi: siz yopganingizdan so'ng qaysi saytlarga kirganingiz tarixi, kiritilgan parollar va cookie fayllari o'sha kompyuterda saqlanib qolmaydi. Bu begona yoki jamoat kompyuterida (masalan, internet kafeda) o'z pochtangizga kirishda juda zarur.
{% endhint %}

### 2.2. Professional Google Qidiruv Operatorlari

Ko'pchilik odamlar qidiruvga uzun jumlalar yozishadi va minglab keraksiz reklama saytlari ichida adashib qolishadi. Professional foydalanuvchilar qidiruv operatorlaridan foydalanadi:

```
[Ilg'or Qidiruv So'rovlari Mantiqi]
  1. "Kompyuter savodxonligi"  ===> Aniq shu ibora qatnashgan sahifalarni topadi
  2. Mehnat kodeksi filetype:pdf => Faqat .PDF kitob fayllarini yuklab beradi
  3. Qaror site:lex.uz           => Faqat rasmiy lex.uz sayti ichidan qidiradi
  4. Noutbuk sotib olish -kredit  => "kredit" so'zi qatnashgan reklamalarni chiqarib tashlaydi
```

* **Qo'shtirnoq `"..."`:** So'zlar aynan shu tartibda birga kelgan sahifalarni qidiradi.
* **`site:sayt_nomi`:** Qidiruvni faqat bitta domenga cheklaydi (masalan: `talaba site:edu.uz`).
* **`filetype:kengaytma`:** Faqat ma'lum bir formatdagi fayllarni topadi (`filetype:docx`, `filetype:pdf`, `filetype:xlsx`).
* **Minus belgisi `-`:** Keraksiz so'zlarni natijadan chiqarib tashlaydi.

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
**📝 Rasmiy Onlayn Test Sinovi (Google Forms — 25 ta savol, 100 ballik baholash):**
Ushbu dars bo'yicha olgan bilimlaringizni sinash uchun quyidagi rasmiy testni topshiring (Har bir to'g'ri javob 4 ball, jami: 100 ball):
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

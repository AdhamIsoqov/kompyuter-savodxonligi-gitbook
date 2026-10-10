# 23-Mavzu: Axborot Xavfsizligi, Kibergigiyena va Raqamli Madaniyat

Assalomu alaykum! Kasbtech Akademiyasining Kompyuter savodxonligi kursidagi 23-darsimizga xush kelibsiz.

Bugungi darsdan boshlab biz butun kursimizning eng mas'uliyatli va hal qiluvchi bosqichi — **4-Modul: "Axborot Xavfsizligi, Raqamli Madaniyat va Umumiy Takrorlash"** bo'limini boshlaymiz.

Oldingi 3-modulda biz global internet tarmog'i, Google bulutli xizmatlari va zamonaviy Sun'iy Intellekt texnologiyalaridan unumli foydalanishni to'liq o'zlashtirdik. Biroq raqamli olam qanchalik keng imkoniyatlar ochib bersa, undagi xavflar — hisoblarni o'g'irlash, fishing firibgarligi, viruslar va bank kartalariga hujumlar xavfi ham shunchalik ortib boradi. Shuning uchun professional foydalanuvchi nafaqat kompyuterda tez ishlashni, balki o'zining va o'z tashkilotining raqamli ma'lumotlarini ishonchli himoya qila olishni (kibergigiyena) bilishi shart!

Kelgusi 24-darsimizda esa butun kurs bo'yicha barcha 4 ta modulni umumlashtiruvchi katta yakuniy takrorlash va sertifikatlashga tayyorgarlik darsi kutmoqda.

{% hint style="info" %}
**Dars maqsadi:** Axborot xavfsizligi asoslari (CIA triadasi), kuchli parollar siyosati, Ikki bosqichli autentifikatsiya (2FA), ijtimoiy muhandislik va fishing (Phishing) hujumlarini aniqlash, bank kartalari va shaxsiy ma'lumotlar xavfsizligi, ommaviy Wi-Fi tarmoqlaridan xavfsiz foydalanish hamda raqamli etika qoidalarini chuqur egallash.
{% endhint %}

### 🎯 Kutilayotgan Kompetensiyalar
* **Bilishingiz kerak:**
  * Axborot xavfsizligi triadasi (Maxfiylik, Butunlik, Foydalanish ochiqligi).
  * Kiberjinoyatchilar tomonidan qo'llaniladigan fishing va ijtimoiy muhandislik usullari.
  * Ikki bosqichli himoya (2FA / Two-Factor Authentication) ning ishlash mexanizmi.
  * Ommaviy ochiq Wi-Fi tarmoqlarida shaxsiy parollarni kiritish xatarlari.
* **Bajara olishingiz kerak:**
  * Akkauntlar (Google, Telegram, Davlat xizmatlari) uchun 2FA himoyasini mustaqil yoqish.
  * Soxta (fishing) havolalarni va firibgarlik xabarlarini bir qarashda aniqlash.
  * Maxsus parol boshqaruvchilari (Password Manager) va xavfsiz parollar generatoridan foydalanish.
  * Bank kartalari va shaxsiy ma'lumotlarni begonalardan himoya qilish.

## 🎬 1. Video Dars

{% hint style="info" %}
**Video darslik:** Kiberxavfsizlik, fishingdan himoyalanish va 2FA o'rnatish bo'yicha quyidagi videoni tomosha qiling:
{% endhint %}

[Iframe/Embed: 23-Mavzu Bo'yicha YouTube Video Dars Havolasi]

### 📊 Dars Slaydlari va Taqdimoti (EduRecurses)

{% hint style="success" %}
**📊 Rasmiy Taqdimot Slaydlari (Microsoft PowerPoint / Google Drive):**
Ushbu darsning barcha mavzulari, grafik sxemalari va ko'rgazmali materiallarini onlayn ko'rish hamda yuklab olish uchun quyidagi rasmiy havoladan foydalaning:
* 🌐 **Onlayn ko'rish va yuklab olish:** <a href="https://drive.google.com/file/d/154FhOqiTFPREI5hf7F12fzNFQRP2anVj/view?usp=sharing" target="_blank" rel="noopener noreferrer">23-Mavzu: Axborot Xavfsizligi va Raqamli Madaniyat — Taqdimot Slaydlarini Ochish</a>
{% endhint %}

{% embed url="https://drive.google.com/file/d/154FhOqiTFPREI5hf7F12fzNFQRP2anVj/preview" %}


## 2. 📖 Chuqurlashtirilgan Nazariy Ma'ruza

### 2.1. Axborot Xavfsizligining 3 Asosiy Ustuni (CIA Triad)

Xalqaro xavfsizlik standartlariga ko'ra, axborot xavfsizligi uchta asosiy tamoyilga tayanadi:
1. **Confidentiality (Maxfiylik):** Ma'lumotlarni faqat ruxsati bor shaxslar ko'ra olishi (begonalardan yashirish).
2. **Integrity (Butunlik):** Ma'lumotlarning soxtalashtirilmasligi, o'g'irlanmasligi yoki buzilmasligi.
3. **Availability (Foydalanish ochiqligi):** Vakolatli foydalanuvchi istalgan vaqtda o'z tizimi va ma'lumotlariga to'siqsiz kira olishi.

### 2.2. Kuchli Parollar Siyosati va 2FA (Ikki Bosqichli Himoya)

Bugungi kunda hatto murakkab bo'lgan oddiy parollar ham xakerlar tomonidan internetga sizdirilgan bazalardan topilishi mumkin. Shuning uchun har bir hisobga **ikki bosqichli himoya (2FA)** o'rnatiladi:

```
[2FA - Ikki Bosqichli Himoya Zanjiri]
  1-Bosqich: Foydalanuvchi paroli (Siz biladigan ma'lumot)
        │
        ▼
  2-Bosqich: Telefoningizga kelgan 6 xonali SMS yoki Authenticator kodi (Sizda bor qurilma)
        │
        ▼
  XAVFSIZ KIRISH (Xaker parolingizni o'g'irlasa ham, telefoningizsiz tizimga kira olmaydi!)
```

| Parametr | Zaif / Xavfli Parol | Kuchli / Xavfsiz Parol |
| :--- | :--- | :--- |
| **Tarkibi** | `123456`, `password`, `qwerty` | Katta harf, kichik harf, raqam va maxsus belgilar |
| **Shaxsiy ma'lumot**| `aziz1998`, `nodira_2004` (Tug'ilgan sana, ism) | Shaxsga umuman aloqasiz so'zlar birikmasi |
| **Uzunligi** | 6–8 ta belgi (bir necha soniyada buziladi) | **Kamida 12–16 ta belgi** |
| **Misol** | `Alisher1995` | `K@sb#Tech_2026!Pro` |

### 2.3. Fishing (Phishing) va Ijtimoiy Muhandislik Turlari

**Fishing (Qarmoqqa ilintirish)** — kiberjinoyatchilarning mashhur tashkilotlar (Markaziy Bank, Payme, Click, Telegram ma'muriyati) nomidan soxta xabarlar yuborib, sizning login, parol va bank karta ma'lumotlaringizni o'g'irlashga qaratilgan tuzog'idir.

* **Phishing (Elektron pochta va saytlar orqali):** Soxta nusxa veb-sayt havolasi yuboriladi.
* **Smishing (SMS orqali fishing):** "Sizga davlatdan moddiy yordam chiqdi, olish uchun havolaga kiring" ko'rinishidagi SMS xabarlar.
* **Vishing (Ovozli telefon qo'ng'iroqlari):** O'zini bank xavfsizlik xodimi yoki huquq-tartibot organi deb tanishtirib, zudlik bilan pulni "xavfsiz hisobga" o'tkazishni yoki SMS kodni aytishni talab qiluvchilar.

**Firibgarlikning 4 ta shubhasiz belgisi:**
1. **Shoshilinch talab va qo'rquv uyg'otish:** *"Akkauntingiz 1 soatda bloklanadi!"* yoki *"Kartangizdan noqonuniy pul yechildi!"*
2. **Katta bepul boylik va'da qilish:** *"Siz 50 000 000 so'm yutib oldingiz!"*
3. **Soxta domen manzili:** Haqiqiy sayt `click.uz` bo'lsa, firibgarlar `click-uz-bonus.com` yoki `payme-tolov.site` ochishadi.
4. **Tasdiqlash kodini so'rash:** Bank xodimlari HECH QACHON telefon qilib SMS orqali kelgan 6 xonali maxfiy kodni so'ramaydi!

{% hint style="success" %}
**Pro-Tip (Telegramda 2FA ni darhol yoqing!):**
O'zbekistonda eng ko'p sodir bo'ladigan kiberjinoyat — Telegram akkauntlarini o'g'irlashdir. Buning oldini olish uchun zudlik bilan Telegram sozlamalariga kiring:
**Settings -> Privacy and Security -> Two-Step Verification (Ikki bosqichli tekshiruv)** bo'limini yoqing va shaxsiy maxfiy parol o'rnating! Endi hech kim sizning nomingizdan yangi qurilmada Telegramga kira olmaydi.
{% endhint %}

## 3. 💻 Bosqichma-bosqich Amaliy Mashg'ulot (Lab Task)

Ushbu amaliy mashg'ulotda siz o'z Google akkauntingiz xavfsizlik darajasini tekshirasiz va 2FA himoyasini sozlaysiz.

### Kerakli Resurslar:
* Kompyuter va internet;
* Shaxsiy Google hisobi;
* Smartfon (SMS yoki tasdiqlash uchun).

### 📄 Amaliy Mashg'ulot Shabloni:
{% hint style="success" %}
**📄 Rasmiy Amaliy Mashg'ulot va Uy Vazifasi Shabloni (Google Docs (Hujjat)):**
Ushbu darsning barcha bosqichlarini bajarish, natijalar/hisobotlarni kiritish va uy vazifasini topshirish uchun quyidagi rasmiy shablondan foydalaning:
* 🌐 **Onlayn ko'rish va tahrirlash:** <a href="https://docs.google.com/document/d/110_t3xTQg_OKiXYBEet9JPAb_Y_svrKCNS6pYyNNJy4/edit?usp=sharing" target="_blank" rel="noopener noreferrer">23-Mavzu: Axborot Xavfsizligi va Raqamli Madaniyat — Shablonni ochish</a>
* 📥 **Shaxsiy Drive-ga nusxalash (Tavsiya etiladi):** <a href="https://docs.google.com/document/d/110_t3xTQg_OKiXYBEet9JPAb_Y_svrKCNS6pYyNNJy4/copy" target="_blank" rel="noopener noreferrer">Nusxa yaratish (Make a copy)</a>
{% endhint %}

{% embed url="https://docs.google.com/document/d/110_t3xTQg_OKiXYBEet9JPAb_Y_svrKCNS6pYyNNJy4/preview" %}

> *Eslatma: Shablondan nusxa oling va quyidagi 6 ta xavfsizlik qadamini bajaring.*

### Bajarish Bosqichlari:

1. **1-Qadam:** Brauzerda Google hisobingiz boshqaruviga kiring (`myaccount.google.com`).
2. **2-Qadam:** Chap paneldan **Security (Xavfsizlik)** bo'limini tanlang.
3. **3-Qadam (Xavfsizlik auditi):** "Security recommendations" (Xavfsizlik tavsiyalari) panelini ko'zdan kechiring.
4. **4-Qadam (2-Step Verification):** **2-Step Verification** bandini oching va o'z telefon raqamingizni ulab, ikki bosqichli himoyani faollashtiring.
5. **5-Qadam (Qurilmalar nazorati):** "Your devices" bo'limiga kiring. Akkauntingizga ulangan barcha kompyuter va telefonlar ro'yxatini tekshiring. Notanish yoki eski qurilmalar bo'lsa, ustiga bosib **Sign out (Chiqib ketish)** buyrug'ini bering.
6. **6-Qadam (Xavfsiz parol sinovi):** Parollarni tekshirish (Password Checkup) vositasida parollaringiz buzilgan ma'lumotlar bazalarida sizib chiqqan yoki yo'qligini tekshirib, hisobotga skrinshot joylang.

{% hint style="warning" %}
**Qat'iy qoida:**
SMS orqali telefoningizga kelgan 6 xonali tasdiqlash kodini (One-Time Password — OTP) HECH KIMGA, hatto o'zini huquq-tartibot organi xodimi yoki bank boshqaruvchisi deb tanishtirgan shaxslarga ham ASLO aytmang! Bu kodni aytishingiz bilan kartangizdagi mablag' bir necha soniyada yechib olinadi.
{% endhint %}

## 4. 🛠 Real Ish Vaziyati va Muammolarni Hal Qilish (Case-Study)

### Muammo:
Kompaniya buxgalteriga Telegram orqali "Kompaniya Rahbari" nomidan va uning rasmi qo'yilgan soxta profildan shoshilinch xabar keldi: *"Hozir bankka zudlik bilan 20 000 000 so'm soliq to'lovini o'tkazishimiz kerak, ushbu hisob raqamiga zudlik bilan pulni o'tkazing va menga chekini tashlang, men muhim majlisdaman, qo'ng'iroq qilmang!"*

### Muammoning Kelib Chiqish Sababi:
Kiberjinoyatchilar rahbarning fotosurati va ism-sharifidan foydalanib klon profil yaratgan (CEO Fraud / Ijtimoiy muhandislik usuli).

### Bosqichma-bosqich Yechim:
1. Hech qachon shoshilinch yozilgan matnli xabarga ko'r-ko'rona ishonib moliyaviy operatsiyalarni bajarmang!
2. Rahbarga Telegram orqali emas, uning o'zining shaxsiy doimiy telefon raqamiga to'g'ridan-to'g'ri qo'ng'iroq qiling (yoki yoniga kiring).
3. Profil nomini tekshiring — haqiqiy rahbar akkauntida yozishmalar tarixi va avvalgi xabarlar bo'ladi, soxta akkauntda esa tarix bo'sh bo'ladi.
4. Soxta akkauntni zudlik bilan "Spam" va "Block" qiling hamda kompaniyaning barcha xodimlarini xabardor qiling.

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz)

{% hint style="info" %}
**📝 Rasmiy Onlayn Test Sinovi (Google Forms — 15 ta saralangan savol, 100 ballik baholash):**
Ushbu dars bo'yicha olgan bilimlaringizni sinash uchun quyidagi rasmiy testni topshiring (15 ta saralangan test savoli, jami: 100 ball):
* 🔗 **Onlayn Testni Ochish (To'liq Ekranda):** <a href="https://docs.google.com/forms/d/e/1FAIpQLSeTWktw67fObwxR6TD_hr-c2lHFOrG5_Dxk6KKSOtGxf3sjHg/viewform" target="_blank" rel="noopener noreferrer">23-Mavzu: Axborot Xavfsizligi va Raqamli Madaniyat — Testni Topshirish</a>
* 📊 **Kunlik Natijalar va Ballar Jadvali:** <a href="https://docs.google.com/spreadsheets/d/1mzx2gUxXSZbrDd2wyjLMmhUdWUhSqNmikJhEhcCJXGg/edit" target="_blank" rel="noopener noreferrer">Google Sheets — Natijalar Jadvali</a>
{% endhint %}

{% embed url="https://docs.google.com/forms/d/e/1FAIpQLSeTWktw67fObwxR6TD_hr-c2lHFOrG5_Dxk6KKSOtGxf3sjHg/viewform" %}

## 6. 🏠 Mustaqil Amaliy Uyga Vazifa

### Topshiriq:
1. O'zingizning asosiy elektron pochtangiz (Google) va Telegram messenjeringizda 2FA (Ikki bosqichli tekshiruv) yoqilganligini tekshiring.
2. Agar yoqilmagan bo'lsa, zudlik bilan yoqing va uning faolligini ko'rsatuvchi skrinshotni oling.
3. Kiberxavfsizlik qoidalariga javob beradigan 16 belgili kuchli parol generatsiya qilish formulasini yozing.

**Topshirish formati:** Bajarilgan ish natijalarini `FIO_23-Mavzu_Kiberxavfsizlik.docx` shaklida platformaga yuklang.

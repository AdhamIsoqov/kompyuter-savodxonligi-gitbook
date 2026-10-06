# 23-Mavzu: Axborot Xavfsizligi, Kibergigiyena va Raqamli Madaniyat

{% hint style="info" %}
**Dars maqsadi:** Axborot xavfsizligi asoslari, kuchli parollar siyosati, Ikki bosqichli autentifikatsiya (2FA), ijtimoiy muhandislik va fishing (Phishing) hujumlarini aniqlash, bank kartalari va shaxsiy ma'lumotlar xavfsizligi, ommaviy Wi-Fi tarmoqlaridan xavfsiz foydalanish hamda raqamli etika qoidalarini chuqur egallash.
{% endhint %}

### 🎯 Kutilayotgan Kompetensiyalar
* **Bilishingiz kerak:**
  * Kiberjinoyatchilar tomonidan qo'llaniladigan fishing va ijtimoiy muhandislik usullari.
  * Ikki bosqichli himoya (2FA / Two-Factor Authentication) ning ishlash mexanizmi.
  * Ommaviy ochiq Wi-Fi tarmoqlarida shaxsiy parollarni kiritish xatarlari.
* **Bajara olishingiz kerak:**
  * Akkauntlar (Google, Telegram, Davlat xizmatlari) uchun 2FA himoyasini mustaqil yoqish.
  * Soxta (fishing) havolalarni va firibgarlik xabarlarini bir qarashda aniqlash.
  * Maxsus parol boshqaruvchilari (Password Manager) va xavfsiz parollar generatoridan foydalanish.

## 🎬 1. Video Dars

{% hint style="info" %}
**Video darslik:** Kiberxavfsizlik, fishingdan himoyalanish va 2FA o'rnatish bo'yicha quyidagi videoni tomosha qiling:
{% endhint %}

[Iframe/Embed: 23-Mavzu Bo'yicha YouTube Video Dars Havolasi]

## 2. 📖 Chuqurlashtirilgan Nazariy Ma'ruza

### 2.1. Kuchli Parol va 2FA (Ikki Bosqichli Himoya)

Bugungi kunda oddiy parollar (hatto murakkab bo'lsa ham) xakerlar tomonidan sizdirilgan ma'lumotlar bazalaridan topilishi mumkin. Shuning uchun har bir foydalanuvchi **ikki qatlamli himoya** o'rnatishi shart:

```
[2FA - Ikki Bosqichli Himoya Zanjiri]
  1-Bosqich: Foydalanuvchi paroli (Siz biladigan ma'lumot)
        │
        ▼
  2-Bosqich: Telefoningizga kelgan 6 xonali SMS yoki Authenticator kodi (Sizda bor qurilma)
        │
        ▼
  XAVFSIZ KIRISH (Xaker parolingizni bilsa ham, telefoningizsiz kira olmaydi!)
```

| Parametr | Zaif / Xavfli Parol | Kuchli / Xavfsiz Parol |
| :--- | :--- | :--- |
| **Tarkibi** | `123456`, `password`, `admin` | Katta harf, kichik harf, raqam, maxsus belgi |
| **Shaxsiy ma'lumot**| `aziz1998`, `nodira_2004` (Tug'ilgan sana, ism) | Shaxsga umuman aloqasiz so'zlar birikmasi |
| **Uzunligi** | 6–8 ta belgi (bir necha soniyada buziladi) | **Kamida 12–16 ta belgi** |
| **Misol** | `Alisher1995` | `K@sb#Tech_2026!Pro` |

{% hint style="success" %}
**Pro-Tip (Telegramda 2FA ni darhol yoqing!):**
O'zbekistonda eng ko'p sodir bo'ladigan kiberjinoyat — Telegram akkauntlarini o'g'irlashdir. Buning oldini olish uchun zudlik bilan Telegram sozlamalariga kiring:
**Settings -> Privacy and Security -> Two-Step Verification (Ikki bosqichli tekshiruv)** bo'limini yoqing va shaxsiy maxfiy parol o'rnating! Endi hech kim sizning nomingizdan yangi qurilmada Telegramga kira olmaydi.
{% endhint %}

### 2.2. Fishing (Phishing) va Ijtimoiy Muhandislik

**Fishing** — bu firibgarlarning mashhur tashkilotlar (Markaziy Bank, Payme, Click, Telegram ma'muriyati) nomidan soxta xabarlar yuborib, sizning parollaringiz va bank karta ma'lumotlaringizni o'g'irlashga qaratilgan tuzog'idir.

**Firibgarlikning 4 ta asosiy belgisi:**
1. **Shoshilinch talab va qo'rquv uyg'otish:** *"Akkauntingiz 1 soatda bloklanadi!"* yoki *"Kartangizdan pul yechib olindi, zudlik bilan kodni ayting!"*
2. **Katta bepul boylik va'da qilish:** *"Davlatdan 1 500 000 so'm moddiy yordam chiqdi, olish uchun havolani bosing!"*
3. **Soxta domen manzili:** Haqiqiy sayt `click.uz` bo'lsa, firibgarlar `click-uz-bonus.com` yoki `payme-tolov.xyz` kabi soxta domen ochishadi.
4. **Tasdiqlash kodini so'rash:** Bank xodimlari hech qachon telefon qilib SMS orqali kelgan 6 yoki 8 xonali maxfiy kodni so'ramaydi!

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
SMS orqali telefoningizga kelgan 6 xonali tasdiqlash kodini (One-Time Password — OTP) HECH KIMGA, hatto o'zini militsiya, xavfsizlik xizmati yoki bank boshqaruvchisi deb tanishtirgan shaxslarga ham ASLO aytmang! Bu kodni aytishingiz bilan kartangizdagi barcha pullar 5 soniyada yechib olinadi.
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

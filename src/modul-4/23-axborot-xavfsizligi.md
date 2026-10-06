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

---

## 🎬 1. Video Dars

{% hint style="info" %}
**Video darslik:** Kiberxavfsizlik, fishingdan himoyalanish va 2FA o'rnatish bo'yicha quyidagi videoni tomosha qiling:
{% endhint %}

[Iframe/Embed: 23-Mavzu Bo'yicha YouTube Video Dars Havolasi]

---

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

---

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
* 🌐 **Onlayn ko'rish va tahrirlash:** [23-Mavzu: Axborot Xavfsizligi va Raqamli Madaniyat — Shablonni ochish](https://docs.google.com/document/d/110_t3xTQg_OKiXYBEet9JPAb_Y_svrKCNS6pYyNNJy4/edit?usp=sharing)
* 📥 **Shaxsiy Drive-ga nusxalash (Tavsiya etiladi):** [Nusxa yaratish (Make a copy)](https://docs.google.com/document/d/110_t3xTQg_OKiXYBEet9JPAb_Y_svrKCNS6pYyNNJy4/copy)
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

---

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

---

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz — 25 ta Savol, 100 Ball)

{% hint style="info" %}
**📝 Rasmiy Onlayn Test Sinovi (Google Forms — 25 ta savol, 100 ballik baholash):**
Ushbu dars bo'yicha olgan bilimlaringizni sinash uchun quyidagi rasmiy testni topshiring (Har bir to'g'ri javob 4 ball, jami: 100 ball):
* 🔗 **Onlayn Testni Ochish (To'liq Ekranda):** [23-Mavzu: Axborot Xavfsizligi va Raqamli Madaniyat — Testni Topshirish](https://docs.google.com/forms/d/e/1FAIpQLSeTWktw67fObwxR6TD_hr-c2lHFOrG5_Dxk6KKSOtGxf3sjHg/viewform)
* 📊 **Kunlik Natijalar va Ballar Jadvali:** [Google Sheets — Natijalar Jadvali](https://docs.google.com/spreadsheets/d/1mzx2gUxXSZbrDd2wyjLMmhUdWUhSqNmikJhEhcCJXGg/edit)
{% endhint %}

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSeTWktw67fObwxR6TD_hr-c2lHFOrG5_Dxk6KKSOtGxf3sjHg/viewform?embedded=true" width="100%" height="800" frameborder="0" marginheight="0" marginwidth="0">Yuklanmoqda…</iframe>

---

### ✍️ 25 ta Rasmiy Test Savollari (Nazorat va O'z-o'zini Tekshirish):

Quyida ushbu dars bo'yicha tuzilgan barcha 25 ta rasmiy test savollari keltirilgan. Har bir savol 4 ta variantdan iborat bo'lib, to'g'ri javob belgilangan:

#### 1-Savol: Kuchli va ishonchli parol qanday xususiyatlarga ega bo'lishi kerak?
- [x] **A) Kamida 12 ta belgi, katta-kichik harflar, sonlar va maxsus belgilar (@#$%) aralashmasi** *(To'g'ri javob)*
- [ ] B) Faqat tug'ilgan yil
- [ ] C) 12345678
- [ ] D) Foydalanuvchi ismi

#### 2-Savol: Ikki bosqichli autentifikatsiya (2FA / MFA) ning asosiy mohiyati nima?
- [x] **A) Paroldan tashqari ikkinchi ishonchli kanal (SMS, ilova kodi, biometriya) orqali shaxsni tasdiqlash** *(To'g'ri javob)*
- [ ] B) Ikki marta parol kiritish
- [ ] C) Ikkita kompyuterda ochish
- [ ] D) Hisobni o'chirish

#### 3-Savol: Fishing (Phishing) hujumi nima?
- [x] **A) Soxta veb-saytlar va yolg'on xabarlar orqali foydalanuvchining login, parol va bank karta ma'lumotlarini o'g'irlash** *(To'g'ri javob)*
- [ ] B) Baliq ovi o'yini
- [ ] C) Kompyuterni qizdirish
- [ ] D) Fayllarni arxivlash

#### 4-Savol: Parollarni xavfsiz yaratish va saqlash uchun qanday dasturlar ishlatiladi?
- [x] **A) Parol menejerlari (Bitwarden, 1Password, KeePass)** *(To'g'ri javob)*
- [ ] B) Oddiy Bloknot (Notepad)
- [ ] C) Telegramdagi saqlangan xabarlar
- [ ] D) Stolga yopishtirilgan qog'oz

#### 5-Savol: Zaxira nusxa olishning (Backup) mashhur 3-2-1 qoidasi nimani anglatadi?
- [x] **A) 3 ta nusxa, 2 xil turdagi saqlash vositasida (disk, fleshka), 1 tasi boshqa joyda (bulutda)** *(To'g'ri javob)*
- [ ] B) 3 ta fayl, 2 ta parol, 1 ta kompyuter
- [ ] C) 3 kunda 2 marta
- [ ] D) Farqi yo'q

#### 6-Savol: Ochiq, parolsiz umumiy Wi-Fi tarmoqlaridan (kafe, vokzal) foydalanishda qanday xavf bor?
- [x] **A) Xakerlar oraliq tarmoqni tutib olib (Man-in-the-Middle), kiritilayotgan parollarni o'g'irlashi mumkin** *(To'g'ri javob)*
- [ ] B) Wi-Fi tezlashib ketadi
- [ ] C) Telefon quvvati to'ladi
- [ ] D) Xavfi yo'q

#### 7-Savol: Zararli to'lov talab qiluvchi viruslar (Ransomware / Вымогатели) nima qiladi?
- [x] **A) Foydalanuvchining barcha fayllarini kuchli algoritm bilan shifrlab qo'yib, ochish uchun pul talab qiladi** *(To'g'ri javob)*
- [ ] B) Kompyuterni tozalaydi
- [ ] C) Windowsni yangilaydi
- [ ] D) Ekranni yorqin qiladi

#### 8-Savol: Shaxsiy ma'lumotlarni himoyalashda 'Raqamli iz' (Digital Footprint) nima?
- [x] **A) Foydalanuvchining internetda qoldirgan barcha faoliyat tarixi, sharhlari, fotosuratlari va qidiruvlari** *(To'g'ri javob)*
- [ ] B) Klaviatura kirligi
- [ ] C) Sichqoncha izi
- [ ] D) Monitor barmog'i

#### 9-Savol: Bir xil parolni barcha ijtimoiy tarmoqlar va pochtalarda ishlatish nima uchun xavfli?
- [x] **A) Bitta saytdagi ma'lumotlar sizib chiqsa, tajovuzkor barcha boshqa hisoblaringizga ham kira oladi** *(To'g'ri javob)*
- [ ] B) Xavfi yo'q
- [ ] C) Parolni eslab qolish oson
- [ ] D) Tezroq kiriladi

#### 10-Savol: SMS orqali kelgan tasdiqlash kodlarini (OTP) boshqa shaxslarga berish mumkinmi?
- [x] **A) Qat'iyan man etiladi! Hatto o'zini bank xodimi yoki xavfsizlik xizmati deb tanishtirganlarga ham** *(To'g'ri javob)*
- [ ] B) Faqat tanishlarga mumkin
- [ ] C) Bank so'rasa berish shart
- [ ] D) Farqi yo'q

#### 11-Savol: Spam va shubhali elektron xatlardagi havolani (link) bosishdan oldin nima qilish kerak?
- [x] **A) Sichqoncha kursorini havola ustiga olib borib, pastda chiquvchi haqiqiy manzilni tekshirish** *(To'g'ri javob)*
- [ ] B) Darhol bosish
- [ ] C) Boshqalarga yuborish
- [ ] D) Xatni chop etish

#### 12-Savol: Ijtimoiy muhandislik (Social Engineering) nima?
- [x] **A) Insonning ishonuvchanligi, qo'rquvi yoki qiziqishidan foydalanib aldov yo'li bilan ma'lumotlarni qo'lga kiritish** *(To'g'ri javob)*
- [ ] B) Dasturlash tili
- [ ] C) Robot yasash
- [ ] D) Kompyuter tarmoqlari

#### 13-Savol: Brauzerda sayt manzilida yopiq qulf (Lock icon) belgisi nimani anglatadi?
- [x] **A) Sayt va sizning qurilmangiz o'rtasidagi aloqa SSL/TLS sertifikati orqali shifrlanganligini** *(To'g'ri javob)*
- [ ] B) Saytga kirish taqiqlanganligini
- [ ] C) Sayt buzilganligini
- [ ] D) Sayt pullik ekanligini

#### 14-Savol: Fleshkadan kompyuterga virus tushishining eng ko'p tarqalgan yo'li qaysi?
- [x] **A) Autorun (avtomatik ishga tushish) va noma'lum .exe, .vbs fayllarini ochish** *(To'g'ri javob)*
- [ ] B) Faqat fleshkani ushlash
- [ ] C) Musiqa eshitish
- [ ] D) Rasm ko'rish

#### 15-Savol: Antivirus dasturlarining asosiy vazifasi nima?
- [x] **A) Zararli dasturlarni real vaqtda aniqlash, bloklash va zararlangan fayllarni davolash** *(To'g'ri javob)*
- [ ] B) Kompyuterni tezlashtirish
- [ ] C) O'yin o'rnatish
- [ ] D) Hujjat chop etish

#### 16-Savol: Shaxsiy kompyuterni begona joyda qoldirib ketayotganda darhol nima qilish lozim?
- [x] **A) Win + L tugmasi orqali ekranni qulflab ketish** *(To'g'ri javob)*
- [ ] B) Monitorni burib qo'yish
- [ ] C) Sichqonchani yashirish
- [ ] D) Hech narsa

#### 17-Savol: Windows da 'BitLocker' funksiyasi nima vazifani bajaradi?
- [x] **A) Butun qattiq diskni to'liq shifrlab, noutbuk o'g'irlanganda ham ma'lumotlarni ochib bo'lmaydigan qiladi** *(To'g'ri javob)*
- [ ] B) Fayllarni o'chiradi
- [ ] C) Windowsni yangilaydi
- [ ] D) Internetni uzadi

#### 18-Savol: Kiberbulling (Cyberbullying) nima?
- [x] **A) Internet va ijtimoiy tarmoqlarda shaxsni ruhiy kamsitish, haqoratlash yoki unga bosim o'tkazish** *(To'g'ri javob)*
- [ ] B) Kiber sport turi
- [ ] C) Dastur tuzish
- [ ] D) Antivirus tekshiruvi

#### 19-Savol: Noma'lum Telegram botlariga yoki guruhlarga telefon raqamni 'Ulashish' (Share Contact) xavflimi?
- [x] **A) Xavfli! Sizning raqamingiz firibgarlar bazasiga tushib, fishing hujumlari nishoniga aylanasiz** *(To'g'ri javob)*
- [ ] B) Mutlaqo xavfsiz
- [ ] C) Foydali
- [ ] D) Telegram so'rasa berish kerak

#### 20-Savol: Zararli dasturlardan 'Troyan' (Trojan) nimasi bilan ajralib turadi?
- [x] **A) O'zini foydali dastur yoki o'yin qilib ko'rsatib, orqa fonda xakerga kompyuterni boshqarish imkonini beradi** *(To'g'ri javob)*
- [ ] B) Faqat vaqtni o'zgartiradi
- [ ] C) O'z-o'zidan ko'payadi
- [ ] D) Ekranni tozalaydi

#### 21-Savol: Brauzerda 'Parolni eslab qolish' (Save password) taklifi chiqqanda, umumiy (begona) kompyuterda nima bosiladi?
- [x] **A) Never (Hech qachon / Hech qachon saqlanmasin)** *(To'g'ri javob)*
- [ ] B) Save
- [ ] C) Yes
- [ ] D) Always

#### 22-Savol: Kompyuter dasturiy ta'minoti va tizimini muntazam yangilab turish (Update) nima uchun zarur?
- [x] **A) Aniqlangan xavfsizlik zaifliklarini (vulnerabilities) yopish va himoyani kuchaytirish uchun** *(To'g'ri javob)*
- [ ] B) Xotirani to'ldirish uchun
- [ ] C) Kompyuterni sekinlashtirish uchun
- [ ] D) Pulingizni olish uchun

#### 23-Savol: DDoS (Distributed Denial of Service) hujumining maqsadi nima?
- [x] **A) Sayt serveriga millionlab soxta so'rovlar yuborib, uni ishdan chiqarish va qotirib qo'yish** *(To'g'ri javob)*
- [ ] B) Parollarni o'g'irlash
- [ ] C) Faylni yuklab olish
- [ ] D) Rasm chizish

#### 24-Savol: VPN xizmatini tanlashda qaysi turdagisi xavfsizroq hisoblanadi?
- [x] **A) Ishonchli, foydalanuvchi ma'lumotlarini qayd etmaydigan (No-log policy) litsenziyali xizmatlar** *(To'g'ri javob)*
- [ ] B) Shubhali bepul VPN lar
- [ ] C) Har qanday VPN bir xil
- [ ] D) VPN xavfsiz emas

#### 25-Savol: Raqamli gigiyena qoidalariga rioya qilishning asosiy natijasi nima?
- [x] **A) Shaxsiy va moliyaviy ma'lumotlarning butunligi, internetda tinch va xavfsiz faoliyat yuritish** *(To'g'ri javob)*
- [ ] B) Juda ko'p vaqt yo'qotish
- [ ] C) Kompyuter buzilishi
- [ ] D) Do'stlar yo'qolishi

---


## 6. 🏠 Mustaqil Amaliy Uyga Vazifa

### Topshiriq:
1. O'zingizning asosiy elektron pochtangiz (Google) va Telegram messenjeringizda 2FA (Ikki bosqichli tekshiruv) yoqilganligini tekshiring.
2. Agar yoqilmagan bo'lsa, zudlik bilan yoqing va uning faolligini ko'rsatuvchi skrinshotni oling.
3. Kiberxavfsizlik qoidalariga javob beradigan 16 belgili kuchli parol generatsiya qilish formulasini yozing.

**Topshirish formati:** Bajarilgan ish natijalarini `FIO_23-Mavzu_Kiberxavfsizlik.docx` shaklida platformaga yuklang.

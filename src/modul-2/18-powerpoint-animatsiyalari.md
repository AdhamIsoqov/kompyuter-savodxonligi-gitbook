# 18-Mavzu: PowerPoint Animatsiyalari, Vizual Effektlar va Namoyish

{% hint style="info" %}
**Dars maqsadi:** PowerPoint dasturida slaydlar orasidagi o'tishlar (Transitions, shu jumladan zamonaviy Morph effekti), obyektlar animatsiyasi (Entrance, Emphasis, Exit, Motion Paths), animatsiyalar paneli (Animation Pane), vaqt boshqaruvi (Timing: On Click, With Previous, After Previous) hamda taqdimotni video (`.mp4`) formatida eksport qilish ko'nikmalarini egallash.
{% endhint %}

### 🎯 Kutilayotgan Kompetensiyalar
* **Bilishingiz kerak:**
  * Slaydlar o'tishi (Transitions) va obyekt animatsiyasi (Animations) o'rtasidagi fundamental farq.
  * Animatsiyaning 4 asosiy toifasi (Entrance — Yashil, Emphasis — Sariq, Exit — Qizil, Motion Paths — Harakat chizig'i).
  * Animatsiya boshlanish rejimlari: On Click, With Previous va After Previous.
* **Bajara olishingiz kerak:**
  * Matn bandlarini birma-bir, chiroyli paydo bo'ladigan qilib sozlash.
  * Animation Pane vositasida animatsiyalar ketma-ketligi va davomiyligini (Duration/Delay) boshqarish.
  * Avtomatik rejimda o'zi aylanuvchi taqdimot tayyorlab, uni `.mp4` video fayl sifatida saqlash.

---

## 🎬 1. Video Dars

{% hint style="info" %}
**Video darslik:** PowerPoint animatsiyalari va vaqt parametrlarini sozlash bo'yicha quyidagi videoni tomosha qiling:
{% endhint %}

[Iframe/Embed: 18-Mavzu Bo'yicha YouTube Video Dars Havolasi]

---

## 2. 📖 Chuqurlashtirilgan Nazariy Ma'ruza

### 2.1. Transitions (O'tishlar) vs Animations (Animatsiyalar)

* **Transitions (O'tishlar):** Bitta slayddan keyingi slaydga o'tish paytidagi umumiy vizual effekt (butun slayd varag'iga qo'llanadi). Masalan: *Fade (Asta erish), Push (Surilish), Morph (Shakllar transformatsiyasi)*.
* **Animations (Animatsiyalar):** Bitta slayd ichidagi alohida obyektlarning (sarlavha, rasm, jadval, shakl) harakatlanishi.

### 2.2. Animatsiyaning 4 Asosiy Toifasi

PowerPoint dasturida barcha animatsiyalar rangli toifalarga ajratilgan:

| Toifa | Belgilanish Rangi | Vazifasi | Mashhur Effektlar |
| :--- | :--- | :--- | :--- |
| **Entrance (Kirish)** | Yashil yulduzcha | Obyektni slayd maydonida paydo qilish | *Appear, Fade, Fly In, Zoom* |
| **Emphasis (Urg'u)** | Sariq yulduzcha | Slaydda turgan obyektga e'tibor qaratish | *Pulse, Spin, Grow/Shrink, Color Wave* |
| **Exit (Chiqish)** | Qizil yulduzcha | Obyektni slayddan yo'qotish | *Disappear, Fade, Fly Out* |
| **Motion Paths (Traektoriya)** | Chiziq belgisi | Obyektni chizilgan yo'nalish bo'ylab yurgizish | *Lines, Arcs, Turns, Custom Path* |

```
[Animatsiya Boshlanish Mantiqi (Start Modes)]
  1. On Click (Sichqoncha bosilganda) ===> Ma'ruzachi tugmani bosgandagina harakat boshlanadi
  2. With Previous (Oldingi bilan birga) => Oldingi obyekt bilan BIR VAQTDA harakatlanadi
  3. After Previous (Oldingidan so'ng) ===> Oldingi harakat tugashi bilan AVTOMATIK boshlanadi
```

{% hint style="success" %}
**Pro-Tip (Professional taqdimotda animatsiya me'yori):**
Animatsiyadan maqsad — auditoriyani chalg'itish emas, balki ma'lumotni bosqichma-bosqich tushuntirishdir. Har bir so'zga turli xil sakraydigan yoki aylanadigan animatsiyalarni bermang. Professional taqdimotlar uchun eng xushbichim va qulay effekt — bu **Fade (Asta paydo bo'lish)** effekti hisoblanadi.
{% endhint %}

---

## 3. 💻 Bosqichma-bosqich Amaliy Mashg'ulot (Lab Task)

Ushbu amaliy mashg'ulotda siz o'z-o'zidan ketma-ket animatsiya bilan ochiladigan interaktiv 3 ta slayd yaratasiz.

### Kerakli Resurslar:
* Microsoft PowerPoint dasturi;
* Amaliy mashg'ulot shabloni.

### 📄 Amaliy Mashg'ulot Shabloni:
[Iframe/Embed: 18-Mavzu Google Docs / MS Office Amaliy Mashq Shabloni Havolasi]

> *Eslatma: Shablondan nusxa oling va quyidagi 6 ta qadam orqali animatsiyalarni o'rnating.*

### Bajarish Bosqichlari:

1. **1-Qadam:** PowerPoint dasturida yangi fayl oching va barcha slaydlarga **Transitions -> Fade** (Duration: 0.70 soniya) o'tishini bering.
2. **2-Qadam:** 1-slaydda sarlavha ("Kompyuter Montaji Bosqichlari") yozing. Sarlavhani tanlab, **Animations -> Fly In (Pastdan uchib kelish)** effektini bering.
3. **3-Qadam (Animation Pane):** Yuqoridagi **Animation Pane (Область анимации)** tugmasini bosing (o'ng tomonda animatsiyalar boshqaruv paneli ochiladi).
4. **4-Qadam (Ketma-ket punktlar):** 3 ta punktli ro'yxat kiriting (1. Qismlarni tanlash; 2. Tizim blokini yig'ish; 3. Dasturlarni o'rnatish). Ushbu ro'yxatga **Fade** animatsiyasini bering.
5. **5-Qadam (Vaqtni sozlash):** Animation Pane'da punktlar animatsiyasini o'ng tugma orqali **Start: After Previous** rejimiga o'tkazing va Duration (davomiyligini) 0.5 soniya qiling (endi punktlar sichqonchasiz o'zi ketma-ket paydo bo'ladi).
6. **6-Qadam (Videoga eksport):** `F5` bosib natijani to'liq ekranda tomosha qiling, so'ng **File -> Export -> Create a Video (Full HD 1080p)** orqali taqdimotni `Animatsion_Taqdimot.mp4` video formatiga saqlang.

{% hint style="warning" %}
**Ehtiyot bo'ling:**
Animatsiyalar uchun baland va keskin ovozli effektlarni (chapak chalish, portlash, hushtak) qo'shmang! Bu jiddiy ilmiy yoki biznes taqdimotlar nufuzini tushiradi.
{% endhint %}

---

## 4. 🛠 Real Ish Vaziyati va Muammolarni Hal Qilish (Case-Study)

### Muammo:
Maktab o'qituvchisi ochiq dars uchun slaydlar tayyorladi. Har bir slaydga 10 tadan turli xil aylanuvchi, uchuvchi, miltillovchi animatsiyalarni qo'ydi va ularning hammasini "On Click" rejimida qoldirdi. Ochiq dars boshlanganda o'qituvchi hayajonlanib, sichqonchani adashib ko'p marta bosib yubordi, natijada animatsiyalar chalkashib, dars rejasi buzildi.

### Muammoning Kelib Chiqish Sababi:
1) Barcha animatsiyalarga me'yorsiz turli-tuman effektlar berilgan;
2) Vaqt rejimi avtomatlashtirilmagan, barchasi faqat sichqoncha bosilishiga bog'lab qo'yilgan.

### Bosqichma-bosqich Yechim:
1. Animation Pane darchasini oching va barcha ortiqcha murakkab animatsiyalarni belgilab `Delete` bilan tozalang.
2. Butun taqdimot bo'ylab faqat bitta standart — **Fade** yoki **Wipe** effektini qo'llang.
3. Asosiy bloklarga **After Previous** (Oldingidan so'ng) yoki **With Previous** buyrug'ini bering, Delay (Kechikish) vaqtini 1–2 soniya qilib belgilang.
4. Natijada taqdimot o'qituvchining aralashuvisiz o'z vaqtida, ravon va professional tarzda namoyish etiladi.

---

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz)

{% hint style="info" %}
**Onlayn Test:** 18-Mavzu bo'yicha olgan bilimlaringizni sinab ko'rish uchun quyidagi Google Forms testini topshiring:
{% endhint %}

[Iframe/Embed: 18-Mavzu Google Forms Rasmiy Test Havolasi]

### ✍️ O'z-o'zini Tekshirish Uchun Test Savollari:

#### Test 1: Bitta slayddan ikkinchi slaydga o'tishdagi umumiy vizual harakat qaysi menyu orqali sozlanadi?
- ( ) A) Animations
- (x) B) Transitions (O'tishlar)
- ( ) C) Slide Show
- ( ) D) View
*Izoh: Transitions butun slaydlar orasidagi o'tish effektlarini boshqaradi.*

#### Test 2: Obyektni slayd maydonida paydo qilish uchun qaysi toifadagi (yashil rangli) animatsiya ishlatiladi?
- (x) A) Entrance (Kirish)
- ( ) B) Emphasis (Urg'u)
- ( ) C) Exit (Chiqish)
- ( ) D) Motion Paths
*Izoh: Entrance yashil belgisi obyektning slaydga kirib kelishi va ko'rinishini ta'minlaydi.*

#### Test 3: Animatsiyalar ketma-ketligini va ularning vaqt shkalasini ko'rsatib turuvchi maxsus o'ng panel nima deb ataladi?
- ( ) A) Status Bar
- (x) B) Animation Pane (Область анимации)
- ( ) C) Selection Pane
- ( ) D) Ribbon
*Izoh: Animation Pane barcha kiritilgan effektlar tartibini vizual boshqarish darchasidir.*

#### Test 4: Animatsiyaning "With Previous" (Oldingi bilan birga) rejimi qanday ishlaydi?
- ( ) A) Sichqoncha bosilganda boshlanadi
- (x) B) Oldingi animatsiya bilan bir vaqtda (parallel) ishga tushadi
- ( ) C) Kompyuter o'chganda ishlaydi
- ( ) D) Slayd oxirida chiqadi
*Izoh: With Previous bir nechta obyektlarning bir vaqtda harakatlanishini ta'minlaydi.*

#### Test 5: Slaydda mavjud bo'lgan obyektga e'tibor qaratish (masalan: kattalashib-kichrayish yoki miltillash) uchun qaysi toifa ishlatiladi?
- ( ) A) Entrance
- ( ) B) Exit
- (x) C) Emphasis (Urg'u berish - sariq)
- ( ) D) Dissolve
*Izoh: Emphasis obyektni yo'qotmasdan, uning ustida turli vizual diqqat harakatlarini bajaradi.*

### 🤔 O'ylantiruvchi Mantiqiy Savollar:
1. Zamonaviy PowerPoint versiyalaridagi "Morph" o'tish effekti qanday ishlaydi va nima uchun u taqdimotlarni kinoga o'xshatib beradi?
2. Nima sababdan taqdimotni namoyish qilish uchun uni `.pptx` emas, to'g'ridan-to'g'ri namoyish rejimida ochiluvchi `.ppsx` (PowerPoint Show) formatida saqlash qulayroq?
3. Taqdimot videosini (`.mp4`) tayyorlashda har bir slayd uchun standart qancha vaqt (sekund) ajratilishi tavsiya etiladi?

---

## 6. 🏠 Mustaqil Amaliy Uyga Vazifa

### Topshiriq:
1. Microsoft PowerPoint dasturida 3 slayddan iborat interaktiv taqdimot tuzing.
2. Har bir slaydga Transitions menyusidan "Morph" yoki "Push" o'tishini o'rnating.
3. Slayd ichidagi matn va rasmlarga Entrance (yashil) va Emphasis (sariq) animatsiyalarini bering.
4. Animation Pane orqali kamida bitta animatsiyani "After Previous" rejimiga moslang.

**Topshirish formati:** Faylni `FIO_18-Mavzu_Animatsiyalar.pptx` nomi bilan saqlab tizimga yuklang.

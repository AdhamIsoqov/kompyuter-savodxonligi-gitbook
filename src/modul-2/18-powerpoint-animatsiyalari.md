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

## 🎬 1. Video Dars

{% hint style="info" %}
**Video darslik:** PowerPoint animatsiyalari va vaqt parametrlarini sozlash bo'yicha quyidagi videoni tomosha qiling:
{% endhint %}

[Iframe/Embed: 18-Mavzu Bo'yicha YouTube Video Dars Havolasi]

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

## 3. 💻 Bosqichma-bosqich Amaliy Mashg'ulot (Lab Task)

Ushbu amaliy mashg'ulotda siz o'z-o'zidan ketma-ket animatsiya bilan ochiladigan interaktiv 3 ta slayd yaratasiz.

### Kerakli Resurslar:
* Microsoft PowerPoint dasturi;
* Amaliy mashg'ulot shabloni.

### 📄 Amaliy Mashg'ulot Shabloni:
{% hint style="success" %}
**📄 Rasmiy Amaliy Mashg'ulot va Uy Vazifasi Shabloni (Google Docs (Hujjat)):**
Ushbu darsning barcha bosqichlarini bajarish, natijalar/hisobotlarni kiritish va uy vazifasini topshirish uchun quyidagi rasmiy shablondan foydalaning:
* 🌐 **Onlayn ko'rish va tahrirlash:** <a href="https://docs.google.com/document/d/1feb5saRkxRdsinD7CCup11NlyCnL27LWjF6hcyV4PQw/edit?usp=sharing" target="_blank" rel="noopener noreferrer">18-Mavzu: PowerPoint Animatsiyalari va Taqdimotlar — Shablonni ochish</a>
* 📥 **Shaxsiy Drive-ga nusxalash (Tavsiya etiladi):** <a href="https://docs.google.com/document/d/1feb5saRkxRdsinD7CCup11NlyCnL27LWjF6hcyV4PQw/copy" target="_blank" rel="noopener noreferrer">Nusxa yaratish (Make a copy)</a>
{% endhint %}

{% embed url="https://docs.google.com/document/d/1feb5saRkxRdsinD7CCup11NlyCnL27LWjF6hcyV4PQw/preview" %}

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

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz)

{% hint style="info" %}
**📝 Rasmiy Onlayn Test Sinovi (Google Forms — 15 ta saralangan savol, 100 ballik baholash):**
Ushbu dars bo'yicha olgan bilimlaringizni sinash uchun quyidagi rasmiy testni topshiring (15 ta saralangan test savoli, jami: 100 ball):
* 🔗 **Onlayn Testni Ochish (To'liq Ekranda):** <a href="https://docs.google.com/forms/d/e/1FAIpQLSei_2WO3AAcn3uC4kEYBZJST5C2tvGkHZMgisUtnFgw3DFKyg/viewform" target="_blank" rel="noopener noreferrer">18-Mavzu: PowerPoint Animatsiyalari va Taqdimotlar — Testni Topshirish</a>
* 📊 **Kunlik Natijalar va Ballar Jadvali:** <a href="https://docs.google.com/spreadsheets/d/1NrCWXilMo8UG1aPyKdjJZOS09j7_FXdyzNxI8v_770w/edit" target="_blank" rel="noopener noreferrer">Google Sheets — Natijalar Jadvali</a>
{% endhint %}

{% embed url="https://docs.google.com/forms/d/e/1FAIpQLSei_2WO3AAcn3uC4kEYBZJST5C2tvGkHZMgisUtnFgw3DFKyg/viewform" %}

## 6. 🏠 Mustaqil Amaliy Uyga Vazifa

### Topshiriq:
1. Microsoft PowerPoint dasturida 3 slayddan iborat interaktiv taqdimot tuzing.
2. Har bir slaydga Transitions menyusidan "Morph" yoki "Push" o'tishini o'rnating.
3. Slayd ichidagi matn va rasmlarga Entrance (yashil) va Emphasis (sariq) animatsiyalarini bering.
4. Animation Pane orqali kamida bitta animatsiyani "After Previous" rejimiga moslang.

**Topshirish formati:** Faylni `FIO_18-Mavzu_Animatsiyalar.pptx` nomi bilan saqlab tizimga yuklang.

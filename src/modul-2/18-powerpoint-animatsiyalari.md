# 18-Mavzu: PowerPoint Animatsiyalari, Vizual Effektlar va Namoyish

Assalomu alaykum! Kasbtech Akademiyasining Kompyuter savodxonligi kursidagi 18-darsimizga xush kelibsiz.

Oldingi 17-darsimizda biz Microsoft PowerPoint dasturining asoslari, slayd maketlari, 6x6 qoidasi va professional taqdimot dizaynini o'rgangan edik. Endi esa oddiy, harakatsiz slaydlarni tomoshabin diqqatini tortuvchi va murakkab g'oyalarni bosqichma-bosqich tushuntiruvchi jonli vizual hikoyaga aylantirish vaqti keldi.

Ushbu darsda biz slaydlar orasidagi o'tishlar (**Transitions**) va alohida elementlarning harakati (**Animations**) bilan qanday ishlashni, ularning vaqtini (Timing) professional darajada boshqarishni to'liq o'rganamiz.

Keyingi 19-darsimizda esa butun 2-Modul bo'yicha katta integratsiyalashgan Amaliy loyiha kutmoqda — unda Word hujjati, Excel jadvallari va bugun o'rganadigan dinamik PowerPoint taqdimotimiz yagona tizim sifatida birlashtiriladi.

{% hint style="info" %}
**Dars maqsadi:** PowerPoint dasturida slaydlar orasidagi o'tishlar (Transitions, shu jumladan zamonaviy Morph effekti), obyektlar animatsiyasi (Entrance, Emphasis, Exit, Motion Paths), animatsiyalar paneli (Animation Pane), vaqt boshqaruvi (Timing: On Click, With Previous, After Previous) hamda taqdimotni avtomatik namoyish (`.ppsx`) va video (`.mp4`) formatida eksport qilish ko'nikmalarini egallash.
{% endhint %}

### 🎯 Kutilayotgan Kompetensiyalar
* **Bilishingiz kerak:**
  * Slaydlar o'tishi (Transitions) va obyekt animatsiyasi (Animations) o'rtasidagi fundamental farq.
  * Animatsiyaning 4 asosiy toifasi (Entrance — Yashil, Emphasis — Sariq, Exit — Qizil, Motion Paths — Harakat chizig'i).
  * Animatsiya boshlanish rejimlari: On Click, With Previous va After Previous.
  * Zamonaviy "Morph" effekti va taqdimot eksport formatlari (`.pptx`, `.ppsx`, `.mp4`).
* **Bajara olishingiz kerak:**
  * Matn bandlarini birma-bir, chiroyli paydo bo'ladigan qilib sozlash.
  * Animation Pane vositasida animatsiyalar ketma-ketligi, davomiyligi (Duration) va kechikishini (Delay) boshqarish.
  * Avtomatik rejimda o'zi aylanuvchi taqdimot tayyorlab, uni `.mp4` video fayl sifatida saqlash.

## 🎬 1. Video Dars

{% hint style="info" %}
**Video darslik:** PowerPoint animatsiyalari va vaqt parametrlarini sozlash bo'yicha quyidagi videoni tomosha qiling:
{% endhint %}

[Iframe/Embed: 18-Mavzu Bo'yicha YouTube Video Dars Havolasi]

### 📊 Dars Slaydlari va Taqdimoti (EduRecurses)

{% hint style="success" %}
**📊 Rasmiy Taqdimot Slaydlari (Microsoft PowerPoint / Google Drive):**
Ushbu darsning barcha mavzulari, grafik sxemalari va ko'rgazmali materiallarini onlayn ko'rish hamda yuklab olish uchun quyidagi rasmiy havoladan foydalaning:
* 🌐 **Onlayn ko'rish va yuklab olish:** <a href="https://drive.google.com/file/d/195Swr8tSokoi22b_UCGwqawMdTvSYgy-/view?usp=sharing" target="_blank" rel="noopener noreferrer">18-Mavzu: PowerPoint Animatsiyalari va Taqdimotlar — Taqdimot Slaydlarini Ochish</a>
{% endhint %}

{% embed url="https://drive.google.com/file/d/195Swr8tSokoi22b_UCGwqawMdTvSYgy-/preview" %}


## 2. 📖 Chuqurlashtirilgan Nazariy Ma'ruza

### 2.1. Transitions (O'tishlar) va Animations (Animatsiyalar) Farqi

Ko'pchilik yangi boshlovchilar slayd o'tishi va animatsiyani bir-biri bilan adashtirib qo'yishadi. Keling, ularning farqini aniq belgilab olamiz:

1. **Transitions (Slaydlararo o'tish):**
   * Bu bitta slayddan keyingi slaydga o'tish paytida butun ekran bo'ylab sodir bo'ladigan vizual o'zgarishdir.
   * Masalan: *Fade (Asta erib paydo bo'lish), Push (Keyingi slaydning surilib chiqishi), Morph (Shakllarning boshqa slaydga silliq o'zgarib o'tishi)*.
   * O'tish effekti alohida matn yoki rasmga emas, butun bir slayd varag'iga tatbiq etiladi.

2. **Animations (Obyektlar animatsiyasi):**
   * Bu bitta slayd ichidagi alohida elementlarning — sarlavhalar, paragraflar, fotosuratlar, grafiklar yoki shakllarning harakatlanishidir.
   * Masalan: birinchi navbatda sarlavha paydo bo'ladi, so'ngra 1-band ochiladi, so'ngra rasm kattalashadi.

```
+-----------------------------------------------------------+
|                    SLAYD O'TISHLARI (Transitions)         |
|  [Slayd 1] ==============( Fade / Morph )==============> [Slayd 2]
+-----------------------------------------------------------+
|               SLAYD ICHIDAGI ANIMATSIYALAR (Animations)   |
|  1. Sarlavha paydo bo'ladi (Entrance - Kirish)            |
|  2. Asosiy raqam miltillaydi (Emphasis - Urg'u)           |
|  3. Eskirgan ma'lumot slayddan ketadi (Exit - Chiqish)    |
+-----------------------------------------------------------+
```

### 2.2. Animatsiyaning 4 Asosiy Toifasi

PowerPoint dasturida har bir obyektga turli xil maqsadlarda harakat berish mumkin. Ular qulaylik uchun to'rtta rangli toifaga ajratilgan:

| Toifa | Rangi | Vazifasi va Mohiyati | Amaliy Misollar |
| :--- | :--- | :--- | :--- |
| **Entrance (Kirish)** | Yashil yulduzcha | Dastlab ko'rinmay turgan obyektni slayd maydonida paydo qilish. | *Appear, Fade, Fly In, Zoom* |
| **Emphasis (Urg'u)** | Sariq yulduzcha | Slaydda allaqachon turgan obyektga tinglovchilar diqqatini qaratish. | *Pulse, Spin, Grow/Shrink, Teeter* |
| **Exit (Chiqish)** | Qizil yulduzcha | Ma'lumot tushuntirib bo'lingach, obyektni slayddan chiqarib yuborish. | *Disappear, Fade, Fly Out, Split* |
| **Motion Paths (Traektoriya)** | Chiziq belgisi | Obyektni belgilangan chiziq, egri yoki aylana yo'nalish bo'ylab ko'chirish. | *Lines, Arcs, Turns, Custom Path* |

### 2.3. Animation Pane (Animatsiyalar Paneli) va Vaqt Boshqaruvi

Slaydda bir nechta obyekt bo'lsa, ularning ketma-ketligi va vaqtini tartibga solish uchun **Animations → Animation Pane (Область анимации)** oynasini ochish shart. Ushbu panelda barcha animatsiyalar ro'yxat bo'lib turadi.

Har bir animatsiya uchun uchta asosiy boshlanish rejimi (Start Modes) mavjud:
1. **On Click (Sichqoncha bosilganda):** Ma'ruzachi klaviatura yoki sichqonchani bosmaguncha obyekt harakatlanmaydi. Bu ma'ruza davomida har bir fikrni o'z vaqtida ochish uchun eng qulayi.
2. **With Previous (Oldingi bilan birga):** Obyekt oldingi harakat bilan aynan bir vaqtda ishga tushadi (masalan, sarlavha va uning orqa foni bir vaqtda paydo bo'ladi).
3. **After Previous (Oldingidan so'ng):** Oldingi animatsiya to'liq yakunlanishi bilan navbatdagi element avtomatik paydo bo'ladi. Bu avtomatlashtirilgan taqdimotlar uchun asosdir.

Shuningdek, muhim vaqt ko'rsatkichlari:
* **Duration (Davomiylik):** Animatsiyaning o'zi necha soniyada bajarilishi (optimal: 0.5 – 0.75 soniya).
* **Delay (Kechikish):** Harakat boshlanishidan oldin necha soniya pauza bo'lishi kerakligi.

### 2.4. Zamonaviy "Morph" O'tishi va Taqdimot Formatlari

* **Morph (Morfing) o'tishi:** Bu Microsoft PowerPoint 2019 va undan yuqori versiyalardagi eng inqilobiy xususiyatdir. Agar bir slayddagi obyektni ikkinchi slaydga nusxalab, ikkinchi slaydda uning o'rnini, hajmini yoki rangini o'zgartirsangiz va ikkinchi slaydga **Transitions → Morph** qo'ysangiz, dastur obyektni silliq transformatsiya qilib o'tkazadi. Bu murakkab videomontaj dasturlarisiz professional kinematik harakat yaratish imkonini beradi.
* **Taqdimotni Saqlash Formatlari:**
  * `.pptx` — Standart tahrirlanadigan loyiha fayli;
  * `.ppsx` (PowerPoint Show) — Ushbu fayl ochilganda tahrirlash oynasi emas, to'g'ridan-to'g'ri to'liq ekranli namoyish ochiladi (mijozga yoki hakamlarga yuborish uchun eng maqbul format);
  * `.mp4` — To'liq avtomatlashtirilgan video fayl. Barcha o'tish va animatsiyalar o'z vaqtida aylanib, musiqa bilan video rolik shaklida saqlanadi.

{% hint style="success" %}
**Pro-Tip (Professional taqdimotda animatsiya me'yori):**
Animatsiyadan maqsad — auditoriyani chalg'itish yoki o'yinchoq qilish emas, balki murakkab tushunchalarni bo'lib-bo'lib yetkazishdir. Har bir so'zga turli xil aylanadigan yoki sakraydigan animatsiyalarni qo'shmang. Professional biznes va ta'lim taqdimotlari uchun eng xushbichim effekt — bu **Fade (Asta paydo bo'lish)** effekti hisoblanadi.
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

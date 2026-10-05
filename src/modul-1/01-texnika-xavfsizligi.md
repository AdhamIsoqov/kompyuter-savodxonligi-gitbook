# 01-Mavzu: Texnika Xavfsizligi va Mehnatni Muhofaza Qilish Umumiy Qoidalari

{% hint style="info" %}
**Dars maqsadi:** Kompyuter xonasida, laboratoriyalarda va ish joyida elektr xavfsizligi, yong'in xavfsizligi hamda kompyuterda ishlash gigiyenasi qoidalarini chuqur o'rganish; statsionar va ko'chma kompyuter qurilmalari bilan ishlashda inson salomatligi va texnika butunligini ta'minlash ko'nikmalarini egallash.
{% endhint %}

### 🎯 Kutilayotgan Kompetensiyalar
* **Bilishingiz kerak:**
  * Kompyuter sinfi va ustaxonalarda elektr xavfsizligi asosiy standartlari (220V xavfi, yerga ulash — grounding ahamiyati).
  * Ergonomika qoidalari: monitor, klaviatura, stul va tananing to'g'ri holati (ko'rish va umurtqa pog'onasi salomatligi).
  * Statik elektr toki (ESD — Electrostatic Discharge) va uning mikrosxemalarga yetkazadigan zarari.
* **Bajara olishingiz kerak:**
  * Ish joyini ergonomik me'yorlar asosida to'g'ri tashkil qilish.
  * Favqulodda vaziyatlarda (tutun chiqishi, elektr toki urishi, qisqa tutashuv) to'g'ri va tezkor harakat qilish algoritmini qo'llash.
  * Tizim blokini ochishdan oldin statik zaryadni xavfsiz zararsizlantirish (antistatik bilaguzuk yoki korpus orqali yerga tushirish).

---

## 🎬 1. Video Dars

{% hint style="info" %}
**Video ko'rsatma:** Darsni boshlashdan oldin quyidagi video qo'llanmani diqqat bilan tomosha qiling:
{% endhint %}

[Iframe/Embed: 01-Mavzu Bo'yicha Video Dars (YouTube / Google Drive Havolasi)]

---

## 2. 📖 Chuqurlashtirilgan Nazariy Ma'ruza

### 2.1. Elektr Xavfsizligi va Statik Elektr (ESD)

Kompyuter elektr tarmog'idan oziqlanadi (220V o'zgaruvchan tok). Kompyuter quvvat ta'minoti bloki (PSU — Power Supply Unit) bu kuchlanishni past darajadagi xavfsiz o'zgarmas toklarga (3.3V, 5V, 12V) aylantirib beradi. Biroq, blokning kirish qismida va rozetkalarda inson hayoti uchun xavfli yuqori kuchlanish mavjud.

| Xavf Turi | Sababi | Oqibati | Himoyalanish Usuli |
| :--- | :--- | :--- | :--- |
| **Elektr toki urishi** | Izolyatsiyasi buzilgan kabellar, yerga ulanmagan korpus | Shikastlanish, hayot uchun xavf | Shnurlarni tekshirish, yerga ulangan (Euro) rozetkadan foydalanish |
| **Statik elektr (ESD)** | Sintetik kiyim, quruq havo, inson tanasida to'plangan zaryad | RAM va protsessor mikrosxemalarining yonishi | Antistatik bilaguzuk taqish, metall korpusga qo'l tekkizib zaryadni chiqarish |
| **Qizib ketish (Overheating)** | Chang to'planishi, shamollatish teshiklarining to'silishi | Qurilmaning o'z-o'zidan o'chishi, yong'in chiqishi xavfi | Ventilyatsiyani to'smaydigan ochiq joyga o'rnatish |

{% hint style="success" %}
**Pro-Tip (Statik elektrni zararsizlantirish):**
Kompyuter tizim blokining ichki qismlariga (ona plata, operativ xotira, videokarta) teginishdan oldin elektr vilkasini rozetkadan uzing, so'ng tizim blokining bo'yalmagan metall korpusiga 5 soniya davomida qo'lingizni tekkizib turing. Bu tanangizdagi ortiqcha statik elektrni yerga yo'naltiradi va mikrosxemalarni kuyishdan saqlaydi!
{% endhint %}

### 2.2. Kompyuterda Ishlash Ergonomikasi

Kompyuter qarshisida uzoq vaqt noto'g'ri o'tirish ko'zning toliqishi, umurtqa egriligi (skolioz) va bilak bo'g'imlari kasalligi (tunnel sindromi / carpal tunnel)ga olib keladi.

```
       [Monitor] 50-70 sm masofada, ko'z sathidan 10-15 sm pastda
           |
       (Ko'z) ---- Gorizontal ko'rish burchagi (0° - 20°)
           |
      [Tana/Orqa] 90° - 105° to'g'ri burchak ostida suyangan
           |
      [Tirsaklar] 90° burchak ostida stol yuzasida erkin
           |
       [Tizzalar] 90° burchak, oyoq kafti to'liq polga tekkan
```

---

## 3. 💻 Bosqichma-bosqich Amaliy Mashg'ulot (Lab Task)

Ushbu amaliy mashg'ulotda siz o'z ish o'rningizni to'liq tekshirib chiqasiz va xavfsizlik auditini o'tkazasiz.

### Kerakli Resurslar:
* Kompyuter ish stoli va stuli;
* O'lchov tasmasi (ruletka yoki santimetr);
* Amaliy mashq shabloni (Google Docs / MS Word).

### 📄 Amaliy Mashq Shabloni (Google Docs / MS Office):
[Iframe/Embed: 01-Mavzu Amaliy Mashg'ulot Shabloni - Google Docs / MS Word Online]

> *Eslatma: Yuqoridagi interaktiv shablonni oching, "Nusxa olish" (Make a copy) tugmasini bosing va o'z hisobotingizni to'ldiring.*

### Bajarish Bosqichlari:

1. **1-Qadam:** Ish joyingizdagi elektr simlarini ko'zdan kechiring. Simlar chalkashib ketmaganligiga, oyoq ostida yotmaganligiga va izolyatsiyasi shikastlanmaganligiga ishonch hosil qiling.
2. **2-Qadam:** Tizim blokining joylashuvini tekshiring. U devordan yoki to'siqdan kamida 10-15 sm masofada turishi, havo aylanuvchi panjaralari to'silmagan bo'lishi lozim.
3. **3-Qadam:** Monitor va ko'z orasidagi masofani o'lchang. O'lchov tasmasi bilan masofani tekshiring — u kamida **50–70 sm** (taxminan bir cho'zilgan qo'l masofasida) bo'lishi shart.
4. **4-Qadam:** Kreslo (stul) balandligini shunday sozlangki, oyoqlaringiz polga to'liq tekkan va tizzalaringiz 90 gradus burchak hosil qilgan bo'lsin.
5. **5-Qadam:** Windows tizimida ko'zni himoya qilish funksiyasini yoqing:
   * Klaviaturada `Win + I` tugmasini bosing (Sozlamalar oynasi ochiladi).
   * **System -> Display -> Night light (Ночной свет)** bo'limini yoqing. Bu rejim ko'k nurni kamaytiradi.
6. **6-Qadam:** Ishchi stolingizda `Mening_Hujjatlarim/Audit/` papkasini yarating va yuqoridagi shablon asosida `Xavfsizlik_Auditi.docx` faylini to'ldirib saqlang.

{% hint style="warning" %}
**Qat'iy taqiqlanadi:**
* Kompyuter apparati ishlab turganda uning orqa panelidagi quvvat kabelini yoki qismlarini sug'urish;
* Kompyuter yonida choy, qahva yoki suv kabi suyuqliklar idishini ochiq qoldirish;
* Elektr tarmog'iga ulangan holatda tizim bloki ichidagi changlarni nam latta bilan artish!
{% endhint %}

---

## 4. 🛠 Real Ish Vaziyati va Muammolarni Hal Qilish (Case-Study)

### Muammo:
Ofisda yangi xodim kompyuterining tizim blokini tozalash maqsadida ichini ochdi. Changlarni tozalab bo'lgach, operativ xotira (RAM) platasini yechib qayta o'rnatdi. Kompyuterni yoqqanda esa monitorga tasvir chiqmadi, tizim bloki esa uzluksiz qisqa "bip" signallarini bera boshladi.

### Muammoning Kelib Chiqish Sababi:
Xodim sintetik kiyimda ishlagan va tizim blokiga teginishdan oldin statik zaryadni yerga tushirmagan. RAM platasini qirralaridan emas, to'g'ridan-to'g'ri mikrosxemalaridan ushlagan. Natijada statik elektr (ESD) RAM mikrosxemasini shikastlagan yoki u o'z uyasiga to'liq o'tirmagan.

### Bosqichma-bosqich Yechim:
1. Kompyuterning quvvat simini rozetkadan uzing.
2. Quvvat tugmasini (Power button) 10 soniya bosib turing (kondensatorlardagi qoldiq tok butunlay so'nadi).
3. Korpusning metall qismiga qo'lingizni tekkizib zaryadsizlaning.
4. RAM platasini chiqarib oling, uning kontakt tishchalarini oddiy qalam o'chirg'ich (rezinka) bilan ehtiyotkorlik bilan tozalang.
5. RAM ni uyasiga (slot) qayta joylashtirib, ikki chetidagi fiksatorlari "chert" etib yopilguniga qadar ehtiyotkorlik bilan bosing.
6. Tizimni qayta yoqing. Agar signal davom etsa, platani almashtirish talab etiladi.

---

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz)

{% hint style="info" %}
**Onlayn Test:** Ushbu dars bo'yicha o'zlashtirish darajangizni baholash uchun quyidagi Google Forms testini topshiring:
{% endhint %}

[Iframe/Embed: 01-Mavzu Google Forms Rasmiy Test Havolasi]

### ✍️ O'z-o'zini Tekshirish Uchun Test Savollari:

#### Test 1: Monitor bilan foydalanuvchi ko'zi orasidagi tavsiya etilgan xavfsiz masofa qancha?
- ( ) A) 20–30 sm
- (x) B) 50–70 sm
- ( ) C) 100–120 sm
- ( ) D) Farqi yo'q
*Izoh: 50–70 sm masofa (taxminan bir cho'zilgan qo'l uzunligi) ko'z nuri charchashining oldini oluvchi xalqaro ergonomik standartdir.*

#### Test 2: Statik elektr toki (ESD) kompyuterning eng ko'p qaysi qismiga xavf soladi?
- ( ) A) Tizim blokining temir korpusiga
- ( ) B) Elektr quvvat shnuriga
- (x) C) Operativ xotira (RAM) va protsessor mikrosxemalariga
- ( ) D) Sovutgich ventilyatoriga
*Izoh: Nozik yarimo'tkazgich mikrosxemalar hatto inson sezmaydigan kichik statik razryaddan ham kuyib qolishi mumkin.*

#### Test 3: Kompyuter xonasida yong'in chiqqanda birinchi navbatda qanday harakat qilinadi?
- (x) A) Zudlik bilan xonaning umumiy elektr tarmog'ini o'chirish (rubilnikdan ajratish)
- ( ) B) Yong'inni darhol suv sepib o'chirish
- ( ) C) Monitor va kompyuterlarni tashqariga tashish
- ( ) D) Oynalarni ochib xonani shamollatish
*Izoh: Elektr qurilmalari yonayotganda suv sepish tok urishiga olib keladi. Birinchi navbatda tok zudlik bilan uzilishi shart.*

#### Test 4: Windows tizimida sozlamalar (Settings) darchasini tezkor chaqirish tugmalari qaysi?
- ( ) A) `Ctrl + Alt + Del`
- (x) B) `Win + I`
- ( ) C) `Alt + F4`
- ( ) D) `Win + D`
*Izoh: `Win + I` tugmalar kombinatsiyasi Windows tizim sozlamalarini darhol ochadi.*

#### Test 5: "Tunnel sindromi" (Carpal tunnel syndrome) kompyuterda qanday noto'g'ri ishlash oqibatida yuzaga keladi?
- ( ) A) Monitorni juda uzoqqa qo'yganda
- (x) B) Sichqoncha va klaviaturada ishlaganda bilak noto'g'ri burchak ostida zo'riqqanda
- ( ) C) Qorong'i xonada ishlaganda
- ( ) D) Quloqchinlardan baland ovozda foydalanganda
*Izoh: Bilak bo'g'imining stol qirrasiga uzoq vaqt noqulay siqilib turishi nerv tolalarining qisilishiga olib keladi.*

### 🤔 O'ylantiruvchi Mantiqiy Savollar:
1. Nima uchun kompyuter tizim blokini to'g'ridan-to'g'ri gilam yoki qalin paxmoq pol ustiga qo'yish tavsiya etilmaydi?
2. Agar ish joyingizdagi rozetkada yerga ulash (grounding / заземление) simi bo'lmasa, qanday texnik xatarlar yuzaga kelishi mumkin?
3. 20-20-20 qoidasi nima va u ko'rish qobiliyatini asrashda qanday ishlaydi?

---

## 6. 🏠 Mustaqil Amaliy Uyga Vazifa

### Topshiriq:
O'z shaxsiy ish joyingiz yoki ta'lim muassasangizdagi kompyuter stolining **Ergonomika va Texnika Xavfsizligi Nazorat Xaritasi**ni tuzing.

Quyidagi mezonlar bo'yicha baholang va hisobot tayyorlang:
1. Monitor masofasi va ko'rish balandligi to'g'riligi (Ha/Yo'q).
2. Stol va stul balandligining 90 gradusli tana burchaklariga mosligi.
3. Elektr kabellarining tartiblanganligi va xavfsizligi.
4. Tizim bloki ventilyatsiyasi uchun yetarli bo'shliq mavjudligi.

**Topshirish formati:** Tekshiruv natijalarini `.docx` yoki `.pdf` fayl shaklida tayyorlab, `FIO_1-Mavzu_Xavfsizlik.docx` nomi bilan platformaga yuklang.

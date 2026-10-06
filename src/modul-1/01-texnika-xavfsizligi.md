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

## 🎬 1. Video Dars

{% hint style="info" %}
**Video ko'rsatma:** Darsni boshlashdan oldin quyidagi video qo'llanmani diqqat bilan tomosha qiling:
{% endhint %}

[Iframe/Embed: 01-Mavzu Bo'yicha Video Dars (YouTube / Google Drive Havolasi)]

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

## 3. 💻 Bosqichma-bosqich Amaliy Mashg'ulot (Lab Task)

Ushbu amaliy mashg'ulotda siz o'z ish o'rningizni to'liq tekshirib chiqasiz va xavfsizlik auditini o'tkazasiz.

### Kerakli Resurslar:
* Kompyuter ish stoli va stuli;
* O'lchov tasmasi (ruletka yoki santimetr);
* Amaliy mashq shabloni (Google Docs / MS Word).

### 📄 Amaliy Mashq Shabloni (Google Docs / MS Office):
{% hint style="success" %}
**📄 Rasmiy Amaliy Mashg'ulot va Uy Vazifasi Shabloni (Google Docs (Hujjat)):**
Ushbu darsning barcha bosqichlarini bajarish, natijalar/hisobotlarni kiritish va uy vazifasini topshirish uchun quyidagi rasmiy shablondan foydalaning:
* 🌐 **Onlayn ko'rish va tahrirlash:** <a href="https://docs.google.com/document/d/1kBxWLdCsIbTy5zVL2Hgf7jfWsdu2S4sHI6G5GsepMw4/edit?usp=sharing" target="_blank" rel="noopener noreferrer">01-Mavzu: Texnika Xavfsizligi va Mehnatni Muhofaza Qilish — Shablonni ochish</a>
* 📥 **Shaxsiy Drive-ga nusxalash (Tavsiya etiladi):** <a href="https://docs.google.com/document/d/1kBxWLdCsIbTy5zVL2Hgf7jfWsdu2S4sHI6G5GsepMw4/copy" target="_blank" rel="noopener noreferrer">Nusxa yaratish (Make a copy)</a>
{% endhint %}

{% embed url="https://docs.google.com/document/d/1kBxWLdCsIbTy5zVL2Hgf7jfWsdu2S4sHI6G5GsepMw4/preview" %}

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

## 5. 📝 Bilimni Tekshirish (Google Forms Test & Quiz)

{% hint style="info" %}
**📝 Rasmiy Onlayn Test Sinovi (Google Forms — 15 ta saralangan savol, 100 ballik baholash):**
Ushbu dars bo'yicha olgan bilimlaringizni sinash uchun quyidagi rasmiy testni topshiring (15 ta saralangan test savoli, jami: 100 ball):
* 🔗 **Onlayn Testni Ochish (To'liq Ekranda):** <a href="https://docs.google.com/forms/d/e/1FAIpQLSfh0t2eCSXcOfWhxvDj_QHM0HjyAKrVZqku71ir4KhkjU0RgA/viewform" target="_blank" rel="noopener noreferrer">01-Mavzu: Texnika Xavfsizligi va Mehnatni Muhofaza Qilish — Testni Topshirish</a>
* 📊 **Kunlik Natijalar va Ballar Jadvali:** <a href="https://docs.google.com/spreadsheets/d/1MUJQ3uYHR5XgKR3h3GNlrbXhE9CSwajy4FeUO3foCHQ/edit" target="_blank" rel="noopener noreferrer">Google Sheets — Natijalar Jadvali</a>
{% endhint %}

{% embed url="https://docs.google.com/forms/d/e/1FAIpQLSfh0t2eCSXcOfWhxvDj_QHM0HjyAKrVZqku71ir4KhkjU0RgA/viewform" %}

## 6. 🏠 Mustaqil Amaliy Uyga Vazifa

### Topshiriq:
O'z shaxsiy ish joyingiz yoki ta'lim muassasangizdagi kompyuter stolining **Ergonomika va Texnika Xavfsizligi Nazorat Xaritasi**ni tuzing.

Quyidagi mezonlar bo'yicha baholang va hisobot tayyorlang:
1. Monitor masofasi va ko'rish balandligi to'g'riligi (Ha/Yo'q).
2. Stol va stul balandligining 90 gradusli tana burchaklariga mosligi.
3. Elektr kabellarining tartiblanganligi va xavfsizligi.
4. Tizim bloki ventilyatsiyasi uchun yetarli bo'shliq mavjudligi.

**Topshirish formati:** Tekshiruv natijalarini `.docx` yoki `.pdf` fayl shaklida tayyorlab, `FIO_1-Mavzu_Xavfsizlik.docx` nomi bilan platformaga yuklang.

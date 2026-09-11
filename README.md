# 📊 Sales Team Performance & KPI Calculation Model (Xodimlar KPI Tahlili)

Ushbu loyiha FMCG hamda savdo sohasidagi savdo agentlari (Trade Representatives) va supervisorlar (TCM) faoliyatini **KPI (Key Performance Indicator)** ko'rsatkichlari asosida baholash, vizual tahlil qilish va ularning oylik motivatsiya bonuslarini avtomatlashtirilgan tarzda hisoblash uchun mo'ljallangan Excel/[Google Sheets](https://docs.google.com/spreadsheets/d/1F-CXmeR7ZcDMiWu3MfvSykfIF6kQLQCZZToLFB0CW1k/edit?usp=sharing)
2 modelidir.

---

<img width="1365" height="1095" alt="image" src="https://github.com/user-attachments/assets/c310d72d-ba6f-49b6-85dc-1b97d1be78cf" />


---


<img width="2548" height="1158" alt="image" src="https://github.com/user-attachments/assets/5ead1fc5-110a-4bb4-88f1-145d2d27853d" />




## 🎯 Loyihaning asosiy maqsadi

* **Odil va shaffof baholash:** Xodimlarning haqiqiy samaradorligini (Sotuv hajmi, Tashriflar, Mijozlar bazasi qamrovi) aniq raqamlar orqali ko'rsatish.
* **Avtomatlashtirilgan oylik maosh hisobi:** Bazaviy maosh hamda KPI darajasiga bog'liq bo'lgan o'zgaruvchan bonus tizimini hisoblash.
* **Tahlil va rejalashtirish:** Hududlar (viloyatlar) va xodimlar kesimida sust ko'rsatkichli va yuqori samarali nuqtalarni aniqlash.

---

## 🔑 Modellashtirilgan KPI Ko'rsatkichlari

Faylda quyidagi **Asosiy Samaradorlik Ko'rsatkichlari (KPI)** avtomatik hisoblab chiqiladi:

1. **Sotuv bajarilishi (Sales Plan vs Fact %):** Rejalashtirilgan va amaldagi sotuv hajmi nisbati.
2. **Tashriflar bajarilishi (Visit Execution %):** Rejalashtirilgan nuqtalarga amalda qilingan tashriflar ulushi.
3. **Mijozlar bazasi qamrovi (AKB % / Active Customer Base):** TCB (Jami mijozlar bazasi) ichidan rejadagi ACB (Faol mijozlar) ulushi.
4. **Strike Rate (%):** Tashriflar va muvaffaqiyatli buyurtmalar o'rtasidagi samadorlik ko'rsatkichi.
5. **O'rtacha chek (Average Order Value):** Bir buyurtmaga to'g'ri keluvchi o'rtacha sotuv summasi va uning plan-fakt tahlili.

---

## 📁 Strukturasi (Worksheets)

* **`KPI Xodimlar`** — Barcha savdo agentlari va supervisorlarning plan-fakt ma'lumotlari hamda ularning umumiy tahlili.
* **`Reja KPI qoyish`** — KPI tizimining nazariy asoslari, mezonlari hamda maqsadlarni to'g'ri belgilash bo'yicha yo'riqnoma.
* **`KPI oylik xisoblash`** — Har bir xodimlarning KPI ko'rsatkichlaridan kelib chiqqan holda oylik maoshini avtomatik shakllantirish jadvali.
* **`Reja KPI oylik xisoblash`** — Oylik hisoblash formulalari va motivatsiya tizimining mantiqiy tuzilishi.
* **`KPI motivatsiya`** — KPI ko'rsatkichlarining og'irlik ulushlari (Weight %) hamda erishilgan natijaga qarab bonus ko'paytiruvchilar matrix'i (Bonus Matrix).

---

## ⚙️ Ishlatilingan Metodologiya va Formulalar

Modelda Excel / Google Sheets'ning quyidagi murakkab va funksional vositalaridan foydalanilgan:
* **Mantiqiy formulalar:** `ЕСЛИ` (`IF`), `ЕСЛИОШИБКА` (`IFERROR`), `И` (`AND`)
* **Matritsali qidiruv va agregatsiya:** `ВПР` (`VLOOKUP`), `СУММЕСЛИ` (`SUMIF`), `СЧЁТЕСЛИ` (`COUNTIF`)
* **Moliyaviy va ulushli hisob-kitoblar:** Nisbiy va absolut KPI og'irliklarini qo'llash.

---

## 🛠️ Qanday ishlatish yoki ko'rish mumkin?

1. Ushbu repository'dan `.xlsx` faylini yuklab oling yoki googe sheets havolisiga [bosing](https://docs.google.com/spreadsheets/d/1F-CXmeR7ZcDMiWu3MfvSykfIF6kQLQCZZToLFB0CW1k/edit?usp=sharing)
2. `KPI Xodimlar` varag'iga o'zingizning xodimlaringizning plan va fakt ma'lumotlarini kiriting.
3. `KPI motivatsiya` bo'limida kompaniyangiz maosh hamda bonus stavkalarini sozlang.
4. Tizim avtomatik ravishda barcha KPI foizlarini va to'lanishi kerak bo'lgan yakuniy oylik maoshlarni hisoblab beradi.

---
🤝 **Muallif:** Akrom Abdurakhmatov  
💼 **Soha:** Finansist / Ma'lumotlar va Biznes tahlilchi (Business & Sales Analyst)

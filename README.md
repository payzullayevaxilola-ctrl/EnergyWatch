# EnergyWatch
Elektr tarmog'ida noqonuniy foydalanishni AI yordamida aniqlash tizimi
Muammo
O'zbekistonda elektr energiyasidan noqonuniy foydalanish (hisoblagichni chetlab o'tish, hisoblagichga aralashish, to'g'ridan-to'g'ri liniyaga ulanish) elektr tarmoq korxonalari uchun katta moliyaviy yo'qotishlarga sabab bo'lmoqda. Hozirgi vaqtda bu holatlar asosan qo'lda o'tkaziladigan reydlar orqali aniqlanadi, bu esa vaqt va resurs talab qiladigan, samarasi cheklangan usul hisoblanadi. Bundan tashqari, mamlakatda 500 mingdan ortiq aqlli hisoblagich markaziy tizimga ma'lumot uzatmayapti, bu esa nazoratni yanada qiyinlashtiradi.Yechim
EnergyWatch — transformatordan chiqqan umumiy tok qiymati bilan unga ulangan barcha aqlli hisoblagichlar ko'rsatkichlari yig'indisi orasidagi farqni real vaqt rejimida hisoblab, sun'iy intellekt yordamida g'ayrioddiy holatlarni (anomaliyalarni) avtomatik aniqlaydigan tizim.
Qanday ishlaydi: Transformator chiqishiga va taqsimlash nuqtalariga tok sensorlari o'rnatiladi. Sensorlar va aqlli hisoblagichlardan ma'lumotlar bulutli ma'lumotlar bazasiga real vaqtda uzatiladi. AI modeli (anomaliya aniqlash algoritmlari) normal iste'mol naqshlaridan chetga chiqishlarni aniqlaydi. Shubhali hududlar geografik xarita orqali xodimlarga ko'rsatiladi, ustuvorlik darajasi (risk score) bilan birga
Aniqlanadigan holatlar: Hisoblagichga texnik aralashish (tamper). Hisoblagichni butunlay chetlab o'tib, to'g'ridan-to'g'ri liniyaga ulanish. Uzoq vaqt ma'lumot uzatmayotgan hisoblagichlar. Texnologiyalar (rejalashtirilgan). Sensorlar: CT clamp tok sensorlari, ESP32 mikrokontroller, GSM/LoRa modul. Backend: Python (FastAPI)
Ma'lumotlar bazasi: PostgreSQL + TimescaleDB: AI/ML: scikit-learn (Isolation Forest), keyingi bosqichda PyTorch. Dashboard: React + xaritalash kutubxonasi
Loyiha holati: Pre-MVP — hozirda texnik arxitektura va biznes-model ishlab chiqilmoqda. Pilot loyiha (bitta transformator, 20-30 abonent) rejalashtirilgan.
Xalqaro tajriba. Shu kabi AI-asoslangan yechimlar AQSh, Yevropa, Xitoy, Malayziya va Pokistonda allaqachon amaliyotda qo'llanilib, isbotlangan natijalar bermoqda. O'zbekistonda bu turdagi AI-asoslangan proaktiv aniqlash tizimi hali joriy etilmagan — bu loyiha shu bo'shliqni to'ldirishga qaratilgan.
Muallif: Payzullayeva Xilola 
Loyiha ustida ishlab chiqilmoqda.

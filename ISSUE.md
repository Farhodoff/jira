# Loyiha Issues (Topilgan muammolar) - Farhodoff

Loyiha ko'rib chiqilgandan so'ng aniqlangan kamchiliklar:

## ⚙️ Backend
1.  **Xatolarni boshqarish (Error Handling):** 
    - [ ] Production muhitida xatolik yuz berganda `err.stack` ni ko'rsatmaslik kerak.
    - [ ] `express-async-errors` kutubxonasidan foydalanib, `try-catch` bloklarini kamaytirish tavsiya etiladi.
2.  **Loglash (Logging):**
    - [ ] So'rovlarni kuzatish uchun `morgan` kutubxonasini qo'shish kerak.
3.  **Xavfsizlik (Security):**
    - [ ] `helmet` CSP sozlamalarini xavfsizroq qilish kerak.
4.  **Static fayllar:**
    - [ ] `uploads` papkasi mavjudligini server ishga tushishidan oldin tekshirish yoki avtomatik yaratish kerak.

## 🎨 Frontend
1.  **Atrof-muhit o'zgaruvchilari (Env Variables):**
    - [ ] `.env` fayli va uning ichidagi o'zgaruvchilar borligini tekshirish uchun validatsiya qo'shish kerak.
2.  **Forma validatsiyasi:**
    - [ ] Login va Register sahifalarida front-end validatsiyasini yanada kuchaytirish kerak (masalan, `zod` yoki `yup` orqali).
3.  **Loading holatlari:**
    - [ ] API so'rovlari vaqtida Skeleton loader-lar yoki Spinner-lar qo'shish kerak.

## 🚀 Umumiy
- [ ] Docker konfiguratsiyasida ma'lumotlar bazasi parollarini `.env` orqali boshqarish kerak.

# Film Nomini Bashorat Qilish

Ushbu loyiha Tensorflow va Keras yordamida film nomlarini bashorat qilish uchun sun'iy intellekt modelini yaratishga qaratilgan. Model TMDB 5000 ta film ma'lumotlar to'plami yordamida o'qitilgan va foydalanuvchi tomonidan kiritilgan boshlang'ich matnga asoslanib keyingi so'zlarni bashorat qiladi.

## O'rnatish

Loyihani ishlatish uchun quyidagi kutubxonalarni o'rnatishingiz kerak:
`pip install pandas tensorflow numpy gradio`

## Foydalanish

1. `tmdb_5000_movies.csv` faylini loyiha papkasiga yuklang.
2. `nwp.h5` modelidagi faylni yuklang (agar sizda o'qitilgan model bo'lmasa, kodni ishga tushirib uni yaratishingiz kerak).
3. Kodni Google Colab yoki boshqa Python muhitida ishga tushiring.
4. Gradio interfeysi ochiladi, bu yerda boshlang'ich matnni kiritib va bashorat qilish uchun so'zlar sonini belgilashingiz mumkin.
5. "Submit" tugmasini bosing va model bashoratini ko'ring.

## Ma'lumotlar

Loyihada TMDB 5000 ta film ma'lumotlar to'plami ishlatilgan. Ma'lumotlar to'plamini quyidagi manzildan yuklab olishingiz mumkin: [TMDB 5000 Movie Dataset].

## Misol
Kirish matni: "Mission" Bashorat qilingan so'zlar soni: 2 Bashorat: "Mission: Impossible"
## Cheklovlar

Model ma'lumotlar to'plamida mavjud bo'lgan film nomlariga asoslanib bashorat qiladi. Shuning uchun, kam uchraydigan yoki yangi film nomlarini bashorat qilishda xatoliklarga yo'l qo'yishi mumkin.

## Kelajakdagi ishlar

Modelni yaxshilash uchun quyidagi ishlarni amalga oshirish mumkin:

* Kattaroq ma'lumotlar to'plamini ishlatish.
* Model arxitekturasini yaxshilash.
* Bashorat qilish aniqligini oshirish uchun boshqa usullarni qo'llash.

## Aloqa

Loyiha haqida savollaringiz bo'lsa, menga asosiyxabar@gmail.com orqali murojaat qilishingiz mumkin.


**Eslatma:** README faylida yuqoridagi braketlarda ko'rsatilgan ma'lumotlarni o'zingizning loyiha ma'lumotlaringiz bilan almashtiring.

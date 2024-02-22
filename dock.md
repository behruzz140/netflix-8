-quarry.selector

### $ ->
    Bu funksiya quarry.selector vazifasini bajaradi.

### $$ ->
    Bu funksiya quarry.selectorALL vazifasini bajaradi.

- render

### renderCategories ->
    Bu funksiya oziga data qabul qilib undagi TITLE larni bosh arrayga yigib beradi.


### renderMovies ->
    Bu finksiya oziga 2 ta argument qabul qilib, data va parent element. Buning vazifasi datani ichidagi elementlarni parent elementga append qilib beradi.


### renderData ->
    Bu funksiya create element vazifasini bajaradi. oziga 3 ta argument qabul qiladi. Class, TegName, content.


### headerSearch ->
    Bu funksiya inputga keyUp bolganida uning value sini olib data elementlarni ichidan qidiradi. Agar bor bolsa el qaytaradi aks xolda null

-addEventListener

### darkBtn.addEventListener('click') ->
    Bu sahifani dark mode qilish yoki olish vazifasini bajaradi.

### multbutton.addEventListener ->
    Bu buttonga click bolganida u formdagi multarr ni ishga tushuradi. va biz kiritgan malumotlar boyicha dataning elementlari ichidan izlashda davom etadi. va uni yigib borib renderdata() funksiyasiga yuboradi.

### moviesWrapper.addEventListener('click) ->
    Bu funksiya cardlarning ichidagi buttonga click bolganda ishlidi. ichida IF orqali biz korsat click bilan tekshiradi, class orqali tekshiradi. bu ammallardan otkanidan song biz bosgan elementni malumotlarini localeStorage ga joylab qoyadi va like qismiga qoshib qoyadi.

### searchMoviebyID() ->
    Bu funksiya LocaleStroge da kelgan ID malumotlarni qabul qilib filterMovieData() funksiyasiga yuboradi.

### filterMovieData() ->
    Bu funksiya qabul qilgan arr ID malumotlarni data.elementlar ichidan qidiradi topganlarni qaytarib uni Renderdata() funksiyasiga yuboradi.
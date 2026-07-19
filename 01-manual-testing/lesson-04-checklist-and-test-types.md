# Manual QA — Dərs 4: Checklist və Test Növləri

## Checklist nədir?

Checklist yoxlanılacaq funksiyaların qısa siyahısıdır.

Checklist-də test addımları detallı yazılmır. Tester yoxlamalı olduğu funksiyaları siyahı şəklində qeyd edir.

Nümunə:

* Düzgün məlumatlarla login yoxlanıldı.
* Səhv şifrə ilə login yoxlanıldı.
* Boş username yoxlanıldı.
* Boş password yoxlanıldı.
* Password maskalanması yoxlanıldı.

## Test Case və Checklist fərqi

### Test Case

Testin bütün addımlarını, məlumatlarını və nəticələrini detallı göstərir.

Test Case-də adətən bunlar olur:

* Test Case ID
* Title
* Preconditions
* Test Data
* Steps
* Expected Result
* Actual Result
* Status

### Checklist

Sadəcə yoxlanılacaq funksiyaların qısa siyahısını göstərir.

Checklist daha sürətli test üçün istifadə olunur.

## Checklist nə zaman istifadə olunur?

Checklist aşağıdakı hallarda faydalıdır:

* Vaxt az olduqda
* Sadə funksiyalar yoxlanıldıqda
* Təkrar test aparıldıqda
* Smoke test zamanı
* Təcrübəli tester məhsulu yaxşı tanıdıqda

## Smoke Testing nədir?

Smoke Testing proqramın əsas və kritik funksiyalarının işləyib-işləmədiyini yoxlayan ilkin testdir.

Məqsəd proqramın geniş testə hazır olub-olmadığını müəyyən etməkdir.

Nümunə:

* Sayt açılır.
* Login işləyir.
* Əsas səhifə açılır.
* Məhsul səbətə əlavə olunur.
* Logout işləyir.

Login ümumiyyətlə işləmirsə, digər funksiyaları geniş test etmək mənasız ola bilər.

## Sanity Testing nədir?

Sanity Testing kiçik dəyişiklik və ya düzəlişdən sonra həmin konkret hissənin düzgün işləməsini yoxlamaqdır.

Nümunə:

Developer login düyməsindəki problemi düzəldib.

Tester əsasən bunları yoxlayır:

* Login düyməsi işləyir.
* Düzgün məlumatlarla giriş mümkündür.
* Səhv məlumatlarla giriş mümkün deyil.

Sanity Testing bütün sistemi yoxlamır. Dəyişdirilən hissəyə fokuslanır.

## Regression Testing nədir?

Regression Testing yeni dəyişikliklərin əvvəllər işləyən funksiyaları pozub-pozmadığını yoxlamaqdır.

Nümunə:

Login funksiyasına yeni “Remember Me” seçimi əlavə edilib.

Tester yoxlayır:

* Login əvvəlki kimi işləyir.
* Logout işləyir.
* Şifrə validation-u işləyir.
* Role yönləndirməsi pozulmayıb.
* Yeni “Remember Me” funksiyası işləyir.

## Smoke, Sanity və Regression fərqi

### Smoke

Proqramın əsas funksiyaları ümumiyyətlə işləyirmi?

### Sanity

Dəyişdirilən konkret hissə düzgün işləyirmi?

### Regression

Yeni dəyişiklik əvvəlki funksiyaları pozubmu?

## Functional Testing

Funksiyanın tələblərə uyğun işləyib-işləmədiyini yoxlayır.

Nümunələr:

* Login
* Register
* Search
* Payment
* Logout

## UI Testing

Səhifənin görünüşünü yoxlayır.

Nümunələr:

* Düymənin mətni
* Rəng
* Ölçü
* Elementlərin yerləşməsi
* Mobil görünüş

## Usability Testing

Sistemin istifadəçi üçün rahat və başa düşülən olub-olmadığını yoxlayır.

Nümunələr:

* Düymələr aydın görünürmü?
* Xəta mesajı başa düşülürmü?
* İstifadəçi lazım olan funksiyanı asan tapa bilirmi?

## Compatibility Testing

Proqramın fərqli mühitlərdə işləməsini yoxlayır.

Nümunələr:

* Google Chrome
* Microsoft Edge
* Firefox
* Windows
* Android
* iPhone

## Exploratory Testing

Tester əvvəlcədən yazılmış detallı test case olmadan sistemi araşdırır.

Tester məhsulu istifadə edir, fərqli məlumatlar daxil edir və gözlənilməyən problemlər tapmağa çalışır.

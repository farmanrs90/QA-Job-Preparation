# Login Functionality Checklist

## Page Loading

* [ x] Login səhifəsi uğurla açılır.
* [ x] Username sahəsi görünür.
* [ x] Password sahəsi görünür.
* [ x] Login düyməsi görünür.
* [ x] Səhifədə qırıq və ya çatışmayan element yoxdur.

## Positive Testing

* [x ] Düzgün username və password ilə login mümkündür.
* [ x] Uğurlu login-dən sonra düzgün səhifə açılır.
* [x ] Login-dən sonra istifadəçinin sessiyası yaranır.

## Negative Testing

* [x ] Səhv username ilə login mümkün deyil.
* [x ] Səhv password ilə login mümkün deyil.
* [ x] Hər iki məlumat səhv olduqda login mümkün deyil.
* [ x] Username boş olduqda validation mesajı görünür.
* [x ] Password boş olduqda validation mesajı görünür.
* [x ] Hər iki sahə boş olduqda validation mesajları görünür.

## Password Field

* [ x] Password simvolları maskalanır.
* [ x] Password adi mətn kimi görünmür.
* [failed ] Password sahəsinə boşluq daxil edildikdə sistem düzgün davranır.

## Error Messages

* [x ] Səhv məlumat daxil edildikdə xəta mesajı görünür.
* [ x] Xəta mesajı istifadəçi üçün aydındır.
* [ x] Xəta mesajında yazı səhvi yoxdur.
* [ x] Xəta mesajı bağlana və ya təmizlənə bilir.

## User Interface

* [x ] Login düyməsinin üzərində düzgün mətn yazılıb.
* [ x] Sahələrin adları düzgün yazılıb.
* [ x] Elementlər bir-birinin üzərinə düşmür.
* [ x] Səhifə kiçik ekran ölçüsündə düzgün görünür.

## Keyboard Testing

* [ x] Tab düyməsi ilə sahələr arasında keçid mümkündür.
* [ x] Enter düyməsi ilə login etmək mümkündür.
* [x ] Fokus sırası məntiqlidir.

## Security Basics

* [x ] Password URL-də görünmür.
* [ x] Səhv login zamanı sistem həddindən artıq şəxsi məlumat göstərmir.
* [x ] Logout-dan sonra qorunan səhifəyə geri qayıtmaq mümkün deyil.

## Test Summary

* Total Checks:31
* Passed:30
* Failed:1
* Blocked:
* Not Executed:

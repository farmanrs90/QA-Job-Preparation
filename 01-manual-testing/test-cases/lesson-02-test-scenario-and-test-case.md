# Manual QA — Dərs 2

## Test Scenario nədir?

Test Scenario yoxlanılacaq funksiyanı ümumi şəkildə ifadə edir.

Test Scenario-da bütün addımlar yazılmır. Sadəcə hansı funksiyanın yoxlanılacağı göstərilir.

### Login üçün Test Scenario nümunələri

1. Düzgün məlumatlarla login olma funksiyasını yoxlamaq.
2. Səhv şifrə ilə login olma davranışını yoxlamaq.
3. Səhv email ilə login olma davranışını yoxlamaq.
4. Boş email ilə login olma davranışını yoxlamaq.
5. Boş şifrə ilə login olma davranışını yoxlamaq.
6. Həm email, həm də şifrə boş olduqda sistemi yoxlamaq.
7. Şifrənin gizli göstərilməsini yoxlamaq.
8. Login düyməsinin işləməsini yoxlamaq.
9. Enter düyməsi ilə login olma funksiyasını yoxlamaq.
10. Uğurlu login-dən sonra düzgün səhifəyə keçidi yoxlamaq.

## Test Case nədir?

Test Case bir funksiyanın necə yoxlanılacağını addım-addım göstərir.

Test Case daxilində aşağıdakılar ola bilər:

* Test Case ID
* Title
* Preconditions
* Test Data
* Steps
* Expected Result
* Actual Result
* Status

## Test Case ID

Hər test case-in unikal nömrəsi olmalıdır.

Nümunə:

* TC-LOGIN-001
* TC-LOGIN-002
* TC-REGISTER-001

`TC` — Test Case deməkdir.

`LOGIN` — yoxlanılan funksiyadır.

`001` — testin sıra nömrəsidir.

## Preconditions

Test başlamazdan əvvəl mövcud olmalı şərtlərdir.

Nümunə:

* İstifadəçinin sistemdə hesabı olmalıdır.
* Login səhifəsi açıq olmalıdır.
* İnternet bağlantısı olmalıdır.

## Test Data

Test zamanı istifadə olunan məlumatlardır.

Nümunə:

* Email: [user@example.com](mailto:user@example.com)
* Password: Test12345

## Steps

Testi yerinə yetirmək üçün ediləcək addımlardır.

Addımlar aydın, konkret və sıra ilə yazılmalıdır.

## Expected Result

Sistemin düzgün işlədiyi halda verməli olduğu nəticədir.

## Actual Result

Test zamanı sistemin real olaraq verdiyi nəticədir.

Test icra edilməyibsə belə yazmaq olar:

Not executed

## Status

Test nəticəsi:

* Passed — gözlənilən və real nəticə eynidir.
* Failed — gözlənilən və real nəticə fərqlidir.
* Blocked — test başqa problemə görə icra edilə bilmir.
* Not Executed — test hələ icra edilməyib.

## Positive Test Case

Düzgün məlumatlarla funksiyanın işləməsini yoxlayır.

Nümunə:

Düzgün email və şifrə ilə login olmaq.

## Negative Test Case

Səhv, boş və ya gözlənilməyən məlumatlarla sistemin davranışını yoxlayır.

Nümunə:

Səhv şifrə ilə login olmağa çalışmaq.

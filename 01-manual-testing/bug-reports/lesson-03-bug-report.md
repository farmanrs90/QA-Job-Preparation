# Manual QA — Dərs 3: Bug Report

## Bug nədir?

Bug proqramın gözlənilən nəticədən fərqli işləməsidir.

Nümunə:

İstifadəçi səhv şifrə daxil edir, amma sistem onu hesaba daxil edir.

## Bug Report nədir?

Bug Report tester tərəfindən tapılmış problemin developer və digər komanda üzvləri üçün aydın şəkildə yazılmasıdır.

Yaxşı bug report-u oxuyan developer problemi özü təkrar edə bilməlidir.

## Bug Report-un əsas hissələri

### Bug ID

Hər bug üçün unikal nömrədir.

Nümunə:

* BUG-LOGIN-001
* BUG-CART-001
* BUG-PAYMENT-001

### Title

Problemi qısa və konkret ifadə edir.

Pis title:

Login işləmir.

Yaxşı title:

İstifadəçi səhv şifrə ilə sistemə daxil ola bilir.

### Environment

Bug-un hansı mühitdə tapıldığını göstərir.

Nümunə:

* Operating System: Windows 10
* Browser: Google Chrome
* Environment: Test
* Website: Example Test Application

### Preconditions

Bug-u yoxlamazdan əvvəl mövcud olmalı şərtlərdir.

Nümunə:

* İstifadəçinin aktiv hesabı mövcuddur.
* Login səhifəsi açıqdır.

### Steps to Reproduce

Bug-u yenidən yaratmaq üçün addımlardır.

Addımlar qısa, konkret və sıra ilə yazılmalıdır.

Nümunə:

1. Login səhifəsini aç.
2. Düzgün email daxil et.
3. Səhv şifrə daxil et.
4. Login düyməsinə bas.

### Actual Result

Sistemdə həqiqətən baş verən nəticədir.

Nümunə:

İstifadəçi səhv şifrə daxil etməsinə baxmayaraq dashboard səhifəsinə yönləndirildi.

### Expected Result

Sistemin düzgün işlədiyi halda baş verməli nəticədir.

Nümunə:

İstifadəçi sistemə daxil olmamalı və yanlış giriş məlumatları haqqında xəta mesajı görməlidir.

## Severity nədir?

Severity bug-un sistemə nə qədər ciddi təsir etdiyini göstərir.

Severity adətən tester tərəfindən təyin edilir.

### Critical

Sistem və ya əsas funksiya tam işləmir.

Nümunələr:

* Sistem açılmır.
* Bütün istifadəçilər login ola bilmir.
* Ödəniş iki dəfə tutulur.
* İstifadəçi məlumatları silinir.

### High

Vacib funksiya işləmir, amma sistemin başqa hissələrindən istifadə etmək mümkündür.

Nümunələr:

* Səbətə məhsul əlavə etmək mümkün deyil.
* İstifadəçi sifarişi tamamlaya bilmir.
* Şifrəni dəyişmək mümkün deyil.

### Medium

Funksiya qismən işləyir və ya alternativ yol mövcuddur.

Nümunələr:

* Filter düzgün işləmir, amma məhsulu axtarışla tapmaq mümkündür.
* Bəzi validation mesajları göstərilmir.
* Düymə birinci klikdə işləmir, ikinci klikdə işləyir.

### Low

Əsasən görünüş, mətn və ya kiçik istifadə rahatlığı problemidir.

Nümunələr:

* Yazı səhvi var.
* Düymənin rəngi dizayna uyğun deyil.
* Element bir neçə piksel sürüşüb.

## Priority nədir?

Priority bug-un nə qədər tez düzəldilməli olduğunu göstərir.

Priority adətən Product Owner, Project Manager və ya komanda tərəfindən müəyyən edilir.

### Urgent və ya P0

Bug dərhal düzəldilməlidir.

### High və ya P1

Bug yaxın zamanda düzəldilməlidir.

### Medium və ya P2

Bug planlaşdırılan işlər sırasında düzəldilə bilər.

### Low və ya P3

Bug vaxt olduqda düzəldilə bilər.

## Severity və Priority fərqi

Severity problemin nə qədər ciddi olduğunu göstərir.

Priority problemin nə qədər tez düzəldilməli olduğunu göstərir.

Nümunə:

Ana səhifədə şirkətin adı səhv yazılıb.

* Severity: Low
* Priority: High

Bu problem sistemin işləməsinə mane olmur, amma bütün istifadəçilər tərəfindən görüldüyü üçün tez düzəldilməlidir.

Başqa nümunə:

Çox az istifadə olunan köhnə səhifə açıldıqda sistem çökür.

* Severity: High
* Priority: Low və ya Medium

Problem ciddidir, amma səhifədən demək olar ki, istifadə olunmursa prioritet aşağı ola bilər.

## Bug Status

Bug müxtəlif statuslarda ola bilər:

* New — yeni tapılıb.
* Open — komanda tərəfindən qəbul edilib.
* In Progress — developer üzərində işləyir.
* Fixed — developer problemi düzəldib.
* Ready for Retest — tester yenidən yoxlamalıdır.
* Reopened — bug düzəlməyib və yenidən açılıb.
* Closed — bug uğurla düzəlib.
* Rejected — komanda bunu bug hesab etmir.
* Duplicate — eyni bug daha əvvəl qeyd olunub.

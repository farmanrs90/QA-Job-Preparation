# Manual QA — Dərs 1

## Software Testing nədir?

Software Testing proqramın gözlənilən qaydada işləyib-işləmədiyini yoxlama prosesidir.

Tester proqramda xətaları tapır, nəticələri yoxlayır və tapdığı problemləri developer komandasına bildirir.

## QA nədir?

QA — Quality Assurance, yəni keyfiyyətin təmin edilməsidir.

QA yalnız hazır proqramda xəta axtarmır. Proqramın hazırlanma prosesinin daha keyfiyyətli olmasına da kömək edir.

## Test Scenario nədir?

Test Scenario yoxlanılacaq ümumi funksiyanı göstərir.

Nümunələr:

- İstifadəçinin login ola bilməsini yoxlamaq.
- İstifadəçinin hesabdan çıxa bilməsini yoxlamaq.
- Yanlış şifrə daxil edildikdə xəta mesajını yoxlamaq.

## Test Case nədir?

Test Case funksiyanı necə yoxlayacağımızı addım-addım göstərir.

### İlk test case

**Test Case ID:** TC-LOGIN-001

**Title:** Düzgün məlumatlarla login olmaq

**Precondition:** İstifadəçinin sistemdə mövcud hesabı var.

**Steps:**

1. Login səhifəsini aç.
2. Düzgün email daxil et.
3. Düzgün şifrə daxil et.
4. Login düyməsinə bas.

**Expected Result:**

İstifadəçi uğurla sistemə daxil olmalı və dashboard səhifəsi açılmalıdır.

## Positive Testing

Düzgün məlumatlarla sistemin işləməsini yoxlamaqdır.

Nümunə:

- Düzgün email və düzgün şifrə ilə login olmaq.

## Negative Testing

Səhv və ya gözlənilməyən məlumatlarla sistemin davranışını yoxlamaqdır.

Nümunələr:

- Səhv şifrə ilə login olmaq.
- Email sahəsini boş saxlamaq.
- Şifrə sahəsini boş saxlamaq.

## Bug nədir?

Bug proqramın gözlənilən nəticədən fərqli işləməsidir.

Nümunə:

İstifadəçi səhv şifrə daxil edir, amma sistem onu yenə də hesaba daxil edir.
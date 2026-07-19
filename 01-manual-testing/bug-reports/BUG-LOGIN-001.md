# BUG-LOGIN-001

## Title

İstifadəçi səhv şifrə ilə sistemə daxil ola bilir

## Bug Type

Functional

## Environment

* Operating System: Windows 10
* Browser: Google Chrome
* Environment: Test
* Application: Login Test Application

## Preconditions

* İstifadəçinin sistemdə aktiv hesabı mövcuddur.
* Login səhifəsi açıqdır.
* İstifadəçi sistemə daxil olmayıb.

## Test Data

* Email: [user@example.com](mailto:user@example.com)
* Password: WrongPassword123

## Steps to Reproduce

1. Login səhifəsini aç.
2. Email sahəsinə `user@example.com` daxil et.
3. Password sahəsinə `WrongPassword123` daxil et.
4. Login düyməsinə bas.
5. Açılan səhifəni yoxla.

## Actual Result

İstifadəçi səhv şifrə daxil etməsinə baxmayaraq sistemə daxil olur və dashboard səhifəsi açılır.

## Expected Result

İstifadəçi səhv şifrə ilə sistemə daxil olmamalıdır. Login səhifəsində yanlış email və ya şifrə haqqında xəta mesajı göstərilməlidir.

## Severity

Critical

## Priority

High

## Reproducibility

Always — 5/5 dəfə təkrarlandı.

## Status

New

## Attachment

Screenshot və ya ekran videosu əlavə edilməlidir.

## Additional Notes

Bu problem icazəsiz şəxslərin istifadəçi hesablarına daxil olmasına səbəb ola bilər və ciddi təhlükəsizlik riski yaradır.

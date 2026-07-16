# SauceDemo Login Test Execution

## Test məlumatları

- Execution Date: 2026-07-16
- Tester: Farman
- Environment: Production Demo
- Browser: Google Chrome
- Operating System: Windows 10
- Website: SauceDemo

---

## TC-LOGIN-001 — Düzgün məlumatlarla login olmaq

**Type:** Positive

**Test Data:**

- Username: standard_user
- Password: secret_sauce

**Steps:**

1. SauceDemo login səhifəsini aç.
2. Username sahəsinə `standard_user` yaz.
3. Password sahəsinə `secret_sauce` yaz.
4. Login düyməsinə bas.

**Expected Result:**

İstifadəçi uğurla sistemə daxil olmalı və məhsullar səhifəsi açılmalıdır.

**Actual Result:**

İstifadəçi uğurla sistemə daxil oldu və məhsullar səhifəsi açıldı.

**Status:** Passed


---

## TC-LOGIN-002 — Səhv şifrə ilə login olmaq

**Type:** Negative

**Test Data:**

- Username: standard_user
- Password: Wrong123

**Steps:**

1. SauceDemo login səhifəsini aç.
2. Username sahəsinə `standard_user` yaz.
3. Password sahəsinə `Wrong123` yaz.
4. Login düyməsinə bas.

**Expected Result:**

İstifadəçi sistemə daxil olmamalıdır. Login məlumatlarının səhv olduğunu bildirən xəta mesajı görünməlidir.

**Actual Result:**

İstifadəçi sistemə daxil olmadı. Login səhifəsində xəta mesajı göstərildi:"Epic sadface: Username and password do not match any user in this service"

**Status:** failed

---

## TC-LOGIN-003 — Username sahəsini boş saxlamaq

**Type:** Negative

**Test Data:**

- Username: boş
- Password: secret_sauce

**Steps:**

1. SauceDemo login səhifəsini aç.
2. Username sahəsini boş saxla.
3. Password sahəsinə `secret_sauce` yaz.
4. Login düyməsinə bas.

**Expected Result:**

İstifadəçi sistemə daxil olmamalıdır. Username sahəsinin tələb olunduğunu bildirən xəta mesajı görünməlidir.

**Actual Result:**

İstifadəçi sistemə daxil olmadı. Login səhifəsində xəta mesajı göstərildi:"Epic sadface: Username and password do not match any user in this service"

**Status:** failed

---

## TC-LOGIN-004 — Şifrənin gizli göstərilməsini yoxlamaq

**Type:** Functional

**Test Data:**

- Password: secret_sauce

**Steps:**

1. SauceDemo login səhifəsini aç.
2. Password sahəsinə `secret_sauce` yaz.
3. Şifrənin ekranda necə göründüyünə bax.

**Expected Result:**

Şifrə adi mətn kimi görünməməlidir. Simvollar nöqtə və ya başqa maskalanmış formada göstərilməlidir.


**Actual Result:**

Password sahəsinə daxil edilən simvollar maskalanmış şəkildə göstərildi.

**Status:** Passed

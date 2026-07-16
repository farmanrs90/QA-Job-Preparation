# Login Test Cases

## TC-LOGIN-001 — Düzgün məlumatlarla login olmaq

**Type:** Positive

**Preconditions:**

* İstifadəçinin sistemdə aktiv hesabı var.
* Login səhifəsi açıqdır.

**Test Data:**

* Email: [user@example.com](mailto:user@example.com)
* Password: Test12345

**Steps:**

1. Email sahəsinə düzgün email daxil et.
2. Şifrə sahəsinə düzgün şifrə daxil et.
3. Login düyməsinə bas.

**Expected Result:**

İstifadəçi uğurla sistemə daxil olmalı və dashboard səhifəsi açılmalıdır.

**Actual Result:** Not executed

**Status:** Not Executed

---

## TC-LOGIN-002 — Səhv şifrə ilə login olmaq

**Type:** Negative

**Preconditions:**

* İstifadəçinin sistemdə aktiv hesabı var.
* Login səhifəsi açıqdır.

**Test Data:**

* Email: [user@example.com](mailto:user@example.com)
* Password: WrongPassword

**Steps:**

1. Email sahəsinə düzgün email daxil et.
2. Şifrə sahəsinə səhv şifrə daxil et.
3. Login düyməsinə bas.

**Expected Result:**

İstifadəçi sistemə daxil olmamalıdır. Ekranda email və ya şifrənin səhv olduğunu bildirən xəta mesajı görünməlidir.

**Actual Result:** Not executed

**Status:** Not Executed

---

## TC-LOGIN-003 — Email sahəsini boş saxlamaq

**Type:** Negative

**Preconditions:**

* Login səhifəsi açıqdır.

**Test Data:**

* Email: boş
* Password: Test12345

**Steps:**

1. Email sahəsini boş saxla.
2. Şifrə sahəsinə məlumat daxil et.
3. Login düyməsinə bas.

**Expected Result:**

İstifadəçi sistemə daxil olmamalıdır. Email sahəsinin tələb olunduğunu bildirən validation mesajı görünməlidir.

**Actual Result:** Not executed

**Status:** Not Executed

---

## TC-LOGIN-004 — Şifrə sahəsini boş saxlamaq

**Type:** Negative

**Preconditions:**

* Login səhifəsi açıqdır.

**Test Data:**

* Email: [user@example.com](mailto:user@example.com)
* Password: boş

**Steps:**

1. Email sahəsinə düzgün email daxil et.
2. Şifrə sahəsini boş saxla.
3. Login düyməsinə bas.

**Expected Result:**

İstifadəçi sistemə daxil olmamalıdır. Şifrə sahəsinin tələb olunduğunu bildirən validation mesajı görünməlidir.

**Actual Result:** Not executed

**Status:** Not Executed

---

## TC-LOGIN-005 — Bütün sahələri boş saxlamaq

**Type:** Negative

**Preconditions:**

* Login səhifəsi açıqdır.

**Test Data:**

* Email: boş
* Password: boş

**Steps:**

1. Email sahəsini boş saxla.
2. Şifrə sahəsini boş saxla.
3. Login düyməsinə bas.

**Expected Result:**

İstifadəçi sistemə daxil olmamalıdır. Hər iki sahə üçün tələb mesajları görünməlidir.

**Actual Result:** Not executed

**Status:** Not Executed

---

## TC-LOGIN-006 — Şifrənin gizli göstərilməsini yoxlamaq

**Type:** Functional

**Preconditions:**

* Login səhifəsi açıqdır.

**Test Data:**

* Password: Test12345

**Steps:**

1. Şifrə sahəsinə məlumat daxil et.
2. Daxil edilən simvolların görünüşünə bax.

**Expected Result:**

Şifrə adi mətn kimi görünməməlidir. Simvollar nöqtə və ya ulduz formasında gizlədilməlidir.

**Actual Result:** Not executed

**Status:** Not Executed


## 1️⃣ OnlineShop

**Class atributi:**

* shop_name (boshlang‘ich: "Tech Market")

**Object atributlari:**

* product_name
* price
* quantity

**Metodlar:**

1. Oddiy method → `total_price()`

   * price * quantity ni qaytarsin

2. Class method → `change_shop_name(new_name)`

   * shop_name ni o‘zgartirsin

3. Static method → `is_valid_price(price)`

   * narx 0 dan katta bo‘lsa True qaytarsin

---

## 2️⃣ Student

**Class atributi:**

* passing_score (boshlang‘ich: 60)

**Object atributlari:**

* name
* score

**Metodlar:**

1. Oddiy method → `is_passed()`

   * agar score >= passing_score bo‘lsa True

2. Class method → `change_passing_score(new_score)`

3. Static method → `is_valid_score(score)`

   * 0–100 oralig‘ida bo‘lsa True

---

## 3️⃣ BankCard

**Class atributi:**

* bank_name ("AgroBank")

**Object atributlari:**

* card_number
* balance

**Metodlar:**

1. Oddiy method → `withdraw(amount)`

   * agar balance yetarli bo‘lsa ayirsin va yangi balansni qaytarsin

2. Class method → `change_bank_name(new_name)`

3. Static method → `is_valid_card_number(number)`

   * 16 xonali bo‘lsa True

---

## 4️⃣ Employee

**Class atributi:**

* company_name ("Tech Corp")

**Object atributlari:**

* name
* salary

**Metodlar:**

1. Oddiy method → `annual_salary()`

   * salary * 12 ni qaytarsin

2. Class method → `change_company(new_name)`

3. Static method → `is_valid_salary(salary)`

   * salary > 0 bo‘lsa True

---

## 5️⃣ Car

**Class atributi:**

* max_speed_limit (180)

**Object atributlari:**

* model
* speed

**Metodlar:**

1. Oddiy method → `is_overspeed()`

   * speed > max_speed_limit bo‘lsa True

2. Class method → `change_speed_limit(new_limit)`

3. Static method → `is_valid_speed(speed)`

   * speed >= 0 bo‘lsa True

---

## 6️⃣ Product

**Class atributi:**

* tax_percent (12)

**Object atributlari:**

* name
* price

**Metodlar:**

1. Oddiy method → `price_with_tax()`

   * narxga soliq qo‘shib qaytarsin

2. Class method → `change_tax(new_tax)`

3. Static method → `is_valid_name(name)`

   * agar name bo‘sh bo‘lmasa True

---

## 7️⃣ University

**Class atributi:**

* university_name ("TATU")

**Object atributlari:**

* student_name
* gpa

**Metodlar:**

1. Oddiy method → `is_scholarship()`

   * gpa >= 3.5 bo‘lsa True

2. Class method → `change_university(new_name)`

3. Static method → `is_valid_gpa(gpa)`

   * 0 dan 4 gacha bo‘lsa True

---

## 8️⃣ Movie

**Class atributi:**

* age_limit (16)

**Object atributlari:**

* title
* duration

**Metodlar:**

1. Oddiy method → `movie_info()`

   * "Film: title, davomiyligi: duration" formatida qaytarsin

2. Class method → `change_age_limit(new_limit)`

3. Static method → `is_valid_duration(duration)`

   * duration > 0 bo‘lsa True

---

## 9️⃣ Laptop

**Class atributi:**

* warranty_year (2)

**Object atributlari:**

* brand
* price

**Metodlar:**

1. Oddiy method → `discount(percent)`

   * chegirma qo‘llab yangi narxni qaytarsin

2. Class method → `change_warranty(new_year)`

3. Static method → `is_valid_percent(percent)`

   * 0–100 oralig‘ida bo‘lsa True

---

## 🔟 Course

**Class atributi:**

* platform_name ("Online Academy")

**Object atributlari:**

* course_name
* students_count

**Metodlar:**

1. Oddiy method → `add_student(count)`

   * students_count ni oshirsin va yangi qiymatni qaytarsin

2. Class method → `change_platform(new_name)`

3. Static method → `is_valid_students_count(count)`

   * 0 dan katta bo‘lsa True

---

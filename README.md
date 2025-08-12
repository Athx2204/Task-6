# Task 6 – Create a Strong Password and Evaluate Its Strength

## Objective
Understand what makes a password strong and test it against password strength tools

---

## Step 1 – Password Creation
Four different passwords with varying complexity were tested:

| Password           | Length | Uppercase | Lowercase | Numbers | Symbols | Complexity Level |
|--------------------|--------|-----------|-----------|---------|---------|------------------|
| `password123`      | 11     | ❌         | ✅         | ✅       | ❌       | Weak              |
| `Pass123`          | 7      | ✅         | ✅         | ✅       | ❌       | Medium            |
| `P@ssword2025`     | 12     | ✅         | ✅         | ✅       | ✅       | Strong            |
| `SecureP@ss2025`   | 14     | ✅         | ✅         | ✅       | ✅       | Very Strong       |

---

## Step 2 – Password Strength Evaluation
**Tool Used:** [PasswordMeter.com](https://passwordmeter.com)

| Password           | Score (%) | Complexity | Password Meter Feedback |
|--------------------|-----------|------------|--------------------------|
| `password123`      | **43%**   | Weak       | Contains dictionary word "password", lacks symbols |
| `Pass123`          | **51%**   | Medium     | Short length, limited variety of characters |
| `P@ssword2025`     | **89%**   | Strong     | Good mix, still contains dictionary word "password" |
| `SecureP@ss2025`   | **100%**  | Very Strong| Long, diverse characters, no common dictionary word |

---

## Step 3 – Observations
- The **SecureP@ss2025** password scored highest due to **length, variety, and no dictionary word**.  
- Adding **symbols** and **uppercase letters** significantly increases strength.  
- Longer passwords are more resistant to brute force attacks.

---

## Step 4 – Best Practices Learned
1. Aim for **12–16+ characters**.
2. Use **uppercase, lowercase, numbers, and symbols** together.
3. Avoid dictionary words and predictable patterns.
4. Use **passphrases** for easy-to-remember yet strong passwords.
5. Store passwords in a **password manager**.
6. Use **multi-factor authentication (MFA)** for added protection.

---

## Step 5 – Common Password Attacks
- **Brute Force Attack** – Tries all possible combinations.
- **Dictionary Attack** – Uses common words to guess passwords.
- **Credential Stuffing** – Uses stolen credentials from breaches.
- **Phishing** – Tricks users into revealing passwords.

---

## Step 6 – How Complexity Affects Security
- Every extra character greatly increases the total possible combinations.
- Using multiple character types makes brute force attacks take exponentially longer.
- Avoiding dictionary words improves resistance to dictionary attacks.

---

## Screenshots
**Include your screenshots from PasswordMeter.com showing each password’s score here:**
Screenshots(screenshots)


---
## Conclusion
Long, complex, and unpredictable passwords are far more secure than short or common ones. Using a mix of characters and enabling MFA greatly improves protection against attacks.

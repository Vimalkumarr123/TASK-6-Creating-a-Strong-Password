# 🔐 TASK 6: Creating a Strong Password and Evaluating Its Strength

## 📌 Objective
The goal of this task is to understand what makes a password strong, test multiple passwords using online strength checkers, and analyze the results to derive best practices for password security.

---

## 🛠 Tools Used
- [PasswordMonster](https://www.passwordmonster.com/)
- [Security.org Password Strength Tester](https://www.security.org/how-secure-is-my-password/)
- [Kaspersky Password Checker](https://password.kaspersky.com/)

---

## 🧪 Passwords Tested & Results

| Password Example        | Length | Complexity                    | Tool Used        | Strength Score / Verdict               |
|------------------------|--------|-------------------------------|------------------|----------------------------------------|
| `abc123`               | 6      | Lowercase + digits            | PasswordMonster  | Weak – Cracked in < 1 sec              |
| `Vimal@123`            | 9      | Uppercase + special + digits | Kaspersky        | Moderate – Cracked in 2 hours          |
| `MyDogLovesPizza2024!` | 20     | Passphrase + digits + symbol | Security.org     | Strong – Cracked in 1 billion years    |
| `P@ssw0rd`             | 8      | Common pattern                | PasswordMonster  | Weak – Cracked instantly               |
| `A!x7bT#9Lm2Qz$`       | 14     | High entropy                 | Kaspersky        | Very Strong – Cracked in 10 trillion years |

---

## 🧠 Key Learnings

### ✅ What Makes a Password Strong:
- **Length**: Minimum 12–16 characters
- **Complexity**: Combination of uppercase, lowercase, digits, and special symbols
- **Unpredictability**: Avoid dictionary words or common patterns
- **Passphrases**: Long, memorable phrases with symbols/numbers (e.g., `MyCat@Night2023!`)

### ❌ Common Mistakes:
- Using personal info (name, birthdate)
- Short or simple patterns (`123456`, `password`)
- Reusing passwords across accounts

---

## 🔐 Common Password Attacks

| Attack Type         | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| **Brute Force**     | Tries all possible combinations until the correct one is found              |
| **Dictionary Attack** | Uses a list of common words and passwords                                 |
| **Credential Stuffing** | Uses leaked passwords to log into other accounts                        |

---

## 🛡️ Defense Strategies

- **Use Multi-Factor Authentication (MFA)**: Adds an extra verification step
- **Use Password Managers**: Generate and store strong, unique passwords
- **Enable Account Lockouts**: Prevent unlimited login attempts
- **Regularly Update Passwords**: Especially after suspected breaches

---

## 🔑 Final Tips

1. Use **14+ characters** with mixed character types.
2. Consider **passphrases** with random but meaningful words.
3. Use a **password manager** (e.g., Bitwarden, KeePass).
4. Never reuse passwords across important services.
5. Always enable **MFA** where available.




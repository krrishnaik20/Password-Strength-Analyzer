# 🔐 Password Strength Analyzer

A simple web-based tool that evaluates the strength of user-entered passwords in real time.

Built as part of my internship project to learn about **password security** and **basic cryptography concepts**.

---

## 🚀 Live Demo

> [Click here to try it live](https://github.com/surajrai1390p-hue/password-strength-analyzer)


---


## ✨ Features

- **Real-time strength meter** — instantly shows Weak / Fair / Good / Strong
- **6 complexity checks** — length, uppercase, lowercase, numbers, symbols, 12+ chars
- **3 stronger password suggestions** — passphrase, random, and enhanced version of yours
- **Copy to clipboard** — one click to copy any suggested password
- **Show / Hide password** toggle for convenience
- **No libraries used** — pure HTML, CSS, and JavaScript only

---

## 🛠️ How It Works

### Strength Scoring (0–4)
The password gets a score based on how many rules it passes:

| Rule | Points |
|------|--------|
| 8+ characters | +1 |
| Has uppercase AND lowercase | +1 |
| Has a number | +1 |
| Has a special symbol | +1 |
| 12+ characters (bonus) | +1 (capped at 4) |

### Password Suggestions
Three types of alternatives are generated:
1. **Passphrase** — random words joined with `-` and a number (e.g. `maple-tiger-river381!`)
2. **Random 16-char** — random mix of letters, numbers, and symbols
3. **Enhanced** — your own password improved with leet-speak substitutions (`a→@`, `e→3`, `o→0`)

---

## 📂 Project Structure

```
password-strength-analyzer/
│
├── index.html      ← All code lives here (HTML + CSS + JavaScript)
└── README.md       ← This file
```

---

## 💡 What I Learned

- How password complexity rules work (length, character variety)
- What makes a password strong vs weak
- How passphrases can be stronger AND easier to remember than random passwords
- Basic DOM manipulation with JavaScript (no frameworks)
- How entropy increases with character set size and password length

---

## 🔒 Security Concepts Covered

| Concept | Description |
|---------|-------------|
| Character set size | Larger set = harder to brute-force |
| Password length | Longer = exponentially harder to crack |
| Passphrase | Multiple words = memorable + secure |
| Leet speak | Symbol substitution improves complexity |

---

## 🧑‍💻 Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript (no frameworks or libraries)

---

## 📌 How to Run Locally

1. Download or clone this repository
2. Open `index.html` in any web browser
3. That's it — no installation needed!

```bash
git clone https://github.com/surajrai1390p-hue/password-strength-analyzer
cd password-strength-analyzer
# Open index.html in your browser
```

---

## 👤 Author

SURAJ RAI
Internship Project — 2026

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

<div align="center">

# 💳 ATM Card Manager

**A beginner-friendly Python console app that simulates an ATM card database.**

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Status](https://img.shields.io/badge/Status-Learning%20Project-orange)
![Storage](https://img.shields.io/badge/Storage-Text%20File-lightgrey)

</div>

---

## ✨ Features

- 🆕 **Create accounts**: name, card number, expire date, card type, PIN and amount
- ✅ **Confirm before saving**: review the details and type `yes` to save
- 💾 **File storage**: every account is saved to `Atmcard_info.txt`
- 🔍 **Search by card number**: find a saved card instantly
- 🛡️ **Input checking**: the amount must be a number
- 💬 **Clear messages**: "Account saved", "Info not saved", "Card not found", "No Account created yet"

---

## 🚀 Getting Started

**1. Clone the repository**
```bash
git clone https://github.com/your-username/atm-card-manager.git
cd atm-card-manager
```

**2. Run the program**
```bash
python atm_card.py
```

No extra libraries are needed, only Python 3.

---

## 🖥️ How It Works

| Step | You type | What happens |
|------|----------|--------------|
| 1 | `new account` | Asks for the card details and saves them after you confirm |
| 2 | anything else | Moves on to the search step |
| 3 | `yes` | Asks for a card number to search |
| 4 | a card number | Shows the saved details, or "Card not found" |

---

## 📸 Sample Run

```text
Enter new account for creating account: new account
Enter name of Cardholder: Ram
Enter card number: 1234
Enter the Expire date: 12/28
Enter card type: debit
enter pin: 1111
Enter the amount: 5000
Enter yes if everything is correct: yes
Account saved

Enter new account for creating account: no
Enter yes for Already created account: yes
Enter the card number: 1234
Cardholder Name = Ram, Card Number = 1234, Expire Date = 12/28, Card type = debit, Pin = 1111, Amount = 5000.0
Info found
```

---

## 🧠 Concepts Used

- 🏗️ Classes and `__init__` (`atm_card`)
- 🔁 `while` loops and `if / else`
- 📂 File handling (`open` in append and read modes)
- ⚠️ Exception handling (`try / except`)
- 🔤 f-strings

---

## 🗂️ Project Structure

```text
atm-card-manager/
├── atm_card.py        # main program
├── Atmcard_info.txt   # saved accounts (created automatically)
├── .gitignore
└── README.md
```

---

## 🛣️ Roadmap

- [ ] Display each field on its own line using the `atm_card` class
- [ ] Ask for the PIN before showing the card details
- [ ] Add deposit and withdraw
- [ ] Store the PIN as a hash instead of plain text
- [ ] Prevent duplicate card numbers

---

## ⚠️ Disclaimer

This project is for **learning only**. Use **fake** card numbers and PINs. The PIN is saved as plain text, so never enter real card details.

---

<div align="center">

Made with ❤️ while learning Python

</div>

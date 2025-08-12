# 💳 Credit Card Checker

![JavaScript](https://img.shields.io/badge/JavaScript-Language-F7DF1E?logo=javascript&logoColor=black&style=flat)
![Node.js](https://img.shields.io/badge/Node.js-Runtime-339933?logo=nodedotjs&logoColor=white&style=flat)
![VS Code](https://img.shields.io/badge/VS_Code-Editor-007ACC?logo=visualstudiocode&logoColor=white&style=flat)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-181717?logo=github&logoColor=white&style=flat)](https://github.com/ArekKrak/credit-card-checker)

A JavaScript program that validates credit card numbers using the Luhn algorithm, identifies invalid cards, and reports the issuing companies — based on the Codecademy Credit Card Checker challenge project. This project automates the manual checking process, providing quick and reusable validation logic for multiple credit cards at once.

---

## 📜 Project Overview

Your company suspects that credit card distributors have been sending out cards with invalid numbers. While other clerks use pen and paper, you build an automated solution to validate cards and pinpoint the companies responsible for invalid ones. This program:
- Validates credit cards via the Luhn algorithm
- Finds and lists all invalid cards from a batch
- Reports unique issuing companies (Amex, Visa, Mastercard, Discover) for invalid cards
- Removes duplicates in company reporting

---

## 🛠️ Tech Stack

- JavaScript (ES6+)
- Node.js (runtime environment)
- Tools: Visual Studio Code, Git, GitHub

---

## 📂 Project Structure

```
credit-card-checker/
├── main.js        # Main program logic
└── README.md      # Project documentation
```

---

## 🚀 How to Run

1. Clone the repository:
   git clone https://github.com/ArekKrak/credit-card-checker.git
   cd credit-card-checker
2. Run with Node.js:
   Make sure Node.js is installed:
   node -v
   Run the program:
   node main.js

---

## 📊 Example Output

For the included sample data:
[ 'Visa', 'Mastercard', 'Amex', 'Discover' ]

---

## Key Concepts Demonstrated

- Implementation of the Luhn algorithm
- Array iteration using for loops
- Conditional logic for validation checks
- Data filtering to find invalid entries
- Removing duplicates using Set and spread syntax
- Mapping data to specific output categories

---

## Future Improvements

- Accept user input for card numbers
- Add validation for card length and numeric content
- Extend issuer recognition to other providers
- Create a simple front-end interface for non-technical users

---

## Acknowledgements

- Codecademy for the original Credit Card Checker challenge project
- General Luhn algorithm reference: https://en.wikipedia.org/wiki/Luhn_algorithm

---

## Contact
If you're a recruiter, mentor, or fellow developer interested in collaboration or feedback:

**Arek Krakowiak**  
[369arek12@protonmail.com](mailto:369arek12@protonmail.com)

---

Thank you for viewing this project!

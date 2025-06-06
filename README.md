rotated-roots-digit-theory
A number theory experiment testing if all digit-rotations of a perfect square are also perfect squares.
# 🔢 Rotated Roots: The Mystery of Digit-Shifted Squares

A number theory exploration by **Anthoni Raj**.

---

## ❓ Problem

Can a perfect square number (with two or more digits) have all of its digit-rotated versions also be perfect squares?

For example:
- 121 → Rotations: 121, 211, 112
- Are all of these perfect squares? (No)

### ✅ What We Did

- Collected all perfect square numbers from 10 up to a user-given number (even up to 10¹⁵ tested)
- Rotated the digits in all possible circular shifts
- Checked if **all** rotations are also perfect squares

---

## 🔍 Conjecture (Based on Testing Up to 1 Trillion+)

> There is **no perfect square number ≥ 10** such that **all of its digit rotations** are also perfect squares.

---

## 📄 How to Use

Open `index.html` in your browser.  
Enter a number (like `1000`, `1000000000000`, etc.)  
Click “Check” and see whether any perfect square passes the full rotation check.

---

## 📊 Example Output
🔢 Rotated Circle Perfect Square Checker  
10000000000000  
Check

Total perfect squares (10 ≤ n ≤ 10000000000000): 3,162,274

No perfect squares found where all rotations are perfect squares.  
Total time: 534.4 seconds
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

---

## 🧠 Observations

- The property is very **rare** (possibly impossible!)
- Even 1 crore, 10 crore, and 1 trillion ranges produce no success.
- This could be the basis of a **new number theory puzzle**.

---

## 👨‍🔬 Credits

- 💡 Invented by: **Anthoni Raj**  
- 🧠 Assisted by: ChatGPT (OpenAI)  
- 📂 Category: Number Theory / Recreational Mathematics

---

## 📖 License

This project is open source and licensed under the [MIT License](LICENSE).

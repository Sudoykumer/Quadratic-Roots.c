
```markdown
# 🧮 Quadratic Equation Solver (C Program)

This is a simple and beginner-friendly C program to
**find the roots of a quadratic equation** of the form:

```

ax² + bx + c = 0

```

It calculates:
- Two real and distinct roots
- Two real and equal roots
- Two complex (imaginary) roots

---

## 📂 Project Structure

```


````


## ✅ Features

- Takes user input for coefficients `a`, `b`, and `c`
- Validates input (e.g. checks if `a` is zero)
- Computes discriminant to determine root type
- Supports:
  - Real and distinct roots
  - Real and equal roots
  - Complex (imaginary) roots

---

## 🛠 How to Compile and Run

### 🔹 Requirements:
- A C compiler (like `gcc`)
- Terminal or command prompt

### 🔹 Steps:

1. **Clone or Download the Repository**

```bash
git clone https://github.com/your-username/quadratic-equation-solver.git
cd quadratic-equation-solver
````

2. **Compile the Program**

```bash
gcc quadratic_solver.c -o quadratic_solver -lm
```

> `-lm` is used to link the math library (`sqrt` function).

3. **Run the Program**

```bash
./quadratic_solver
```

4. **Example Input:**

```
Enter coefficient a (non-zero), b, and c: 1 -3 2
```

### ✔ Sample Output:

```
Quadratic Equation Solver: ax^2 + bx + c = 0
------------------------------------------------
Enter coefficient a (non-zero), b, and c: 1 -3 2
Discriminant (D) = 1.00
✅ Roots are real and distinct:
Root 1 = 2.00
Root 2 = 1.00
```

---

## 💡 What is a Quadratic Equation?

A quadratic equation is a second-degree polynomial equation of the form:

```
ax² + bx + c = 0
```

Where:

* `a`, `b`, and `c` are real numbers
* `a ≠ 0`
* Roots are found using the **quadratic formula**:

```
x = (-b ± √(b² - 4ac)) / 2a
```

---

## 📄 License

This project is open-source and free to use under the [MIT License](LICENSE).

---

## 👨‍💻 Author

NAME: SUDOY KUMER GHOSH

GitHub: [@Sudoykumer](https://github.com/Sudoykumer)

---

## 🙋‍♂️ Contributions

Pull requests are welcome! If you find any bugs or want to improve the code, feel free to fork and submit a PR.

```

---


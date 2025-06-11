# 🏭 Employee Indemnity Management for MOTOPROD

This C program manages **employee indemnities** for different workshops (ateliers) in a company called **MOTOPROD**. It allows you to input workshop names, responsible persons, employee details, and production data to calculate and display the total indemnities per workshop and globally.

---

## 💡 Features

- Input the number of workshops
- For each workshop:
  - Store workshop name and its responsible person
  - Register each employee and the number of parts produced
  - Apply a piece-based rate (`A`, `B`, or `C`) to calculate the indemnity
- Display:
  - A summary table per workshop
  - Total indemnity per employee
  - Total per workshop and across all workshops

---

## 🧮 Indemnity Rates

| Indice | Rate (per piece) |
|--------|------------------|
| A      | 20 DH            |
| B      | 10 DH            |
| C      | 5 DH             |

---

## 🚀 Getting Started

### Requirements

- GCC or any C compiler
- A terminal or IDE that supports C input/output

### Compilation

```bash
gcc -o motoprod motoprod.c
./motoprod

```
### 📌 Example Input Flow
Entrer le nombre des ateliers : 2
Entrer le nom d'atelier 1 : Mecanique
Entrer le nom du responsable de l'atelier 1 : Karim
Entrer le nombre des employés de l'atelier 1 : 2
...


### 📋 Output Example
![image](https://github.com/user-attachments/assets/0a827c4e-b8b8-4879-a9be-eb8e4148fb06)


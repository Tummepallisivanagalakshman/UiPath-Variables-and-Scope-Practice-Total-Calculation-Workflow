# 🧮 UiPath – Managing Variables and Arguments (Total Amount Calculation)

A simple UiPath automation project focused on understanding how variables are created, managed, and used to perform calculations within a workflow.

This project is part of hands-on practice to build a strong foundation in UiPath data handling and scope management.

---

## ✨ Project Objective

To calculate the total amount using price and quantity values and display the result, while learning how UiPath handles variables and workflow data.

---

## 🔁 Workflow Overview

1. Declare variables for `price`, `quantity`, and `total`.
2. Assign values to `price` and `quantity`.
3. Calculate the total using an Assign / Multiple Assign activity.
4. Display the calculated total using a Message Box.

---

## 📌 Workflow Logic


START

Declare variables:
    price (Int32)
    quantity (Int32)
    total (Int32)

Assign values:
    price = 500
    quantity = 2

Calculate total:
    total = price * quantity

Display:
    "Total amount: 1000"

END

UiPath_Managing_Variables_And_Arguments
│
├── Main.xaml
├── project.json
├── project.uiproj
├── entry-points.json
├── .gitignore
└── README.md


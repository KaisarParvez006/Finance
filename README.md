# 💸 C++ OOP Finance Tracker

A finance management system built using Object-Oriented Programming concepts in C++. It allows users to manage income, expenses, budgets, and provides financial summaries with smart savings recommendations.

---

## 🚀 Features

### 🔄 Transactions Management
- Record **Income** (Source & Amount)
- Record **Expenses** (Category, Amount & Date)

### 💰 Budget Management
- Set budgets for different categories
- Display allocated budgets using templates

### 📊 Financial Summary
- Total Income
- Total Expenses
- Remaining Balance

### 💡 Savings Recommendation
- Suggests saving **20%** of total income
- Warns if expenses exceed recommended limits

---

## 🧱 Object-Oriented Structure

### 📚 Class Hierarchy

- `Transaction` *(Abstract Base Class)*
  - Pure virtual method: `display()`
- `IncomeTransaction` *(Derived from Transaction)*
- `ExpenseTransaction` *(Derived from Transaction)*
- `User` – Manages all user transactions and balances
- `Budget<T>` – Template class for category-wise budget handling
- `Recommendation` – Provides smart financial tips

---

## 🔧 Concepts Used

| Concept               | Description |
|------------------------|-------------|
| **Polymorphism**       | Abstract base class with overridden methods in derived classes |
| **Templates**          | Budget class uses templates for flexibility |
| **Exception Handling** | Prevents negative/invalid transactions |
| **Input Validation**   | Utility functions for safe user input |

---

## 📁 File Structure

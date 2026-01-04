# 💰 Personal Finance CLI

> **Assigned to:** Chaitanya Sikka  
> **Difficulty:** Beginner-Intermediate  
> **Estimated Time:** 6-8 hours (1-2 hours/day for 4 days)  
> **Deadline:** January 10, 2026

---

## 📌 Project Overview

Build a command-line expense tracker! Users can add expenses, categorize them, set budgets, and view reports. All data is stored in a local SQLite database.

### Example Commands:
```bash
python finance.py add --amount 500 --category food --note "Lunch"
python finance.py list --month january
python finance.py report
python finance.py budget --category food --limit 5000
```

---

## 🎯 What You'll Learn

| You Already Know | You Will Learn |
|------------------|----------------|
| Python basics | SQLite database |
| SQL basics | Argparse for CLI arguments |
| Logic building | Tabulate for pretty tables |

---

## ✅ Tasks

- [ ] Set up SQLite database with tables (expenses, budgets)
- [ ] Learn argparse for command-line arguments
- [ ] Implement "add" command to add new expense
- [ ] Implement "list" command to show expenses (filter by date/category)
- [ ] Implement "delete" command to remove expense
- [ ] Implement "report" command showing summary by category
- [ ] Implement "budget" command to set category limits
- [ ] Warn when expense exceeds budget
- [ ] Use tabulate library for pretty output tables
- [ ] Add export to CSV feature

---

## 🌟 Bonus Challenges

- [ ] **+5 points:** Add monthly comparison (this month vs last month)
- [ ] **+10 points:** Add ASCII bar chart for category breakdown
- [ ] **+10 points:** Add recurring expenses feature
- [ ] **+5 points:** Add search functionality by note/description

---

## 📦 Deliverables

1. Working CLI expense tracker
2. All commands functional
3. Data persists in SQLite
4. Code pushed to GitHub
5. Demo video or screenshots

---

**Good luck! 🚀**

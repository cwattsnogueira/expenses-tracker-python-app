# expenses-tracker-python-app

Personal Expense Tracker — CLI App in Python
Author: Carllos Watts-Nogueira
Course: Artificial Intelligence & Machine Learning
University of San Diego / Fullstack Academy
Section: 2504-FTB-CT-AIM-PT
Due Date: May 12
Anticipated Graduation: October 2025
Project Type: Applied Data Science & Programming Exercise

Project Overview
This project is a command-line expense tracker designed to help users log, categorize, and analyze their personal spending habits. Built entirely in Python, the app enables users to manage daily expenses, set monthly budgets, monitor performance against financial goals, and persist data using CSV files.
The idea was to create a simple yet powerful CLI tool that promotes personal accountability and budget awareness — and to apply core programming concepts in a real-world challenge.

Objectives
- Add and categorize expenses with intuitive prompts
- Set monthly budgets and compare them against real expenses
- View filtered records (by period or completeness)
- Track whether budgets were exceeded or remained intact
- Edit entries and save/load all data through CSV
- Navigate via a responsive, menu-driven interface

Technologies Used
- Python 3
- Built-in modules: csv, datetime
- CLI structure using input() and formatted outputs
- Data storage in dictionaries & lists
- Persistent saving/loading with custom CSV handling
- Localization-friendly with UTF-8-SIG encoding for broader compatibility

Project Structure
├── personalexpenses.csv         # Auto-generated with expense history
├── budget.csv                   # Auto-generated with monthly budgets
├── expense_tracker.py           # Full application logic
└── README.md                    # Project description and instructions

Features Implemented
- Add expenses (with date, category, amount, description)
- View expenses with filtering by month, year, or completeness
- Edit expenses and manage data dynamically by ID
- Set budgets per month/year and track status
- Budget warning messages when spending exceeds limits
- Save and load all data using local CSV files
- Interactive menu with numbered options for all actions

Bonus Additions
- Expense & budget entry validation
- Budget summary across entire year or specific months
- Highlight months where budget was exceeded or saved
- Organized input picklists for consistent UX
- Persistent ID tracking across sessions





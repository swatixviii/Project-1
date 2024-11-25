# Budget Tracker
## Overview
The Budget Tracker is a simple Python program that helps users manage their finances by recording income and expenses. It provides features to view a summary of the current budget and detailed records of all entries.

## Features
### Add Entries:
Record income with a description.
Record expenses with a description.
### Show Summary:
Total income.
Total expenses.
Current balance (income - expenses).
### View Entries:
Displays all recorded income and expense entries in a tabular format.
### Interactive Menu:
Easy-to-use menu for navigating through the program.

## Code Structure
### Global Variables:
data: A pandas DataFrame to store entries with the following columns:
Type: Specifies whether the entry is "Income" or "Expense".
Amount: The monetary value of the entry.
Description: A brief note about the entry.
### Functions:
add_entry(entry_type, amount, description): Adds an entry (income or expense) to the DataFrame.
show_summary(): Displays the total income, total expenses, and balance.
show_entries(): Displays all entries in a tabular format.
main_menu(): Provides an interactive menu for the user to navigate the program.

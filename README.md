Rent Calculator
A professional, command-line interface (CLI) tool developed in Python to streamline the process of splitting household expenses among roommates. This script automates the calculation of shared costs, including rent, food, and electricity billing, ensuring a fair and transparent distribution of expenses.

# Core Features
# Multi-Occupancy Support: Dynamically calculates cost-sharing based on the total number of residents in a single room.
# Utility Billing Logic: Automatically computes total electricity costs by multiplying unit consumption by the specific charge per unit.
# Consolidated Expense Tracking: Aggregates rent, snacking/food orders, and utility bills into a single total amount.
# Per-Person Breakdown: Provides an instant calculation of the exact amount due from each individual.
# Calculation Logic
The application follows a structured mathematical flow to ensure accuracy:

# Electricity Cost: (Electricity Units Spent) × (Charge Per Unit)
# Grand Total: (Rent) + (Food/Snacks) + (Total Electricity Cost)
# Individual Share: (Grand Total) / (Number of Persons)
# Installation & Usage
# 1. Prerequisites: Ensure Python 3.x is installed on your local machine.
# 2. Deployment: Clone or download the rent_calculator.py file to your directory.
# 3. Execution: Run the script via the terminal using the following command:
# python rent_calculator.py
# 4. Operation: Enter the requested values at the prompts to receive the final cost breakdown.
# Technical Details
# Language: Python
# Input Handling: Standard CLI input() with integer conversion.
# Dependencies: None (Uses Python Standard Library).
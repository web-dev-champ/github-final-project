# github-final-project
Final Project for Git hub Certification
# Simple Interest Calculator

A simple command-line calculator to compute **Simple Interest** based on the given **Principal**, **Annual Rate of Interest**, and **Time Period in Years**.

---

## 🧮 Formula Used

> Simple Interest (SI) = P × T × R


Where:
- **P** = Principal Amount  
- **T** = Time Period in Years  
- **R** = Annual Rate of Interest (in decimal or percentage)

> **Note:** If rate is provided in percentage, convert it to decimal by dividing it by 100.

---



# Example usage
principal = float(input("Enter the principal amount: "))
time = float(input("Enter the time period in years: "))
rate = float(input("Enter the annual rate of interest (as a decimal, e.g., 0.05 for 5%): "))

si = calculate_simple_interest(principal, time, rate)
print(f"Simple Interest: {si}")

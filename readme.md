# 🧪 QA Automation Portfolio: Transportation on Vacation & Unit Testing

> About this repository: This project demonstrates unit testing and algorithm validation using Jest for a JavaScript application calculating car rental costs with promotional discount tiers. It also highlights a modern "Shift-Left" QA approach through extensive static code analysis and Continuous Integration (CI/CD).

![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Static Analysis](https://img.shields.io/badge/Static_Analysis-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)

## 🎯 Project Overview

This application is a Vanilla JavaScript implementation designed to calculate total car rental costs based on the number of days rented, incorporating conditional business logic and discount thresholds (e.g., long-term rental discounts).

As a QA Automation / Software Testing Engineer, my focus in this repository is to validate core algorithmic calculations, handle edge cases (such as boundary rental days), and ensure business rule accuracy through comprehensive unit testing.

## 🛠️ QA Tech Stack & Tools

* **Unit Testing:** Jest (`src/calculateRentalCost.test.js`)
* **CI/CD Pipeline:** GitHub Actions (Automated test execution on push/PR)
* **Static Code Analysis (Shift-Left QA):** ESLint, Prettier
* **Core Technologies:** Vanilla JS (ES6+)

## 📊 Test Strategy & Coverage

### 1. Unit Testing (Jest)
Located in `src/calculateRentalCost.test.js`, the unit test suite verifies:
* Accurate cost calculation for standard rental durations.
* Proper application of discount thresholds (e.g., 3+ days and 7+ days rules).
* Edge cases, boundary values, and invalid input handling.

### 2. Continuous Integration (CI/CD)
The project utilizes GitHub Actions (`.github/workflows/test.yml`) to enforce quality gates. Every commit automatically triggers a pipeline that:
* Lints the code files to catch syntax and formatting issues early.
* Runs the Jest unit test suite in a headless environment.

## 🚀 How to Run the Tests Locally

To evaluate the test scripts and static analysis tools on your local machine, follow these steps:

### 1. Environment Setup
Clone the repository and install the Node.js dependencies:
```bash
npm install

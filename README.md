# 🏦 Playwright Bank Automation Framework

A robust and scalable end-to-end automation framework built using **Playwright** and **JavaScript** following the **Page Object Model (POM)** design pattern.

This project automates common banking application workflows such as login, account validation, transactions, and other user journeys while maintaining clean, reusable, and maintainable test code.

---

# 🚀 Tech Stack

* Playwright
* JavaScript
* Node.js
* VS Code
* Git & GitHub

---

# 📁 Project Structure

```
playwright-bank-framework/
│
├── fixtures/              # Test fixtures and reusable setup
├── pages/                 # Page Object Model classes
├── test-data/             # Test data and JSON files
├── tests/                 # Test specifications
│
├── playwright.config.js   # Playwright configuration
├── package.json
└── README.md
```

---

# ✨ Framework Features

* ✅ Playwright Test Framework
* ✅ Page Object Model (POM)
* ✅ Reusable Page Classes
* ✅ Test Data Separation
* ✅ Centralized Fixtures
* ✅ Cross Browser Execution
* ✅ Easy to Maintain
* ✅ Scalable Folder Structure
* ✅ HTML Reporting
* ✅ Screenshot Support

---

# ⚙️ Prerequisites

Make sure the following are installed:

* Node.js (v18 or above recommended)
* Visual Studio Code
* Git

Verify installation

```bash
node -v
npm -v
```

---

# 📥 Clone Repository

```bash
git clone https://github.com/parasjangra-sf/playwright-bank-framework.git
```

Move into project

```bash
cd playwright-bank-framework
```

---

# 📦 Install Dependencies

```bash
npm install
```

Install Playwright browsers

```bash
npx playwright install
```

---

# ▶️ Running Tests

Run all tests

```bash
npx playwright test
```

Run a single test

```bash
npx playwright test tests/<test-file>.spec.js
```

Run in headed mode

```bash
npx playwright test --headed
```

Run on Chromium

```bash
npx playwright test --project=chromium
```

Run on Firefox

```bash
npx playwright test --project=firefox
```

Run on WebKit

```bash
npx playwright test --project=webkit
```

Debug mode

```bash
npx playwright test --debug
```

---

# 📊 Test Reports

After execution

```bash
npx playwright show-report
```

Reports include:

* HTML Report
* Failed Test Details
* Execution Summary

---

# 📸 Failure Evidence

The framework supports:

* Screenshots on Failure
* Playwright Trace
* Console Logs

To view traces

```bash
npx playwright show-trace trace.zip
```

---

# 🏗 Framework Design

This framework follows the **Page Object Model (POM)** architecture.

Benefits:

* Better code reusability
* Easy maintenance
* Less duplicate code
* Clean test scripts
* Improved scalability

---

# 📂 Folder Description

### fixtures/

Contains reusable fixtures and common setup used across tests.

### pages/

Contains Page Object classes with reusable page actions.

### test-data/

Stores reusable test data, JSON files, and constants.

### tests/

Contains all Playwright test cases.

---

# 🌍 Browser Support

* Chromium
* Firefox
* WebKit

---

# 🔄 Future Enhancements

* API Testing Integration
* Environment Configuration (.env)
* CI/CD using GitHub Actions
* Allure Reporting
* Docker Support
* Parallel Test Optimization
* Jenkins Integration

---

# 👨‍💻 Author

**Paras Jangra**

GitHub:
https://github.com/parasjangra-sf

---

# ⭐ If you like this project

If this repository helps you, consider giving it a **Star ⭐** on GitHub.

---

# 📄 License

This project is licensed under the **MIT License**.

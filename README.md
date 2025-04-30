# 🧪 Cypress E2E Test 

Automated end-to-end tests using Cypress and TypeScript for the [SauceDemo](https://www.saucedemo.com) mock e-commerce website.  
Perfect for showcasing QA skills in a realistic testing scenario.

---

## 🔧 Tech Stack

- ✅ Cypress 13+
- ✅ TypeScript
- ✅ GitHub Actions (CI/CD)
- ✅ Mock site: saucedemo.com

---

## 📂 Test Coverage

| Feature         | Test Cases                                      |
|----------------|--------------------------------------------------|
| Login           | Valid & Invalid credentials                     |
| Add to Cart     | Add single & multiple items                     |
| Checkout        | Successful flow & form validation errors        |
| Logout          | Logout and Redirect login page                  |
| Product-Sort    | sort product by span and check the values       |

---

## 🚀 How to Run Tests

# Install dependencies
npm install

# Open Cypress test runner
npx cypress open

# Run all tests headlessly
npx cypress run

## 📂 Project Structure

ecommerce-cypress-tests/ ├── cypress/ │ └── e2e/ │ ├── login.cy.ts │ ├── search.cy.ts │ └── checkout.cy.ts ├── test-cases.xlsx # Manual test cases ├── cypress.config.ts ├── package.json └── README.md


---

## 🛠️ How to Install & Run Tests

### 1. Clone the Repository

git clone https://github.com/yourusername/ecommerce-cypress-tests.git
cd ecommerce-cypress-tests
2. Install Dependencies
Make sure you have Node.js v16+ installed.

npm install
3. Run Cypress Tests (Headed or Headless)

# Headed mode (interactive)
npx cypress open

# Headless mode
npx cypress run
📄 Manual Test Cases
Manual test cases are documented in test-cases.xlsx, covering both positive and negative scenarios.

🐞 Bug Reports (Optional)
This project also includes sample bug observations, documented in GitHub Issues (if available).

📌 Notes
This project was created as part of a career shift from creative media (video editing) to software testing.
It demonstrates basic QA workflow including test design, execution, and reporting using modern tools.

📫 Contact
Feel free to connect via GitHub or LinkedIn. Feedback is welcome!

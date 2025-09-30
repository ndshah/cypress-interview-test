# Cypress Interview Test – Candidate Instructions

## Objective
The goal of this test is to evaluate your automation skills using **Cypress**.  
You will automate a basic **SauceDemo** scenario: login, add a product to the cart, and optionally extend to checkout.

---

## 🔹 Setup Instructions

1. **Clone the repo**
```bash
git clone https://github.com/YOUR_USERNAME/cypress-interview-test.git
cd cypress-interview-test
Install dependencies

bash
Copy code
npm install
Open Cypress test runner

bash
Copy code
npx cypress open
Choose a browser (Chrome recommended).

Tests can be run headed (UI visible) or headless using npx cypress run.

🔹 Tasks for Candidates
Task 1: Login & Verification
Visit SauceDemo.

Login using:

Username: standard_user

Password: secret_sauce

Verify that you are redirected to /inventory.html.

Verify that the products page shows 6 products.

Task 2: Add Product to Cart
Click “Add to cart” for the first product.

Verify the cart icon shows 1 item.

Open cart page and verify the product is listed.

Task 3: Checkout Flow (Optional / Advanced)
Click Checkout.

Fill in First Name, Last Name, and Postal Code.

Click Continue → verify summary page appears.

Click Finish → verify “THANK YOU FOR YOUR ORDER” appears.

Note: Completing Task 1 & 2 is sufficient to evaluate your skills. Task 3 is optional for strong candidates.

🔹 Guidelines
Use Cypress best practices (e.g., .should(), .then(), aliases).

Use stable selectors (data-test recommended).

Ensure your code is readable and maintainable.

Avoid hardcoding waits (cy.wait) unless necessary.

🔹 Submission
Push your test script(s) to a separate branch and share the branch name.

Ensure the repo runs successfully in Cypress without additional setup.
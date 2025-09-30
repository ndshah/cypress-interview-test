
# Cypress Interview Test – Candidate Instructions

## Objective

The goal of this test is to evaluate your automation skills using **Cypress**.

You will automate a basic **SauceDemo** scenario: login, add a product to the cart, and optionally extend to checkout.
  

## 🔹 Setup Instructions

  
### Clone the repo
```
git clone https://github.com/ndshah/cypress-interview-test
cd cypress-interview-test
```
### Install  dependencies
```
npm install
```
### Open  Cypress  test  runner
```
npx cypress open
```
## 🔹  Tasks  for  Candidates

**Task  1:**  Login & Verification

1. Visit  SauceDemo. https://www.saucedemo.com/
2. Login  using:
Username:  `standard_user`
Password:  `secret_sauce`
3. Verify  that  you  are  redirected  to  `/inventory.html`.
4. Verify  that  the  products  page  shows  6  products.

**Task  2:**  Add  Product  to  Cart

1. Click  “Add  to  cart”  for  the  first  product.
2. Verify  the  cart  icon  shows  1  item.
3. Open  cart  page  and  verify  the  product  is  listed.

**Task  3:**  Checkout  Flow 
1. Click  Checkout.
2. Fill  in  First  Name,  Last  Name,  and  Postal  Code.
3. Click  Continue  →  verify  summary  page  appears.
4. Click  Finish  →  verify  “THANK  YOU  FOR  YOUR  ORDER”  appears.

# 🔹  Guidelines

1. Use  Cypress  best  practices (e.g., .should(),  .then(),  aliases).
2. Use  stable  selectors (data-test recommended).
3. Ensure  your  code  is  readable  and  maintainable.
4. Avoid  hardcoding  waits (cy.wait) unless necessary.

# 🔹  Submission
- Push  your  test  script(s) to  a  separate  branch  and  share  the  branch  name.
- Ensure  the  repo  runs  successfully  in  Cypress  without  additional  setup.

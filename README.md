# 🧪 Manual Testing Projects

This repository contains a collection of **manual testing projects** based on sample user stories.  
The goal is to demonstrate requirement analysis, test design techniques, and documentation of test cases.

---

## 📂 Projects Included

### 1. Credit Card Discounts
**User Story:**  
_As a customer, I want to open a credit card account so that I can receive discounts on my purchases._

**Acceptance Criteria:**
1. New customers receive **15% discount** on all purchases today.  
2. Existing customers with a loyalty card receive **10% discount**.  
3. Customers with a coupon receive **20% discount** (not combinable with new customer discount).  
4. Discounts are cumulative if applicable (e.g., Loyalty + Coupon = 30%).  

**Deliverables:**
- [Decision Table](DecisionTable_CreditCardDiscounts.csv) (8 scenarios compressed into 5 rules).  
- [Test Cases](TestCases_CreditCardDiscounts.csv) (9 detailed cases mapped to rules).  

---

### 2. Add to Cart
**User Story:**  
_As a customer, I want to add a product to my cart so that I can purchase it._

**Acceptance Criteria:**
1. Product must have at least one item in stock.  
2. If product is out of stock, user cannot add it.  
3. User must be logged in to add to cart.  
4. On adding, a message should confirm the item is added.  
5. The confirmation message should contain a **valid link** redirecting to the cart.  

**Deliverables:**
- [Traceability Table](TraceabilityTable_AddToCart.csv) mapping acceptance criteria to rules.  
- [Test Cases](TestCases_AddToCart.csv) including both valid and invalid scenarios.  

---

### 3. Contact Us
**User Story:**  
_As a customer, I want to contact the website about a problem with my product._

**Acceptance Criteria:**
1. Email field is **mandatory** and must be valid (name@domain.xyz).  
2. Contact name is **mandatory**.  
3. Message field is **mandatory** and must not exceed 500 characters.  

**Deliverables:**
- [Test Cases](TestCases_ContactUs.csv) covering input validation (positive and negative cases).  

---

## 🚀 Key Skills Demonstrated
- Requirement Analysis & Acceptance Criteria Breakdown  
- Decision Table Testing Technique  
- Test Case Design & Documentation  
- Requirement Traceability Matrix (RTM)  
- Positive & Negative Scenario Coverage  

---

## 📎 How to Use
- Open the `.csv` files directly on GitHub to view them as tables.  
- Download `.xlsx` versions if you prefer working in Excel.  
- Each Test Case ID includes a mapping to the corresponding requirement (e.g., `TC1-R1`).  

---

## 👨‍💻 Author
**Ramy Kotb**  
- [GitHub Profile](https://github.com/ramy2m)  
- [LinkedIn](https://www.linkedin.com/ramy2m)

---

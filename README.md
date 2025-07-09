Welcome! This is a technical challenge for QA Engineer candidates applying to Perch.

---

## 🎯 Objective

Your mission is to:

- Create as many **test cases** as possible for the different pages of this ecommerce application.
- Detect and clearly document **bugs, broken flows, or inconsistencies**.
- Suggest **functional or usability improvements** where relevant.

---

## 🧰 Technologies to Use

You are expected to complete this challenge using the following technologies:

- ✅ Cypress  
- ✅ Cucumber (Gherkin syntax)  
- ✅ JavaScript

---

## 🛒 Application Overview

This is an e-commerce web application where users can browse products, purchase them, and view their profile and order history. The application consists of the following key pages:

🔹 **Home Page** (`/`)  
- Displays a list of available products (name and price)  
- Each product links to its individual Product Page  
- Includes sorting functionality  

🔹 **Product Page** (`/product/:id`)  
- Shows details of a specific product: name, price, description  
- Allows selection of quantity  
- Button to add the product to the cart  

🔹 **Cart Page** (`/cart`)  
- Shows products added to the cart  
- Allows modifying quantity or removing items  
- Proceeds to checkout  

🔹 **Address Page** (`/checkout/address`)  
- Collects shipping and personal information  
- Fields for name, address, postal code, and phone number  

🔹 **Payment Page** (`/checkout/payment`)  
- Accepts credit card information  
- Validates card number, expiration date, and name  

🔹 **Success Page** (`/checkout/success`)  
- Confirmation screen after successful order placement  

🔹 **Profile Page** (`/profile`)  
- Displays user information  
- Shows order history with details for each purchase  

---

## 📋 Submission Instructions

1. **Clone the project**
    ```bash
    git clone https://github.com/estefaniaMiceliQA/perch-qa-ecommerce-challenge.git
    ```

3. **Create a new public repository in your GitHub account and push your changes there**

4. **Notify us**
   - Share the public repository URL with us by email once you're done

---

## ✅ Evaluation Criteria

We will evaluate your submission based on:

- Coverage and relevance of test cases
- Accuracy in identifying issues
- Communication of findings
- Code and folder organization

---

## 🛠️ Step-by-Step Guide

1. **Clone the project**

    ```bash
    git clone https://github.com/estefaniaMiceliQA/perch-qa-ecommerce-challenge.git
    ```

3. **Navigate to the project folder**

   ```bash
   cd perch-qa-ecommerce-challenge
   ```

4. **Install project dependencies using Yarn**

   ```bash
   yarn
   ```

5. **Start the web application**

   ```bash
   yarn start
   ```

6. **Run the tests**
  
   To open Cypress in interactive mode:
   
   ```bash
   yarn cypress:open
    ```

   To open Cypress in headless mode:

    ```bash
   yarn cypress run
    ```
    
   OR
   
    ```bash
   yarn test
    ```
---
Good luck! If you have any questions, feel free to reach out before starting the challenge.

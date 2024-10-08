# Loan EMI Calculator

This project is a simple **Loan EMI (Equated Monthly Installment) Calculator** built using **HTML**, **CSS**, and **JavaScript**. It allows users to calculate their EMI, total interest, and total payment based on the loan amount, interest rate, and loan tenure (in years or months).

## Features

- **Input fields** for loan amount, interest rate, and loan tenure.
- **Radio buttons** to select loan tenure as yearly or monthly.
- Calculates and displays:
  - EMI (₹)
  - Total interest (₹)
  - Total payment (₹)
- Simple, clean design with a custom CSS stylesheet and background image.

## Technologies Used

- **HTML5**: For structuring the content and input forms.
- **CSS3**: For styling the layout, including form inputs and output display, using a responsive design with custom fonts and background.
- **JavaScript**: To handle user input, validate values, and perform the EMI calculation using the following formula:

 EMI = [P * r * (1 + r)^n] / [(1 + r)^n - 1]
Where:
- `P` = Loan Amount
- `r` = Monthly interest rate (Annual interest rate divided by 12)
- `n` = Loan tenure in months

## Project Structure

- **HTML**: The structure of the form and output display is defined in the `index.html` file.
- **CSS**: The design and layout are styled in the `css/style.css` file.
- **JavaScript**: The calculations and event handling logic are included in the `js/script.js` file.

## Usage

1. Enter the loan amount in the **Loan Amount (₹)** field.
2. Enter the interest rate in the **Interest Rate (%)** field.
3. Enter the loan tenure and select whether it is in **years** or **months**.
4. Click on the **Calculate** button to display the calculated EMI, total interest, and total payment.


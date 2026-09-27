# Shop Manager – Desktop POS & Inventory System

A desktop application for small shops to manage products, barcodes, customer invoices, returns, expenses, and profit calculation.  
Built with **React, Node.js, and SQLite** as an offline PC application.

## Features

- **Product Management**
  - Add, edit, and delete products
  - Categories, prices, stock quantity
  - Barcode generation and barcode-based search

- **Barcode Support**
  - Generate and print barcodes for products
  - Search products quickly by scanning barcode

- **Customer Invoices**
  - Create invoices with multiple products
  - Automatic total calculation
  - Print or save invoice

- **Returns**
  - Process customer product returns
  - Automatically update stock
  - Adjust sales and profit calculations

- **Shop Expenses**
  - Record expenses such as rent, electricity, water, salaries, etc.
  - Deduct expenses from profit automatically

- **Profit Reports**
  - Calculate net profit = sales − returns − expenses
  - Daily, monthly, and custom reports

- **User Roles**
  - **Admin**: full access to products, users, expenses, reports, and settings
  - **Cashier**: limited access to sales, invoices, and returns only

- **Offline Desktop App**
  - Works without internet
  - Local SQLite database
  - Fast and lightweight for daily shop use

## Tech Stack

- **Frontend:** React
- **Backend:** Node.js
- **Database:** SQLite
- **Desktop:** Electron *(remove if you used another desktop wrapper)*



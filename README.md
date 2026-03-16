# Fast Food Restaurant — Order Management POS System
A complete, professional Point of Sale system for restaurants and fast food businesses. Built with Node.js, PostgreSQL, and React — runs locally on your own PC.
> This is not a web application. Every restaurant download and runs it on their own machine with their own private database.

## Overview
This system covers the full restaurant workflow — from taking orders at the table, sending them to the kitchen, tracking preparation status, and collecting payment — all in one place.

## Features
| Module             | Description                                                                        |
|---                 |---                                                                                 |
| POS Terminal       | Table-wise order taking with live cart and payment                                 |
| Kitchen Display    | Real-time order queue — Incoming, Preparing, Ready                                 |
| Order Management   | Full order history with status and payment tracking                                |
| Menu Manager       | Add and edit products with image, price, and category                              |
| Payment System     | Cash, Card, Mobile Wallets, and Bank Transfer                                      |
| Dashboard          | Revenue charts, top items, and order statistics                                    |
| Staff Management   | Add staff with assigned roles                                                      |
| Table Manager      | Configure tables with custom seating capacity                                      |
| Notifications      | Real-time alerts for orders, payments, and kitchen updates                         |
| Backup and Restore | Export full data as JSON, restore on any machine                                   |
| Bank Support       | 30+ Pakistani banks and mobile wallets (HBL, Meezan, Easypaisa, JazzCash and more) |

## Tech Stack
Frontend : HTML, React.js, Chart.js  
Backend : Node.js, Express.js  
Database : PostgreSQL with Prisma ORM  
Real-time : Socket.io  
Authentication : JWT

## Getting Started
This system runs locally on your computer. Each restaurant gets their own private installation.

Steps:
1. Download the ZIP file from this repository
   (Green "Code" button → "Download ZIP")
2. Extract the ZIP to any folder on your PC
3. Open `SETUP_GUIDE.html` from inside the extracted folder
4. Follow the guide — it walks you through everything:
   - Installing Node.js
   - Installing PostgreSQL
   - Configuring the database
   - Starting the server
   - Opening the application
The setup guide includes step-by-step instructions and a troubleshooting section for common errors.

## Default Login
```
Restaurant Name : The Grand Table
Password        : admin123
```
Both can be changed from the Settings page after first login.

## Project Structure
```
restaurant-pos/
├── backend/
│   ├── src/
│   │   ├── routes/         API endpoints
│   │   ├── middleware/      JWT authentication
│   │   └── server.js        Main entry point
│   ├── prisma/
│   │   └── schema.prisma   Database schema
│   ├── .env.example        Environment variables template
│   └── package.json
├── frontend/
│   └── index.html          Complete frontend application
└── SETUP_GUIDE.html        Full installation guide
```

## Suitable For
- Fast food restaurants
- Pizza and burger shops
- Cafes and coffee shops
- Food courts
- BBQ restaurants and dhabas
- Any food business needing a simple local POS

## Important
- Runs fully offline — no internet required after setup
- All data stays on your own machine
- Nothing is sent to any external server
- Compatible with Windows 10 and Windows 11

## Support
If you run into any issues during setup, the `SETUP_GUIDE.html` file covers the most common errors and their solutions.
*Professional Restaurant POS System — Built with Node.js and PostgreSQL*

# 🍕 FoodHub — Online Food Ordering Website

FoodHub is a responsive food ordering website where users can explore food items, manage their shopping cart, and proceed to checkout. Built with HTML, CSS, and JavaScript, the project demonstrates an interactive food ordering experience with an eSewa test payment gateway.

## ✨ Features

- **Food Categories:** Browse pizza, burgers, and coffee.
- **Interactive Menu:** View food images, descriptions, and prices in Nepalese rupees.
- **Shopping Cart:** Add items, adjust quantities, remove items, and calculate the total.
- **Dark Mode:** Switch between light and dark themes.
- **Checkout Interface:** Enter customer details and special instructions.
- **eSewa Sandbox Integration:** Test the payment flow using eSewa's test environment.
- **Manual Payment Flow:** Demonstrates a manual eSewa transfer confirmation interface.
- **Admin Dashboard Preview:** Displays menu item count, cart item count, and a revenue figure based on the current cart.
- **Responsive Design:** Adapts the layout to different screen sizes.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- Font Awesome
- Google Fonts (Inter)
- CryptoJS for HMAC-SHA256 payment signature generation
- eSewa ePay v2 test gateway

## 📂 Project Structure

```text
FoodHub/
├── index.html
└── README.md
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- An internet connection for externally hosted fonts, icons, food images, and the eSewa test gateway

### Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/bishalkshah70-art/FoodHub.git
   ```

2. Open the project folder:

   ```bash
   cd FoodHub
   ```

3. Open `index.html` in your browser, or use the Live Server extension in Visual Studio Code.

## 💳 Payment Information

FoodHub demonstrates an eSewa sandbox payment flow for development and testing.

- The gateway uses the eSewa test product code.
- Sandbox payments are intended for testing, not collecting real payments.
- The manual transfer option demonstrates an order confirmation interface; it does not independently verify whether a payment was received.
- Real payment processing requires appropriate merchant credentials, secure server-side signature generation, and server-side payment verification.

**Security note:** Do not publish personal wallet details, real payment credentials, or private secrets in a public repository. Keep production payment operations on a secure backend.

## ⚠️ Project Limitations

This project is a front-end demonstration. It does not currently provide a persistent database, user authentication, server-side order management, or a production-ready administrative system. Cart data and dashboard figures are maintained in the browser.

## 🔮 Future Improvements

- Add a backend API and database for menu items and orders.
- Implement customer accounts and order history.
- Add search, sorting, and more food categories.
- Integrate verified production payments.
- Build an administrator dashboard with authentication.
- Add order status tracking and delivery management.

## 🎯 Learning Objectives

This project explores DOM manipulation, event handling, responsive layouts, shopping cart logic, dynamic calculations, theme switching, and payment gateway integration concepts.

## 👨‍💻 Author

**bishalkshah70-art**

GitHub: [@bishalkshah70-art](https://github.com/bishalkshah70-art)

---

If you find this project useful, consider giving the repository a ⭐ on GitHub.

# ASC Store Manager

**ASC Store Manager** is a modern, efficient, and user-friendly Point of Sale (POS) and Inventory Management System designed specifically for the **Ardh Sainik Canteen (JAJAULI)**. 

Built with **React** and **Vite**, this application offers a premium "Glassmorphism" UI, ensuring a seamless experience for billing, stock tracking, and sales monitoring.

> **Developed by:** Akash Pandey

---

## 🚀 Key Features

### 🛒 Billing & POS
-   **Fast Checkout:** Support for Barcode Scanning and manual product search.
-   **Cart Management:** Real-time total calculation, tax (GST) handling, and stock validation.
-   **Smart Receipts:** Generates professional, print-ready invoices (Envelope Size: 105mm x 241mm) with custom branding.
-   **Sound Feedback:** Audio cues for success, errors (out of stock), and interactions.

### 📦 Inventory Management
-   **Product Tracking:** Add, Edit, and Delete products with ease.
-   **Stock Control:** Auto-deduction of stock upon sale; safeguards against overselling.
-   **GST Integration:** Built-in GST percentage fields for accurate tax calculations.

### 📊 Dashboard & Analytics
-   **Sales Overview:** Visual charts and KPI cards showing daily sales and profit.
-   **Real-time Data:** Instant updates as transactions occur.

### 📝 Transaction History
-   **Detailed Records:** View complete history of all past bills.
-   **Return System:** sophisticated return logic allowing partial or full returns of items.
-   **Record Management:** Ability to permanently delete old or fully returned transaction records.

### 💾 Data Persistence
-   **Local Storage:** All data (Inventory, Transactions, Cart) is saved locally on the device, ensuring no data loss on page refreshes.

---

## 🛠️ Tech Stack

-   **Frontend Framework:** [React 19](https://react.dev/)
-   **Build Tool:** [Vite](https://vitejs.dev/)
-   **Styling:** Modern CSS3 with Glassmorphism aesthetic.
-   **Icons:** [Lucide React](https://lucide.dev/)
-   **Charts:** [Chart.js](https://www.chartjs.org/)
-   **State Management:** React Context API

---

## ⚡ Getting Started

Follow these steps to set up the project locally on your machine.

### Prerequisites
-   Node.js (v16 or higher)
-   npm (Node Package Manager)

### Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/your-username/asc-store-manager.git
    cd asc-store-manager
    ```

2.  **Install Dependencies**
    ```bash
    npm install
    ```

3.  **Run Development Server**
    ```bash
    npm run dev
    ```
    The app will open at `http://localhost:5173`.

### Building for Production
To create an optimized build for deployment:
```bash
npm run build
```

---

## 🖨️ Printing Setup
This app is optimized for a specific thermal/receipt printer size.
-   **Paper Size:** 105mm x 241mm (Envelope)
-   **Margins:** 5mm
-   **Layout:** Portrait

---

## 🤝 Contributing
1.  Fork the repository.
2.  Create your feature branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

---

## 📄 License
This project is proprietary software developed for Ardh Sainik Canteen.

**© 2025 Akash Pandey. All Rights Reserved.**

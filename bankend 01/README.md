# BankEase – NextGen Net Banking Frontend

A modern, responsive, high-fidelity **NextGen Net Banking frontend prototype** crafted with **React.js + JavaScript (ES6+)**, **Vite**, **Tailwind CSS**, **React Router DOM**, **React Icons**, and **Recharts**.

---

## 🎨 Color Palette

Built strictly with the official **BankEase** color specification:

* **Primary Blue:** `#2563EB`
* **Dark Blue:** `#1E3A8A`
* **Deep Navy:** `#0F172A`
* **Secondary Blue:** `#3B82F6`
* **Light Blue:** `#EFF6FF`
* **Blue Border:** `#BFDBFE`
* **Main Background:** `#F8FAFC`
* **Card Background:** `#FFFFFF`
* **Sidebar:** `#0F172A`
* **Primary Text:** `#0F172A`
* **Secondary Text:** `#64748B`
* **Muted Text:** `#94A3B8`
* **Success:** `#16A34A`
* **Warning:** `#F59E0B`
* **Danger:** `#DC2626`

---

## 🚀 Getting Started

### Prerequisites
* Node.js (v18+ recommended)
* npm

### Running the App

```bash
# Navigate to the project directory
cd D:\Bankease

# Start the Vite development server
npm run dev
```

The application will be available at **`http://localhost:3000`** (or next available port).

To produce an optimized production bundle:
```bash
npm run build
```

---

## 🏦 Application Pages & Features

| Route | Page | Description |
| :--- | :--- | :--- |
| `/login` | **Login** | Premium split login page with security branding, illustration, client validation, show/hide password, and forgot password modal. |
| `/account` | **Account Dashboard** | Account overview with balance card (₹84,250.50), copyable account number, balance hide/reveal, 5 quick action cards, Recharts multi-metric graph (Income, Expenses, Transfers), and recent 5 transactions. |
| `/transactions` | **Transactions** | Comprehensive transactions ledger with real-time search, type (Credit/Debit), status, date period filters, sorting, responsive table, pagination, and transaction details modal. |
| `/payments` | **Payments & Transfers** | 8 payment service cards (Money Transfer, UPI, Electricity, Water, Internet, Mobile Recharge, Gas, Credit Card) with bill payment modals, interactive money transfer with confirmation step & success animation, plus Beneficiary management (Add, Edit, Delete). |
| `/notifications` | **Notifications** | Filterable notifications (Transaction, Security, Payment, Warning, Unread), unread counter badges, mark as read, mark all as read, and delete. |
| `/fraud-help` | **Fraud & Help** | Emergency controls (instant Debit Card lock, Net Banking account lock, suspicious activity flags), Fraud Report submission form with case ID generation, 6 FAQ accordions, and 4 support cards. |
| `/profile` | **Profile** | User profile (Siddharth Rawat, BE102938), phone reveal/mask toggle, interactive edit profile modal, change password modal, and security settings. |

---

## 💻 Demo Credentials

* **Customer ID / Email:** `BE102938` or `siddharth@example.com`
* **Password:** `bankease123` (or any 6+ character password)

---

## 📱 Responsive Layouts

* **Desktop:** Fixed dark navy sidebar (`#0F172A`), top navbar with notification dropdown and user menu, and main content area.
* **Tablet:** Collapsible sidebar with backdrop drawer and responsive cards.
* **Mobile:** Top bar + bottom navigation bar with active icon states and notification badge.

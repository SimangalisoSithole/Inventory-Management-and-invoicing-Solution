# TNO Machinery Hire - Management Portal

A comprehensive, cloud-based fleet management and invoicing portal custom-built for the heavy machinery sector. Engineered by Smiiso Tech Solutions.

## 🚀 Features
* **Secure Authentication:** Firebase-backed employee login.
* **Live Dashboard:** Real-time KPI tracking for outstanding balances, monthly revenue, and active equipment on hire.
* **Dynamic Invoice Generator:** Auto-populates line items from the database, calculates totals, and generates professional PDF invoices natively.
* **Smart Asset Scanner:** Built-in QR code reader to instantly check out machinery to clients or return them to the yard.
* **Customer Ledger:** Tracks total client spend and current outstanding balances.

## 🛠️ Tech Stack
* **Frontend:** HTML5, CSS3 (Custom UI/UX), JavaScript (ES6+).
* **Backend / Database:** Firebase Authentication & Cloud Firestore.
* **Libraries:** `html5-qrcode` (Scanner), `jsPDF` & `AutoTable` (Invoice generation).

## 🔒 Security Architecture
* **Frontend:** Cross-Site Scripting (XSS) is mitigated via strict DOM sanitization (`escapeHTML`) before any database queries are injected into the UI. 
* **Backend:** Data integrity is enforced via Firebase Security Rules, restricting database read/write access exclusively to authenticated JSON Web Tokens (JWT).

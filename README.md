# 🏥 MediProcure — Level 5 Hospital ERP System

A comprehensive hospital procurement management system built with React, TypeScript, and Tailwind CSS.

## ✨ Features

### 📊 Dashboard
- Real-time KPI cards (Budget, Spending, Orders, Suppliers, Savings Rate, Pending Orders)
- Monthly spending trend vs budget (Area Chart)
- Category spend breakdown (Pie Chart)
- Monthly order volume (Bar Chart)
- Recent purchase orders summary
- Active alerts panel

### 🛒 Procurement
- Full procurement workflow pipeline (Requisition → Approval → Processing → Delivery)
- Pending approvals with one-click approve/reject
- Category-wise procurement breakdown chart

### 📋 Purchase Orders
- Full CRUD with search, filter by status
- Priority indicators (High/Medium/Low)
- One-click approve/reject for pending orders
- Detailed order view modal

### 📦 Inventory
- Stock level visualization with progress bars
- Low stock / out-of-stock alerts
- Filter by category and status
- One-click reorder

### 👥 Suppliers
- Grid and table view toggle
- Supplier rating, compliance score, and lead time
- Contact management

### 💊 Pharmacy
- Drug-specific inventory with expiry tracking
- Emergency order support for out-of-stock drugs

### 🔬 Equipment
- Medical equipment tracking with service schedules
- Asset valuation
- Maintenance requests

### 👤 Patients
- Patient-linked supply consumption tracking
- Cost per patient analytics

### 💰 Finance
- Budget vs spending overview
- Department-level budget utilization
- Transaction history
- Annual spending trend

### 👨‍💼 Staff
- Staff profiles with department and salary info
- Active/Leave status

### 📈 Reports & Analytics
- Multi-chart analytics dashboard
- Supplier performance radar chart
- Top suppliers by spend
- PDF export capability

### 🔔 Alerts
- Critical/Warning/Info/Success alert classification
- Resolve and dismiss functionality

### ⚙️ Settings
- Profile management
- Notification preferences
- Security (password change)
- Regional settings (currency, language)
- System information

## 🚀 Getting Started

```bash
# Install dependencies
npm install

# Copy environment file
cp .env.example .env

# Add your Supabase credentials to .env

# Start development server
npm run dev
```

## 🏗️ Tech Stack

- **Frontend**: React 18 + TypeScript
- **Routing**: React Router v6
- **Styling**: Tailwind CSS + shadcn/ui
- **Charts**: Recharts
- **State**: TanStack Query
- **Backend**: Supabase (PostgreSQL)
- **Build**: Vite

## 📁 Project Structure

```
src/
├── components/
│   ├── layout/         # Layout, sidebar, topbar
│   ├── dashboard/      # Reusable dashboard components
│   └── ui/             # shadcn/ui components
├── data/               # Mock data
├── lib/                # Utilities
├── pages/              # All page components
└── App.tsx             # Routes
```

## 🔐 Environment Variables

| Variable | Description |
|---|---|
| `VITE_SUPABASE_URL` | Supabase project URL |
| `VITE_SUPABASE_PUBLISHABLE_KEY` | Supabase anon key |
| `VITE_SUPABASE_PROJECT_ID` | Supabase project ID |

---

Built with ❤️ for Level 5 Hospital Procurement Management

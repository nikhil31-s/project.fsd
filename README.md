# DevAdmin - Full Stack Dashboard

A comprehensive administrative dashboard designed to demonstrate Full Stack Developer capabilities, featuring CRUD operations, data visualization, and simulated API integrations.

![Dashboard Preview](https://replit.com/public/images/opengraph.png)

## 🚀 Overview

This project is a high-fidelity frontend prototype built to simulate a Python (Django) + PostgreSQL stack. It demonstrates:
- **CRUD Operations**: Create, Read, Update, and Delete resources in the "Resources" tab.
- **Data Visualization**: Real-time traffic analysis using interactive charts.
- **API Integration**: Management of API keys and external service connections (Stripe, Slack).
- **Responsive Design**: Fully responsive layout using Tailwind CSS.

## 🛠️ Tech Stack

- **Frontend**: React 18, TypeScript, Vite
- **Styling**: Tailwind CSS v4, Shadcn/UI (Radix Primitives)
- **Routing**: Wouter
- **Charts**: Recharts
- **Icons**: Lucide React
- **State Management**: React Query

## 📦 Setup & Installation

1. **Clone the repository** (if applicable) or open in Replit.
2. **Install dependencies**:
   ```bash
   npm install
   ```

## 🏃‍♂️ Running the Application

To start the development server:

```bash
npm run dev:client
```

The application will be available at `http://0.0.0.0:5000`.

## 🧪 How to Test

### 1. Dashboard Overview
- Navigate to the **Dashboard** page.
- Verify that the **Activity Chart** renders and displays traffic data.
- Check the **System Health** indicators.

### 2. CRUD Functionality (Resources)
- Navigate to the **Resources** page.
- **Create**: Click the "**+ Add Resource**" button. A new row should appear in the table (simulated).
- **Read**: View the list of infrastructure resources in the table.
- **Update**: (Visual only) Status badges indicate the state of resources.
- **Delete**: Click the three dots `...` on a row and select "**Delete resource**". The row will be removed.

### 3. API Integrations
- Navigate to the **Integrations** page.
- Toggle switches for external services (Stripe, Slack).
- View simulated API keys.

## 📝 Notes

This is a **frontend-only mockup**. Data persistence is handled via local React state and will reset upon page reload. In a full production environment, this would connect to a Django backend API serving data from a PostgreSQL database.

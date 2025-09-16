# React Next.js Sensor Management UI

This project is a **frontend interface** built with **React (Next.js)** to display and manage sensor data.  
It connects to the backend API (FastAPI) and provides a user-friendly way to view alerts and sensor activity.

---

## 🚀 Features
- **Sensor Alerts**
  - List all alerts from `sensor_alerts` table
  - Delete alert entries from the interface
  - Hover effects for better user experience
- **Sensor Activity**
  - Show only the **latest activity timestamp** for each sensor
  - Easily switch between *Alerts* and *Activity* tabs
  - Modern UI with hover animations
- **Responsive UI** using Tailwind CSS

---

## 📂 Project Structure
```
next-ui/
├── app/
│   ├── page.js        # Main page with tab navigation (Alerts & Activity)
│   ├── layout.js      # Root layout for Next.js
│   └── globals.css    # Global styling (Tailwind)
├── lib/
│   └── api.js         # API functions (fetch alerts, delete alerts, fetch activity)
├── package.json       # Project dependencies
├── next.config.mjs    # Next.js configuration
└── README.md          # Project documentation
```

---

## ⚙️ Requirements
- Node.js (>= 18)
- npm or yarn

---

## 🛠️ Installation & Running
1. Clone the repository:
   ```bash
   git clone https://github.com/aliefecakir/ReactNextjsUI.git
   cd ReactNextjsUI/next-ui
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the development server:
   ```bash
   npm run dev
   ```

4. Open in browser:
   ```
   http://localhost:3000
   ```

---

## 🔗 API Connection
This frontend communicates with the **FastAPI backend**.  
Set the API URL in `.env.local`:

```
NEXT_PUBLIC_API_URL=http://127.0.0.1:8000
```

---

## 📸 Preview
- **Sensor Alerts Tab**
  - Shows alert list with delete option
- **Sensor Activity Tab**
  - Shows the latest activity per sensor

---

## 📄 License
This project is licensed under the MIT License.

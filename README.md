# 🚀 Node-RED Challenge — BrazilAPI Dashboard

This project is a **Node-RED Challenge** that displays data from the **BrazilAPI** using an interactive dashboard.

---

## 📋 Requirements

Before running the project, make sure you have the following installed:

- **Node.js** (v18 or newer)
- **npm** (comes with Node.js)
- **Node-RED** v4.1.1
- **@flowfuse/node-red-dashboard** v1.29.0
- **node-red-node-sqlite** v1.1.1

---

## ⚙️ Installation

1. **Clone the repository**

```bash
git clone https://github.com/FelipeFantato/Node-RED-Challange.git
cd <REPOSITORY_FOLDER>
```

2. **Install Node-RED globally (if not installed yet):**
```bash
npm install -g node-red
```

3. **Install project dependencies:**
```bash
npm install @flowfuse/node-red-dashboard@1.29.0 node-red-node-sqlite@1.1.1
```

4. **Start Node-RED:**
```bash
node-red
```

---

## 🧠 Project Overview

This flow consumes **BrazilAPI** to retrieve and display zip code details through the Node-RED dashboard.

### Main Endpoint
The dashboard can be accessed locally at:

👉 **http://localhost:1880/dashboard/brasilapi**

---

## 📁 Project Structure

```
.
├── flows.json               # Node-RED flow configuration
└── README.md                # This file
```

---

## 🧩 Useful Commands

| Command | Description |
|----------|-------------|
| `node-red` | Starts Node-RED locally |
| `npm install <package>` | Installs a specific package |
| `Ctrl + C` | Stops Node-RED server |

---

## 🧰 Notes

- Make sure your SQLite database (`data.db`) exists under `./data/` before starting Node-RED.
- You can modify your dashboard layout directly from the Node-RED editor at **http://localhost:1880**.

---

## 🏁 Challenge Goal

Create a simple Node-RED flow that consumes **BrazilAPI** to retrieve CEP (zip code) information and display it in the dashboard.


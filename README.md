# 🧮 CanBetSplitter

**CanBetSplitter** (short for *Cancellation Bet Splitter*) is a smart, browser-based sequence manager built around the **Labouchere betting system** — with a twist.

It helps you **manage multiple sequences**, **split and merge them**, and **track your progress** with full local persistence and export/import capabilities.

---

## 🚀 Features

### 🎯 Core Logic
- Implements the **Labouchere (Cancellation) betting system**
- **Win** ➜ removes the first and last numbers of the sequence  
- **Loss** ➜ adds the sum of the first and last numbers to the end

### ⚙️ Sequence Management
- Auto-named sequences  
  - e.g. `Main → Main-A / Main-B → Main-A-A / Main-A-B`
- Split any sequence into two halves (`A` and `B`)
- Merge valid pairs automatically (via a smooth animated modal)
- Select active sequence for Win/Loss actions
- Automatically calculate and display **next bet** (sum of first + last number)
- LocalStorage persistence (your data stays even after reload)

### 💾 Data Control
- **Export / Import sequences** as:
  - `JSON` → perfect for restoring your exact setup later  
  - `CSV` → for spreadsheet or data analysis  
- All accessible under a clean **⚙️ Settings** dropdown
- Includes a **Reset All** button to start fresh

---

## 🖥️ Interface
- Clean, light-themed background for better readability  
- Smooth animations for modals and transitions  
- Intuitive buttons for Win / Loss / Split / Merge  
- Active sequence always clearly highlighted

---

## 📦 Installation & Usage

1. **Clone or download** the repository  
   ```bash
   git clone https://github.com/your-username/CanBetSplitter.git

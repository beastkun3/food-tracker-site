# 📋 Yet Another Calorie Tracker

A lightweight, local-first web application to track daily calorie consumption, auto-learn frequently consumed foods, and synchronize data with a formatted Excel spreadsheet. It runs completely in the browser and permanently enforces the `DD/MM/YYYY` date format across all devices.

---

## 🛠️ Key Features

*   **Fixed Date Formatting:** Forces a strict `DD/MM/YYYY` sequence regardless of your device's regional settings.
*   **Dual Entry Modes:** Log items instantly using a **Master Reference Dictionary Dropdown** or type them manually.
*   **Auto-Learning Database:** New manual entries are automatically saved to your master dropdown list for future speed-logging.
*   **Archive Filters:** Isolate and review historical logs broken down by specific months.
*   **Bi-Directional Excel Sync:** Export logs into structured spreadsheet tabs by month (plus a standalone `Food_Dictionary` tab), or import your `Calorie_Tracker.xlsx` file back into the browser to resume tracking.

---

## 📖 How to Use

### 1. Daily Logging
*   **Dropdown Mode:** Select a saved food item to automatically populate its default calories, then click **"Save Entry"**.
*   **Manual Mode:** Toggle to manual mode to type a new food item and its calorie count. Saving will automatically "learn" this food for future dropdown use.

### 2. Viewing History & Filtering
*   Your logs are displayed in the left-hand column, newest items first.
*   Use the **"Filter History View By Month"** dropdown to switch between your all-time data or specific monthly breakdowns.

### 3. Backing Up Data (Exporting)
*   Click **"↓ Export All to Master Excel File"** to download your structured `Calorie_Tracker.xlsx` file. Do this regularly to keep a physical copy of your data.

### 4. Syncing Your Log (Importing)
*   If you clear your browser cache, switch devices, or manually update your spreadsheet on a desktop, use the file zone at the bottom to upload your `Calorie_Tracker.xlsx` file. This restores your history and dictionary settings instantly.

---

## 🔒 Data Privacy
Your data belongs entirely to you. No parameters, analytics, or calorie metrics are transmitted to cloud servers; all computations execute locally inside your browser sandbox.

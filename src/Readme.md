# Saturday Schedule App

The **Saturday Schedule App** is a web-based tool designed to help teams manage their Saturday work schedules. It includes features for generating schedules, tracking workload distribution, and viewing schedule history. The app is styled with a professional **Investment Blue** and **Attentive Gold** theme.

---

## Features

### 1. **Schedule Generator**
- Automatically generates a Saturday schedule based on workload requirements:
  - **4 people** scheduled on most Saturdays.
  - **5 people** scheduled on Saturdays during the 1st–3rd of the month (extra busy days).
- Each schedule includes:
  - **1 MOD (Manager on Duty)**.
  - **3–4 Fillers** (depending on the workload).

### 2. **Workload Tracker**
- Tracks how many shifts each team member has worked.
- Ensures fair distribution of workload across the team.
- Includes a **Reset Tracker** button to reset all counts to zero.

### 3. **Schedule History**
- Displays a detailed history of all submitted schedules.
- Includes:
  - Date of the schedule.
  - Assigned MODs and Fillers.
- Features a **Clear History** button to delete all saved schedules.

---

## Pages

### 1. **Main Page (`index.html`)**
- Generate and submit schedules.
- Navigate to the **Workload Tracker** or **Schedule History** pages.

### 2. **Workload Tracker (`tracker.html`)**
- View the number of shifts worked by each team member.
- Reset the tracker to start fresh.

### 3. **Schedule History (`history.html`)**
- View a detailed history of all submitted schedules.
- Clear the history if needed.

---

## Technologies Used

- **HTML**: Structure of the app.
- **CSS**: Styling with a professional black and gold theme.
- **JavaScript**: Logic for generating schedules, tracking workload, and managing history.
- **LocalStorage**: Persistent storage for tracker data and schedule history.

---

## How to Use

### 1. **Generate a Schedule**
- Open the app on the main page (`index.html`).
- Select a date and click **Generate Schedule**.
- Review the generated schedule and click **Submit Schedule** to save it.

### 2. **View Workload Tracker**
- Navigate to the **Workload Tracker** page (`tracker.html`).
- View the number of shifts worked by each team member.
- Click **Reset Tracker** to reset all counts to zero.

### 3. **View Schedule History**
- Navigate to the **Schedule History** page (`history.html`).
- View a detailed history of all submitted schedules.
- Click **Clear History** to delete all saved schedules.

---

## File Structure

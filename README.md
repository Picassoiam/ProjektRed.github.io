# 🚖 Yango Commute Analysis

This project explores my **Yango ride data** compared to a fixed **K40 public transport cost**.  
The analysis answers key questions about spending, frequency, ride duration, and usage times.

---

## 🔍 Key Questions Answered

### 1. How much was I spending on Yango in a Year, Month, Week?
- **Weekly:** Aggregated costs per 7-day period.  
- **Monthly:** Summed per calendar month.  
- **Yearly:** Summed across all available data.  
- Also compared to public transport (flat K40/day).

### 2. Which day of the week did I use Yango most?
- Extracted **day names** from ride dates.  
- Counted frequency of rides per weekday.  
- Visualized with a **bar chart** (e.g., most rides on Fridays).

### 3. How often did I use Yango spread across months in a year?
- Counted **number of rides per month**.  
- Visualized with a **monthly frequency plot**.  
- Shows seasonal or monthly variation in usage.

### 4. How long did I spend on average on a Yango ride?
- Extracted duration (from `Details` column).  
- Computed **average ride duration in minutes**.  
- Answer: typically around **X minutes per ride**.

### 5. What times of the day did I use Yango mostly?
- Extracted hour from `Email_Timestamp`.  
- Counted rides per **hour of the day**.  
- Visualized with a **histogram (0–23 hours)** to show peak usage times.

---

## 📊 Visualizations Included
- **Daily Costs:** Side-by-side bar chart (Yango vs Public Transport).  
- **Monthly Costs:** Red vs blue comparison by month.  
- **Average Daily Costs:** Bar chart of Yango vs Public Transport.  
- **Cumulative Spending:** Running total over time.  
- **Ride Duration:** Average ride length.  
- **Time-of-Day Analysis:** Hourly ride distribution.  
- **Day-of-Week Analysis:** Which weekday had the most rides.  
- **Monthly Ride Frequency:** Number of rides per month.

---

## 📂 Files
- `yango_data.csv` → Raw Yango data (rides, payments, details).  
- `ProjektRed.ipynb` → Full exploratory notebook with analysis and plots.  
- `README.md` → Project overview (this file).  

---

## ⚙️ How to Run
1. Place `yango_data.csv` in the project folder.  
2. Open `yango_commute_analysis_v2.ipynb` in Jupyter Notebook or JupyterLab.  
3. Run all cells to reproduce the analysis and visualizations.  

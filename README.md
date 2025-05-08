# PowerBI_Project

## 🎯 Key Metrics Tracked
- Total tasks completed
- Samples reviewed and sampling rate
- Defect count and defect rate
- Fatal errors and fatal error rate
- Quality scores per supervisor and overall

## 📊 Visuals & Insights
- Custom charts
- Supervisor-level sampling analysis
- Employee-level sampling analysis
- Monthly trends on fatal errors
- Scatterplot comparing samples to defects per employee
- Employee Tooltip Graph linked to the Donut Chart

### 🧠 Main Findings(Quality):
- William’s team recorded the most fatal errors while having the most sampling.
- Quality scores are tightly clustered across supervisors.
- Fatal errors peaked in **March and May**

### 🧠 Main Findings(Employee Performance/Supervisor):
-William's team recording the most tasks 
-Jack’s team maintains a strong performance with low defects and fatal errors while handling a reasonable workload. This suggests that productivity
 improves when task volume remains manageable
-Maude Rowland achieved the lowest fatal error count while maintaining a strong task completion rate, making her the top performer based on error reduction

## ⚙️ Tools Used
- Power BI (dashboard creation, data modeling,DAX measures)
- CSV (used to clean import issues with Excel)

## 📝 Tech Note
The original `.xls` file had ~460 blank rows when I tried to import it to Power BI,even though the preview seemed fine. Converting it to `.csv` resolved the problem.

## 📂 File Structure
- `employee_performance.csv` → Cleaned dataset
- `final_Assignment.pbix` → Power BI report file
- `dashboard1.jpg` → Full visual layout of Overall Performance
- `dashboard2.jpg` → Full visual layout of Employee Performance


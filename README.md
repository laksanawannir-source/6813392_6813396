# 🧮 Health Tracker App

A user-friendly web-based application for calculating BMI, BMR, TDEE, and tracking daily food intake with calorie analysis and visualizations.

Built with [Gradio](https://gradio.app/) and [Pandas](https://pandas.pydata.org/), this app allows you to:
- Calculate your **BMI** and visualize trends over time.
- Calculate your **BMR** and **TDEE** based on activity level.
- Track your **daily food intake**, compare it with your TDEE, and visualize weekly calorie trends.

---

## 🚀 Features

### 👨🏻‍⚕️ BMI Calculator
- Calculates Body Mass Index (BMI) from weight and height.
- Categorizes BMI (Underweight, Normal, Overweight, Obese).
- Saves BMI history to a CSV file.
- Generates a **line chart** to show BMI changes over time.

### 🏋🏻‍♂️ BMR/TDEE Calculator
- Calculates:
  - **Basal Metabolic Rate (BMR)** using Mifflin-St Jeor Equation.
  - **Total Daily Energy Expenditure (TDEE)** based on selected activity level.
- Provides calorie suggestions for:
  - Weight loss
  - Maintenance
  - Weight gain

### 🥪 Food Tracker
- Add food items with calorie count.
- View total calories consumed today.
- Compare intake to TDEE and receive feedback.
- Remove individual entries by index.
- Visualize daily intake using a **stacked bar chart** for the past week.
- Stores data persistently in CSV files.

---

## 🧱 Built With

- [Gradio](https://gradio.app/) - Web UI framework
- [Pandas](https://pandas.pydata.org/) - Data processing
- [Matplotlib](https://matplotlib.org/) - Plotting
- [Python](https://www.python.org/) - Core language

---

## 📁 File Structure

```bash
├── app.py                # Main Python application file
├── food_entries.csv      # Auto-saved food entries
├── bmi_history.csv       # Auto-saved BMI history
├── recent_week_intake_stacked.png  # Generated plot of weekly intake
├── bmi_history_plot.png  # Generated BMI history plot
├── README.md             # This file

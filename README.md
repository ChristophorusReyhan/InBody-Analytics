# InBody Analytics Dashboard

A sleek, privacy-focused web application to visualize your InBody measurement history. This tool transforms your exported data into an interactive dashboard with trend analysis, body composition breakdowns, and progress tracking—all without your data ever leaving your computer.

**Live Demo:** [inbody-analytics.creyhan.site](https://inbody-analytics.creyhan.site/)
<img width="1349" height="2787" alt="image" src="https://github.com/user-attachments/assets/2c038349-914a-4484-aa9e-aa5baaae918a" />

## 🛡️ Privacy First
Most health data tools require you to upload sensitive information to their servers. This project takes a different approach:
* **100% Client-Side:** Data is processed entirely in your browser's memory.
* **No Backend:** There is no server-side storage or API.
* **Local File Reading:** Uses the `FileReader` API to parse your CSV locally. 

Your health data stays where it belongs: **with you.**

## ✨ Latest Features (New UI)
* **8 Real-time Stat Cards:** Instantly view latest values for Weight, Muscle Mass, Body Fat (kg & %), Muscle-to-Fat Ratio, Lean Mass Index, InBody Score, and Visceral Fat.
* **TDEE Calculator:** Integrated Total Daily Energy Expenditure calculator based on your latest body composition and selectable activity levels (Sedentary to Extra Active).
* **Dynamic Deltas:** Automatically calculates the difference (↑/↓) and percentage change between your two most recent sessions.
* **Advanced Visualizations:**
    * **Muscle to Fat Ratio:** A new dedicated trend line to track body composition quality.
    * **Trend Charts:** Track Weight vs. Fat Mass over time.
    * **Muscle vs. Fat:** Side-by-side comparison bar charts.
    * **InBody Score & BMR:** monitor overall health scores and metabolic rate trends.
    * **Visceral Fat Level:** Color-coded tracking to ensure you stay in the healthy range.
* **Body Composition Bar:** A multi-segment visual breakdown of Skeletal Muscle, Other Lean Mass, and Body Fat.

## 📊 Compatibility
Specifically tested with **InBodyDial H30** exports. 
* Ensure your export is in **CSV format**.
* If you have an export from a different model (H20, 270, 570, etc.) that isn't rendering, please open an issue with a redacted sample of your CSV headers!

## 🚀 How to Use
1. **Export:** Download your data as a CSV from your InBody app.
2. **Upload:** Drag and drop the file into the [Dashboard](https://inbody-analytics.creyhan.site/).
3. **Analyze:** View your charts and TDEE instantly. 

## 🛠️ Built With
* **Vanilla JS/HTML5/CSS3**
* **PapaParse** (CSV Parsing)
* **Chart.js** (Visualizations)

---
*Disclaimer: For personal data visualization only. Not a substitute for professional medical advice.*

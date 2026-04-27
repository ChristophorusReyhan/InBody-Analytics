# InBody Analytics Dashboard

A sleek, privacy-focused web application to visualize your InBody measurement history. This tool transforms your exported data into an interactive dashboard with trend analysis, body composition breakdowns, and progress tracking—all without your data ever leaving your computer.

**Live Demo:** [inbody-analytics.creyhan.site](https://inbody-analytics.creyhan.site/)

## 🛡️ Privacy First
Most health data tools require you to upload sensitive information to their servers. This project takes a different approach:
* **100% Client-Side:** Data is processed entirely in your browser's memory.
* **No Backend:** There is no server-side storage or API.
* **Local File Reading:** Uses the `FileReader` API to parse your CSV locally. 

Your health data stays where it belongs: **with you.**

## 📊 Compatibility
This tool was specifically developed and tested using data exports from the **InBodyDial H30**.
While it may work with other InBody devices, CSV headers can vary between models and app versions. If your data isn't rendering correctly:
* Ensure your export is in CSV format.
* Check if your column headers match the standard InBodyDial output.
  
Contributions welcome: If you have an export from a different model (H20, 270, 570, etc.) that isn't working, feel free to open an issue with a redacted sample of your CSV headers!

## ✨ Features
* **8 Real-time Stat Cards:** Instantly view latest values for Weight, Muscle Mass, Body Fat, BMI, InBody Score, BMR, and Visceral Fat.
* **Dynamic Deltas:** Automatically calculates the difference (↑/↓) and percentage change between your two most recent sessions.
* **Interactive Visualizations:**
    * **Trend Charts:** Track Weight and Fat over time.
    * **Muscle vs. Fat:** A side-by-side comparison bar chart.
    * **InBody Score & BMR:** Line graphs to monitor overall health scores and metabolic rate.
    * **Visceral Fat Level:** A color-coded bar (Green/Amber/Red) for quick health assessment.
* **Body Composition Bar:** A visual breakdown of Muscle, Lean, and Fat as a percentage of total body weight.
* **Comprehensive Session History:** A detailed table of all recorded measurements with color-coded score badges.

## 🚀 How to Use
1.  **Export:** Export and download your measurement data as a CSV from your InBody application.
2.  **Upload:** Drag and drop the CSV file into the dashboard at [inbody-analytics.creyhan.site](https://inbody-analytics.creyhan.site/).
3.  **Analyze:** View your charts and stats instantly. 

## 🛠️ Built With
* **Vanilla JS/HTML5/CSS3:** For a lightweight and fast user interface.
* **[PapaParse](https://www.papaparse.com/):** For robust, in-browser CSV parsing.
* **Chart.js:** For responsive and interactive data visualization.

## 📝 License
This project is open-source. Feel free to fork, modify, and use it for your personal fitness tracking.

---
*Disclaimer: This tool is intended for personal data visualization only and should not be used as a substitute for professional medical advice.*

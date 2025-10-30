# Flammability-Diagram + Purge Calculator
This is my Placement short-term project, which began with the Purge Calculations for a spherical LPG Tank, which was then overlapped with the flammability diagram during he purges to track composition during phases of purging to keep away from the flammability zone of the hydrocarbon.

This project is an automated tool, built in Microsoft Excel, designed to model the purging process of a spherical LPG tank. It automatically calculates and plots the purge gas composition onto a flammability diagram to ensure the purge path remains safely outside the flammable (explosive) zone.

This tool was developed as a short-term project during my 12-month industrial placement in Process Safety.

## 🎯 Problem & Purpose

* **The Problem:** Manually calculating the purge composition at various stages and plotting it against a flammability diagram is a time-consuming process (often taking 30+ minutes) and can be prone to human error.
* **The Solution:** This tool automates the entire process. By inputting key parameters, it provides an instant visual representation of the tank's safety profile during the purge, reducing calculation time to mere seconds and enhancing process safety.

## ✨ Key Features

* **Automated Calculations and Visual Safety Check:** Dynamically plots the changing tank composition onto a ternary flammability diagram.
* **Safety Assurance:** Clearly shows the purge path relative to the Upper Flammable Limit (UFL) and Lower Flammable Limit (LFL), ensuring the flammable envelope is never entered.
* **Multiple Models:** Includes files for both homogenous mixtures and more complex gas mixtures.

## 🛠️ Technology Used

* **Microsoft Excel:** Used for the front-end interface, data input, and chart display.

## 🚀 How to Use

1.  Download either `Flammability Diagram (Gas Mixture).xlsx` or `Flammability Diagram (Homogenous Mix).xlsx`.
2.  Open the file in Microsoft Excel.
3.  **Important: Enable macros** when prompted. The automation will not work otherwise.
4.  Enter your starting parameters ONLY IN THE GREEN BOXES (e.g., initial hydrocarbon composition, purge gas type is Nitrogen, pressure, etc.) in the designated input cells.
5.  The flammability diagram chart will automatically update to show the calculated purge path.

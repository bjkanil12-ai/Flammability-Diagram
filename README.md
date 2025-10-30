# Flammability-Diagram + Purge Calculator
This is my Placement short-term project, which began with the Purge Calculations for a spherical LPG Tank, which was then overlapped with the flammability diagram during he purges to track composition during phases of purging to keep away from the flammability zone of the hydrocarbon.

This project is an automated tool, built in Microsoft Excel, designed to model the purging process of a spherical LPG tank. It automatically calculates and plots the purge gas composition onto a flammability diagram to ensure the purge path remains safely outside the flammable (explosive) zone.

This tool was developed as a short-term project during my 12-month industrial placement in Process Safety.

## Problem & Purpose

* **The Problem:** Manually calculating the purge composition at various stages and plotting it against a flammability diagram is a time-consuming process (often taking 30+ minutes) and can be prone to human error.
* **The Solution:** This tool automates the entire process. By inputting key parameters, it provides an instant visual representation of the tank's safety profile during the purge, reducing calculation time to mere seconds and enhancing process safety.

## Key Features

* **Automated Calculations and Visual Safety Check:** Dynamically plots the changing tank composition onto a ternary flammability diagram.
* **Safety Assurance:** Clearly shows the purge path relative to the Upper Flammable Limit (UFL) and Lower Flammable Limit (LFL), ensuring the flammable envelope is never entered.
* **Multiple Models:** Includes files for both homogenous mixtures and more complex gas mixtures.

## Technology Used

* **Microsoft Excel:** Used for the front-end interface, data input, and chart display.

## How to Import

1.  Download either `Flammability Diagram (Gas Mixture).xlsx` or `Flammability Diagram (Homogenous Mix).xlsx`.
2.  Open the file in Microsoft Excel.
3.  **Important: Enable macros** when prompted. The automation will not work otherwise.

## Using the Spreadsheet

This spreadsheet aims to find the minimum number of purges necessary to remove the O₂ in the spherical tanks and down to a safe concentration, using iterative methods. As well as this, it can calculate the total volume and mass of Nitrogen needed, both liquid and gaseous phases.

There are a few basic rules and directions to use this spreadsheet, and the colours of the cells are the guidance to distinguish between the constants and the variables.

### Purge Iteration

Specific cells in this file are colour-coded to inform the user if the cell should be edited or not.

The basic principles of the colour coding in this spreadsheet are:

* **Green** – These cells are for the variables and can be edited; these are the values required to undergo the calculations for the decrease in concentration of O₂ between every purge.
* **Orange Text** – These are the generated values from the 'Calculations' section and are also important not to manipulate these cells as they are interlinked with the Grey cells.
* **Grey** – These cells are for the values in the 'Calculations' section and are **NOT to be edited*; this is because these cells contain the equations for the purging calculations. The generated values from these cells are also displayed in the 'Purge Iteration' section; therefore, these cells mustn't be manipulated.

### Flammability Diagram

In cell C7, there is a drop-down, labelled as an input cell, which will have options of Methane, Ethane, Propane, Butane and Hydrogen. The flammability diagram is already automated, and the diagram will adjust the flammability zone according g the calculations made, then linking them to a word prompt on cell C7. This ensures that, for example, if there is the word 'Butane' in the input cell, the properties of Butane will be used to construct the flammability diagram.

### Sections that **SHOULD NOT** be Edited

1) The most important sheet in this file is the 'Calcul de Diagram' section. This is not something that must be edited without informing someone, as these contain all the interlinked cells that lead to the calculations necessary within the flammability diagram.

2) Anything in the cells outlined by a thick line below the flammability diagram should also not be touched, as it contains the essential equations for the purging calculations.

3) Flammability Diagram (In any sheet)


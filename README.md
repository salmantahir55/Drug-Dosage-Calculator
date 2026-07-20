Drug Dosage Calculator

Overview

The Drug Dosage Calculator is a beginner-friendly Python application that determines a medication dose using a patient's body weight. It demonstrates the concept of weight-based dosing, which is commonly expressed in milligrams per kilogram (mg/kg).

The program also performs a basic safety check by comparing the calculated dose with a predefined maximum allowable dose before estimating the required number of tablets or vials.

Features

Calculates the total medication dose using patient weight and prescribed dosage.

Verifies whether the calculated dose exceeds the maximum permitted dose.

Prevents further calculations if the dose is above the safety threshold.

Determines the number of tablets or vials required based on the medication strength.

Simple command-line interface suitable for beginners learning Python.

Running the Program

Run the script from a terminal:

python drug_dosage_calculator.py

Alternatively, copy the code into a Google Colab notebook cell and execute it there.

Required Inputs

The program will prompt you to enter:

Patient weight (in kilograms)

Prescribed dosage (mg/kg)

Maximum allowable total dose (mg)

Drug strength per tablet or vial (mg)

Sample Input

Patient weight: 20

Dosage: 5

Maximum safe dose: 150

Drug strength per tablet: 25

Sample Output

Total calculated dose: 100.00 mg

Safety Status:

Dose is within the recommended maximum limit.

Tablets/Vials Required: 4

If the calculated dose exceeds the maximum allowable dose, the program immediately displays a warning message and terminates without calculating the number of tablets or vials.

Educational Purpose

This project is intended solely for educational and programming practice. The calculations are simplified and should not be used for prescribing medication or making clinical decisions. In real healthcare settings, medication dosing should always follow approved medical guidelines and be verified by qualified healthcare professionals.

Technologies Used

Python

Built-in math module (no third-party libraries required)

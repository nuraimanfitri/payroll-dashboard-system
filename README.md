# Payroll Dashboard System

A payroll management and automation system built using Google Sheets and Google Apps Script. This system is designed to manage staff payroll records, calculate deductions, generate PDF payslips and send payslips through email.

## Overview

This project uses Google Sheets as the payroll database and Google Apps Script as the backend logic. The dashboard interface is built using HTML, CSS and JavaScript through Google Apps Script Web App.

## Features

* Payroll dashboard interface
* Dynamic month/sheet selection
* Staff payroll table display
* Edit payroll data from dashboard
* Automated payroll calculation
* KWSP, SOCSO and SIP deduction calculation
* Employer contribution calculation
* PDF payslip generation
* Multiple payslip template support
* Email payslip distribution
* Google Drive file storage
* Payroll status tracking

## Tech Stack

* Google Apps Script
* Google Sheets
* HTML
* CSS
* JavaScript
* Google Drive Service
* Google Docs Service
* Gmail Service

## System Flow

1. Payroll data is stored in Google Sheets.
2. Admin opens the payroll dashboard through Google Apps Script Web App.
3. The system loads payroll data based on the selected month sheet.
4. Admin can calculate payroll deductions using the calculation button.
5. The system refers to KWSP, SOCSO and SIP reference sheets.
6. Admin selects the payslip template type.
7. The system generates PDF payslips using Google Docs templates.
8. Payslips are saved into Google Drive.
9. Payslips are sent to staff through email.
10. The payroll status and stored file link are updated in Google Sheets.

## Main Modules

* Payroll Dashboard
* Payroll Calculation Engine
* KWSP Reference Table
* SOCSO Reference Table
* SIP Reference Table
* Payslip Generator
* Email Automation
* Google Drive Storage

## Repository Files

* `index.html` - Payroll dashboard interface
* `Code.gs` - Google Apps Script backend logic
* `README.md` - Project documentation

## Notes

This project was developed for internal payroll operations using Google Workspace tools. Sensitive payroll data, staff information, Google Drive template IDs and production credentials have been removed or replaced for security purposes.

## Author

Nur Aiman Fitri

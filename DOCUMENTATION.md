🧩 Assignment Round 03 — Documentation

Name: Blessy Sam A S
Date: 07 October 2025
Tech Stack: Flask (Python), HTML, CSS, JavaScript, SQLite

🏗️ Project Title

Invoicing ROI Simulator

🧠 Problem Statement

To build an application that helps small businesses or freelancers calculate the Return on Investment (ROI) for their invoicing and payment operations. The goal is to create a tool that demonstrates how automation or digital invoicing could save time and increase revenue compared to manual methods.

🎯 Objective

Design a simple, functional web app using Flask.

Allow users to enter details like total invoices, average payment value, manual hours spent, and automation costs.

Compute ROI = (Profit − Cost) / Cost × 100 and show visualized results.

Provide an option to generate and download a report.

⚙️ System Architecture

Frontend:

HTML/CSS for layout and styling

JavaScript for form validation and AJAX requests

Backend:

Flask handles routes and business logic (app.py)

SQLite database to store user submissions and computed results

Flow:

User → Web Form → Flask Server → ROI Computation → Result Page → (Optional) Report Download

🧮 Core Features

Input Form — total invoices, cost per invoice, automation cost, manual hours.

Real-time ROI computation.

Display of profit percentage and comparative insights.

Data persistence in SQLite for tracking previous results.

Simple report export option (as HTML or PDF).

🗂️ Database Design

Table: roi_data

Column Name	Type	Description
id	INTEGER (PK)	Auto increment
total_invoices	INTEGER	Number of invoices processed
avg_value	REAL	Average value per invoice
manual_hours	REAL	Hours spent manually
automation_cost	REAL	Cost of automation software
roi_percentage	REAL	Calculated ROI
created_at	TIMESTAMP	Date of entry
🚀 Deployment Plan

Use Render, Vercel, or Flask-based PythonAnywhere for live hosting.

Connect SQLite (or upgrade to PostgreSQL on Render).

Push code to GitHub → deploy → generate live URL.

🧾 Sample Workflow

Open homepage → enter invoice details.

Backend computes ROI and stores data.

Results page shows ROI percentage and financial summary.

Option to download report or reset for a new calculation.

🔍 Future Enhancements

Add login/authentication for multi-user tracking.

Enable data visualization (charts using Chart.js).

Integrate email notifications for report delivery.

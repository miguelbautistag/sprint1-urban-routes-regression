# Urban Routes – Regression & Functional Testing Project

## 🗓️ Execution Period

- **Project Type:** QA Bootcamp Project (TripleTen LatAm)
- **Execution Window:** January 2025
- **Status:** Completed

## 📌 Project Overview

This project focuses on **manual functional and regression testing** of the **map and navigation features** of the *Urban Routes* web application.

The main objective was to validate that all **map interactions, UI elements, and navigation behaviors** work as expected according to the design specifications, while identifying functional, usability, and logical defects that could impact the user experience.

Testing was executed from an **end-user perspective**, simulating real interactions with the map, address inputs, view modes, and Street View functionality.

---

## 🛠️ Tools Used

- **Google Sheets** – Test case design, execution tracking, and defect documentation  
- **Browser (Chrome)** – Manual UI testing and interaction validation  
- **Application Under Test** – Urban Routes Web App  

---

## 📋 Test Scope

The testing scope covered the following map-related functionalities:

- Map navigation (scroll, zoom, objects rendering)
- Address input fields (“From” and “To”)
- Address pin placement and removal
- Map view modes (Default, Satellite, Terrain)
- Full-screen mode behavior
- Points of Interest (POIs)
- 3D objects rendering
- Street View activation and deactivation
- Application information modal

---

## 🧪 Test Artifacts

### ✅ Test Cases
- **Total Test Cases:** 24  
- **Passed:** 15  
- **Failed:** 9  

Each test case includes:
- Preconditions
- Step-by-step actions
- Expected results
- Execution status
- Linked defect ID (when applicable)

📎 **Test Cases Document (Google Sheets)**  
👉 *https://shorturl.at/h9lnw – currently maintained in Spanish*

---

### 🐞 Bug Reports

- **Total Bugs Identified:** 9  
- **Severity Breakdown:**
  - 🔴 Critical: 2  
  - 🟠 Major: 3  
  - 🟡 Minor: 3  
  - 🔵 Trivial: 1  

Each bug report contains:
- Clear reproduction steps
- Expected vs Actual results
- Severity classification
- Direct traceability to failed test cases

📎 **Bug Reports Document (Google Sheets)**  
👉 *https://shorturl.at/qtOu2 – currently maintained in Spanish*

---

## 🔍 Key Findings

- Address pins **do not appear or disappear correctly** when modifying input fields, leading to critical map inconsistencies.
- The map **fails to react to single-field address inputs**, only updating when both “From” and “To” are completed.
- Full-screen mode hides essential UI elements such as address fields.
- Some UI elements behave inconsistently with expected UX patterns.
- Street View and map rendering features work correctly under most scenarios.

---

## 🌐 Language Note (Important)

> ⚠️ **Documentation Language Notice**  
All test cases and bug reports for this project were originally created and delivered in **Spanish**, as required by the project guidelines at the time of execution.

To preserve authenticity and avoid misinterpretation, the original documents have been kept in Spanish.  
This README provides a **clear English summary** of the scope, execution, and results for international reviewers.

# PRODIGY_ST_02 - Compatibility Testing Report

🚀 **Task 02** of the Prodigy Infotech Software Testing Internship

## 📋 Task Objective
To perform **compatibility testing** on a basic web page across various:
- Browsers: Chrome, Firefox, Safari, Edge
- Devices: Desktop, Tablet, Mobile

## 🔍 What Was Tested
- Gradient backgrounds
- Circle with gradient shapes
- Typography (e.g., "Comillas Negras")
- Layout and link functionality

## 🧪 Tools & Environment
- Browsers: Chrome, Firefox, Edge, Safari (Desktop and Mobile)
- Devices: Windows PC, macOS, Android, iOS
- Manual Testing and Developer Tools (Inspect Element, Console logs)

## 🐞 Issues Found
- Gradient rendering issues on Safari and Firefox (Mobile)
- Layout shift on screen resize in Edge
- Font not loading properly in Firefox
- Dummy link `#` found (non-functional)
- Circle overlapping text in small screen views

## ✅ Solutions Recommended
- Add fallback color to gradients
- Use Flexbox/Grid for responsive layout
- Properly host custom fonts with fallbacks
- Fix or remove dummy links
- Use media queries for better responsiveness

## 📁 Files Included
- `PRODIGY_ST_02_Compatibility_Testing_Report.docx`: Detailed test report in Word format

## 🔗 GitHub Repository Name Format

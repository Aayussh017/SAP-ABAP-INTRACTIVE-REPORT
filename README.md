# SAP-ABAP-INTRACTIVE-REPORT
This SAP ABAP report displays Sales Order header details in an ALV Grid. On clicking a Sales Order number, the report performs a drill-down and displays the corresponding Sales Order item details in a second ALV Grid . 

## Features
- Selection Screen for Sales Order Number
- ALV Grid using REUSE_ALV_GRID_DISPLAY
- Header → Item Drill-down
- USER_COMMAND callback handling
- Hotspot-based navigation
- Clean modular FORM-based design

## Tables Used
- VBAK – Sales Order Header
- VBAP – Sales Order Items
- KNA1 – Customer Master

## Technical Highlights
- Uses RS_SELFIELD-VALUE for ALV Grid interaction
- Uses global variable to pass key between forms
- Demonstrates interactive reporting in ALV Grid

## How to Execute
1. Run the report
2. Enter Sales Order numbers
3. Click on Sales Order number to view items

# VM Capacity Analysis
This is a spreadsheet created to perform basic VM capacity calculations and planning, without requiring expensive commercial products or tools only available to partners. This was developed during a new cluster design project, after about the 4th time I had to re-run my capacity numbers based on different scenarios.

The intent is to assist with analyzing your current capacity and provisioning levels, as well as determining specifications to meet a given capacity need. It also makes it easy to model different scenarios by turning on and off various new workloads/projects to see how different combinations will affect the numbers.

# Contributing
Issues and Pull Requests are welcome!

* To modify outside of the user-entry areas, you must unprotect the "Calculations" worksheet. Re-protect the worksheet before saving.
* If you are adding additional user-input fields, make sure they are unlocked (Format Cells -> Protection -> clear Locked).
* Use named cells scoped to the sheet (not workbook) if adding a new value to be used in a calculation. Right-click cell, Define Name, Scope: Calculations

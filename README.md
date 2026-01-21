# Elite Dangerous Build Tool (Coriolis JSON Powered)

A lightweight, browser based tool for analysing **Elite Dangerous** ship builds using **Coriolis.io JSON exports**.  
Designed for simplicity, accuracy, and speed  no backend, no installs, no dependencies.

This tool lets you:

- Paste a Coriolis JSON export  
- Auto‑fill all ship stats instantly  
- Run a full build analysis  
- Open the exact same build back in Coriolis  
- Avoid the “stock ship” issue caused by missing build codes  

Perfect for players who want a fast way to evaluate builds without manually typing stats.


##  Features

### ** Coriolis JSON Import**
Paste your exported JSON from Coriolis.io and the tool automatically extracts:

- Ship name  
- Jump ranges (laden & unladen)  
- Power usage  
- Heat capacity  
- Shield strength & resistances  
- Hull HP & resistances  
- Distributor stats  
- And more  

No manual entry required.


### ** OneClick “Open in Coriolis”**
The tool reads the JSON’s internal `code=` and `shipId`, ensuring Coriolis opens the **exact same build**, including:

- All modules  
- All engineering  
- All internals  
- All stats  

No more blank ships.  
No more 8 LY stock Pythons.


### ** Build Analysis**
The tool evaluates:

- Power balance  
- Heat profile  
- Effective shield strength  
- Effective hull strength  
- Distributor performance  
- Jump range  
- General build health  

Results are displayed in a clean, readable format.


##  How to Use

1. Open the HTML file in any modern browser  
2. Export your build from Coriolis.io  
   - Click **Export → JSON**  
3. Paste the JSON into the text box  
4. Click **Add New Build**  
   - All stats auto‑fill  
5. Click **Run Analysis**  
   - View your build evaluation  
6. Click **Open in Coriolis**  
   - Loads the exact build in Coriolis  



##  Why JSON Instead of Journal Files?

Elite Dangerous journals **do not** contain full build stats.  
Coriolis JSON **does**.

This tool uses the JSON because it includes:

- Full engineering  
- Full module stats  
- Full resistances  
- Full power data  
- Full jump range calculations  

This guarantees accurate analysis.


##  Technology

- Pure HTML  
- Pure JavaScript  
- No frameworks  
- No backend  
- Runs entirely in the browser  

© 2026 D. Hughson. All rights reserved.






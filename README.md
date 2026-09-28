# smr-grid-integration-simulator
A free, browser-based scenario calculator for exploring how Small Modular Reactors (SMRs) could replace part of a grid's fuel-burning electricity generation. Change the SMR size, number of units, rollout pathway, fuel cost, emission factor and demand growth, and see the effect on grid share, CO2 avoided and fuel cost avoided.
[README.md](https://github.com/user-attachments/files/32713361/README.md)
# SMR Grid Integration Simulator

**Version 1.0 (First Version)**

A free, browser-based scenario calculator for exploring how Small Modular Reactors (SMRs) could replace part of a grid's fuel-burning electricity generation. Change the SMR size, number of units, rollout pathway, fuel cost, emission factor and demand growth, and see the effect on grid share, CO2 avoided and fuel cost avoided.

> **Important:** every number shown when the tool first opens is a demonstration value, not real data for any country. Replace them with your own sourced numbers before drawing conclusions. This is a first-pass screening tool, not a grid-stability study or a full economic analysis.

## Authors and Subject Matter Experts (Nuclear Field)

- Florencia Renteria del Toro, PhD
- Professor Akira Tokuhiro, PhD

## Files

| File | Purpose |
|---|---|
| `SMR_Grid_Integration_Simulator.html` | The simulator. One self-contained file; no installation needed. |
| `SMR_Simulator_User_Manual.docx` | Step-by-step user guide for beginners (no prior background required). |

## How to Open the Simulator

1. Download `SMR_Grid_Integration_Simulator.html` (open the file on GitHub, then use the download button).
2. Double-click it, or right-click and choose **Open With** and pick a web browser (Chrome, Edge, Firefox or Safari).
3. Use an internet connection the first time you open it; the page loads its charts and fonts from the internet.

From a terminal, in the folder containing the file:

```
macOS:                  open SMR_Grid_Integration_Simulator.html
Windows (cmd):          start SMR_Grid_Integration_Simulator.html
Windows (PowerShell):   Invoke-Item SMR_Grid_Integration_Simulator.html
Linux:                  xdg-open SMR_Grid_Integration_Simulator.html
```

Note: clicking the HTML file inside GitHub shows its source code, not the working dashboard. Download it, or use the GitHub Pages link below if the repository owner has enabled it.

**Live page (if GitHub Pages is enabled):** `https://<org>.github.io/<repo>/SMR_Grid_Integration_Simulator.html`

## Check That It Works

With the starting values (generation 1200 GWh, grid capacity 600 MW, emission factor 0.70, fuel cost 140, unit size 100 MW, 2 units, phased rollout, capacity factor 90%, load growth 3%, horizon 15 years, threshold 15%), the cards should show:

- Total SMR Capacity: 200 MW
- Grid Share (final year): 33.3%, labelled ABOVE THRESHOLD
- CO2 Avoided (cumulative): 15,650.8 kt
- Fuel Cost Avoided (cumulative): $3,130.2M

If your numbers match, the tool is working correctly on your device.

## What It Does Not Do

- It does not test grid stability (frequency response, outages, power flow).
- "Fuel cost avoided" is gross; it does not subtract SMR construction, operating or decommissioning costs.
- SMR lifecycle emissions are counted as zero.
- Fuel cost, emission factor and capacity factor stay constant across years.

See Section 13 of the user guide for the full list.

## Version

1.0 (First Version)

## License

To be chosen by the authors before public release.

---
layout: default
---

[back](./index.md)

# Registry Acquisition and Parsing Tool
##### GitHub Repository: [https://github.com/JohnBadels/SECU3-LAB-3](https://github.com/JohnBadels/SECU3-LAB-3)
A tool for acquiring and parsing Windows Registry hives, capable of operating in both live and offline environments.

### Key Features
#### Registry Acquisition Tool
- Extracts key registry hives (Live)
  - SAM
  - SECURITY
  - SOFTWARE
  - SYSTEM
  - DEFAULT

#### Registry Parsing Tool
- Parses registry hives
  - from Registry Acquisition Tool (Live)
  - from FTK Imager (Offline)
- Converts parsed data to .csv and .json

### Screenshots
##### Registry Acquisition Tool w/ extracted registry hives
![reg-acq-tool-execute](./pictures/reg-acq-tool-execute.png)

##### Registry Parser Tool w/ parsed registry hives from Registry Acquisition Tool
![reg-par-tool-from-reg-acq-tool](./pictures/reg-par-tool-from-reg-acq-tool.png)

##### Registry Parser Tool w/ parsed registry hives from FTK Imager
![reg-par-tool-from-ftk](./pictures/reg-par-tool-from-ftk.png)

##### Comparison of parsed registry hives from Registry Acquisition Tool and FTK Imager
![compare-parsed-data](./pictures/compare-parsed-data.png)

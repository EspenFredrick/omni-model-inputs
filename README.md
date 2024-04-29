# Examining the Accuracy of The OMNI Data in Representing Storm Time Observations Near Earth and the Effect on Global Modeling
## By Espen Fredrick and Ramon Lopez
### University of Texas at Arlington
___
### Contact Info:
**Name:** Espen Fredrick *(Lead graduate student)*  
**Email:** espen.fredrick@uta.edu
___
### Table of Contents:
- README.md - *This file.*

```bash
├── 📁 2012-11-13                                             # Good event
│   ├── 📁 inputs                                             # Input data set
│   │   ├── 📄 Artemis_SWMF_Input_2012.txt
│   │   └── 📄 Omni_SWMF_Input_2012.txt
│   ├── 📁 output-indices                                     # Files with model output data 
│   │   ├── 📁 LFM
│   │   └── 📁 SWMF
│   ├── 📁 real-indices                                       # Files with real-world data
│   ├── 📁 plots                                              # Plots
│   │   ├── 🖼️ Series-2012.jpg                                # ├── The entire series overview
│   │   ├── 🖼️ 2012-11-13-Pearson-normal-cumulative.jpg       # ├── Cumulative correlation coefficients
│   │   ├── 🖼️ 2012-11-13-Pearson.jpg                         # ├── Binned correlation coefficients
│   │   ├── 🖼️ OvsA_linregress.jpg                            # ├── Linear fit of input data
│   │   ├── 📁 LFM                                            # ├── Plots with LFM output data
│   │   └──  📁 SWMF                                          # └── Plots with SWMF output data
│   │       ├── 🖼️ indexstats-modelouts-both.jpg              #     ├── Plots doing statistical tests between model outputs
│   │       ├── 🖼️ indexstats.jpg                             #     ├── Plots doing statistical tests between output and real data
│   │       └── 📁 indices                                    #     └── Plots comparing model indices to the real world
│   ├── 📓 Plots.ipynb                                        # Plotting notebook
│   └── 📓 stats.ipynb                                        # Statistical tests
└── 📄 README.md                                              # This file
```

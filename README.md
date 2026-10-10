## EDS223-HW1: Environmental Justice Screening

Repository for the first homework assignment in EDS 223
This repository houses data from the US Environmental Protection Agency’s Environmental Justice Screening and Mapping Tool. This tool no longer exists with the EPA, but an unofficial version of it can be accessed from https://pedp-ejscreen.azurewebsites.net/ . 

Author(s): Natasha Clemencon-Charles

This repo has the following structure: 
```{r}
EDS223-HW1  
└───EDS223-HW1
    └───data
    └───ej_screen_files
    └───.gitignore
    └─── ej_screen.html
    └─── ej_screen.qmd
    └─── README.md
 ```

The graphing for this assignment was completed in the ej_screen.qmd.

The qmd uses the ejscreen data to create 2 graphs: one of percentile PM 2.5 and one of percentile Cancer in San Luis Obispo, California. Looking at these two graphs together shows that areas in SLO county in a higher national percentile of PM 2.5 also appear to often be in a higher national percentile of cancer reportings. This indicates a potential issue of environmental injustice, because those being exposed to more PM 2.5 may also have a higher risk of having cancer. There might be other confounding factors at play, but this indicates a potential environmental equity issue for those living in areas with more PM 2.5 in the air. 

References: US Environmental Protection Agency EJScreen, https://pedp-ejscreen.azurewebsites.net/

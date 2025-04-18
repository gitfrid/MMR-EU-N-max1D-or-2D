### MMR-py coverage max(1st or 2nd Dose)  
<br>
<br>

**<small>Confirmed reported cases, including those confirmed clinically,
epidemiologically-linked or by laboratory investigation,
EXCEPT for countries that have eliminated. For countries that HAVE eliminated,
cases confirmed clinically should not be included in the sum of total cases!</small>**

Reported Case incidence
[Download Link atlas.ecdc.europa.eu](https://atlas.ecdc.europa.eu/public/index.aspx?Dataset=27&HealthTopic=37)
<br>Vac coverage official Numbers Measles-containing vaccine 2d Dose
[Download Link atlas.ecdc.europa.eu](https://atlas.ecdc.europa.eu/public/index.aspx?Dataset=27&HealthTopic=37)

### Disclaimer:
**The results have not been checked for errors. Neither methodological nor technical checks or data cleansing have been performed.**
_________________________________________

### Dowhy causal impact estimation vax coverage on measles case incidence for differnt countries, <br>M-containing vac max(1st or 2nd) Dose

<br>
<p>DoWhy is a Python library for causal inference that allows modeling and testing of causal assumptions, based on a unified language for causal inference.
<strong>See the book <em>Models, Reasoning, and Inference</em> by Judea Pearl for deeper insights, that goes far beyond my horizon.</strong></p>
<br>

Phyton script [C) MMR.py](https://github.com/gitfrid/MMR-max1D-or-2D/blob/main/C%29%20MMR.py) for visualizing the downloaded CSV data
<br>DoWhy Library see: https://github.com/py-why/dowhy

<br>
<img src=https://github.com/gitfrid/MMR-max1D-or-2D/blob/main/C%29%20Dowhy%20causal%20estimate%20on%20mean%20vac%20coverage%20and%20cases%20Measles%201980-2023.png width="1280" height="auto">
<br>
To select or deselect all, double-click on the legend. To select a single legend, click on it once
<br>

<br>[Download interactive html](https://github.com/gitfrid/MMR-max1D-or-2D/blob/main/C%29%20Dowhy%20causal%20estimate%20on%20mean%20vac%20coverage%20and%20cases%20Measles%201980-2023.html) 1980-2023
<br>[Years for each country the dowhy estimation is based on](https://github.com/gitfrid/MMR-max1D-or-2D/blob/main/C%29%20Dowhy%20causal%20estimate%20on%20mean%20vac%20coverage%20and%20cases%20Measles%20valid%20years%20for%20dowhy%20calc%201980-2023.txt)
<br>
<br>

Interpretation of Causal Effect Estimation:

The causal effect estimation gives a numerical value indicating how much the outcome (reported cases) changes when the treatment (coverage) changes by one unit.

    Positive causal effect (e.g. 0.5): For each 1% increase in coverage, reported cases expected to increase by 0.5 cases.
    Negative causal effect (e.g. -0.5): For each 1% increase in vaccination coverage, reported cases are expected to decrease by 0.5 cases.
    Warning: the results were not checked for confounding factors or lack of causality neither methodological errors

_________________________________________
<br>

### Vax coverage vs case incidence rate for differnt countries, M-containing vac max(1st or 2nd Dose)

Phyton script [A) MMR.py](https://github.com/gitfrid/MMR-max1D-or-2D/blob/main/A%29%20MMR.py) for visualizing the downloaded CSV data


To select or deselect all countries, double-click on the legend. To select a single country, click on it once
<br>
<img src=https://github.com/gitfrid/MMR-max1D-or-2D/blob/main/A)%20MMR%20vaccination_vs_reported_cases%201980-2023.png width="1280" height="auto">
<br>
<br>
[Download interactive html](https://github.com/gitfrid/MMR-max1D-or-2D/blob/main/A%29%20MMR%20vaccination_vs_reported_cases%201980-2023.html) 1980-2023
<br>
_________________________________________
<br>

### Vax coverage vs case incidence rate for differnt countries including trend line categories , M-containing vac max(1st or 2nd Dose) 1980-2023:
    Rising Coverage and Rising Cases:
    Falling Coverage and Falling Cases:
    Rising Coverage and Falling Cases:
    Falling Coverage and Rising Cases:

<br>

Phyton script [B) MMR.py](https://github.com/gitfrid/MMR-max1D-or-2D/blob/main/B)%20MMR.py) for visualizing the downloaded CSV data with trend lines 
<br>


**Rising Coverage and Rising Cases:**
<br>
<img src=https://github.com/gitfrid/MMR-max1D-or-2D/blob/main/B%29%20MMR%20rising%20vac%20coverage%20and%20rising%20cases%20trend%201980-2023.png width="1280" height="auto">
<br>

[Download interactive html](https://github.com/gitfrid/MMR-max1D-or-2D/blob/main/B%29%20MMR%20rising%20vac%20coverage%20and%20rising%20cases%20trend%201980-2023.html) 1980-2023
<br>
_________________________________________

**Falling Coverage and Falling Cases:**
<br>
<img src=https://github.com/gitfrid/MMR-max1D-or-2D/blob/main/B%29%20MMR%20falling%20vac%20coverage%20and%20falling%20cases%20trend%201980-2023.png width="1280" height="auto">
<br>

[Download interactive html](https://github.com/gitfrid/MMR-max1D-or-2D/blob/main/B%29%20MMR%20falling%20vac%20coverage%20and%20falling%20cases%20trend%201980-2023.html) 1980-2023
<br>

_________________________________________

**Rising Coverage and Falling Cases:**
<br>
<img src=https://github.com/gitfrid/MMR-max1D-or-2D/blob/main/B%29%20MMR%20rising%20vac%20coverage%20and%20falling%20cases%20trend%201980-2023.png width="1280" height="auto">
<br>

[Download interactive html](https://github.com/gitfrid/MMR-max1D-or-2D/blob/main/B%29%20MMR%20rising%20vac%20coverage%20and%20falling%20cases%20trend%201980-2023.html) 1980-2023
<br>

_________________________________________

**Falling Coverage and Rising Cases:**
<br>
<img src=https://github.com/gitfrid/MMR-max1D-or-2D/blob/main/B%29%20MMR%20falling%20vac%20coverage%20and%20rising%20cases%20trend%201980-2023.png width="1280" height="auto">
<br>

[Download interactive html](https://github.com/gitfrid/MMR-max1D-or-2D/blob/main/B%29%20MMR%20falling%20vac%20coverage%20and%20rising%20cases%20trend%201980-2023.html) 2000-2023
<br>
_________________________________________
<br>

### Vax coverage vs case incidence rate for differnt countries, <br>M-containing vac max(1st or 2nd Dose) for years 1980-2023:

.
<br>
<br>Includes Dropdown menu for easy selection: 
<br>
<img src=https://github.com/gitfrid/MMR-max1D-or-2D/blob/main/D%29%20MMR%20vaccination_vs_reported_cases_dropdown_1980-2023.png width="1280" height="auto">
<br>
[Download interactive html](https://github.com/gitfrid/MMR-max1D-or-2D/blob/main/D%29%20MMR%20vaccination_vs_reported_cases_dropdown_1980-2023.png) 1980-2023
<br>
_________________________________________



---
layout: page
title: Limitations
---
## <span style="color: #D35400 ;">Limitations of our datasets</span>

**1. Use of historical data**

Due to difficulties accessing property websites' APIs, we have conducted our analysis using a historical dataset. Despite remaining valuable in recognising long-term trends and patterns, this dataset might only partially capture the current situation as the dynamic housing market is subject to rapid changes. Therefore, periodically considering updated models to account for changes in underlying patterns is essential. External factors may also affect and skew the data, such as COVID-19 affecting the housing market between 2020 and 2023.


**2. Endogeneity**

The relationship between variables may be independent. Endogeneity is observed when there is a complex cause-and-effect relationship between different variables, making it unclear which influences what. In this context, changes in rental prices could affect the supply or demand for housing, leading to reverse causation. We need to use a more advanced model or Implicit instrumental variables to solve it.

## <span style="color: #D35400 ;">Limitations of our analysis</span>

**3. Housing configuration ambiguity**

Our rent data set identifies various housing configurations, ranging from one bedroom to a studio to four or more bedrooms. This last arrangement encompasses more than one specific number of rooms (might include five, six, or seven-room configurations), making comparing rent per single tenant harder. To tackle this problem, we have decided to limit the '4 or more bedrooms' to four bedrooms only, meaning that our rent analysis overestimates prices for that housing configuration.

**4. Restricted connectivity mapping**

For the connectivity analysis, we have chosen to consider transport accessibility of different boroughs to UCL only to narrow our focus and avoid mapping potentially five more areas to connect to other London universities. However, this limits our analysis because we might need to recognise emerging trends by considering routes to other universities.

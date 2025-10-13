# 🌍 Altitude and Elite Marathon Performance
Exploring whether high-altitude environments shape elite long-distance running performance using Olympic marathon data.

---

## Overview
This project investigates whether altitude influences elite marathon performance. Specifically, it examines whether runners born (or possibly training) in high-altitude regions perform better and how socioeconomic factors—such as population size and national income—interact with athletic outcomes. 

The project uses both **country-level** and **within-country** analyses to distinguish physiological effects of altitude from cultural, economic, or selection-based factors.

---

## Key Questions and Findings

1. **(Main Research Question 1) Is country altitude associated with long-distance running performance?**
   → No. After controlling for socioeconomic factors, country altitude was not significantly associated with marathon performance.  

2. **(Main Research Question 2) Does altitude at the runner’s birth region predict performance within countries?**
   → No. Within-country analyses showed no significant relationship between birth-region altitude and performance once national-level factors were controlled for. 
3. **Are many elite runners from Ethiopia and Kenya actually born in high-altitude regions?**
   → Yes. Many runners from Kenya and Ethiopia—two of the top-performing countries—were born in regions situated above their respective national average elevations. 

4. **What about runners from other countries with even higher altitudes?**
   → Some are, and others are not. Unlike Kenya and Ethiopia, most runners from the highest-altitude countries do not come from regions above their national average elevation. Overall, there is no clear pattern among the top 10 highest-altitude countries. However, since their national averages are already very high, all runners from Nepal, Tajikistan, and Lesotho come from regions above 1,500 m, with Tajikistan’s runners all originating from elevations over 3,000 m.  

5. **How do socioeconomic factors interact with performance?**
   → Population size emerged as the strongest predictor of performance, while national income (GNI) showed a moderate role. The negative association between GNI and marathon times suggests that higher-income countries may benefit from superior facilities and infrastructure rather than low-income countries performing better due to stronger motivation for economic advancement.  
---

## Data and Methods
- **Data sources:** Olympic records, global elevation datasets, and socioeconomic indicators (Population, GNI).
- **Sample:** Elite marathon and half-marathon runners (men and women).  
- **Variables:**
  - Runner birth-region altitude  
  - Country average altitude  
  - Performance times  
  - Population and GNI  

- **Analysis:**
  - Linear mixed models with country-level random effects  
  - Robustness checks excluding outlier countries (Kenya and Ethiopia)  

---

## Key Findings
- Kenyan and Ethiopian runners tend to be born at higher altitudes than their national averages.  
- Most runners from other high-altitude countries do not follow this pattern.  
- Population size strongly predicts performance, likely reflecting a larger talent pool and sports culture.  
- GNI shows a moderate negative effect, suggesting better facilities and infrastructure may aid performance in wealthier countries.  
- Neither country altitude nor birth-region altitude has a significant independent effect on performance after accounting for socioeconomic variables.  

---

## Visuals
| Birth Region vs. Country Altitude | Model Coefficients |
|-----------------------------------|--------------------|
| ![Altitude Distribution](figures/altitude_dist.png) | ![Model Results](figures/model_results.png) |

---

## Conclusion
While altitude has long been considered a key factor behind East Africa’s running dominance, this analysis finds that altitude alone cannot explain differences in elite marathon performance. Instead, broader socioeconomic and demographic factors—such as population and infrastructure—appear to play more influential roles.  

These findings highlight the complexity of athletic success, which likely arises from a combination of environmental, cultural, and economic influences rather than altitude alone.

---

## Future Work
- Incorporate detailed training-location data where available.  
- Examine physiological and cultural factors beyond altitude.  

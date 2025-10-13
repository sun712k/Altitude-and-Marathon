# 🌍 Altitude and Elite Marathon Performance
Exploring whether high-altitude environments shape elite long-distance running performance using Olympic marathon data.

---

## Overview
This project investigates whether altitude influences elite marathon performance. Specifically, it examines whether runners born (or possibly training) in high-altitude regions perform better and how individual factors-age, sex, BMI and socioeconomic factors—such as population size and national income—interact with athletic outcomes. 

Since many researchers hypothesize that regional altitude influences performance through physiological mechanisms, the second stage of this study will analyze within-country variation—examining whether runners born in higher-altitude regions perform better after controlling for country-level factors. This approach helps isolate the potential physiological effect of altitude while minimizing confounding influences such as genetics and socioeconomic conditions.
 
 *If altitude is truly a causal driver of endurance performance (e.g., through oxygen adaptation or VO₂ max improvements), then the relationship should appear both *across* and *within* countries. Conversely, if the apparent country-level association is instead driven by cultural, genetic, or selection effects, the relationship may disappear when examined within countries.*

The project uses both **between-country** and **within-country** analyses to distinguish physiological effects of altitude from cultural, economic, or selection-based factors.

---

## Key Questions and Findings

1. **(Main Research Question 1) Is country altitude associated with long-distance running performance?**
   → No. After controlling for socioeconomic factors, country altitude was not significantly associated with marathon performance.  

2. **(Main Research Question 2) Does altitude at the runner’s birth region predict performance within countries?**
   → No. Within-country analyses showed no significant relationship between birth-region altitude and performance once national-level factors were controlled for. 
3. **Are many elite runners from Ethiopia and Kenya actually born in high-altitude regions?**
   → Yes. Many runners from Kenya and Ethiopia—two of the top-performing countries—were born in regions situated above their respective national average elevations. 
<img width="880" height="389" alt="C 1 Distribtion of altitudes" src="https://github.com/user-attachments/assets/0a109084-f279-4028-9efd-5d149ee479cd" />

4. **What about runners from other countries with even higher altitudes?**
   → Some are, and others are not. Unlike Kenya and Ethiopia, most runners from the highest-altitude countries do not come from regions above their national average elevation(750m and 1,330m each). Overall, there is no clear pattern among the top 10 highest-altitude countries. However, since their national averages are already very high, all runners from Nepal, Tajikistan, and Lesotho come from regions above 1,500 m, with Tajikistan’s runners all originating from elevations over 3,000 m.  

5. **How do socioeconomic factors interact with performance?**
   → Population size emerged as the strongest predictor of performance, while national income (GNI) showed a moderate role. The negative association between GNI and marathon times suggests that higher-income countries may benefit from superior facilities and infrastructure rather than low-income countries performing better due to stronger motivation for economic advancement.  
---

## Regression Table
<img width="882" height="490" alt="C 3 Results table" src="https://github.com/user-attachments/assets/788e8e46-011c-4c98-8cb4-f8493c11f6e1" />

>Across all models, individual-level factors were the strongest predictors of marathon performance. Sex (β ≈ 18, p < .001) and BMI (p < .05) consistently predicted slower finish times, with females and runners with higher BMI showing longer completion times. Country-level population was also a robust negative predictor (β ≈ −1.5, p < .001), indicating faster average performances in more populous countries. **In contrast, birth-region altitude and country altitude showed weak or non-significant effects across models, suggesting limited influence once individual and national characteristics were controlled. Allowing random intercepts and slopes for countries did not substantially change the results, implying that the effect of altitude on performance was largely consistent across countries.**

---

## Future Work
- Incorporate detailed training-location data where available.  
- Examine physiological and cultural factors beyond altitude.  

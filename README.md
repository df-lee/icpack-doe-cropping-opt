```
# DOE Flow: Cropping Stage Parameter Optimization

1. Define Objective
    └─ Reduce burr formation  
       Improve visual yield

2. Select Parameters
    └─ Blade speed, cutting force, tape type, angle, etc.  
       Identify key influential factors

3. Fractional Factorial Design (Screening)
    └─ Resolution IV  
       Eliminate unimportant variables

4. Full Factorial Design
    └─ 3-level experiments  
       Analyze main & interaction effects

5. Response Surface Modeling (CCD)
    └─ Fit quadratic model  
       Generate prediction surface  
       Center point replicates (alpha = 1.414)

6. Model Evaluation
    └─ ANOVA  
       Lack-of-Fit test  
       Canonical analysis

7. Robustness Testing
    └─ Taguchi L9 array  
       Sensitivity check ±5%

8. Validation Experiment
    └─ Pilot trial  
       Confirm burr reduction

9. Final Spec & Documentation
    └─ Parameter recommendations  
       Integrated into process spec

```

| Parameter             | Type           | Unit       | Example Levels           |
|-----------------------|----------------|------------|--------------------------|
| Blade Speed           | Control Factor | rpm        | 3000 / 4000 / 5000       |
| Cutting Force         | Control Factor | N          | 20 / 25 / 30             |
| Blade Material        | Control Factor | —          | Steel / Coated Alloy     |
| Cutting Angle         | Control Factor | °          | 0 / 15 / 30              |
| Tape Adhesion Type    | Control Factor | —          | Type A / Type B          |
| Leadframe Thickness   | Control Factor | mm         | 0.15 / 0.20              |
| Ambient Humidity      | Noise Factor   | %RH        | Low / Medium / High      |
| Room Temperature      | Noise Factor   | °C         | 20 / 25 / 30             |



## 📈 Cropping Stage Parameter Optimization Flow

flowchart LR
    A[1. Define Objective\nReduce burrs\nImprove yield] --> 
    B[2. Select Parameters\nIdentify key factors] --> 
    C[3. Fractional Factorial Design\nResolution IV\nEliminate variables] --> 
    D[4. Full Factorial Design\n3-level DOE\nInteraction effects] --> 
    E[5. Response Surface Modeling\nCCD alpha = 1.414\nQuadratic model fit] --> 
    F[6. Model Evaluation\nANOVA\nLack-of-Fit test\nCanonical analysis] --> 
    G[7. Robustness Testing\nTaguchi L9\n±5% Sensitivity check] --> 
    H[8. Validation Experiment\nPilot trial\nConfirm improvement] --> 
    I[9. Final Spec & Documentation\nRecommend window\nUpdate process spec]


1. Define Objective
    └─ Reduce burr formation  
       Improve visual yield

2. Select Parameters
    └─ Identify key influential factors

3. Fractional Factorial Design
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
## 📐 Parameters Used in Fractional Factorial Design

<div align="center">
    
| Category              | Parameter            | Type           | Unit | Example Levels                                                  |
|:---------------------:|:--------------------:|:--------------:|:----:|:-------------------------------:                                |
| Machine Parameter     | Blade Speed          | Control Factor | rpm  | 3000<br>4000<br>5000                                            |
| Machine Parameter     | Cutting Force        | Control Factor | N    | 20<br>25<br>30                                                  |
| Machine Parameter     | Cutting Angle        | Control Factor | °    | 0<br>15<br>30                                                   |
| Material Parameter    | Blade Material       | Control Factor | —    | High-Speed Steel (HSS)<br>TiAlN-Coated Carbide                  |
| Material Parameter    | Tape Adhesion Type   | Control Factor | —    | Acrylic-Based Pressure-Sensitive Tape (PSA)<br>UV Dicing Tape   |
| Material Parameter    | Leadframe Thickness  | Control Factor | mm   | 0.15<br>0.20                                                    |
| Environment Parameter | Ambient Humidity     | Noise Factor   | %RH  | 25–35<br>45–55<br>65–75                                         |
| Environment Parameter | Room Temperature     | Noise Factor   | °C   | 20<br>25<br>30                                                  |

</div>



# Chapter-2-Individual-Exercise-1-Decision-Tree

Simran Amesar <br>
Matriculation number - 100007050

# California Housing

## Overview
Compares **DecisionTreeRegressor**, **RandomForestRegressor**, and **ExtraTreesRegressor** on California Housing dataset (20,640 samples, house prices in $100k).

## Key Results
| Model          | MSE  | R²    | Rank |
|----------------|------|-------|------|
| Random Forest  | 0.296| **0.774** | **1** |
| Decision Tree  | 0.415| 0.683  | 2    |
| Extra Trees    | 0.419| 0.680  | 3    |

## Findings
- **Random Forest** wins (best generalization via bagging)
- **Ensembles >> Single Tree** (0.77 vs 0.68 R²)
- **MedInc, Latitude/Longitude** dominate feature importance

**Recommended: RandomForestRegressor**

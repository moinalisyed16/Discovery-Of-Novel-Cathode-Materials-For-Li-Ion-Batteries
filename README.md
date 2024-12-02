# Discovery-Of-Novel-Cathode-Materials-For-Li-Ion-Batteries
# ML-Driven Discovery of High-Performance Cathode Materials for Li-Ion Batteries  

This project focuses on leveraging machine learning to discover high-performance cathode materials for Li-ion batteries, addressing the challenges of time-consuming and expensive traditional experimental methods.

## Problem Statement  
Li-ion batteries are widely used in portable electronics, electric vehicles, and renewable energy systems. Discovering new cathode materials is crucial for improving performance but is limited by traditional methods. This project aims to develop ML models to predict properties of new battery materials, specifically targeting **specific discharge capacity at 25 cycles**.

## Methodology  
1. **Data Collection**  
   - Dataset: 170 entries from literature, including cathode material attributes and specific discharge capacities.  
   - Features: Atomic properties and stoichiometric distribution of materials were used to construct descriptors.

2. **Feature Selection**  
   - Random Forest was chosen for its ability to handle non-linear relationships, high-dimensional data, and its robustness to outliers.  
   - Linear and Support Vector Regressions were also evaluated for comparison.  

3. **Models Used**  
   - **Random Forest Regression**: Best results with R² = 0.86 for predicting specific discharge capacity.  
   - **Support Vector Regression**: Effective for theoretical capacity.  
   - **Linear Regression**: Used for baseline comparisons.

4. **Visualization and Optimization**  
   - HEXBIN and Partial Dependency Plots to analyze relationships.  
   - Grid Search for hyperparameter optimization.  

## Results  
- **Model Performance**: Random Forest outperformed other models in predicting specific discharge capacity and capacity retention.  
- **Key Findings**: Predicted values closely matched literature values, confirming the model's accuracy, though some absolute errors persist.  

## Additional Features  
- **GUI Integration**: A Tkinter-based user interface allows non-ML users to input material properties and predict target variables.  

## Conclusion  
This project demonstrates the potential of ML in material discovery, offering a scalable, cost-effective solution for exploring new cathode materials for Li-ion batteries. Random Forest regression emerged as the most effective model for this task.  

## Contributors  
- Ritika Wawge (22M1367)  
- Rahul Humane (22M1358)  
- Moin Ali Syed (22M1352)  

**Guided by:** Prof. Alankar Alankar  
Department of Energy Science and Engineering  
Indian Institute of Technology, Bombay  

---
Explore the repository to find code, data, and further insights!


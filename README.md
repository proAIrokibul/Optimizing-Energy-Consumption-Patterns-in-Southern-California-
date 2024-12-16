# Optimizing Energy Consumption Patterns in Southern California 🌍⚡  

This project focuses on leveraging machine learning to optimize energy consumption patterns, enabling smarter energy management strategies in Southern California. By analyzing energy usage trends, identifying key drivers, and providing actionable insights, this initiative aims to support sustainability efforts and cost-effective energy practices.

---

## 🏗️ Project Overview  

The dataset used in this project captures various energy consumption aspects, including environmental, operational, and structural features such as:  

- **Temperature (°C)**  
- **Humidity (%)**  
- **Lighting Consumption (kWh)**  
- **HVAC Consumption (kWh)**  
- **Occupancy Rate (%)**  
- **Energy Prices ($/kWh)**  
- **Carbon Emission Rate (g CO2/kWh)**  
- **Power Factors, Voltage Levels, and Reactive Power**  
- **Building Properties:** Age, Size, Window-to-Wall Ratio, and Efficiency Ratings  

### **Objective**  
Transform raw energy consumption data into actionable insights using machine learning techniques.  

### **Approach**  
1. Converted the problem from regression to classification.  
2. Implemented machine learning models for multi-class classification to predict energy usage patterns.  
3. Evaluated model performance using accuracy, precision, recall, and F1-score.  

### **Tools and Libraries**  
- **Programming Language:** Python  
- **Key Libraries:** Pandas, NumPy, Scikit-learn, XGBoost  

---

## 📊 Results  

The performance of three machine learning models was analyzed to predict energy consumption classes. Below are the metrics and confusion matrices for each algorithm:

### Logistic Regression  

- **Strengths:** Simple and interpretable baseline model.  
- **Challenges:** Limited performance due to linear decision boundaries.  
- **Metrics:**  
  - Accuracy: **33.42%**  
  - Precision: **33% (average)**  
  - Recall: **33% (average)**  


### Random Forest  

- **Strengths:** Robust to feature interactions and captures non-linear relationships.  
- **Challenges:** Computationally heavier than Logistic Regression.  
- **Metrics:**  
  - Accuracy: **34.18%**  
  - Precision: **34% (average)**  
  - Recall: **34% (average)**  


### XGBoost  

- **Strengths:** Handles imbalanced datasets effectively and identifies complex relationships.  
- **Challenges:** Computationally intensive and requires careful tuning.  
- **Metrics:**  
  - Accuracy: **33.56%**  
  - Precision: **34% (average)**  
  - Recall: **34% (average)**  


---

## 💼 Business Impact  

This project directly supports the energy and sustainability goals of businesses and communities by:  

- **Reducing Operational Costs:** Identifying inefficient energy usage patterns to optimize consumption.  
- **Enhancing Decision-Making:** Providing data-driven insights for energy pricing and resource allocation.  
- **Promoting Sustainability:** Encouraging lower carbon emissions and efficient use of energy resources.  
- **Supporting Policy Development:** Informing policymakers on energy-saving strategies and regulatory decisions.  
- **Boosting Stakeholder Engagement:** Presenting clear, actionable information for better communication and collaboration.

---




 


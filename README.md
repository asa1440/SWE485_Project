# SWE485_Project

## Project title
Fast Food Advisor

## Team Members
1- Nawaf Wael ALdahhasi 443101207

2- Abdullah AlDawood 443105723

3- Moahmmed Alfatesh 443106231

## Motivation
We chose this problem because obesity has become a major global health issue, and frequent consumption of fast food is one of its leading contributors. Since many people rely on fast food due to its convenience and accessibility, completely avoiding it is often unrealistic. Therefore, our goal is to help users make smarter and healthier choices when selecting fast-food meals. By providing personalized nutritional recommendations, our system aims to reduce the negative health impact associated with fast food consumption and promote more balanced eating habits among users. We selected the “Nutritional Fast Food Dataset” from Kaggle because it provides detailed nutrient values (calories, protein, fat, sodium, sugar, carbohydrates, etc.) across multiple fast-food restaurants. These attributes are ideal for building an advice system that tailors recommendations to each user’s nutritional needs.


### Phase 2 – Supervised Learning
In this phase, two supervised models were implemented and compared:
- **Support Vector Machine (SVM)**
- **Multi-Layer Perceptron (MLP Neural Network)**

Both models were trained using the Fast Food Nutrition dataset.  
The goal was to classify food items as **Healthy** or **Unhealthy** based on nutritional values (Calories, Fat, Sugars, Protein).

**Results Summary:**
- **SVM Accuracy:** 0.986  
- **MLP Accuracy:** 1.000  
- MLP achieved perfect accuracy but may indicate *overfitting* due to the small dataset.  
- SVM gave slightly lower accuracy but is expected to generalize better.

📊 *Both models demonstrate the ability to capture nutritional patterns effectively.*

# Recommendation-System
# Recipe Recommendation System - Flavor Fusion 🍽️

Many people, when only a few ingredients are available in their homes, don’t think it is possible to make a dish they like or even any dish at all. Hence, they often turn to ordering food online.

Our goal is to recommend dishes they like based on the ingredients available to them. This system aims to encourage users to choose homemade food over restaurant-made food while introducing them to new recipes and cuisines.

---

## 🚀 Features
- Recommends recipes based on the user's available ingredients.
- Provides a nutrition sensitivity feature for tailored recommendations.
- Suggests recipes from a variety of cuisines to enhance culinary exploration.

---

## 🛠️ Implementation Details
1. **Data Analysis:**
   - Calculated the top 20 most-rated recipes from the dataset.
   - Created user embeddings based on their ratings for these top 20 recipes.

2. **User Interaction:**
   - For new users, the system requests ratings for the top 20 recipes to create personalized recommendations.
   - Incorporates Natural Language Processing (NLP) to analyze user reviews and enhance recommendation accuracy.

3. **Recommendation System:**
   - Used collaborative filtering to recommend recipes that match user preferences.
   - Ensured compatibility with available ingredients through ingredient-based filtering.

---

## 💡 Objective
- Empower users to cook at home by recommending dishes based on the ingredients they already have.
- Reduce reliance on restaurant-made food and promote healthier eating habits.
- Introduce users to new recipes and cuisines for a diverse dining experience.

---

## 🛠️ Tools & Technologies
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, scikit-learn, NLTK, Matplotlib

---

## 🌟 How It Works
1. A user provides a list of available ingredients.
2. The system filters recipes compatible with those ingredients.
3. Recommendations are refined using collaborative filtering based on user ratings of the top 20 recipes.
4. A final list of dishes is suggested to the user.

---


---

## 📈 Results
- Enhanced user satisfaction by recommending dishes tailored to their preferences and available ingredients.
- Promoted homemade cooking and reduced dependency on online food delivery services.

---

---

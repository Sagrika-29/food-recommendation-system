# food-recommendation-system
# 🍽️ Time-Aware Food Recommendation System

## 📌 Overview
This project presents a hybrid food recommender system that integrates deep learning and graph clustering to deliver personalized, time-sensitive meal suggestions. It addresses key challenges like ingredient awareness, cold-start problems, and evolving user preferences over time.

## 🔍 Key Features

### ✅ Ingredients-Aware Recommendations
- Combines content-based filtering (food ingredients) with collaborative filtering (user ratings).
- Avoids recommending foods with allergens or disliked ingredients.

### ⏰ Time-Aware Personalization
- Captures changes in user preferences across different times of day and seasons.
- Uses temporal embeddings and dynamic clustering to adapt recommendations.

### 🤝 Trust & Community Modeling
- Builds a trust network using follower-following relationships.
- Enhances prediction accuracy for cold-start users and items.

### 🧠 Deep Learning + Graph Clustering
- Applies RNNs/LSTMs for sequential user behavior.
- Uses graph-based clustering to group similar users and food items.

## 🛠️ Tech Stack

| Layer         | Tools & Frameworks                         |
|--------------|---------------------------------------------|
| Language      | Python                                      |
| Front-End     | HTML, CSS, JavaScript                       |
| Back-End      | Django ORM                                  |
| Database      | MySQL (via WAMP Server)                     |
| ML Frameworks | PyTorch, TensorFlow, Keras                  |
| Graph Tools   | NetworkX, PyTorch Geometric, Apache Spark   |

## 🚀 How to Run (Coming Soon)
Setup instructions and runnable scripts will be added once the model is finalized.

## 📊 Evaluation Metrics
- Precision, Recall, F1 Score
- AUC (Area Under Curve)
- NDCG (Normalized Discounted Cumulative Gain)

## 🎯 Outcome
A scalable, intelligent system that adapts to user behavior and time context, promoting healthier eating habits and personalized food discovery.

## 🌱 Future Scope
- Integration with wearable health devices
- Real-time feedback loop for adaptive learning
- Cultural and regional food personalization
- Restaurant and smart kitchen integration

## 📚 References
Includes academic papers, datasets from Allrecipes.com, and tools like NetworkX, PyTorch Geometric, and TensorFlow.


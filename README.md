🏠 House Price Prediction using Naive Bayes
📘 Overview

This mini-project applies Artificial Intelligence (AI) and Machine Learning (ML) techniques to predict the price category of houses using the Naive Bayes algorithm.
It classifies homes into Low, Medium, or High price ranges based on key features such as area, number of rooms, and furnishing type.

🧠 Objective

To develop an AI model that learns from past housing data and predicts the price range for new properties using probabilistic reasoning.

⚙️ Algorithm Used: Naive Bayes Classifier

Based on Bayes’ Theorem

Assumes independence among features

Simple, fast, and suitable for categorical and small datasets

Used for classification problems like price category prediction

𝑃
(
𝐶
𝑙
𝑎
𝑠
𝑠
∣
𝐹
𝑒
𝑎
𝑡
𝑢
𝑟
𝑒
𝑠
)
=
𝑃
(
𝐹
𝑒
𝑎
𝑡
𝑢
𝑟
𝑒
𝑠
∣
𝐶
𝑙
𝑎
𝑠
𝑠
)
×
𝑃
(
𝐶
𝑙
𝑎
𝑠
𝑠
)
𝑃
(
𝐹
𝑒
𝑎
𝑡
𝑢
𝑟
𝑒
𝑠
)
P(Class∣Features)=
P(Features)
P(Features∣Class)×P(Class)
	​

📊 Datasets Used
File Name	Description
house_data.csv	Training dataset containing historical house features and price categories.
new_houses.csv	Test dataset containing new house details for which price predictions are generated.

Key Columns:
Area, Bedrooms, Bathrooms, Stories, Parking, Furnishing, Price_Category

🚀 How the Model Works

The model is trained on house_data.csv.

It learns relationships between features and price categories.

It predicts the price category and approximate range for each house in new_houses.csv.

Example Output:

Area	Bedrooms	Bathrooms	Furnishing	Predicted_Category	Approx_Price_Range
1500	3	2	Semi-Furnished	Medium	₹40–80 Lakhs
2000	3	2	Furnished	High	₹80 Lakhs–₹1.5 Crore
🧩 Project Files
File	Description
house_prediction_project.ipynb	Main Jupyter Notebook with full Python code, training, testing, and output.
house_data.csv	Training dataset.
new_houses.csv	Testing dataset.
Screenshot 2025-10-28 183949.png	Model accuracy output.
Screenshot 2025-10-28 184032.png	Prediction result output.
🖼️ Output Screenshots

Model Accuracy Output:


Prediction Results:


🧰 Tech Stack

Language: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib

Platform: Google Colab / Jupyter Notebook

Algorithm: Gaussian Naive Bayes

🎯 Expected Outcome

Predicts Low / Medium / High price category

Displays approximate cost range (₹20L–₹1.5Cr)

Demonstrates AI-based decision making using probabilistic reasoning

📄 Conclusion

This project showcases how Naive Bayes classification can effectively be used in AI-based decision systems for real estate valuation.
It provides a fast, interpretable, and accurate method for predicting house prices based on multiple categorical and numerical features.

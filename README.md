# Naive Bayes Classifier on Social Network Ads Dataset

This Google Colab notebook demonstrates an implementation of the **Naive Bayes** classification algorithm using the Social Network Ads dataset. The model predicts whether a user purchases a product based on their age and estimated salary. **This project can be easily adapted to work with other datasets** containing different or additional independent variables.

## 📊 Dataset Overview

- Dataset: `Social_Network_Ads.csv`
- Features: Age, Estimated Salary
- Target: Purchased (0 or 1)

## 🚀 Getting Started

### 1. Clone the Repository or Upload the Notebook

```bash
git clone https://github.com/MaddyRizvi/Naive-Bayes_social_network_analysis.git
```

Or simply upload the notebook to [Google Colab](https://colab.research.google.com/) and start running the cells.

### 2. Upload the Dataset

Make sure to upload `Social_Network_Ads.csv` to your Colab session by using the file upload tool.

```python
from google.colab import files
uploaded = files.upload()
```

### 3. Run the Notebook

The notebook includes the following steps:

- Data loading and preprocessing
- Train-test split
- Feature scaling using `StandardScaler`
- Training a `GaussianNB` classifier
- Prediction and evaluation
- Visualization of decision boundaries

## 📈 Output

- Predicted output for a sample input: `[30, 87000]`
- Confusion Matrix and Accuracy Score
- Visualizations for both Training and Test sets
- ![Image](https://github.com/user-attachments/assets/05f3f49d-178d-41c8-bd59-40bbaeb3f540)
- ![Image](https://github.com/user-attachments/assets/0a6f9a68-00d2-4a41-ba97-fae21c72e480)
  
## 🧠 Libraries Used

- numpy
- pandas
- matplotlib
- scikit-learn

## 🖼️ Visualizations

The notebook contains plots showing the decision boundary of the Naive Bayes classifier over the training and test data.

## 📂 Folder Structure

```
├── NaiveBayes_SocialNetworkAds.ipynb
├── Social_Network_Ads.csv
├── README.md
└── CONTRIBUTING.md
```

## 🤝 Contributing

Contributions are welcome! Please refer to the [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

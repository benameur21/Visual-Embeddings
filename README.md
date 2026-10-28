# Visual Embeddings

## 📌 Project Description

This project explores visual embeddings using **MobileNetV2** pretrained on ImageNet and the Oxford-IIIT Pet dataset. It aims to extract numerical representations of images and evaluate their ability to identify visually similar images.

## 🎯 Objectives

- Extract 1280-dimensional image embeddings using MobileNetV2.
- Measure image similarity using cosine similarity.
- Retrieve the Top-5 most similar images.
- Evaluate retrieval performance using Precision@5.
- Visualize embeddings in 2D using Principal Component Analysis (PCA).
- Apply K-Means clustering to group images based on visual features.
- Explore the impact of fine-tuning on the quality of visual representations.

## 🛠️ Technologies

- Python
- TensorFlow / Keras
- TensorFlow Datasets
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## 📂 Dataset

The project uses the **Oxford-IIIT Pet Dataset**, which contains images of cats and dogs belonging to different breeds.

## ⚙️ Methodology

1. Load and preprocess the images.
2. Extract visual features using MobileNetV2.
3. Generate 1280-dimensional embeddings using Global Average Pooling.
4. Calculate cosine similarity between image embeddings.
5. Retrieve the Top-5 most similar images.
6. Evaluate retrieval quality using Precision@5.
7. Apply PCA and K-Means to visualize and analyze the embeddings.
8. Compare pretrained and fine-tuned models.

## 📊 Evaluation

The project evaluates the quality of visual representations through:

- **Cosine Similarity:** Measures the similarity between image embeddings.
- **Top-5 Retrieval:** Retrieves the five images most similar to a query image.
- **Precision@5:** Measures the proportion of retrieved images belonging to the same breed as the query.
- **PCA:** Reduces the dimensionality of embeddings to visualize their distribution.
- **K-Means:** Groups images according to their visual representations.

## 🚀 Getting Started

1. Open the notebook in Google Colab.
2. Install or import the required libraries.
3. Load the Oxford-IIIT Pet dataset.
4. Run the notebook cells in order to extract embeddings and perform the experiments.

## 📁 Project Structure

```text
Visual-Embeddings/
├── TP4_Embeddings_Visuels.ipynb
└── README.md
```

## 👤 Author

**Islem Ben Ameur**

## 📄 License

This project was developed for educational purposes.

# DeepWeeds Classification

As technology advances, agriculture is poised for a transformation with the integration of intelligent systems like robotic weed control. However, effective deployment of these systems hinges on accurately classifying weed species, which is crucial for their efficiency as farmers in Australia alone spend AUD1.5 billion on weed management activities and lose a further AUD2.5 billion due to reduced crop yields (Olsen, 2019). This project aims to tackle the challenge of weed classification to enhance robotic systems, offering farmers a powerful tool for precise weed management. By addressing this issue, we can significantly improve crop yields and reduce ecological damage, paving the way for more sustainable and productive agricultural practices.

## Details

The DeepWeeds dataset contains 17,509 images capturing eight distinct weed species native to Australia, photographed in situ alongside neighboring flora. These weed species include Chinee apple (0), Lantana (1), Parkinsonia (2), Parthenium (3), Prickly acacia (4), Rubber vine (5), Siam weed (6), and Snake weed (7). The dataset originates from a 2019 study published in Nature by Alex Olsen, a renowned expert in image processing for agricultural applications, ensuring high reliability and quality of the data.

Project Structure
Our project is divided into three key sections:

1. Data Preprocessing:
- Addressing class imbalance using undersampling techniques.
- Preprocessing images by applying: Resizing and normalization, Edge detection to highlight critical features, Feature extraction, and dimensionality reduction using PCA (Principal Component Analysis) and LDA (Linear Discriminant Analysis).

2. Model Training:
- Linear Models: k-Nearest Neighbors (kNN), Random Forest, and SVM.
- Deep Learning Models: Convolutional Neural Networks (CNNs).

3. Model Evaluation:
- Classification reports and confusion matrices.
- Advanced interpretability techniques like GradCAM to visualize CNN decision-making.

This structured approach ensures thorough exploration of the dataset, robust model training, and insightful evaluation, paving the way for accurate weed classification and potential real-world applications in agricultural management.
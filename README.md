# DeepWeeds Classification

As technology advances, agriculture is poised for a transformation with the integration of intelligent systems like robotic weed control. However, effective deployment of these systems hinges on accurately classifying weed species, which is crucial for their efficiency as farmers in Australia alone spend AUD1.5 billion on weed management activities and lose a further AUD2.5 billion due to reduced crop yields (Olsen, 2019). This project aims to tackle the challenge of weed classification to enhance robotic systems, offering farmers a powerful tool for precise weed management. By addressing this issue, we can significantly improve crop yields and reduce ecological damage, paving the way for more sustainable and productive agricultural practices.

## Details

The DeepWeeds dataset consists of 17,509 images capturing eight different weed species native to Australia in situ with neighbouring flora: Chinee apple (0), Lantana (1), Parkinsonia (2), Parthenium (3), Prickly acacia (4), rubber vine (5), siam weed (6), and snake weed (7).The data was sourced from a 2019 Nature study led by Alex Olsen, an expert in image processing for agricultural applications, highlighting the dataset’s reliability.  

Our project comprises 3 main sections:

1. Data Preprocessing - dealing with imbalanced data using undersampling and doing feature engineering using PCA.

2. Model Training - Linear Models(kNN, Random Forest and SVM) and CNNs.

3. Model Evaluation - Visualizing the results using confusion matrix, GradCAM..
# This is a repository to try different computer vision architectures and techniques.
PLANETS AND MOONS DATASET - AI IN SPACE 
1. DATASET OVERVIEW
The Planets and Moons dataset consists of 8 confirmed planets, 2 dwarf planets, and Earth's Moon — totaling 11 classes. Each class contains approximately 149 optimized 3D photos. The dataset was collected by Emirhan BULUT and licensed under CC BY-NC 4.0, prohibiting commercial use.
2. LIBRARIES AND IMPORTS
Key libraries used include TensorFlow, Keras, NumPy, Pandas, Seaborn, Matplotlib, and Scikit-learn. These were used for image processing, model building, evaluation, and visualization.
3. DATA PREPARATION
Images were loaded using ImageDataGenerator with rescaling and data augmentation applied. A stratified 5-fold cross-validation split was performed to ensure balanced distribution across folds. Each fold generated training, validation, and test CSV files.
A class distribution plot confirmed that all 11 classes were evenly represented, ensuring balanced training.

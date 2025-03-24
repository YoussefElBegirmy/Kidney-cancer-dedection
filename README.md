# Kidney-cancer-dedection
Data & Preprocessing:
Kaggle data
https://www.kaggle.com/datasets/nazmul0087/ct-kidney-dataset-normal-cyst-tumor-and-stone
https://www.kaggle.com/datasets/raagbhutani/kidneystone
). Using data augmentation and oversampling, we boosted our dataset to 20K images 📈, ensuring robust training with stratified sampling for balanced splits.
Custom CNN Architecture:
 Our model features 4 convolutional layers with LeakyReLU activations, BatchNormalization, and MaxPooling, capped off with GlobalMaxPooling2D and dense layers for effective feature extraction. Optimized with the Adam optimizer (learning rate = 0.0001) and trained using categorical crossentropy, our model achieved an impressive 93% accuracy! 🎯
Clinical Impact:
 This tool is set to revolutionize kidney cancer diagnostics by:
Accelerating Diagnosis: Cutting down the time per CT scan ⏱️, so doctors can focus more on patient care.
Enhancing Accuracy: Early detection saves lives and streamlines clinical workflows.
Reducing Workload: Less charting means more meaningful patient interactions and reduced burnout ❤️.

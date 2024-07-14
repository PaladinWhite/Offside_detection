# Offside Detection

**Professor** : Irene Amerini

**Content** : Project for Computer Vision exam 2023/2024.

**Setup** :

To run this code you should have the dataset. You can follow one of this methods:

1. Use the same dataset on which the project haas been run
2. Generate another dataset

## Method 1
1. Go to the following links:

   - Dataset : https://drive.google.com/drive/folders/1XujJW_Uwcp3TxbiA62u23ZimPOknAn_k?usp=drive_link
   - Training set : https://drive.google.com/drive/folders/19bLjkROrC2L8pJZTxikHkQ9VGl97g1es?usp=drive_link
   - Validation set : https://drive.google.com/drive/folders/1sOMD51rWBeXKaeEee3aHz2kXNdLcyrYW?usp=drive_link
   - Test set : https://drive.google.com/drive/folders/1ZXOhnmFf7ChcRT8OGLgeMNGUC8C8B7Yy?usp=drive_link

2. Copy the folders in your own Drive. So you should have:

   <img width="900" alt="image" src="https://github.com/user-attachments/assets/9aaf84e4-8917-459f-911f-528bc495d517">

3. Substitute the path in the colab notebooks **Computer_Vision_based.ipynb** and **Deep_Learning_based.ipynb** with the paths in your drive:

   3.1 In CV based notebook substitute:

   <img width="539" alt="image" src="https://github.com/user-attachments/assets/d8f1463a-8ea9-44bc-b038-c4ec3b9d62d0">

   **Attention** : don't run the cell **SPLIT DATASET**, because your dataset already splitted!

   3.2 In DL based notebook susbtitute:

   <img width="539" alt="image" src="https://github.com/user-attachments/assets/c08d135d-d5d7-4dc8-b89c-6c0baf43bb86">

## Method 2
1. Open the notebook **Dataset.ipynb**
2. Define the destination path for the dataset:

   <img width="517" alt="image" src="https://github.com/user-attachments/assets/8c16b965-f9c7-47e6-9cf2-96bdeb15950a">

3. Generate the dataset, and use this path in  CV based to split it.


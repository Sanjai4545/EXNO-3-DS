## EXNO-3-DS

# AIM:
To read the given data and perform Feature Encoding and Transformation process and save the data to a file.

# ALGORITHM:
STEP 1:Read the given Data.
STEP 2:Clean the Data Set using Data Cleaning Process.
STEP 3:Apply Feature Encoding for the feature in the data set.
STEP 4:Apply Feature Transformation for the feature in the data set.
STEP 5:Save the data to the file.

# FEATURE ENCODING:
1. Ordinal Encoding
An ordinal encoding involves mapping each unique label to an integer value. This type of encoding is really only appropriate if there is a known relationship between the categories. This relationship does exist for some of the variables in our dataset, and ideally, this should be harnessed when preparing the data.
2. Label Encoding
Label encoding is a simple and straight forward approach. This converts each value in a categorical column into a numerical value. Each value in a categorical column is called Label.
3. Binary Encoding
Binary encoding converts a category into binary digits. Each binary digit creates one feature column. If there are n unique categories, then binary encoding results in the only log(base 2)ⁿ features.
4. One Hot Encoding
We use this categorical data encoding technique when the features are nominal(do not have any order). In one hot encoding, for each level of a categorical feature, we create a new variable. Each category is mapped with a binary variable containing either 0 or 1. Here, 0 represents the absence, and 1 represents the presence of that category.

# Methods Used for Data Transformation:
  # 1. FUNCTION TRANSFORMATION
• Log Transformation
• Reciprocal Transformation
• Square Root Transformation
• Square Transformation
  # 2. POWER TRANSFORMATION
• Boxcox method
• Yeojohnson method

# CODING AND OUTPUT:
![DS exp 3 ipynb - Colab_page-0001](https://github.com/user-attachments/assets/76f69589-f93b-46a7-ba85-e6025bc0a293)
![DS exp 3 ipynb - Colab_page-0002](https://github.com/user-attachments/assets/7c24386e-e00f-4073-91cd-1a2f7adea8a3)
![DS exp 3 ipynb - Colab_page-0003](https://github.com/user-attachments/assets/8af451ab-e016-49e1-815f-9062c1fa10d0)
![DS exp 3 ipynb - Colab_page-0004](https://github.com/user-attachments/assets/7a7bb255-4689-4dd7-815a-efb8a98a3347)
![DS exp 3 ipynb - Colab_page-0005](https://github.com/user-attachments/assets/e5f781a0-a061-4e25-a0e1-41d471dff8dd)
![DS exp 3 ipynb - Colab_page-0006](https://github.com/user-attachments/assets/05f169d9-cf81-4701-8227-96295dc96172)
![DS exp 3 ipynb - Colab_page-0007](https://github.com/user-attachments/assets/aade151d-34de-4694-9a86-dbb89e7c9954)
![DS exp 3 ipynb - Colab_page-0008](https://github.com/user-attachments/assets/88c405c3-e3a4-4eb4-8af5-a486acd809d2)
![DS exp 3 ipynb - Colab_page-0009](https://github.com/user-attachments/assets/fa2fc989-3ac7-441a-b74b-2a3d166f2aee)

# RESULT:
       Thus we have read and performed Feature Encoding and Transformation process and save the data to a file

       

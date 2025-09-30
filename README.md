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

```
Developed by: Rishab p doshi
Register No: 212224240134
```
<img width="430" height="277" alt="Screenshot 2025-09-30 105200" src="https://github.com/user-attachments/assets/e25da9d6-39a7-44f3-b4a9-ca71718845f1" />
<img width="572" height="277" alt="Screenshot 2025-09-30 105218" src="https://github.com/user-attachments/assets/8758c975-f2b3-4713-880f-4d554f782250" />
<img width="365" height="409" alt="Screenshot 2025-09-30 105230" src="https://github.com/user-attachments/assets/e921bea4-c878-4264-ad4f-b90ac3120010" />
<img width="387" height="442" alt="Screenshot 2025-09-30 105241" src="https://github.com/user-attachments/assets/dea9dc44-67e7-4cee-8265-573eb55685f2" />
<img width="736" height="487" alt="Screenshot 2025-09-30 105251" src="https://github.com/user-attachments/assets/453e7034-39c9-47b4-aba6-1e8055384a6b" />
<img width="923" height="397" alt="Screenshot 2025-09-30 105302" src="https://github.com/user-attachments/assets/95ca6f3a-ed60-47f0-8408-6ca9be9214fa" />
<img width="1227" height="287" alt="Screenshot 2025-09-30 105330" src="https://github.com/user-attachments/assets/b1580f74-977c-43d0-8994-af5cd51cae82" />
<img width="502" height="429" alt="Screenshot 2025-09-30 105339" src="https://github.com/user-attachments/assets/42f4a9dc-82be-43d3-b47e-392c1c99f545" />
<img width="558" height="433" alt="Screenshot 2025-09-30 105346" src="https://github.com/user-attachments/assets/beaeb81b-7df2-4602-9c56-9056797a9a82" />
<img width="702" height="416" alt="Screenshot 2025-09-30 105354" src="https://github.com/user-attachments/assets/087cc911-7055-4339-b4d9-724b77a9a7da" />
<img width="646" height="481" alt="Screenshot 2025-09-30 105406" src="https://github.com/user-attachments/assets/e5a4543a-986f-4224-9fb3-d653110c2861" />
<img width="836" height="532" alt="Screenshot 2025-09-30 105415" src="https://github.com/user-attachments/assets/bfda5f21-2a6a-46fe-abb2-0f1b91e89908" />
<img width="339" height="231" alt="Screenshot 2025-09-30 105423" src="https://github.com/user-attachments/assets/c76bdab6-a6fa-42f6-932c-7ba22caba1d2" />
<img width="266" height="489" alt="Screenshot 2025-09-30 105441" src="https://github.com/user-attachments/assets/bf36b5aa-3ade-4ff1-8894-a4c5e13a7254" />
<img width="356" height="465" alt="Screenshot 2025-09-30 105452" src="https://github.com/user-attachments/assets/b9af13a7-6251-424f-a4a5-82db46238809" />
<img width="311" height="493" alt="Screenshot 2025-09-30 105501" src="https://github.com/user-attachments/assets/ff49416f-167e-4113-9133-a0f762630dee" />
<img width="289" height="493" alt="Screenshot 2025-09-30 105509" src="https://github.com/user-attachments/assets/54d2cd4a-40d9-4ade-b024-9678f3725931" />
<img width="1049" height="465" alt="Screenshot 2025-09-30 105522" src="https://github.com/user-attachments/assets/d8b3f693-3963-4e15-bde3-3a112169212f" />
<img width="815" height="324" alt="Screenshot 2025-09-30 105532" src="https://github.com/user-attachments/assets/d2a61e1f-63b9-4809-881c-2040c75db1bd" />
<img width="1453" height="521" alt="Screenshot 2025-09-30 105558" src="https://github.com/user-attachments/assets/00d03a87-3ee7-41c3-a3bc-ea59238f2e82" />
<img width="691" height="557" alt="Screenshot 2025-09-30 105608" src="https://github.com/user-attachments/assets/d3f361e7-eaf5-4de6-a2ee-7af731ae3c09" />
<img width="724" height="501" alt="Screenshot 2025-09-30 105614" src="https://github.com/user-attachments/assets/4e33b17c-f3ea-497e-a508-48838cfd2f3f" />
<img width="680" height="564" alt="Screenshot 2025-09-30 105622" src="https://github.com/user-attachments/assets/d6924504-87ba-4309-9efc-f733a98f77e6" />
<img width="645" height="547" alt="Screenshot 2025-09-30 105630" src="https://github.com/user-attachments/assets/a53dbdcd-db2c-42da-befb-54768a33319f" />
<img width="1196" height="481" alt="Screenshot 2025-09-30 105655" src="https://github.com/user-attachments/assets/3c6b1466-d7d6-490d-a844-f5cbda7da13a" />
<img width="602" height="560" alt="Screenshot 2025-09-30 105703" src="https://github.com/user-attachments/assets/dbb5147f-d0cf-4581-8853-6d4aba71ac64" />
<img width="630" height="511" alt="Screenshot 2025-09-30 105712" src="https://github.com/user-attachments/assets/189724ab-ec6b-44ad-a57c-ba20475a6a7e" />










# RESULT:
Thus the given data, Feature Encoding, Transformation process and save the data to a file was performed successfully.

       

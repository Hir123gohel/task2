# task2
**company name**:CodTechIT
**Name**:Hir Gohel Paragbhai
**offerId**:CT08DS415
**University name**:GSFC University
**Domain**:Data anylytics
**Duration**:dec 5th 2024 to jan 5th 2025
**task name**:exploratory data anaylsis
**mentor name**:Neela santhosh kumar
**overview**:# Check columns with missing data
print("\nMissing Values in Each Column:")
print(df.isnull().sum())

# Fill missing Age with median value
df['Age'].fillna(df['Age'].median(), inplace=True)

# Drop Cabin column (too many missing values)
df.drop(columns=['Cabin'], inplace=True)

# Fill missing Embarked with mode value
df['Embarked'].fillna(df['Embarked'].mode()[0], inplace=True)

print("\nMissing Values After Imputation:")
print(df.isnull().sum())
![image](https://github.com/user-attachments/assets/455620e2-d09a-4a28-8e5b-fb80938fbcb9)
![image](https://github.com/user-attachments/assets/6719f968-276f-4846-9940-99913eab501a)
![image](https://github.com/user-attachments/assets/b427a1cd-cf85-4079-9589-49e20ebbba4c)
![image](https://github.com/user-attachments/assets/6fe31064-2ac8-4500-8eff-1fa98faee831)
![image](https://github.com/user-attachments/assets/40517ecf-ce92-4684-8a9b-345cbc5b5ef0)
![image](https://github.com/user-attachments/assets/58297ce8-7aa3-46ec-bcc8-fab5f5d1d4cf)
![image](https://github.com/user-attachments/assets/3dda31c5-60f0-4810-bb7d-55f9bc7e70fd)
![image](https://github.com/user-attachments/assets/b1f96ca7-8708-485d-97f3-e55d91bfee32)
![image](https://github.com/user-attachments/assets/b9e1203c-42ec-402a-a804-233b2e6e7035)
![image](https://github.com/user-attachments/assets/d7fb13ed-2785-4581-9a9f-474e1739f9a6)
![image](https://github.com/user-attachments/assets/f43b223f-1086-4f65-b21c-63b6e8d9ec4e)

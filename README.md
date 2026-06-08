Student Performance Analysis Using Data Science (250 Students Dataset)

1.Overview

In today’s education system, understanding student performance is essential for improving academic outcomes and providing personalized support. This project, titled “Student Performance Analysis”, focuses on analyzing the academic data of 250 students using data science techniques.

The project aims to explore how different factors such as subject marks, attendance percentage, and internal assessment scores contribute to a student’s overall performance. By applying data preprocessing, exploratory analysis, and machine learning algorithms, meaningful insights are generated.

Additionally, a predictive model is developed to estimate student performance, which can be useful for educators to identify students who may require extra attention.

2. Dataset Description

The dataset used in this project is synthetically generated to simulate a real-world academic environment. It contains 250 student records, each representing an individual student.

Dataset Features: Student_ID: Unique identifier assigned to each student Name: Student name generated using the Faker library Gender: Male or Female Department: CSE, IT, or ECE Year: Academic year (1st, 2nd, 3rd) Maths Marks: Scores between 50 and 100 Science Marks: Scores between 50 and 100 English Marks: Scores between 40 and 100 Attendance (%): Percentage between 50 and 100 Internal Marks: Scores between 2 and 25

The dataset is designed to closely resemble real academic data used in educational institutions.

3. Objectives of the Project

The main objectives of this project include:

To analyze student academic performance using structured data To identify key factors that influence student success To perform data cleaning and preprocessing To conduct exploratory data analysis (EDA) To develop a machine learning model for performance prediction To generate insights that can help improve teaching strategies 4. Project Highlights Creation of a realistic dataset using Faker Implementation of complete data preprocessing pipeline Detailed exploratory analysis with multiple perspectives Development of predictive machine learning models Visualization of data for better understanding Generation of actionable insights 5. Data Preprocessing

Data preprocessing is a critical step that ensures the dataset is clean, consistent, and suitable for analysis.

Steps Performed: 1.Handling Missing Values: Missing values are identified using isnull() and handled appropriately using techniques like forward fill or mean substitution. 2.Removing Duplicates: Duplicate entries are removed to maintain data integrity. 3.Encoding Categorical Variables: Text-based columns such as Gender, Department, and Year are converted into numerical values using Label Encoding. 4.Feature Scaling: Numerical features are standardized using StandardScaler to ensure uniformity in data distribution. 5.Feature Selection: Irrelevant columns such as Student_ID and Name are removed before modeling. These preprocessing steps improve the quality of data and enhance model performance.

6. Exploratory Data Analysis (EDA)

EDA is performed to understand the structure and relationships within the dataset.

Key Analyses: *Distribution of marks across different subjects *Department-wise comparison of performance *Gender-based academic trends *Relationship between attendance and academic scores *Correlation analysis between features Insights from EDA: *Students with higher attendance generally score better *Internal marks have a strong impact on final performance *Slight variations exist across departments *EDA provides a deeper understanding of the dataset and guides model building.

7. Data Visualization

Visualization techniques are used to present insights clearly and effectively.

Types of Visualizations: Bar Charts: Compare subject-wise marks Pie Charts: Show gender and department distribution Scatter Plots: Analyze attendance vs marks relationship Heatmaps: Display correlations between variables

👉 Visualization enhances understanding and communication of results.

8. Tools and Technologies Used

The project is implemented using the following tools and libraries:

Python – Core programming language Pandas – Data manipulation and analysis NumPy – Numerical computations Matplotlib – Basic data visualization Seaborn – Advanced visualization Scikit-learn – Machine learning algorithms Faker – Synthetic data generation 9. Results and Findings

The analysis and model implementation led to the following conclusions:

Attendance plays a significant role in academic performance Internal marks strongly influence final results Students from different departments show slight performance variation The machine learning model provides accurate and reliable predictions

👉 These findings can help improve academic strategies.

10. Pipeline Workflow

The project follows a structured pipeline:

Data Generation Data Collection and Loading Data Cleaning Data Preprocessing Exploratory Data Analysis Model Training Model Evaluation Prediction Generation 11. Generating Predictions

The trained model can be used to predict student performance:

Input new student data (marks, attendance, etc.) Model processes the input Output is predicted performance score

👉 This helps identify students who may need academic support.

12. Future Enhancements

The project can be improved in several ways:

Use real-world academic datasets Apply advanced algorithms like XGBoost or Neural Networks Include additional features such as study hours and extracurricular activities Develop a web-based application Integrate dashboards using Power BI or Tableau 13. Applications

This project has practical applications in education:

Monitoring student progress Identifying weak students Supporting teachers in decision-making Enhancing academic performance strategies 14. Limitations Dataset is synthetic and may not reflect real-world complexity Limited number of features Small dataset size (250 students)

OUTPUT SCREENSHOTS
<img width="556" height="417" alt="image" src="https://github.com/user-attachments/assets/d9b67fd2-5573-400a-bb2e-b1e7ade10eca" />
<img width="557" height="417" alt="image" src="https://github.com/user-attachments/assets/dfe909a3-d790-47ea-9bac-927d7c094bf8" />
<img width="551" height="427" alt="image" src="https://github.com/user-attachments/assets/9686cf29-d0bc-41f3-97a7-0952f47053f5" />
<img width="511" height="417" alt="image" src="https://github.com/user-attachments/assets/76003fb6-7eb5-427e-9f2b-a8de42636070" />
<img width="502" height="421" alt="image" src="https://github.com/user-attachments/assets/9816786c-c999-4384-a7bc-e137c6031e22" />
<img width="567" height="416" alt="image" src="https://github.com/user-attachments/assets/7fb3e94b-9246-41d0-80be-fc134ba9b5f5" />
<img width="546" height="413" alt="image" src="https://github.com/user-attachments/assets/aebf9422-e90f-4f3f-9f6f-b747d6a39b68" />
<img width="548" height="397" alt="image" src="https://github.com/user-attachments/assets/e2107e12-fed2-44ca-b27d-a0be1511ba03" />
<img width="687" height="478" alt="image" src="https://github.com/user-attachments/assets/455c72f0-1ee4-406a-b1f0-d095681a5b40" />
<img width="503" height="358" alt="image" src="https://github.com/user-attachments/assets/0e9d4f53-af53-4a45-8b37-d68a33e82341" />










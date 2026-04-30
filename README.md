# -Retail-Supplier-Delivery-Time-Analysis-project
Retail Supplier Delivery Time Analysis
MINOR-II PROJECT (FM: 100 | PM: 40)Institute Information
College: Rungta College of Engineering & Technology (RCET), Bhilai
Course: B.Tech (Computer Science and Engineering)
Semester: 4th SemesterStudent 
Name: Md Rizwan Ali Khan 
Project OverviewThis project focuses on evaluating supplier reliability by analyzing delivery lead times. In a retail environment, inconsistent delivery schedules can lead to stockouts.Goal: Use Python to calculate performance metrics and visualize lead-time variability.Significance: Identifying suppliers with high variance helps businesses mitigate supply chain risks.Technical ImplementationThe project utilizes Pandas for data manipulation and Matplotlib for statistical visualization.1. Data ProcessingThe dataset consists of supplier names and their respective delivery durations (in days).Pythonimport pandas as pd

2. Statistical AnalysisWe group the data by supplier to calculate the Mean ($\mu$) and Standard Deviation ($\sigma$).Mean: Represents the average delivery time.Standard Deviation: Measures the consistency. A higher $\sigma$ indicates an unreliable supplier.3. Visualization (Box Plot)A box plot is used to detect outliers. For instance, in the code provided, Supplier B shows a delivery time of 10 days, which is a significant outlier compared to its other entries (2 and 3 days).Python# Visualizing trends

Results and ObservationsSupplier A: Highly consistent with a standard deviation of 1.0.Supplier B: High risk. Although the mean is 5.0, the standard deviation is 4.35, indicating extreme unpredictability.Supplier C: The most reliable supplier with the lowest standard deviation of 0.57.Tools and TechnologiesLanguage: Python 3.xLibraries: Pandas (Data Crunching), Matplotlib (Plotting)Environment: Jupyter Notebook / VS CodeAcademic Integrity DeclarationThis project is an original implementation developed for the Minor-II requirement at RCET. All code and analysis comply with the institutional Academic Integrity Policy.

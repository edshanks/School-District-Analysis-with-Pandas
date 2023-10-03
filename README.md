# School District Analysis with Pandas
This project aims to analyze data from a school district's public high schools and its students in order to find correlations between a school's size, type (district or charter), and spending per student, and the performance of its students. All calculations and aggregations were performed, stored, and displayed with the Pandas module in Python.

<h3>Raw Data</h3>

Student Data <br>
![](screenshots/student_data.png)<br>

School Data <br>
![](screenshots/school_data.png)<br>

<h3>Data Cleaning and Aggregation</h3>
Below are screenshots of the dataframes created within the 'main.ipynb' Jupyter Notebook script located in the PyCitySchools folder located in the main repository.

Summary of All Schools in the School District<br>
![](screenshots/district_summary.png)<br/>

Summary of Each School in the School District (% Overall Passing in Descending Order)
![](screenshots/best_schools.png)<br/>

Summary of Each School in the School District (% Overall Passing in Ascending Order)
![](screenshots/worst_schools.png)<br/>

Next, binning was used for School Size (the number of students) and Spending per Student (per student budget), resulting in the following two dataframes:<br>

Dataframe with binned School Size column:<br>
![](screenshots/binned_size.png)<br/>

Dataframe with binned Spending Range column<br>
![](screenshots/binned_spending.png)<br/>

With the binned data from the previous two dataframes, it's possible to aggregate the data and look for correlations between a school's size, type, and per student budget and a school's performance, i.e. the average grades of students.

Performance Summary Broken Down by School Size<br>
![](screenshots/size_summary.png)<br/>

Performance Summary Broken Down by School Type<br>
![](screenshots/type_summary.png)<br/>

Performance Summary Broken Down by Spending per Student<br>
![](screenshots/spending_summary.png)<br/>
















<h3>Anaysis and Conclusions</h3>


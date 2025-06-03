CBSE Result Analyzer – TXT to Excel Report Generator
This project helps school staff convert official CBSE .txt result files into organized and insightful Excel reports using Python and Pandas.

It automatically analyzes student marks, calculates subject-wise statistics, identifies top scorers, and generates charts — making it easier for teachers and administrators to evaluate results quickly and visually.

Features
Reads CBSE .txt result files shared with schools

Performs subject-wise analysis (mean, grade distribution, top scorers)

Generates pie charts for grade distributions

Exports all data to a formatted Excel report with multiple sheets

Embeds performance graphs directly into the Excel file

Technologies Used
Python 3

Pandas

Matplotlib

OpenPyXL

Jinja2

Regular Expressions (re)

How to Use
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/CBSE-Result-Analyzer.git
cd CBSE-Result-Analyzer
Install the required packages:

bash
Copy
Edit
pip install pandas matplotlib openpyxl jinja2
Place the CBSE .txt result file (e.g., data.txt) in the project folder.

Run the script:

bash
Copy
Edit
python cbse_result_analyzer.py
After execution, you'll receive an Excel report containing:

All results

Subject-wise sorted scores

Top 10 scorers

Grade distribution counts

Pie chart embedded in the Excel file

Output Example
The generated Excel file (student_data_<Subject>.xlsx) includes:

All Subjects – Complete student data

<Subject> Only – Sorted list of students by score

<Subject> Top Scorers – Top 10 performers

<Subject> Grade Count – Grade count and corresponding chart

Ideal For
School examination departments

Teachers preparing performance reports

CBSE schools looking to digitize result analysis

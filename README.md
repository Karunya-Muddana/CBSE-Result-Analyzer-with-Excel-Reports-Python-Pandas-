📊 CBSE Result Analyzer – TXT to Excel Report Generator
This project helps school staff convert official CBSE .txt result files into organized and insightful Excel reports using Python and Pandas.

It automatically analyzes student marks, calculates subject-wise statistics, identifies top scorers, and generates charts — making it easier for teachers and administrators to evaluate results quickly and visually.

🔧 Features
📄 Reads CBSE .txt result files shared with schools

📊 Performs subject-wise analysis (mean, grade distribution, top scorers)

📈 Generates pie charts for grade distributions

📁 Exports everything to a formatted Excel report with multiple sheets

🖼️ Embeds performance graphs directly into the Excel report

📦 Technologies Used
Python 3

Pandas

Matplotlib

OpenPyXL

Jinja2

Regular Expressions (re)

▶️ How to Use
Clone this repository:

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
Place the CBSE .txt result file in the project folder.

Run the notebook or script:

bash
Copy
Edit
jupyter notebook "Pandas JN.ipynb"
After running, you'll get:

An Excel file with multiple sheets:

All results

Subject-wise sorted scores

Top 10 scorers

Grade distribution counts

A pie chart embedded inside the Excel file for each subject.

📁 Output Example
Generated Excel file (student_data_<Subject>.xlsx) contains:

All Subjects – Complete student data

<Subject> Only – Sorted list of students by score

<Subject> Top Scorers – Top 10 performers

<Subject> Grade Count – Count and chart of grade distribution

💡 Ideal For
School examination departments

Teachers preparing class performance reports

CBSE schools digitizing result analysis


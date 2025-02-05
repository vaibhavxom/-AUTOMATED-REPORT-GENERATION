# AUTOMATED-REPORT-GENERATION

This project generates a PDF report summarizing student scores from a CSV file. It provides an overview of the total number of students, average score, highest score, and lowest score, along with a detailed table of individual student scores.

## Features

- Reads student data from a CSV file.
- Analyzes the data to provide summary statistics.
- Generates a PDF report with the summary and detailed student scores.

## Technologies Used

- Python
- - Pandas
- - FPDF

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/vaibhavxom/AUTOMATED-REPORT-GENERATION.git
    cd AUTOMATED-REPORT-GENERATION
    ```
#
2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    ```
#
3. Activate the virtual environment:
    - On Windows:
      ```bash
      venv\Scripts\activate
      ```
    - On macOS/Linux:
      ```bash
      source venv/bin/activate
      ```
#
4. Install dependencies:
    ```bash
   pip install fpdf pandas
    ```
5.Prepare your CSV file:

Create a CSV file named data.csv in the project directory with the following structure:
```csv
Name,Score
Alice,85
Bob,90
Charlie,78
```    
6.Run the application:
```bash
python weather_dashboard.py
```

7.Check the generated PDF report:  
After running the application, a PDF report named report.pdf will be created in the project directory.  

# Usage  

  - The application reads the data.csv file, analyzes the student scores, and generates a PDF report containing:  

    - Total number of students  
    - Average score  
    - Highest score  
    - Lowest score
  A table listing each student's name and score
# output  
![image](https://github.com/user-attachments/assets/5b6365dd-63e1-48ac-8239-49196f3c1af5)


# Troubleshooting
Ensure that the data.csv file is correctly formatted and located in the project directory.
If you encounter any issues, check the console for error messages.  

# License
This project is licensed under the GNU 3 License.



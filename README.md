# Student Loan Data Analysis

This project involves analyzing student loan data from Ladoke Akintola University of Technology (LAUTECH). The data is extracted from a PDF file and processed to gain insights into various aspects such as student names, courses of study, and bank account information.

## Project Process

1. **Extract Text from PDF**: 
   - The project starts by extracting text from a PDF file using the `pdfplumber` library.
   - The PDF contains student loan data including names, matric numbers, courses, and bank account details.

2. **Data Cleaning and Processing**:
   - The extracted text is processed to create a structured DataFrame using `pandas`.
   - Columns such as `jamb_number`, `institution`, `location`, `current_fees`, and `account_name` are dropped to focus on relevant data.
   - The `course_of_study` column is cleaned to remove degree types and standardize course names.

3. **Data Analysis**:
   - The project includes functions to analyze and visualize the data.
   - Visualizations include the distribution of student levels and the top 10 courses of study.
   - Additional analysis functions provide insights into common first and last names, and the distribution of students across different banks.

4. **Visualization**:
   - The project uses `seaborn` and `matplotlib` for creating visualizations.
   - Bar plots and count plots are used to display the distribution of levels and courses.

## Insights and Personal Experience

I enjoyed working on this project because it provided insights that are closer to me and my peers at LAUTECH. It was interesting to see the distribution of courses and the common names among students. This project can be adapted for other institutions or datasets by following the same process.

## How to Use This Project

1. **Install Required Libraries**:
   - Ensure you have the required libraries installed by running:
     ```
     pip install -r Requirements.txt
     ```

2. **Run the Jupyter Notebook**:
   - Open the `Loan Data Analysis.ipynb` notebook in Jupyter.
   - Follow the cells to extract, clean, and analyze the data.

3. **Adapt for Your Own Data**:
   - Replace the PDF file with your own dataset.
   - Modify the data extraction and cleaning steps as needed to fit your data structure.

## Requirements

- `pandas==1.5.3`
- `seaborn==0.12.2`
- `matplotlib==3.7.1`
- `pdfplumber==0.5.28`

## Conclusion

This project demonstrates how to extract, clean, and analyze data from a PDF file. It provides a framework that can be adapted for similar datasets, offering valuable insights into student loan data.

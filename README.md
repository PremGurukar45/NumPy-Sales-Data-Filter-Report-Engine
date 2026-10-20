NumPy Sales Data Filter & Report Engine
Project 3 from the “5 NumPy Projects for Your Resume” PDF
Level: Intermediate | Suggested effort in source PDF: 2 days
Objective
Simulate one year of sales for 10 stores and 12 months, then filter the data and produce monthly, store-wise, and quarterly reports.
Features
- Creates a reproducible synthetic sales array with shape (10, 12).
- Uses np.arange, np.random, np.linspace, and array shape/size attributes.
- Slices the data into Q1–Q4 and extracts individual stores.
- Uses Boolean masks and combined conditions with &, |, and ~.
- Uses fancy indexing to select stores with indices [1, 4, 7] (store IDs 2, 5, 8) and the top three months.
- Produces monthly and store-wise tables with Pandas.
- Plots monthly and annual store totals with Matplotlib.
- Includes a reusable query_sales() helper and validation assertions.
Run in Google Colab
1. Upload NumPy_Sales_Data_Filter_Report_Engine.ipynb to Google Colab, or open it from your GitHub repository.
2. Choose Runtime → Run all.
3. Review the generated tables, charts, and validation message.
4. If sharing the notebook, set its access to Anyone with the link can view if appropriate.
Run locally
Python 3.10+ is recommended. Install the dependencies:
pip install numpy pandas matplotlib jupyter
Then launch:
jupyter notebook NumPy_Sales_Data_Filter_Report_Engine.ipynb
Dataset and interpretation
All sales are synthetic random integer values for demonstration, not real business records. target = 3000 and the np.linspace(2000, 3000, 12) targets are illustrative query thresholds, not business recommendations or forecasts. The random seed is set to 42 for repeatability within compatible NumPy versions.
Repository contents
- NumPy_Sales_Data_Filter_Report_Engine.ipynb — runnable notebook.
- README.md — project guide.
- Project_Report.pdf — project report; actual execution results and benchmark timings are not fabricated.
Resume bullet
Built a NumPy-based sales reporting engine for a 10-store, 12-month synthetic dataset using quarterly slicing, combined Boolean masks, fancy indexing, and monthly/store-wise reports.
Validation
The notebook includes assertions for array shape, monthly/store totals, quarter totals, and Boolean-mask counts. Run all cells to verify the current environment.

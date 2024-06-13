# python_assignment
Django-based web application that allows users to upload CSV files, performs data analysis using pandas and numpy, and displays the results and visualizations on the web interface.<br>
This Django web application allows users to upload CSV files containing numerical data. Upon upload, the application calculates summary statistics (including median, mean, standard deviation, and quartiles) for each numerical column and generates histograms for visualization.<br>

Features<br>
1.Upload CSV File: Users can upload CSV files containing numerical data.
2.Summary Statistics: Calculate and display summary statistics (mean, median, standard deviation, quartiles) for each numerical column in the uploaded CSV file.
3.Histogram Visualization: Generate histograms for each numerical column and display them in the web interface.
4.User Interface: Simple web forms for uploading CSV files and displaying results.<br>

the "TEMPORARY_DIR" environment variable is set to a writable directory path for storing temporary files during file uploads.<br>
The application uses Pandas for data manipulation and Matplotlib for generating histograms.

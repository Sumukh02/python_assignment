# python_assignment
Django-based web application that allows users to upload CSV files, performs data analysis using pandas and numpy, and displays the results and visualizations on the web interface.<br>
This Django web application allows users to upload CSV files containing numerical data. Upon upload, the application calculates summary statistics (including median, mean, standard deviation) for each numerical column and generates histograms for visualization.<br>

Features<br>
1.Upload CSV File: Users can upload CSV files containing numerical data.<br>
2.Summary Statistics: Calculate and display summary statistics (mean, median, standard deviation, quartiles) for each numerical column in the uploaded CSV file.<br>
3.Histogram Visualization: Generate histograms for each numerical column and display them in the web interface.<br>
4.User Interface: Simple web forms for uploading CSV files and displaying results.<br>

The "TEMPORARY_DIR" environment variable is set to a writable directory path for storing temporary files during file uploads.<br>
The application uses Pandas for data manipulation and Matplotlib for generating histograms.<br>

Setup Instructions<br>
Prerequisites
Python (>= 3.6),
Django (>= 3.2),
Pandas,
Matplotlib.<br>

* Installation Steps

1. Clone the repository:
<br>
git clone <repository-url>

<br>
cd csv-analysis-webapp

<br>
2. Create a virtual environment:
<br>

python -m venv venv

<br>

3. Activate the virtual environment:

<br>

On Windows
source venv/bin/activate
<br>

4. Install dependencies:<br>
pip install -r requirements.txt

5. Set up environment variables:<br>

Create a .env file in the root directory of your project and add the following:<br>
TEMPORARY_DIR=<path-to-temporary-directory><br>
Replace <path-to-temporary-directory> with the absolute path to a directory where temporary files can be stored during file uploads.<br>

6. Apply migrations:<br>
python manage.py migrate

<br>
7. Run the development server:

python manage.py runserver<br>

8. Access the application:
Open the web browser and go to http://localhost:8000 to access the CSV file upload form.

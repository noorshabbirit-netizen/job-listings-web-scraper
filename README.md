# Job Listings Web Scraper and Analysis

A Python-based web scraping project that collects job listings from a practice jobs website and analyzes job types, locations, remote opportunities, and posting dates.

## Project Overview

This project demonstrates a complete web scraping and data analysis workflow using Python.

Job listings were collected from 6 pages of a practice jobs website using Requests and BeautifulSoup. The scraped data was then cleaned and analyzed using Pandas, with Matplotlib used to create visualizations.

> **Note:** The website used for this project provides synthetic practice data and does not represent real-world job market information.

## Objectives

* Scrape job listings from multiple pages
* Extract relevant job information
* Clean and organize the collected data
* Analyze job types and locations
* Identify remote job opportunities
* Analyze posting dates
* Create visualizations from the collected data
* Save the final dataset as a CSV file

## Technologies Used

* Python
* Requests
* BeautifulSoup
* Pandas
* Matplotlib
* Jupyter Notebook

## Data Collection

The project collected the following information from each job listing:

* Job Title
* Company
* Location
* Job Type
* Posted Date

A total of **30 job listings** were collected from **6 pages**.

## Data Cleaning

The scraped data was processed using Pandas.

The following steps were performed:

* Converted posting dates to datetime format
* Identified remote job listings
* Cleaned location information
* Checked for missing values
* Checked for duplicate records

The final dataset contained **no missing values and no duplicate rows**.

## Analysis

The project analyzed:

### Job Type Distribution

The collected listings included:

* Intern: 9
* Full-time: 9
* Part-time: 6
* Contract: 6

### Remote Jobs

* Remote: 12
* Non-remote: 18

### Location Analysis

Austin, TX, US had the highest number of job listings in the collected dataset.

### Latest Job

The latest listing in the dataset was a **Senior PHP Engineer** position posted on **October 1, 2026**.

## Visualizations

The project includes the following visualizations:

* Job Type Distribution
* Remote vs Non-Remote Jobs
* Job Listings by Location
* Remote Jobs by Job Type

## Project Structure

```text
job-listings-web-scraper/
│
├── Job_Listings_Web_Scraper.ipynb
├── job_listings_final.csv
├── job_type_distribution1.png
├── remote_vs_nonremote.png
├── job_location_distribution.png
└── remote_jobs_by_type.png
```

## How to Run

1. Clone or download the repository.
2. Open the Jupyter Notebook.
3. Install the required libraries:

```bash
pip install requests beautifulsoup4 pandas matplotlib
```

4. Run the notebook cells.

## Key Skills Demonstrated

* Web Scraping
* HTML Parsing
* Data Extraction
* Data Cleaning
* Exploratory Data Analysis
* Data Visualization
* Python Programming
* Pandas Data Manipulation

## Project Outcome

This project demonstrates a complete workflow from **web data collection to data analysis and visualization**, using Python-based web scraping and data analysis tools.

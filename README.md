---

# Scrape Job Listings from JobStreet

This repository contains a data scraping project focused on extracting job listings related to data-related jobs from JobStreet. The data was collected on **30 September 2024** using the keyword **"Data"**.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Files in this Repository](#files-in-this-repository)
- [How to Run](#how-to-run)
- [Dependencies](#dependencies)
- [Future Work](#future-work)
- [License](#license)

## Project Overview
The aim of this project is to gather job listings data with the keyword "Data" from JobStreet, and process it for further analysis or insights into the current job market.

## Dataset
The dataset includes job titles, companies, job type, sallary, job description and other relevant fields related to data-related job opportunities. This can be used to analyze trends in the job market, the demand for specific data-related skills, and locations where these opportunities are concentrated.

### Columns in `data_crawling.csv`:
- Job Title
- Company
- Job type
- Job category
- Job sub category
- Job id
- job desc

## Files in this Repository
- `Scrape_Job_Street.ipynb`: Jupyter Notebook for scraping the job listings and saving them into a structured dataset.
- `data_crawling.csv`: The dataset collected from the scraping process, including various data-related job listings.

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   ```
2. Install the required dependencies (see below).
3. Open the Jupyter notebook `Scrape_Job_Street.ipynb` and run the cells to execute the scraping process or modify it for future use.

## Dependencies
- Python 3.x
- Jupyter Notebook
- Required Python libraries:
  - `requests`
  - `beautifulsoup4`
  - `pandas`

Install the dependencies using:
```bash
pip install -r requirements.txt
```

## Future Work
- Expand the scraping to include more job boards or add more filters for advanced keyword searches.
- Perform in-depth analysis of the data, such as salary predictions, popular skills, and location-based job demand.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

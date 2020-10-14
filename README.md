<img src="https://raw.githubusercontent.com/codecaviar/digital_asset_management/master/assets/bingyune-and-company-logo-6400x3600.png" align="left" width="200" height="auto">

<br/><br/><br/><br/>

----------

# Bike Share for All: Beginner's Guide to Basic SQL

**Code Caviar Story**: https://www.bingyune.com/blog/bike-share-basic-sql

## Project Overview

Structured Query Language, or more commonly known as SQL (pronounced "ess-cue-ell" or "si-kwel"), is a standard programming language for accessing and manipulating databases. Though SQL is commonly used by engineers in software development, SQL is also popular with data scientists and analysts because of it's ability to scale. Traditional spreadsheets can be used to manage small-to-medium-sized pools of data such as between multiple worksheets, but you will need a different solution when handling excessively large records. Whether it's 1,000 records or 100 million, SQL can rapidly navigate databases and query, retrieve, and aggregate records. SQL is also more adept than spreadsheets at creating data flows for cleaning and preparing data at high volumes. Because SQL allows users to also remotely interact with large datasets in production environments, SQL is still the industry standard in data science and analytics for data query and retrieval. Almost all of the biggest names in tech use SQL - Netflix, Instagram, LinkedIn, Lyft, Dropbox - the list goes on. Long story short: yes, you need to learn SQL to be more qualified for a job in data.

**The goal of this project is** to provide a Beginner's Guide to the basic hacking skills needed to start analyzing data with SQL. TThe project makes use of the [Bay Area Bike Share](https://mtc.ca.gov/our-work/operate-coordinate/traveler-services/bay-area-bike-share) data sourced from [Kaggle](https://www.kaggle.com/benhamner/sf-bay-area-bike-share). The original dataset contains data for 70 stations (where users can pickup or return bikes), about 71M status updates (number of bikes and docks available for given station), about 670k trips (individual bike trips), and about 3k weather forecasts (for a specific day for a certain zip code).

## Summary:

Although there are a number of different types of SQL database implementations and platforms (e.g. SQLite - the tutorial uses this one, PostgreSQL, MySQL, Microsoft SQL Server, and Oracle Database), all versions support at least the major commands (such as SELECT, FROM, and WHERE) in a similar fashion.

* **SELECT**: *selects* the columns
* **FROM**: *points* to the table
* **WHERE**: *filters* on rows
* **GROUP BY**: *aggregates* across values of a variable
* **HAVING**: *filters* groups
* **ORDER BY**: *sorts* or *arranges* the results
* **LIMIT**: *limits* the results to the first n rows

SQL can query, retrieve, and aggregate millions of records. SQL is cloud-based data query and retrieval is not limited to your local computer system. SQL can organize data tables. SQL allows users to remotely interact with large data sets in production environments. Although SQL has quite a few impressive superpowers, there is also one main limitation...SQL is not a data visualization tool. It's normally used in conjunction with other tools such as Python, Tableau, Excel.

## Getting Started

First, cloning the git repository and installing the provided packages will help you get a copy of the project up and running on your local machine. The analysis for this project was performed using Jupyter Notebook (.ipynb) and the packages were managed using the Anaconda platform.

```
git clone https://github.com/codecaviar/bike_share_basic_sql.git
conda env create -f environment.yml
```

File Description:
* environment.yml - packages used to perform this analysis
* notebook_bike_share_basic_sql.ipynb - Jupyter Notebook for this project including code examples and explanations
* solutions_bike_share_basic_sql.ipynb - Jupyter Notebook for this project including solutions to practice problems

## Authors

- **BingYune Chen** - [LinkedIn](https://www.linkedin.com/in/bingyune-chen/)
- **BingYune & Co** - [GitHub](https://github.com/codecaviar)

## License

The project is licensed under the GNU General Public License v3.0 License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

The project referenced the following resources:
* https://mode.com/sql-tutorial/
* https://www.w3schools.com/sql/
* https://www.sqlitetutorial.net/

----------
The Code Caviar is a digital magazine about data science and analytics that dives deep into key topics, so you can experience the thrill of solving at scale.

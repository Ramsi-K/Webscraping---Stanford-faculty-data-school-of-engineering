# Webscraping---Stanford-faculty-data-school-of-engineering
Data contains faculty name, association, personal profile link, orcid website link, research interests if provided on personal website and published articles {name,authors,year}

## Introduction

This is a snippet of the data that will be gathered for my project under the Data Science Fellowship at TDI.
This data was scraped from https://profiles.stanford.edu/

The data contains faculty information from the Institute for Computational and Mathematical Engineering (ICME).
Data was scraped at off-peak hours.

The data was scraped in Python with requests and BeautifulSoup packages. It is formatted as a csv file.

## Columns 

- faculty_name - Name of Faculty
- faculty_association - Subject 
- profile - Personal Profile link
- orcid_website - Orcid website link (as orcid has a publicly available API)
- research_interests - If mentioned on the personal profile else None
- published_articles - Title, Authors and Year of publishing of all articles mentioned in the Personal Profile

## Goal

The goal of this project is to  Quantifying Academic Publications Prestige.

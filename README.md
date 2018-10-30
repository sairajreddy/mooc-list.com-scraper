# mooc-list scraper

Web Scraper to extract the following course features data from mooc-list.com 

  - Course Name 
  - Course Description 
  - Number of Staff 
  - Course Duration Workload (Hours per Week) 
  - Course Start Date 
  - Is_Course_Active 
  - Subject Area 
  - Course Level 
  - Course Platform 
  - Universities 
  - Number of Universities 
  - Country 
  - Assessment Type 
  - Language 
  - Certificate (Free or Paid)
  - Certificate Fee 
and so on.

### Pre-requisites

You should have Python3 Kernel installed and Jupyter Notebook as well.
The following libraries also need to be installed

* BeautifulSoup - https://www.crummy.com/software/BeautifulSoup/bs4/doc/
* Pickle - https://docs.python.org/3.1/library/pickle.html
* Requests - http://docs.python-requests.org/en/master/

### Instructions

This is a two step process to extract complete mooc-list data. 

1. Run every cell in 1_Course_List_Scraper_mooc-list.ipynb to get a list of all mooc-list's course pages and this is exported as a pickle file.
2. Run every cell from 2_Course_Data_Scraper_mooc-list.ipynb and you get a CSV file consisting of all the data. 

### NOTE :

Make sure there's uninterrupted internet and this takes probably few hours (2 to 3 hours) to extract complete data depending on your bandwidth capacity. 

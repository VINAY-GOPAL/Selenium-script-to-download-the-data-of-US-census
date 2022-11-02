# Selenium-script-to-download-the-data-of-US-census


In this script, I automated the downloading of the employment status table using selenium. The employment data is related to US country and the data can be found in US census website. In this website, we can find the data of various states, cities and year wise and there are lot of filters using which we can get the data. The script I written takes 3 parameters: state, place/city and year.There are only 2000 to 2021 years data in the website. We can give state, city and year and It will automatically download a zip file where we can find an excel sheet. 

url: https://data.census.gov/cedsci/table

This is a screenshot of website:

![WhatsApp Image 2022-11-02 at 5 45 17 PM](https://user-images.githubusercontent.com/57621970/199487322-163dbdeb-f8fb-4344-9c03-3cd672ed9c7c.jpeg)


This is the screenshot after opening in excel sheet:

![WhatsApp Image 2022-11-02 at 5 42 58 PM](https://user-images.githubusercontent.com/57621970/199486927-b8690e74-74f4-453a-a53e-c6af394b4dc1.jpeg)

The rows which we see in website are converted to columns when we download the excel sheet. There will be lot of columns in the downloaded sheet. We need to delete many columns to keep only wanted columns. After downloading the data for all the years we need to merge into one excel/csv file so that we can create a dataset.

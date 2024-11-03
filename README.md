### Name : Sowmya V
### Reg no : 212222110045
### Date : 
# Exercise 5 - Scrape data from a website and save it to a CSV file

### Aim:
To Scrape data from a website and save it to a CSV file.

### Software required:
UiPath Studio-community edition

### Procedure:

- Use the Open Browser activity.
- Set the URL property to https://www.w3schools.com/html/html_tables.asp.
- Choose the browser type (e.g., Chrome, Edge).

- Use the Data Scraping wizard available in UiPath.
- Indicate the table on the webpage using the wizard.
- Configure the scraping wizard to extract the data into a DataTable variable named extractedData.

- Use the Write CSV activity.
- Set the Input property to extractedData.
- Set the FilePath property.
  
### Main.xaml:

![image](https://github.com/user-attachments/assets/8b10ac58-d037-4100-adb8-53820a8c6f85)


### Output:

![image](https://github.com/user-attachments/assets/0c101008-ced0-4054-a30a-b4138b9a2a02)


### Results:
Thus the data from the website is successfully scraped and saved to a CSV file.




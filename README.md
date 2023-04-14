# Selenium Automation


### Project's goal:
	Create a Project that involves process automation via the Web, using Selenium, analyzing the best product prices, creating an Excel file and sending an analysis with the processed data by email.

	
### Recommendations:
	As this project deals with sending e-mails, remember to complete the code with your data!
	

### Description:
	Our role is to open a webpage, search for the products listed,
	Compare with our indicators (like Min Price or Max Price),
	Create an Excel Spreadsheet, and we'll send you an email with the best offers found.	


## Inspirations and Credits:
	Curso PythonImpressionador - Professor Jõao Paulo Lira
	https://www.hashtagtreinamentos.com/


## Requirements:
### Bibliotecas Utilizadas:
	Libraries Used:
	from selenium import webdriver
	from selenium.webdriver.common.keys import Keys
	from selenium.webdriver.common.by import By
	import pandas as pd
	import smtplib
	from email.mime.multipart import MIMEMultipart
	from email.mime.text import MIMEText
	from email.mime.base import MIMEBase
	from email import encoders
	import pathlib
	import time


## Folders and Files Used in the Project:
	buscas.xlsx (Excel file with the Indicators)


### Att, Gabriel Souza

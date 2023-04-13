# Automação Selenium


### Objetivo do Projeto:
	Criar um Projeto que envolva automatização de processo pela Web, Utilizando o Selenium, analizando os melhores preços dos produtos, criando um arquivo Excel e mandando uma análise com os dados tratados por e-mail
	


### Descrição:
	Nosso papel é abrir uma página da Web, pesquisar os produtos listados,
	Comparar com nossos indicadores (como Preço Min ou Preço Max),
	Criar uma Planilha Excel, e enviarmos um e-mail com as melhores ofertas encontradas.	


## Inspirações e Créditos:
	Curso PythonImpressionador - Professor Jõao Paulo Lira
	https://www.hashtagtreinamentos.com/


## Requisitos:
### Bibliotecas Utilizadas:
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


## Pastas e Arquivos Utilizados no Projeto:
	buscas.xlsx (Arquivo Excel com os Indicadores)


### Att, Gabriel Souza






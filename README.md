# ETL Country Sosio Economic - Mini Project Data Engineer

## About Project
Proses ETL (Extract - Transform - Load) pada beberapa data source seperti data project Bank Dunia, data population, data rural population, data electricity access, dan data GDP untuk mendapatkan insight mengenai keadaan Sosio Economic yang ada diberbagai negara di Dunia. Selain itu hasil data yang sudah dilakukan proses ETL diharapkan dapat menjadi data source untuk menjalankan model prediksi biaya total proyek Bank Dunia pada proses yang akan dilakukan selanjutnya.

## Tech Stacks
Berikut merupakan library yang digunakan dalam pengerjaan project ini, sebagai berikut : 
- Data Ingestion
  - pandas
  - bs4 (BeautifulSoup)
  - sqlite3
  - requests
- Data Transformation
  - pandas
  - numpy
  - MinMaxScaler (sklearn)
  - re
  - os
  - opennai
- Data Loading
  - google.cloud.storage
  - dotenv
  - json
  - datetime
- Data Visualization
  - matplotlib
  - seaborn  


Tools and Programming Language :
- Python 
- VSCode 
- Github
- Jupiter Notebook

## Architecture Diagram
![preview](https://github.com/Ikaap/mini-project_ika-purwanti/blob/main/screenshots/etl_pipeline.png)  

## Setup 
Berikut cara menggunakan project di lokal :
![preview](https://github.com/Ikaap/mini-project_ika-purwanti/blob/main/screenshots/setup_program.png)  
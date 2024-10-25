# Toll Plazas of Minas Gerais

This project was developed to scrape toll data in the state of Minas Gerais from the site emsampa.com.br. Using a Python script, data is automatically extracted, organized, and saved to an Excel file for easy access and analysis.

**KEY FEATURES**

1. **Toll Data Scraping**  
   The system scrapes data from various toll plazas in Minas Gerais, extracting information such as:
   - Highway, KM, Location, Number of Axles, and Toll Fee (Since)

2. **Integration with Pandas**  
   The extracted data is organized into a Pandas DataFrame, facilitating data manipulation and analysis before export.

3. **Excel Export**  
   The system automatically saves the scraped data to an Excel file, enabling further analysis in tools like Microsoft Excel, Google Sheets, or any compatible software.

**TECHNOLOGIES USED**

1. **Python**: Main language used for automating the scraping process.
2. **Requests**: Used to make HTTP requests and retrieve the page's HTML content.
3. **BeautifulSoup**: Library for parsing HTML and extracting data from tables.
4. **Pandas**: Used to organize data into a DataFrame and export it to Excel.
5. **OpenPyXL**: Auxiliary library for Pandas to save data in Excel files.

**HOW IT WORKS**

1. The script accesses emsampa.com.br and makes a request to obtain the HTML content.
2. Using BeautifulSoup, it navigates the tables containing toll data.
3. Data (highway, KM, location, axles, and fee) is extracted and organized into a list of dictionaries.
4. The list is converted into a Pandas DataFrame.
5. Data is saved to an Excel file named `TollPlazasMG.xlsx`.

**CONCLUSION**

This project automates the collection of toll information in Minas Gerais, providing a simple way to extract and organize useful data directly from a web page. The system is efficient and exports data in a widely-used format, simplifying data analysis and storage.

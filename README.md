# **Toll Plazas of Minas Gerais**

This project automates the extraction of toll plaza data in Minas Gerais from the website *emsampa.com.br*. It organizes the data and exports it to an Excel file, simplifying analysis and accessibility.

---

## **KEY FEATURES**

### 1. **Toll Data Scraping**
   - Extracts key data from toll plazas, including:
     - Highway
     - KM
     - Location
     - Number of Axles
     - Toll Fee (Since)

### 2. **Integration with Pandas**
   - Organizes the scraped data into a structured Pandas DataFrame for easy manipulation and analysis.

### 3. **Excel Export**
   - Automatically saves the processed data to an Excel file, compatible with tools like Microsoft Excel and Google Sheets.

---

## **TECHNOLOGIES USED**

### 1. **Python**
   - Main programming language for automating the data extraction process.

### 2. **Requests**
   - Fetches the HTML content of the web page.

### 3. **BeautifulSoup**
   - Parses and extracts data from HTML tables.

### 4. **Pandas**
   - Structures the extracted data into a DataFrame for easy manipulation and analysis.

### 5. **OpenPyXL**
   - Assists with exporting the DataFrame to an Excel file.

---

## **HOW IT WORKS**

1. The script sends an HTTP request to *emsampa.com.br* and retrieves the HTML content.
2. BeautifulSoup parses the content and extracts relevant toll plaza data from HTML tables.
3. The data, including highway name, KM, location, axles, and toll fee, is stored in a list of dictionaries.
4. This list is converted into a Pandas DataFrame for further processing.
5. Finally, the data is saved as an Excel file named `TollPlazasMG.xlsx`.

---

## **CONCLUSION**

The **Toll Plazas of Minas Gerais** system automates the tedious process of collecting toll plaza data, ensuring accuracy and efficiency. With its ability to export data in Excel format, it is a practical solution for organizations and individuals looking to analyze toll information in Minas Gerais.

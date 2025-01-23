# SEBI-PMS-Data-Extraction-and-Analysis-
## **Description**

- **Objective**:  
  - Extract, preprocess, and analyze data from the SEBI PMS (Portfolio Management Services) website.  
  - Gain insights into portfolio managers, client segmentation, and assets under management (AUM).  

- **Data Extraction**:  
  - Used Python libraries like `Selenium` and `BeautifulSoup` for web scraping.  
  - Automated interactions with dropdown menus and tables on the SEBI PMS website.  
  - Collected key data fields, such as company names, client categories, and AUM details.  

- **Data Preprocessing**:  
  - Removed irrelevant columns and standardized company names for consistency.  
  - Handled missing data gracefully and saved cleaned data in CSV format.  

- **Analysis and Visualization**:  
  - Imported the structured data into **Power BI** for detailed analysis.  
  - Created visualizations like bar charts, pie charts, line graphs, and DAX measures.  

- **Key Findings**:  
  - **Disparities**: Identified gaps between client numbers and their asset contributions.  
  - **High-Value Clients**: AUM is heavily concentrated among a few key clients, especially Domestic PF/EPFO and Foreign FPI entities.  
  - **Inactive Companies**: Found 80 companies with no clients or assets.  
  - **Client Segmentation Trends**: Foreign clients (especially FPIs) dominate asset contributions despite being fewer in number.  

- **Recommendations**:  
  - Focus on acquiring and retaining high-value client segments like PF/EPFO and FPIs.  
  - Address disparities in asset contributions from domestic non-corporates and foreign non-residents.  
  - Investigate and activate the 80 inactive companies or consider merging them.  
  - Expand into underutilized markets to drive strategic growth.  

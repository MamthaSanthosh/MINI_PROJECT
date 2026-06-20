# SPONSOR THE DISHES FOR OCCASION
**1. Project Overview and Objective:**<br/>
This project involves cleaning, transforming, formatting, strip syntax noise (brackets, semicolons), correct spelling variations and analysing raw data using Excel and creating an interactive Power BI dashboard to derive meaningful visualization.<br/>
The main objective is to demonstrate data processing techniques using Excel and an interactive Power BI dashboard visualization to make informed decisions.<br/>
_____________________________________________________________________________________________________________________________________________________<br/>
**2. Data Sources:**<br/>
●	Source Description and Timeline: The underlying source data represents a valuable archive of commercial  records that captures the economic, social, and cultural patterns of consumer dining at the start of the 20th century. The transactions track specific historical events, physical menu structural components, branding descriptions, and detailed food options. The dataset contains a highly focused temporal window, mapping transactions exclusively within the calendar year 1900. The timeline spans exactly nine operational months, tracking dates from February 13, 1900, through November 13, 1900.<br/>
●	Domain: Analyzing this domain within Power BI allows modern analysts to uncover early corporate branding mechanisms, trace how travel networks used  to differentiate services, and measure the operational footprint of commercial food systems.<br/>
_____________________________________________________________________________________________________________________________________________________<br/>
**3. Problem Statement**<br/>
●	To analyse the context of the records , the primary challenge was that the baseline raw table was unfit for corporate visualization or dashboard due to several fatal data.<br/>
●	To evaluate High-Volume Data Voids like complete columns (name, keywords, language, and location_type) ,Syntax and Textual Noise like critical dimensions like event and place were severely compromised by arbitrary bracket notations (e.g., [DINNER]), trailing semicolons (e.g., GOVT;), and minor typos (e.g., DINNE),Unstructured Qualitative Metadata like valuable contextual clues regarding corporate branding and physical assets were buried in unparsed, free-form text blocks within the notes.<br/>
●	To study crop production patterns across states and years for better agricultural planning.<br/>
●	To evaluate employee performance and attrition factors for improved HR decision-making.<br/>
●	To understand that if left without correcting these data anomalies cause major reporting failures inside business intelligence platforms like Power BI.<br/>
_____________________________________________________________________________________________________________________________________________________<br/>
**4. Attribute (Column /Features) Details:**<br/>
| Attribute Name	|  Data Type | Description |
| :--: | :--: | :--: |
| ID | Integer | Unique identifier for each employee |
| Text	| Text	| Text Corporate |
| Event	| Text	| Meal/Function Dimension |
| Venue	| Text	| Classification Category |
| Place	| Text	| Geographic Dimension |
| City	| Text	| Geographic Dimension |
| Payment	| Text	| Financial Attribute |
| Date	| DateTime	| Temporal Key |
| Status	| Text	| System Process Flag |
| Page_Count	 | Integer	| Quantitative Metric | 
| Dish_Count	 | Integer	| Quantitative Metric |
| Floor	| Text |	System Process Flag |
________________________________________
**5. Tools & Technologies:**<br/>
●	Excel: Data cleaning, transformation, and Pivot Tables.<br/>
●	Power BI: Data modelling, DAX calculations, visualization, and interactive dashboard creation.<br/>
_____________________________________________________________________________________________________________________________________________________<br/>
**6. Data Pre-Processing (Excel / Power Query)**<br/>
Tasks Performed:<br/>
●	Data Cleaning & Transformation: Removed duplicates, handled missing values, standardized formats, and created calculated fields.<br/>
●	Filtering & Sorting: Organized data to focus on relevant records.<br/>
_____________________________________________________________________________________________________________________________________________________<br/>
**7. Data Modelling and DAX (Power BI)**<br/>
●	Data Model: Created lookup table.<br/>
<img width="325" height="485" alt="Screenshot 2026-06-20 210900" src="https://github.com/user-attachments/assets/eb7dd34a-f65b-428f-ae2b-493527c28bd5" />

●	Calculated Columns & DAX Measures: Implemented DAX formulas for key metrics, such as Floor is elif condition.<br/>
_____________________________________________________________________________________________________________________________________________________<br/>
**8. Analysis and Visualizations (Power BI)**<br/>
Desktop Layout View:<br/>
<img width="1339" height="746" alt="Screenshot 2026-06-20 211707" src="https://github.com/user-attachments/assets/ed21b830-1be5-4255-9aef-fb917299ee5e" />


Mobile Layout View:<br/>
<img width="401" height="746" alt="Screenshot 2026-06-20 211831" src="https://github.com/user-attachments/assets/40a5ec8f-d477-422a-8531-38bc3c3f6a6a" />
                                                   

_____________________________________________________________________________________________________________________________________________________<br/>
**9. Insights & Conclusions:**<br/>
●	Key Findings: <br/>Summarize the records and found a Calculated Column using if…elif condition.<br/>
●	Provide the analysis insights:<br/>
▪	Descriptive : The clean dataset tracks 500 unique historical menu records from the year 1900.<br/>
▪	Diagnosis : High dish counts are strongly tied to Commercial venues.<br/>
▪	Predictive : Based on 1900 timeline cycles, menu volumes and dish complexity are highly predictable<br/>
▪	Prescriptive : Implement a top-level interactive slicer for Meal Window inside your Power BI canvas to let users instantly switch between Breakfast, Lunch, and Dinner profiles.<br/>
_____________________________________________________________________________________________________________________________________________________<br/>
**10. Conclusions:**<br/>
This project demonstrates a successful, end-to-end data pipeline that transforms noisy legacy records into a high-performance BI asset. By executing targeted Power Query cleanups and implementing a clean Star Schema design, the resulting Power BI dashboard successfully resolves structural data voids. Ultimately, this model delivers clear, executive-ready insights into how 1900-era travel networks strategically deployed luxury culinary branding to dominate the marketplace. 


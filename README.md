---

**"Defining Low-Income, Low-Access Food Areas"**, Congressional Research Service, 06-01-2021, page 1:
> - low-income (LI): poverty rate of 20% or greater, or median family income at or below 80% of the statewide or metropolitan area median family income; and 
> - low-access (LA): a low-income tract with at least 500 people or 33% of the tract’s population living more than 1 mile (urban areas) or more than 10 miles (rural areas) from the nearest supermarket or grocery store. (USDALA data are also available assuming different measures of distance, ranging 0.5 miles to 20 miles).
(https://crsreports.congress.gov/product/pdf/IF/IF11841)
----

**UDSA Food Access Research Atlas (FARA)**:
- info = https://www.ers.usda.gov/data-products/food-access-research-atlas/
- data = https://www.ers.usda.gov/data-products/food-access-research-atlas/download-the-data/
    - This is the "current", or most recent version of FARA, last updated 04-27-2021.
    - Note that even though this FARA is "current", it uses 2010 Census Tracts, not 2020.
----

**Census Tract Mapping data: US Census Bureau TIGER/Line Shapefiles**
- Main page = https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html
- Download via web interface = https://www.census.gov/cgi-bin/geo/shapefiles/index.php 
    - Select year = 2010
    - Select layer type = Census Tracts
    - Submit
    - Census Tract (2010), Select a State = Colorado
- Note: we use 2010 Census Tract data to match the 2010 Tracts used in the FARA data from USDA.
----

**Denver Urban Gardens (DUG): Garden Directory**:
- website = https://dug.org/find-a-garden/
- linked Google Map = https://www.google.com/maps/d/viewer?mid=1DQq0JnovDqoXbygKTYweQsUfG4A&ll=39.74082951828451%2C-105.00433671452163&z=12
    - From the Google Map, click the 3-dot menu and "Download KML"
----
**ProPublica Nonprofit Explorer: Denver Urban Gardens, IRS Form 990s**:
- site = https://projects.propublica.org/nonprofits/organizations/742374848
- Note: ProPublica also has an API that allowed me to access this Form 990 information directly from Python as well. HOWEVER, because some of the more interesting information on "Operating Expenses" are included in item #24 of the IRS Form 990, which has "write-in" names of the expense categories, and those "write-in" names are not entered in the same order every year, and the "write-in" names change over time, I also referenced the PDF files to extract that information.

---

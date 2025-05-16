# Surplus Inventory Simulator
An Excel dashboard that can be used to simulate the impact of shelf-life extensions and production changes. This was developed with real company data for my employer. As such, I will only provide a high level view of the project. You can follow along this in this README while looking at the PDF file in this repository.

<h2>Definitions</h2>
<ul>
  <li><b>SKU: </b>A stock keeping unit is a number that is assigned to a product for identification and tracking purposes.</li>
  <li><b>NSV: </b>Net Sales Value is the amount of profit we would generate. Revenue minus Cost of Goods Sold.</li>
  <li><b>Shelf life: </b>The number of days between product production date and bast by date.</li>
  <li>Excel Charts</li>
</ul>

<h2>Data Structure</h2>
<p>Data Sources: The dashboard required connecting to multiple sources in order to work. Sales Forecast, NSV by SKU, and production summaries were all web scraped from Google Sheets. In-house inventory data was provided from a 3PL data source. Shelf-life by SKU was pulled linked to a SharePoint file, and Fiscal Calendar data was generated manually within the sheet.</p>

# Azure-ASA-Automation

Project Update: Automating Data Flows and Reporting with Azure Synapse Analytics

In my latest project, I focused on automating data flow and reporting processes in Azure Synapse Analytics, building on previous [project](https://github.com/durgaprasadkoppala/Azure-ASA-Integration-and-Analysis) data integration and transformation skills to streamline monthly reporting.

Project Highlights:

🔹 Data Flow Automation: Similar to Azure Data Factory, I created data flows in Synapse to automate data processing. After setting up a database and inserting data through Azure Data Studio, I linked this data as a source in Synapse.

🔹 Dynamic Data Export: Queried the data, added a sink, and exported it as a dynamically named CSV file, creating monthly reports for easy tracking and analysis. This automation ensures that data is consistently prepared and stored in a targeted location for analysis.

🔹 Pipeline and Scheduling: Built a pipeline incorporating the data flow, adding a scheduled trigger for automatic, recurring runs. Now, each month’s report is automatically generated and saved to the destination location without manual intervention.


# power-bi-data-modeling-and-visualization
The design and creation of Power BI reports &amp; dashboards.



### Power BI platforms
Power BI offers users the ability to choose from various platforms
depending on their needs:
Power BI service
Power BI Desktop
Power BI Premium


### Power BI service
Power BI service is a free, cloud-based platform that works on Microsoft
Azure. This version of Power BI is not available on a private cloud or as an
internal service.

### Power BI service includes the following capabilities and features:
- The capability to connect with hundreds of data sources
- An online dashboard with analytics information including graphs and
reports
- Customizable dashboards
- Customizable reports
- The capability to edit reports online
- The capability to easily share reports
- Navigation controls that allow easy access to datasets
- Workspaces to collaborate with others on dashboards, reports, and
datasets to create apps
- Home, Help, and Feedback buttons
- An Office 365 app launcher
- A Question and Answer box that enables users to search for data using
plain English


### Power BI Desktop
Power BI Desktop is like Power BI service except that it lives on the user’s
desktop machine and not in the cloud. This free tool integrates seamlessly
with queries, data modelling, and visualizations for effective and accurate
reporting of data, and offers a wide range of features to enable users to create
appealing visualizations and detailed reports that can be published directly to
other apps, to the web, or for mobile view. Note, however, that Desktop users
cannot share reports.

### Advantages of using Power BI Desktop include the following:
- Power BI Desktop supports various data sources, which is helpful in
adapting to complex business requirements.
- Power BI Desktop includes an auto-detect relationship option for loaded
datasets to help users gain understanding and insights.
- A user-friendly interface facilitates the creation and editing of custom
visuals.
- Users can save reports for easy access. Reports that are saved have a
PBIX extension.
- Users can create and publish reports from a single Power BI Desktop
dashboard.



### Power BI Premium
Power BI Premium provides greater capabilities and performance by
increasing capacity-based offerings to end users. These act as dedicated
resources to run the Power BI service for any organization. This dedicated
capacity provides better support and stability.


### Architecture of Power BI
#### Data preparation layer
In this phase, or layer, the system data sources
synchronize data. At first, the data sourced from the system exists in
different file formats. To read these various sources of information,
Power BI first employs a gateway to process the data and then integrates
it into a dataset.
#### Data warehouse layer 
In this layer, a data warehouse applies filters to
the dataset to process it. To maintain accuracy, the data warehouse also
uses ETL processes to identify flaws and make corrections as needed. It
then forwards the processed data to a Power BI OLAP storage unit.
#### Data presentation layer 
After the dataset has been processed by the
data warehouse and stored in an OLAP storage unit, it is ready to be
converted into reports and visualizations by Power BI. Users can access
these visualizations on their dashboard.







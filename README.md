# Server-Log-Project
The project titled "Server Log Project" aims to analyze server log data from the year 2015 to gain insights into user activities and system usage. The primary goal is to provide a comprehensive overview of the system's usage patterns through data analysis and visualization.

The project begins with an introduction that highlights the significance of analyzing server log data and outlines the dataset used in the analysis. The focus is on examining user activities and system usage during the specified time period.

The data preparation stage involves loading the necessary datasets, "vdi_serverlogs.csv" and "vdi_statsapps.csv," and merging them based on a common identifier. The date and time variables are then converted to the appropriate format, and the dataset is filtered to include only entries from the year 2015 and VDI machines with specific names. This step ensures that the analysis is focused on relevant data.

The analysis section calculates key metrics to understand system usage. It begins by determining the total number of users on the system by counting the distinct user IDs. The average number of users per day is then calculated by grouping the data based on the logon date and summarizing the number of users. The highest number of users per day is also identified by filtering and summarizing the data.

The project further explores specific aspects of user behavior and application usage. The top off-site users logged in are identified by filtering the data for users who logged in from off-site locations and summarizing their login frequency. The top applications are determined based on the total time they were run, calculated by subtracting the start and stop times. The analysis focuses on the top three users and top three applications by login frequency and total time, respectively.

To visualize the findings, the project includes two bar plots. The first plot represents the top off-site users logged in, where each bar represents a user and its height represents the number of logins. The second plot illustrates the top applications by the time they were run, with each bar representing an application and its height representing the total time.

In conclusion, the project provides valuable insights into user activities and system usage based on the server log data. The findings can be utilized to understand user behavior, optimize system performance, and make informed decisions regarding resource allocation and system management. Further analysis and exploration of the data are encouraged to uncover additional patterns and anomalies that may enhance understanding of the system's usage dynamics.






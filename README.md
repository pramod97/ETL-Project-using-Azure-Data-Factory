# ETL Project using Azure Data Factory

## **Overview**  

This project demonstrates an ETL (Extract, Transform, Load) process using Azure Data Factory (ADF) to extract data from an Excel file, transform it by filtering, and load the final data into a production environment. The project is structured to highlight best practices in data processing and the use of Azure services for scalable and efficient data workflows.

Project Structure
Linked Services:

Configured linked services for Azure Data Factory and Azure Storage Account.
Created connections to both the ADF and the storage account to ensure secure and efficient data handling.

![image](https://github.com/user-attachments/assets/c47614ff-6122-4384-acfc-aba47385bba4)


Data Storage:

Uploaded the initial data into an Azure Storage Account.
Organized the storage into two folders: Development and Production to manage different stages of the ETL process.

![image](https://github.com/user-attachments/assets/b2044b51-4ec2-40c9-b5ed-40bc6fbfbb1f)

Datasets:

Created a dataset in ADF to represent the Excel file stored in the Azure Storage Account.

![image](https://github.com/user-attachments/assets/fa047261-8cb0-4b1b-9479-59c1eadddde1)

Dataflows:

Designed a dataflow in ADF to transform the data by applying a filter.

![image](https://github.com/user-attachments/assets/a199100a-eb2b-41a1-8ffa-caaf429f880d)

Created a final, filtered dataset named Final which contains the transformed data.

![image](https://github.com/user-attachments/assets/79575590-7847-4030-89e3-c74318e7bd46)

Pipelines:

Developed pipelines to automate the ETL process.
Configured parameters within the pipeline to allow dynamic sinking of the Final dataset into the production file.

![image](https://github.com/user-attachments/assets/00d206c7-2964-481e-998f-b24727fa1e39)

Technologies Used
Azure Data Factory (ADF)
Azure Storage Account
Excel
Conclusion
This project showcases a complete ETL process using Azure services, demonstrating proficiency in data integration, transformation, and deployment using cloud-based tools. The structure of the project ensures that it is both scalable and maintainable, making it suitable for real-world data processing scenarios.

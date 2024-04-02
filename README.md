# Context
### Analyze distribution transactions to optimize supply chain operations and improve product availability in the pharmaceutical industry.
# Content
### Each row represents a distribution transaction, and each column contains attributes related to the transaction details.

# The data set includes information about:
### *Distributor: This table contains information about distributors, including the DistributorID and Distributor name
### *Organization_Distribution: ### This table likely represents a mapping or junction table between organizations and distributors, containing the OrganizationID and DistributorID as foreign keys.
### *Organization: This table holds details about organizations, such as OrganizationID, OrganizationName, AddressID (presumably a foreign key to the Address table), TypeID (a foreign key to the Type table), and City.
### *Type: This table likely contains different types or categories of organizations, with TypeID as the primary key and OrganizationType as the descriptive field.
### *Address: This table stores address information, including AddressID, City, Latitude, and Longitude.
### *Order: This appears to be a fact or transactional table, containing order details such as OrderID, Quantity, Price, Total sales, Month, Year, OrganizationID (foreign key to Organization), OrganizationName, ProductName, ProductID (foreign key to Product), Name of Sales Rep, Sales_PersID (foreign key to Sales_Person), and DistributorID (foreign key to Distributor).
### *Product: This table holds product information, including ProductID, ProductName, and ProductClass.
### *Product_Class: This table likely contains different classes or categories of products, with ProductClassID as the primary key and ProductClass as the descriptive field.
### *Sales_Person: This table stores information about sales personnel, with fields like Sales_PersID and Sales_Person.
### *Team: This table may contain information about different teams or groups, with fields like TeamID and TeamName.
### *Country: This table stores country information, with CountryID as the primary key and Country as the descriptive field.

# Data visualization:
## Power bi:
![Screenshot 2024-03-24 175113](https://github.com/mohamedsabry20/Pharma-Distribution-Graduation-Project-in-ITI/assets/155188606/b52cd1c1-c4cd-4cb9-baca-64a72ffe9228)
![Screenshot 2024-03-24 175129](https://github.com/mohamedsabry20/Pharma-Distribution-Graduation-Project-in-ITI/assets/155188606/5def4b69-1c16-4dfa-8ed3-e3ac64b656f2)
![Screenshot 2024-03-24 175145](https://github.com/mohamedsabry20/Pharma-Distribution-Graduation-Project-in-ITI/assets/155188606/b34674b3-9e59-483c-9f54-26d2adc99ca6)
![Screenshot 2024-03-24 175225](https://github.com/mohamedsabry20/Pharma-Distribution-Graduation-Project-in-ITI/assets/155188606/77df21ae-fb0c-4bae-8e0a-a5106407a2ea)
![Screenshot 2024-03-24 175239](https://github.com/mohamedsabry20/Pharma-Distribution-Graduation-Project-in-ITI/assets/155188606/af417785-898f-46e3-b040-275e6eda7d9c)
## Tableau:
![Screenshot 2024-03-22 022357](https://github.com/mohamedsabry20/Pharma-Distribution-Graduation-Project-in-ITI/assets/155188606/3ab2c444-7c31-462a-b41d-072c1fe96b8a)
![Screenshot 2024-03-22 022415](https://github.com/mohamedsabry20/Pharma-Distribution-Graduation-Project-in-ITI/assets/155188606/f57a628e-0c2b-4d55-adcb-3c5716d1488a)
![Screenshot 2024-03-22 022430](https://github.com/mohamedsabry20/Pharma-Distribution-Graduation-Project-in-ITI/assets/155188606/86d870f7-b0f0-453f-9ccd-58d91a7d3768)
![Screenshot 2024-03-22 142731](https://github.com/mohamedsabry20/Pharma-Distribution-Graduation-Project-in-ITI/assets/155188606/74891600-caef-4139-ba36-eac61fe4c45b)
![Screenshot 2024-03-22 022504](https://github.com/mohamedsabry20/Pharma-Distribution-Graduation-Project-in-ITI/assets/155188606/2ba99d01-033c-4e1f-9fff-46ba58691c97)











# Inspiration

### To explore and understand the distribution patterns and logistics involved in the pharmaceutical supply chain. This analysis can help identify bottlenecks, streamline operations, and ensure timely and efficient delivery of life-saving medications to patients. Additionally, it can provide insights into customer behavior, product demand, and inventory management, ultimately contributing to better healthcare outcomes and cost optimization.

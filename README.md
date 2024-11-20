# Supply Chain Management

The objective of this project is to design and implement a Supply Chain Management (SCM) solution using Qlik Sense, a business intelligence and data visualization tool, and the DataCo dataset, which provides a comprehensive dataset of supply chain operations. The project aims to analyze and optimize the supply chain operations, identify areas of inefficiency, and provide actionable insights to improve supply chain performance. Real time monitoring of sales and orders, checking transaction mode, managing inventories and demand forecasting using historical data are main insights captured in this project.

### Specifying the business problem
In today's fast-paced business landscape, supply chain management has become a critical component of success. However, traditional methods of supply chain management can be slow and inefficient, leading to missed opportunities and increased costs. Our innovative project aims to revolutionize supply chain management by harnessing the power of data-driven insights using Qlik. By leveraging advanced analytics, we seek to optimize logistics, forecasting, and inventory management, resulting in enhanced operational efficiency and responsiveness. 
This transformative project employs cutting-edge analytics to reshape the landscape of supply chain management. By leveraging Qlik's data-driven insights, we can identify areas of improvement and make data-driven decisions to optimize key facets of supply chain management. With this project, organizations can expect significant improvements in operational efficiency, reduced costs, and enhanced customer satisfaction. 

### Technical Architecture
1. Data Ingestion:
            
        a. Data is downloaded from Kaggle and ingested into Qlik sense.
            
        b. Data is transformed in data loader and editor according to their requirements
2. Qlik Sense Integration:

        a. The Qlik Sense platform is integrated with the data warehouse using APIs or ODBC connectors.

        b. Qlik Sense extracts data from the data warehouse and creates visualizations, reports, and stories.
3. Application Server:

        a. The Qlik Sense application is hosted on an application server.
        b. Users access the application server to interact with the Qlik Sense dashboard.
4. Edit Section:

        a. Different sheets of visualizations are created according to the requirements of dashboards. 
5. Frontend:

        a. The frontend is used to display the Qlik Sense dashboard and provide user interaction.

6. Story Telling:

       a. Throughout the storytelling process, it's essential to consider the audience's needs and ensure the report effectively communicates insights from the data

### Understanding the dataset
The dataset comes with a CSV file that provides detailed descriptions of each field, explaining what each field represents.

Here are the following fields, 

- Type: Type Count  
- Days for shipping (real): Product shipment days
- Days for shipment (scheduled): product getting prepared for shipment
- Benefit per item: profit earned per product   
- Sales per customer: No of products purchased by the customer
- Delivery: Products delivery date.
- Late_delivery_risk: percentage of late delivery risk 
- Category Id: product category ID
- Category: product category
- Customer City: Customer purchase city
- Customer Country: Customer purchase country
- Customer Email: Customer purchase Email
- Customer Fname: Customer First name.
- Customer ID: Customer order ID
- Customer Lname: Customer's last name
- Customer Segment: Types of Customer 
- Customer State: Customer order state
- Customer Street: Customer address
- Customer Zipcode: Customer area code.
- Market: top 10 country Market 
- Order City: Customer purchase city
- Order Country: Customer purchase country
- Order Customer ID: Customer 
- order date (DateOrders): Customer order date
- Order Item Product Price: product price
- Order Item Profit Ratio: profit ratio
- Order Item Quantity: No of orders placed
- Sales: total no of sales
- Order Item Total: total price of the order placed
- Order Profit Per: product
- Order Region: order placed region
- Order State: order placed State
- Order Status: order delivery status
- Order Zipcode: customer area code
- Product Card ID: product number
- Product Category Id: a product whose category belongs to
- Product: what product 
- Product Image: image of the product
- Product Price: Price of the product.

### Dashboard

## Screenshots
![1717347095054](https://github.com/user-attachments/assets/41aea7f2-163d-4127-aeb5-7a82bd51e5f3)





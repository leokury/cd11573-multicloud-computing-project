# DynamoDB x Cosmos DB

One of the requirements of this project is a NoSQL database, so I did a research about the options available on the selected clouds providers: AWS DynamoDB and Azure CosmosDB.

The criterias are: global availability, highly scalable and pricing. 

* Global Availability

Both databases have global availabilty as we can instatiate them from regions distrubuted around all the world.

* Highly scalable

Both databases are highly scalable as we can configure them to automatically increase number of instance to attend usage peaks.

* Pricing

The pricing depends of a number of factors. But for comparison purpose we simulated a usage of 15GB and 1.000 transactions per minute using the online pricing calculators. AWS DynamoDB result is a monthly cost of 55.94 USD while CosmosDB result is 91.35 USD.

Considering the pricing criteria we selected the AWS DynamoDB for this project.
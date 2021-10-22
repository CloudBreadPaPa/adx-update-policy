# Azure Data Explorer update policy review
In this repository, will reviwe Azure Data Explorer update policy code - CSV file and event hub streaming

# Getting Started
- TODO: Setup python 3.8+ environment and run code 
- Review [Azure Data Explorer에서 Trigger 기능 구현 - update policy](https://www.sqler.com/board_Azure/1104135) document

# Build kafka-eventhub-ADX streaming messaging
- [Azure Event Hubs로 kafka message 전송 처리](https://www.sqler.com/board_Azure/1102215)
- [Azure Event Hubs의 데이터를 Azure Data Explorer로 전송](https://www.sqler.com/board_Azure/1102239)

# Execute policy update kusto query
- Upload `data/train_10000.csv` file to storage account and generate SAS token
- Open & run `adx-update-policy-query.kql` kusto query file

# Build and Test
- Compatible with Python 3.8+
# Are you looking for an automated interactive solution that would help you to handle large call volumes and maintain zero wait time for your customers?
This LUIS enabled solution creates an intelligent Interactive Voice Response (IVR) application for automated customer interaction.


# Underlying Architecture
Skype Client: User initiates call; 
Bot Connector + Skype Calling Channel: Routes calls from Skype to the bot; 
Azure App Services: Hosts the bot application, which manages logic and API calls; 
Cosmos DB: Stores bot state and event logs; 
Bing Speech Service: Processes speech-to-text; 
LUIS (Language Understanding Intelligent Service): Extracts intent and entities from text; 
Azure Search: Indexes the product catalog for product-query matching; 
Azure SQL: Stores product and order data; 
Azure Storage: Stores bot audio data for debugging


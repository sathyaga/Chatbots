# Are you looking for an automated solution that would handle large call volumes and maintain zero wait-time for your customers?
This LUIS enabled solution could help create an intelligent Interactive Voice Response (IVR) application for automated customer interaction.


# Underlying Architecture

# 1 Skype Client: 
  --User initiates call 
# 2 Bot Connector + Skype Calling Channel
  --Routes calls from Skype to the bot; 
# 3 Azure App Services: 
  --Hosts the bot application, which manages logic and API calls; 
# 4 Cosmos DB: 
  -- NO SQL, stores bot state and event logs; 
# 5 Bing Speech Service
  --Processes speech-to-text; 
# 6 LUIS (Language Understanding Intelligent Service) 
  --Extracts intent and entities from text; 
# 7 Azure Search: 
  --Indexes the product catalog for product-query matching; 
# 8 Azure SQL: 
  --Stores product and order data; 
# 9 Azure Storage: 
  --Stores bot audio data for debugging


# Continental-Resources

Technologies Utilized
  - OSISoft PI System
  - Microsoft Azure Function
  - Microsoft Event Hub
  - Microsoft Azure Streaming Analytics
  - Microsoft PowerBI
  
How To Build & Deploy
1. Create Azure EventHub
2. Create Azure Function (AF) to monitor the OSISoft PI WebChannel for data changes (send messages to EventHub - see attached AF code)
3. Create Azure Streaming Analytics (ASA) Service and connect to EventHub
4. Change ASA query to adding additional calculation (see attached ASA document)
5. Create PowerBI Dashboard

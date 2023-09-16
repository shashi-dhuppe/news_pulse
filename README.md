# NewsPulse: AWS-Powered Real-Time News Analytics

Utilizes AWS, Kafka, and ELT processes to aggregate, analyze, and visualize news data in real-time. Designed to offer scalable and real-time insights into global news trends through a simple web interface.

## Technologies Used:

1. **AWS Services**
   - EC2: For hosting scraping and backend servers
   - S3: For storing raw scraped articles
   - Lambda: For running transformations and loading data into the database
   - RDS/Aurora: As your SQL database to store processed articles and analytics
  
2. **Apache Kafka**: For message queuing, handling incoming raw articles, and publishing processed data for analytics.

3. **Directed Acyclic Graph (DAG)**
   - Using Apache Airflow: For implementing your analytics logic as a DAG.

4. **Programming Languages**
   - Python: For data scraping and perhaps for some AWS Lambda functions
   - SQL: For database operations
   - HTML/CSS/JavaScript: For building the web interface, possibly with a library or framework like React.js for the frontend

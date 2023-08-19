# System Design Best Practices

System design best practices from cloud platform like Google Cloud Platform, Amazon and Azure.

### Table of contents
- Financial analysis - GCP
- IoT - GCP
- AdTech - GCP
- Genomics data processing - GCP
- Event-driven analysis - GCP

<br>
<br>

## Financial analysis - GCP

Build models based on historical behavior. Continually update fraud patterns and compare with real-time transactions. Store and consolidate market data, trade activity, and other data, such as social and transactional data. [Check out more at Google Cloud Platform](https://cloud.google.com/bigtable#section-7)

![Financial analysis](imgs/FA.svg)

*img from GCP*

**Components**

| Components  |  Summary  | Similar Product |
| ---         | ---             | ---       |
| Bigtable    |  HBase-compatible, enterprise-grade NoSQL database service with single-digit millisecond latency, limitless scale, and 99.999% availability for large analytical and operational workloads.  | Amazon DynamoDB, Apache HBase, Apache Cassandra |
| Dataflow    |  Unified stream and batch data processing that's serverless, fast, and cost-effective.  | Apache Beam, Amazon Kinesis, Apache Flink |
| Pub/Sub    | Ingest events for streaming into BigQuery, data lakes or operational databases.  | Apache Beam, Amazon Kinesis, Apache Flink |

**Related Interview Questions**

| Application | Question  |
| ---         | ---       |
| Amazon      |  How would you design a system like Amazon to detect and prevent fraudulent transactions in real time?  |
| Robinhood   |  While creating a trading platform like Robinhood, how would you ensure optimal utilization of historical trade data to predict future market trends?  |
| eBay        |  If tasked to design a platform like eBay, how would you ensure fraudulent transactions are minimized?  |
| Binance     |  Suppose you are designing real-time trade monitoring for a cryptocurrency exchange like Binance. How would you structure the system to update and compare fraud patterns in real-time? |


## IoT - GCP

Ingest and analyze large volumes of time series data from sensors in real time, matching the high speeds of IoT data to track normal and abnormal behavior. Enable customers to build dashboards and drive analytics on their data in real time. [Check out more at Google Cloud Platform](https://cloud.google.com/bigtable#section-7)

![IoT](imgs/IoT.svg)

*img from GCP*

**Components**

| Components  |  Summary  | Similar Product |
| ---         | ---             | ---       |
| Bigtable    |  HBase-compatible, enterprise-grade NoSQL database service with single-digit millisecond latency, limitless scale, and 99.999% availability for large analytical and operational workloads.  | Amazon DynamoDB, Apache HBase, Apache Cassandra |
| Dataflow    |  Unified stream and batch data processing that's serverless, fast, and cost-effective.  | Apache Beam, Amazon Kinesis, Apache Flink |
| Pub/Sub    | Ingest events for streaming into BigQuery, data lakes or operational databases.  | Apache Beam, Amazon Kinesis, Apache Flink |
| Cloud Storage | Cloud Storage is a managed service for storing unstructured data. Store any amount of data and retrieve it as often as you like. | Amazon S3, Azure Storage |

**Related Interview Questions**

| Application | Question  |
| ---         | ---       |
| Nest      |  How would you design an IoT system like Nest to absorb, process, and react to real-time sensor data? |
| Fitbit   |  How would you create an IoT system like Fitbit that uses time-series data from a wearable device to monitor and analyze user health data in real time? |
| Tesla        |  Can you discuss how you would design an IoT platform similar to Tesla's auto-pilot feature that utilizes sensors to analyze real-time data, determining normal and abnormal behavior?  |
| Apple Watch     |  How would you allow for real-time analytics in a wearable technology system, like Apple Watch, where data from sensors is highly persistent? |


## AdTech - GCP

Integrate large volumes of unrefined data from many sources, typically to drive consistent customer activity across channels. Collect and compare large volumes of behavior data across customers to find common patterns that can drive recommendations and sales. [Check out more at Google Cloud Platform]((https://cloud.google.com/bigtable#section-7))

![AdTech](imgs/AdTech.svg)

*img from GCP*

**Components**

| Components  |  Summary  | Similar Product |
| ---         | ---             | ---       |
| Bigtable    |  HBase-compatible, enterprise-grade NoSQL database service with single-digit millisecond latency, limitless scale, and 99.999% availability for large analytical and operational workloads.  | Amazon DynamoDB, Apache HBase, Apache Cassandra |
| Dataflow    |  Unified stream and batch data processing that's serverless, fast, and cost-effective.  | Apache Beam, Amazon Kinesis, Apache Flink |
| Pub/Sub    | Ingest events for streaming into BigQuery, data lakes or operational databases.  | Apache Beam, Amazon Kinesis, Apache Flink |
| APP Engine | Build monolithic server-side rendered websites. App Engine supports popular development languages with a range of developer tools. | Amazon Elastic Beanstalk, Azure App Service |

**Related Interview Questions**

| Application | Question  |
| ---         | ---       |
| Google Ad     |  How would you design a system for a company like Google to integrate and process different kinds of AdTech data in order to drive consistent customer activity across multiple channels? |
| Facebook's ad platform   |  Consider Facebook's ad platform. How would you collect and analyze large volumes of user behavior data to identify common patterns and drive ad targeting? |
| LinkedIn        |  Suppose you were designing an ad targeting algorithm for LinkedIn. How would the system collect and compare large volumes of user behavior data to generate accurate ad targeting?  |
| Spotify    |  How might you build a system like Spotify's that gathers and analyzes large volumes of user behavior data for making playlist recommendations? |


## Genomics data processing - GCP

Process petabytes of genomic data in seconds with Compute Engine and our high performance computing solution. Our scalable and flexible infrastructure enables research to continue without disruptions. Competitive pricing and discounts help you stay within budget to convert ideas into discoveries, hypotheses into cures, and inspirations into products. [Check out more at Google Cloud Platform](https://cloud.google.com/compute#section-8)

![GDP](imgs/GDP.svg)

*img from GCP*

**Components**

| Components  |  Summary  | Similar Product |
| ---         | ---             | ---       |
| Compute Engine | Secure and customizable compute service that lets you create and run virtual machines on Google’s infrastructure. | Amazon EC2, Azure Virtual Machines |
| Cloud Storage | Cloud Storage is a managed service for storing unstructured data. Store any amount of data and retrieve it as often as you like. | Amazon S3, Azure Storage |

**Related Interview Questions**

| Application | Question  |
| ---         | ---       |
| 23andMe     |  How would you design a system like 23andMe to process petabytes of genomic data efficiently and within seconds? |
| NIH     |  If you were designing a genomics data processing system for a biomedical research organization like NIH, how would you approach the infrastructure design to facilitate uninterrupted research? |


## Event-driven analysis - GCP

Gain a competitive advantage by responding to business events in real time with event-driven analysis. Built-in streaming capabilities automatically ingest streaming data and make it immediately available to query. This allows you to stay agile and make business decisions based on the freshest data. Or use Dataflow to enable fast, simplified streaming data pipelines for a comprehensive solution. [Check out more at Google Cloud Platform](https://cloud.google.com/bigquery#real-time-analytics)

![Event-driven analysis](imgs/EDA.svg)

*img from GCP*

**Components**

| Components  |  Summary  | Similar Product |
| ---         | ---             | ---       |
| Bigtable    |  HBase-compatible, enterprise-grade NoSQL database service with single-digit millisecond latency, limitless scale, and 99.999% availability for large analytical and operational workloads.  | Amazon DynamoDB, Apache HBase, Apache Cassandra |
| Dataflow    |  Unified stream and batch data processing that's serverless, fast, and cost-effective.  | Apache Beam, Amazon Kinesis, Apache Flink |
| Pub/Sub    | Ingest events for streaming into BigQuery, data lakes or operational databases.  | Apache Beam, Amazon Kinesis, Apache Flink |
| Cloud Functions    | Run your code in the cloud with no servers or containers to manage with our scalable, pay-as-you-go functions as a service (FaaS) product.  | Amazon Lambda, Azure Functions |

**Related Interview Questions**

| Application | Question  |
| ---         | ---       |
| Uber     |  How would you design a system for a company like Uber to handle event-driven analysis effectively, allowing for real-time responses to a flurry of ride requests? |
| Twitter     | In the context of Twitter, how would you ensure the streaming data such as tweets, likes, or retweets are immediately available for query as part of an event-driven analysis? |
| Meta     | Imagine you're designing an event-driven analysis system for Facebook. How might you leverage streaming capabilities to make incoming data from likes, shares and comments immediately available for querying? |
| Netflix     | Consider a video streaming platform like Netflix. How would you design your system to handle massive amounts of streaming and user interaction data for real-time decision-making? |


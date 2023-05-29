JEANNE MAY CAROLINO
ALMIRA JILL GARCIA
JOHN PAUL MONTER


Objectives (CAROLINO)

-Describe what data science is and the role of data scientists.
I. The data science
II. The role of a data scientist
III. The data science process
A. Problem formulation
B. Data collection
C. Data preparation
D. Exploratory data analysis and modeling
E. Interpreting and communicating results

-Difference in data and information
I. Data in data science
II. Information in data science
III. Difference between information and data

-Describe data processing life cycle
I. What is data processing life cycle
II. Stages of data processing life cycle

-Understand different data types from diverse perspectives 
I. What are the different data types

-Describe data value chain in emerging era of big data. 
I. Collection
II. Publication
III. Uptake
IV. Impact

-Understand the basics of Big Data. 

-Describe the purpose of the Hadoop ecosystem components. 
I. What is Hadoop Ecosystem
II. Purpose of the key components of the Hadoop ecosystem


PART B
Discussions 

	3. Describe data processing life cycle.(CAROLINO)

The data processing life cycle is a systematic approach to managing and transforming data from its raw state to valuable insights. It consists of several stages that work together to ensure that data is collected, prepared, analyzed, visualized, reported, and maintained accurately and effectively.
1) Data Collection is the first step involved in the data processing cycle. It is validated by prioritizing the information resources provided, such as the company's profits and losses, user data, staff data, market net worth, and other necessary data, after acquiring the raw information from other organizations in the enterprise.

2) Data Preparation in the processing cycle involves the duties to prioritize the data collected and filter out the unnecessary and inaccurate data. Before the conclusion, the errors in the data, replication of the data, duplicate data, and such misleading data are corrected and filtered to guarantee the quality. Once the data quality is checked, it is then encoded for further cycle. Because of all the methods used, the term "data cleaning" is also used to describe this step of data processing.

3) The Data Input stage of data processing is where the cleaned or encoded data is transformed into inputs that can be read by machines. It is ensured that the data is in a format that can be read by a computer and processed before feeding it to the computer. At this stage of the case, the priority is to validate the data before supplying it to the computer's Central Processing Unit (CPU).

4) Data Processing makes the data subject to various data processing methods like algorithmic and statistical calculations, depending on the tools that are being used. Most of the available tools make use of algorithms designed using machine learning and artificial intelligence for processing the cleaned data.

5) Data outputs are the form of data that has been processed and obtained by the previous steps. The output data obtained is then decoded which is ready to be displayed to the users. These outputs help the users immediately extract the statistics. Based on these extracted statistics, the presentation is done. For presentation, charts, reports, tables, graphs, and other such information-conveying statistics are used.

6) Storage is a major asset in any kind of data processing. The final step in the cycle is to store the decoded output data and metadata for future calibration and use. Through this, the user would be able to retrieve any particular data whenever needed. For a reliable use, the organizations buy huge amounts of memory to store all the data.
     In conclusion, the data processing life cycle is a continuous process that involves the collection, preparation, input, output, reporting, and storage. It is an iterative process, and the stages may be repeated multiple times to refine the results and improve the quality of the data. This process helps organizations to make informed decisions, gain a competitive advantage, and achieve their goals.



	4. Understand different data types from diverse perspectives.(CAROLINO)

Data can be classified into different types based on the way it is collected, its structure, and its content. Understanding the different data types is important because it helps in selecting the appropriate analytical methods and tools to extract insights from the data.
Numerical Data:
Statistical Perspective: Numerical data can be analyzed using statistical techniques such as measures of central tendency, dispersion, correlation, and regression.
Scientific Perspective: Numerical data can be used to represent measurements, observations, and experimental results in various scientific fields.
Business Perspective: Numerical data can be employed for financial analysis, forecasting, sales figures, and other quantitative business metrics.


Categorical Data:
Sociological Perspective: Categorical data can provide insights into social divisions, demographics, cultural attributes, and group affiliations.
Marketing Perspective: Categorical data can assist in market segmentation, customer profiling, target audience identification, and product preferences.
Political Perspective: Categorical data can be utilized to analyze voting patterns, political affiliations, public opinion, and demographic influences on elections.
 
Textual Data:
Natural Language Processing Perspective: Textual data can be processed using NLP techniques like sentiment analysis, topic modeling, named entity recognition, and text classification.
Information Retrieval Perspective: Textual data can be indexed and searched to extract relevant information, build search engines, and enable document clustering.
Customer Support Perspective: Textual data can be analyzed to understand customer feedback, sentiment, and trends, helping improve products and services.

Geospatial Data:
Environmental Perspective: Geospatial data can be used to analyze ecosystems, land use patterns, climate change, and natural resource management.
Urban Planning Perspective: Geospatial data can aid in city planning, infrastructure development, traffic management, and location-based services.
Disaster Management Perspective: Geospatial data can support emergency response, risk assessment, evacuation planning, and spatial modeling of hazards.

Time Series Data:
Financial Perspective: Time series data can be utilized for stock market analysis, asset pricing, forecasting, and risk management.
Medical Perspective: Time series data can help monitor patient health, analyze physiological signals, detect anomalies, and predict disease progression.
Energy Perspective: Time series data can assist in energy consumption analysis, demand forecasting, grid optimization, and renewable energy planning.

In conclusion, understanding the different data types and their characteristics is essential for data scientists to select the appropriate methods and tools to analyze and interpret the data. Each type of data requires a specific approach to analysis, and the analytical techniques used must be adapted to the structure and content of the data to extract valuable insights.



	7. Describe the purpose of the Hadoop ecosystem components.(CAROLINO)

	The Hadoop ecosystem is a collection of open-source software components that work together to enable the storage, processing, and analysis of large-scale data sets. Each component within the ecosystem has a specific purpose and plays a crucial role in building a distributed and scalable data processing infrastructure. Here are some key components of the Hadoop ecosystem and their purposes:

Hadoop Distributed File System (HDFS): HDFS is a distributed file system that provides reliable, scalable, and fault-tolerant storage for big data. It breaks large files into blocks and distributes them across a cluster of machines, allowing for high throughput and parallel processing.
MapReduce: MapReduce is a programming model and processing framework for distributed data processing. It allows developers to write parallelizable algorithms that can process large amounts of data by dividing the workload into maps and reducing tasks, which are executed in parallel across the cluster.
YARN (Yet Another Resource Negotiator): YARN is a resource management framework in Hadoop that handles resource allocation and scheduling of tasks. It manages the cluster resources and enables different data processing frameworks, such as MapReduce, Apache Spark, and Apache Flink, to run concurrently on the same Hadoop cluster.
Apache Hive: Hive is a data warehouse infrastructure built on top of Hadoop that provides a high-level query language, HiveQL, similar to SQL. It allows users to write queries and perform data analysis on large datasets using a familiar SQL-like interface.
Apache Pig: Pig is a high-level data flow scripting language and runtime environment for Hadoop. It allows users to express data transformations and analysis tasks using a scripting language called Pig Latin. Pig optimizes and executes these scripts on the Hadoop cluster.
Apache Spark: Spark is a fast and general-purpose distributed data processing engine that can run on top of Hadoop. It provides an in-memory computing capability and supports various programming languages, including Scala, Java, Python, and R. Spark offers a rich set of libraries for batch processing, stream processing, machine learning, and graph processing.
Apache HBase: HBase is a distributed, scalable, and column-oriented NoSQL database that provides real-time read/write access to large datasets. It is built on top of HDFS and is designed for random, low-latency access to big data, making it suitable for applications that require fast data retrieval.
Apache Kafka: Kafka is a distributed streaming platform that allows for the storage and real-time processing of high-throughput, fault-tolerant, and event-driven data streams. It provides pub-sub messaging capabilities and is often used for building real-time data pipelines and streaming applications.

These are just a few examples of the components within the Hadoop ecosystem. There are several other tools and frameworks available, such as Apache ZooKeeper for distributed coordination, Apache Flume for collecting and aggregating log data, and Apache Sqoop for data integration between Hadoop and relational databases. The purpose of the Hadoop ecosystem components is to provide a comprehensive set of tools and technologies for handling big data challenges, including storage, processing, analysis, and streaming, in a distributed and scalable manner.

 





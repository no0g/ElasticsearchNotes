# Elasticsearch Notes
  
## What is Elasticsearch?
Elasticsearch is a distributed document-oriented search engine, which is used to store data in the form of a document. 

## Pros
- Elasticsearch is compatible to run on every platform because it is developed in Java.
- It is a real-time search engine, which means that only just one second before added document is searchable in this engine.
- Elasticsearch offers the concept of gateway, which allows for creating full backups easily.
- It is distributed document-oriented that makes easy to scale up in large organization. The developer can easily integrate it to any large organization by scaling it.
- Multi-tenancy can be easily handled in Elasticsearch in comparison to Apache Solr.
- Its documentation is available in several languages. Therefore, people from different regions can use it in their languages.
- Elasticsearch is an open-source. So, there is no need to pay any license cost for downloading it.
- It supports all document type, only except for those that do not support text rendering.

## Cons

- Sometimes, the problem of split-brain situations occurs in Elasticsearch.
- Unlike Apache Solr, Elasticsearch does not have multi-language support for handling request and response data.
- Elasticsearch is not a good data store as other options such as MongoDB, Hadoop, etc. It performs well for small use cases, but in case of streaming of TB's data per day, it either chokes or loses the data.
- It is a flexible and powerful data storage search engine, but it is a bit difficult to learn. Especially in terms of enterprise search usage, it is not as simplest as out the box search.

## Introduced Features
1. Scalable   
It can be scalable across multiple nodes. So eventually, you can start with a single node or two or three nodes. If the workload grows, in that case, you scale across multiple nodes. So, the more instances can be added to a cluster whenever needed. It is horizontally scalable.   

2. Performance   
It is very fast comparatively other search engines. It executes operations on data very fast.   

3. Multilingual   
Elasticsearch is a multilingual means it is available in various languages. So, the people of different regions can use it in their languages.   

4. Document Oriented   
Elasticsearch is document-oriented, which does not use schemas and tables to store data. It stores all the data in a document form. Therefore, whatever document is created, the data is presented in the form of JSON format, which is a widely accepted web format. So, you can integrate several solutions as it provides you the output in terms of JSON format.   

5. Autocompletion and Instant Search   
It supports auto-completion and instant search. So, whenever you start typing queries, it automatically does support the auto-completion. It automatically provides suggestions to complete queries.   

6. Schema less   
It is schema-less because it follows the document-oriented approach instead of schemas and tables. So, the data is stored in documents in Elasticsearch.   

7. Open Source   
It is an open-source search database search engine. So, anyone can download it without paying any license cost.   

## Installation
The service can be downloaded from its official [website](https://www.elastic.co/downloads/elasticsearch).  
Once started it will be deployed on localhost:9200 by default

## Python Notebook
`elasticnotes.ipynb` covers the basic use of elasticsearch and an attempt to move data from mysql database to elasticsearch.   
![alt text](https://i.imgur.com/ccI7XFR.png)   


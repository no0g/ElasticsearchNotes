# Elasticsearch Notes
  
## What is Elasticsearch?
Elasticsearch is a search engine built on apache lucene. It is an open source and developed in Java. It is a real time distributed and analytic engine which helps in performing various kinds of search mechanism. It is able to achieve fast search responses because, instead of searching the text directly, it searches an index instead. Additionally, it supports full-text search which is completely based on documents instead of tables or schemas.  

## Basic Concepts

- Near Real Time: Elasticsearch is a near real time search platform which perform search as quickly as you index a document.

- Cluster: A cluster is a collection of one or more nodes that together holds the entire data. It provides federated indexing and search capabilities across all nodes and is identified by a unique name (by default it is ‘elasticsearch’).

- Node: A node is a single server which is a part of cluster, stores data and participates in the cluster’s indexing and search capabilities.

- Index: An index is a collection of documents with similar characteristics and is identified by a name. This name is used to refer to the index while performing indexing, search, update, and delete operations against the documents in it.

- Type: A type is a logical type of an index whose semantics is complet. It is defined for documents that have a set of common fields. you can define more than one type in your index.

- Document: A document is a basic unit of information which can be indexed. It is demonstrated in JSON which is a global internet data interchange format.

- Shards: Elasticsearch provides the ability to subdivide the index into multiple pieces called shards. Each shard is in itself a fully-functional and independent “index” that can be hosted on any node within the cluster

- Replicas: Elasticsearch allows you to make one or more copies of your index’s shards which are called replica shards or replica.

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

## Kibana
Kibana is an open source data visualization dashboard for Elasticsearch. It provides visualization capabilities on top of the content indexed on an Elasticsearch cluster. Users can create bar, line and scatter plots, or pie charts and maps on top of large volumes of data.   

Kibana also provides a presentation tool, referred to as Canvas, that allows users to create slide decks that pull live data directly from Elasticsearch.   

You can access the features of kibana [here](https://www.elastic.co/kibana/features).  

Kibana can be deployed on cloud using elastic cloud's service or downloaded from [here](https://www.elastic.co/downloads/kibana) and deployed locally.  

- Dashboard
![alt text](https://i.imgur.com/u1OaVEa.png)   
Kibana's Dashboard that shows your visualized data.   
- Dev Tools
![alt text](https://i.imgur.com/lHJEHsm.png)   
Kibana's Dev tools that helps you to debug and/or communicate directly to the elasticsearch.
- Canvas
![alt text](https://i.imgur.com/jL0Jb7B.png)   
Generate your data into a presentable item!  

## Sources
- [Advantages and disadvantage of Elasticsearch](https://www.javatpoint.com/advantages-and-disadvantages-of-elasticsearch)
- [Build A Search App With ElasticSearch](https://www.youtube.com/watch?v=9hHWI02Axl8)
- [Chapter 2: Insert and Get query | Elasticsearch using Python](https://www.youtube.com/watch?v=-l3stO46CJc)
- [What is Elasticsearch?](https://medium.com/@AIMDekTech/what-is-elasticsearch-why-elasticsearch-advantages-of-elasticsearch-47b81b549f4d)

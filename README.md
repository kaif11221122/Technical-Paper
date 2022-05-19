# Analysis of Lucene,Solr and Elasticsearch for Full Text Search

### Abstract

    Full text search used for searching some text inside extensive text data stored electronically 
    and returning results that contain some or all of the words from the query. We will be analyzing the Lucene, 
    Solr and Elasticsearch for Full text searching with there features and efficiency. 
  
### Details about Lucene, Solr and Elasticsearch


  #### Lucene -

    * Lucene is a high performance full text search engine which is written in Java 
    
    * It is basically underlying search technology which is used by Solr and Elastic
    
    * Lucene offers implementation of algorithm for, 
        - ranked searching, fielded searching
        - multiple type of powerful queries
        - fielded searching
        - allows simultaneous update and searching
        - flexible faceting, highlighing, joins and result grouping
        - nearest neighbor search for high dimensionality vectors
        - congigurable storage engine (codecs)
    * It provides Cross Platform Solution as its available as Open Source software under the Apache 
      which lets you use it both commercial and Open Source programs and Implentations in other languages 
      available that are index compatible.
    * Now because of this all features it is used for any application which requires full text search, 
      espeacailly cross platform used by great developer and user community.
  
  #### Solr
    
     * Apache Solr is an open source search server platform written in Java by Apache.
     * It's highly scalable and ready to deploy engine which can handle large volume of text data.
     * Basically Solr is a REST API based HTTP wrapper which uses the full text seach engine named as Lucene
     * Solr provides following features,
        - Automatic Load balancing
        - Standards-Based open interfaces - XML,JSON, and HTTP
        - Recommendations and spell suggestions are supported
        - Support for Auto completion and Geo spatial search
        - Build in Security for authentication and authorization
        - Batch and Streaming processing
        - Building machine learning models are easy
        - Faceted search and filtering
        - Central configuration for entire cluster
     * As Solr support for multi tenant architecture, it provides you to scale, distribute and manage 
       indexes for large scale applications.
    
  #### Elasticsearch
  
    * Elasticsearch is a distributed ,open source search engine build on Lucene which is developed in Java.
    * As it is built on Java programming language and hence Elasticsearch can run on different platoforms.
    * Elasticsearch allows you to store, search and analyze the huge volumes of data quickly in realtime and 
      give back answers in milliseconds.
    * It provides us fast search responses because instead of searching the text directly, Elasticsearch 
      searches an index.
    * General features of Elasticsearch
        - Elasticsearch is highly scalable as it can goes upto petabytes of structured and unstructured data.
        - It can be replaced with document stores likes MongoDB and RavenDB.
        - Uses denormalization to improve the seach performance.
        - Elasticsearch is popular search engine and is currently being used by many big organizatons 
          like Wikipedia, The Guardian, StackOverflow, Github etc.
    * As a result of this all features provided by Elasticsearch, it become most popular search engine in 
      very less time and its commonly being used for log analytics, full text search.
  
  #### Difference betweeen Solr and Elasticsearch in terms of Full Text Search Features
    
    * Solr and Elasticsearch take advantage of lucene's features in almost realtime which allows queries to match
      documents immediately after indexing.
    * When you compare the Solr code base with Elasticsearch, it has more and huge features related to 
      full text search.
    * On the otehr hand Elasticsearch has a dedicated tip man API that hides implementation details of user 
      which gives us an easier way to implement recommendations at the expense of reducing flexibility.
    * Elastic search developers are putting a lot of efforts to make this query more efficient at reducing memory 
      usage and CPU usage at lucene and elasticsearch levels.
    * Solr have features of faceted search, Highlighters, spell check, Autocomplete and Filter queries while 
      Elasticsearch have features of Inverted index, cross cluster search, Highlighters, Query DSL, Typeahead, 
      corrections(Spell check). 
    
### Conclusion
  
  * Pick Lucene if you wants to build quick standalone search app which could be web service also and 
    if wants to implement the server side search application with ease then use Solr or Elasticsearch for 
    diving deep into Lucene's abstractions, search, index management etc.
   
  * Now coming to the pick the Solr and Elasticsearch, Solr is even more focused on text search while 
    Elastic search is generally used for filtering and grouping, parsing query and not necessarily text searches.

### References

1. https://sematext.com/blog/solr-vs-elasticsearch-differences/
2. https://wordcounter.net/
3. https://logz.io/blog/solr-vs-elasticsearch/
4. https://www.tutorialspoint.com/elasticsearch/elasticsearch_basic_concepts.htm
5. https://aws.amazon.com/opensearch-service/the-elk-stack/what-is-elasticsearch/#:~:text=Elasticsearch%20is%20a%20distributed%20search,and%20operational%20intelligence%20use%20cases.
6. https://sematext.com/guides/solr/
7. https://www.lucenetutorial.com/
8. https://lucene.apache.org/core/

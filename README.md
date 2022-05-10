# uk-security

A simple NoSql database (Neo4J) for the UK cyber-security structure


Directions:

1. start a Neo4j database
2. import the UKcyberV1.cql
3. add enteries into index.html to connect to the neo4j (bolt) server 
3. open/serve index.html

OR

just run the docker-compose file  - not fully working yet

  - using a browser connect to localhost:7474
  - in the page, login with neo4j and pw: test
  - past in the contents of UKcyberv2.cql  and run
  - run 'MATCH (n) RETURN (n)' to show all nodes and relationships.



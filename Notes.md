


### Vector databases
### Key-value store
### Tuple store
### Triplestore
### Object databases
### Document store
### Wide-column store
### Native multi-model database
### Graph database
### Multivalue database

## Example
Running app
- Users (Document)
- Users can have:
  - Friends
  - Give likes
  - Write comments
  - Create routes
- Likes (Document)
- Comments (Document)
- Routes (Geo data)
- Live tracking data (Time series)
- Running game (Mem cache)
- Statistics (Relational)
- Predictions (ML)



## Vector database

## Key-value

key            value
user:23:bio -> i like turtles

In Redis all data is stored in memory.

## Wide column

row key   Columns
bob    -> Name(bob) Age(23) Eyes(brown)

Query language CQL

Casandra
HBASE

## Document based

A document is a container for key-value pairs.
Each document can have sub documents (collections)

MongoDB
Firestore
DynamoDB
CouchDB

## Relational

Called relational because Edgar Codd used Relational algebra to create it. 

Schema is required

Primary, foreign keys

Structured Query Language

MySql
Postgres
SQL Server
Cockroach labs (Designed to scale) 

## Graph

Node (Data)
Edge (Relationship)

Node -> Edge -> Node

Neo4J
DGraph

## Search

Closely related to document based databases. 
Indexed. 

Algolia (Cloud based)
MeiliSearch (Cloud based)
Lucene (OG)
Elastic
Solr

## Multimodel
FaunaDB (uses graphql)

## Time series

## Data warehouses

## File storage?

## Network database?

## New databases
### Planetscale (serverless myssql / Vitess)
### YugabyteDB (serverless Postgresql open source)
### Neon (serverless Postgresql open source)
### Dolt (MySql / Github)
Create branches from the main database without breaking things.
### CockroachDb (NewSql)
FoundationDB
TiDB
### Cloudflare D1 (Sqlite on the edge)
Stored procedures with javascript.
### Xata (Serverless relational db)
Developer friendly alternative to airtable and notion. Treats data as a spreadsheet.
### 8Base **
Provides graphql out of the box. 
Can also build frontend components. 
### EdgeDb (ORM for postgresql)
### SurrealDB (Supports acid transactions SQL/Cipher, Multimodel)
### Fauna (FQL, GraphQl)
Document-Relational, Native joins
### MemGraph (Neo4J)
### Redis (ModJs)
### MeiliSearch (Open source)
### mindsdb (Ai tables)
Integrates machine learning features.
### TimescaleDB
Timeseries database



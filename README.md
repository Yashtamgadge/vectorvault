Project Idea in a Nutshell
Business/Enterprise have a lot of data
Revolves around entities
Each department has data; "hidden" in a way that not always accessible to other departments
Like for marketing use case, some finance data might be hidden which could be useful
Different data formats. No structured way to go through non-database data
Use vector embeddings and then clustering on this data
Now, each document can be part of multiple clusters
One doc can contain different information
While data retrieval - let's say it is found in doc 1
doc 1's other information if related gets added to context and data retrieval result
The cluster of course is important
In addition to the above, for each clusters, using Named Entity Recognition - entities are formed
For each entity, knowledge graph using graph embeddings are formed
These are also used in data retrieval result
In every data retrieval result, reference of the doc, named entities, etc. are also shared
What are Problem Statements?
Different form of textual data in enterprises (Apart from DB data like RDBMS)
Each department has their set of data docs
Use of Named Entity Recognition could be super useful for businesses that provides services
No intelligent knowledge management system for enterprise data
Use cases
Creating customized marketing plans
Support management
Strategic plans
Advanced data retrieval systems
Legal
Customized renewal strategies
Important Notes
Please find the link to the Google Collab notebook in the attachment section. Also sharing here
The objective of the code is to create an MVP. No LLM, not even local LLM have been deployed (This could augment data query answers)

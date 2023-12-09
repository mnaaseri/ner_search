# Semantic Search Using NER

This notebook shows how to use Named Entity Recognition (NER) for hybrid metadata + vector search with Pinecone. We will:

1. Extract named entities from text.
2. Store them in a Pinecone index as metadata (alongside respective text vectors).
3. We extract named entities from incoming queries and use them to filter and search only through records containing these named entities.

This is particularly helpful if you want to restrict the search score to records that contain information about the named entities that are also found within the query.


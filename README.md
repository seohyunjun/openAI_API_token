# openAI API token
openAI API token information

[OpenAI v2 Embeddings - Part 2 (text-embedding-ada-002)](https://www.youtube.com/watch?v=oQdgyGywfr4)

#### API price
Number of tokens: 2675


|MODEL|VERSION|COST|
|---|---|---|
|Ada		|v1	|$0.0107|
|Babbage		|v1	|$0.013375|
|Curie		|v1	|$0.0535|
|Davinci		|v1	|$0.535|
|Ada		|v2	|$0.00107|


### Model dimension

https://platform.openai.com/docs/guides/embeddings/what-are-embeddings 

|MODEL|OUTPUT DIMENSIONS|
|---|---|
|Ada|1024|
|Babbage|2048|
|Curie|4096|
|Davinci|12288|

### Text search embeddings

- 가장 많이 사용 문서 탐색

|USE CASES|AVAILABLE MODELS|
|---|---|
|Search, context relevance, information retrieval|text-search-ada-doc-001 text-search-ada-query-001 text-search-babbage-doc-001 text-search-babbage-query-001 text-search-curie-doc-001 text-search-curie-query-001 text-search-davinci-doc-001 text-search-davinci-query-001|

### OpenAI Text & Embedding Rate Limits?

- Rate limits are enforced at the organization level, not user level, based on the specific endpoint used as well as the type of account you have.

- Rate limits are measured in two ways: RPM (requests per minute) and TPM (tokens per minute).

- TEXT & EMBEDDING
- Free trial users •20 RPM •150,000 TPM

- Pay-as-you-go users (first 48 hours) •60 RPM •250,000 TPM

- Pay-as-you-go users (after 48 hours) •3,000 RPM •250,000 TPM

- https://beta.openai.com/docs/guides/rate-limits/overview


|TYPE|	1 TPM EQUALS|
|---|---|
|davinci|	1 token per minute|
|curie|	25 tokens per minute|
|babbage|	100 tokens per minute|
|ada|	200 tokens per minute|







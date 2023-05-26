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


test text / token_counts = 37
[kor_text]  
`금융통화위원회는 다음 통화정책방향 결정시까지 한국은행 기준금리를 현 수준(3.50%)에서 유지하여 통화정책을 운용하기로 하였다. 물가상승률이 둔화 흐름을지속하겠지만 상당기간 목표수준을 상회할 것으로 전망되는 만큼 현재의 긴축기조를 유지하는 것이 적절하다고 보았다. 추가 인상 필요성은 대내외 정책여건의 변화를 점검하면서 판단해 나갈 것이다.`. 

[eng_text]  
`The old, creaky wooden door swung open slowly, revealing a dimly lit room filled with dusty books and antique furniture, while a faint scent of lavender lingered in the air, evoking a sense of nostalgia and mystery.`

|model|max_dim|kor_cost|eng_cost|kor_dim|eng_dim|price|
|---|---|---|---|---|---|----|
|AlephAlphaAsymmetricSemanticEmbedding|128~5120|1.0295090675354004|0.4645390510559082|128|128|Base Price per 1000 input tokens 0.03 (€0.006)|
|AlephAlphaSymmetricSemanticEmbedding|128~5120|1.4380428791046143|0.3773219585418701|128|128|Base Price per 1000 input tokens 0.03 (€0.006)|
|CohereEmbeddings|4096|1.168846845626831|0.3746333122253418|768|768|$1.0 / 1k Embeddings|
|VertexAIEmbeddings|1024|-|-|-|-|$0.01 / 1k token|
|HuggingFaceEmbeddings|768|0.20738792419433594|0.04394221305847168|768|768|no cost|
|HuggingFaceInstructEmbeddings|512|0.1447281837463379|0.1259918212890625|768|768|no cost|
|LlamaCppEmbeddings|-|-|-|-|-|-|
|JinaEmbeddings|512|2.2679479122161865|1.4199268817901611|512|512|usage per credit(1000 req)|
|OpenAIEmbeddings|1536|0.30863404273986816|0.389833927154541|1536|1536|$0.0004 / 1k tokens|





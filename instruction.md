Install antigravity
Install Neo4j

create project folder
copy tiktoken-cache directory
copy .env file
check the practice key

setup npm - run below in terminal
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
npm config set strict-ssl false

create python venv
python -m venv .venv
\.venv\Scripts\Activate.ps1

install gsd
npx @opengsd/gsd-core@latest

/gsd-new-project
/gsd-new-milestone <provide the entire context for the application build>

Context should include below along with the main business case - Give these instructions along with the Usecase to Gemini and ask to create a copy paste safe Spec document for antigravity. Do not give the use case alone.

Backend python. Use UI_Spec.md (download from github) for generating the frontend. Create an Ontology for the problem statement, from ontology create knowledge graph in neo4j desktop installed locally. Documents are required to chunked and pushed into vector db. 
Frontend should be in react & look and feel should be premium. The solution should be production like. Always provide authentication. Add guard rails configurable using Admin persona. The solution should show 
the task level view, should implement a Glassbox architecture. Use langgraph. Use Lngchain for calling LLM api. Create config file for all configuration related components so that config can be toggled. Every answer should have citation and it can be tracked back to the source. Every response should be grounded. Every response should be evaluated against a Benchmark, should have LLM as Judge and should use Evals before posting the answer to the user. Every PII data should be redacted before data is embeded and finally when before showing the answer to the user the response should include the actual data in the place of 
placeholders. Use SQLLite for PII redaction. Use Presidio for PII identification. Every answer should be evaluated against LLM Judge. Use gpt 5 for judge. Use gpt 4O mini for all other tasks. 

***Define multiple personas
Add admin persons. Admin should have Agent observability, Tokenomics & performance parameters. Admin should be able to configure the guardrails and security parameters.
*** Chat should always have short term memory & long term memory. Long term memory can be stored into SQLLite.

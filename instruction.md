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

Context should include below along with the main business case -
Create an Ontology for the problem statement, from ontology create knowledge graph in neo4j desktop installed locally. Documents are required to chunked and pushed into vector db. 
Frontend should be in react & look and feel should be premium. The solution shuuld be prodction like.



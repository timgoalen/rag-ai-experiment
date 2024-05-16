# rag-ai-experiment

An example of Retrieval-Augmented Generation (RAG) from: https://github.com/wordsmith-ai/hello-wordsmith/

A way of providing additional context along with a question sent to a LLM.

1. User -> question
2. RAG -> adds context
3. LLM receives question + context
4. LLM returns more accurate answer, and is able to access provided additional information (documents etc.)

## Launch the virtual environment
- cd hello-wordsmith
- source ./bin/activate
## Set the OpenAI API key
- export OPENAI_API_KEY="sk-..."
## Start the AI assistant REPL
- hello-wordsmith
# Clarium
## Summary & Background  
I'm building this app because I want to know facts about U.S. politics. I think there's an opportunity to have unbiased, factual reporting about Presidential and Congresional actions through the utilization of LLMs. 
I want to create an app that ingests all federal orders and produces social media posts and generates content for an email newsletter. Eventually, I'd love to make this a searchable tool that has all federal orders in a vector DB
and utilize RAG to have a knowledge assistant for federal documents.

## Progression
- ✅ **MVP1 Developed:** Scrapes executive order text from Whitehouse.gov, stores data in a CSV, calls GPT-4 API to generate content, stores content in CSV.
- 🚧 **MVP2 Developed:** Download PDF documents from [Federal Register](https://www.federalregister.gov/presidential-documents) and store in a database. Push PDFs to GPT-4 API call to create content via prompt from MVP1.
- 🔜 **Alpha:** Build on MVP2

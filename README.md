# Talk-to-any-Website-LLM

This project uses the open-source **crawl4AI** web crawler (inspired by [Ottomator Agents](https://github.com/coleam00/ottomator-agents/tree/main/crawl4AI-agent)) to extract and convert website data into markdown. The markdown data is then stored in a **RAG database** powered by **Supabase** for efficient retrieval. The system leverages **OpenAI GPT-4o-mini** as the LLM and features a **Streamlit**-based chat interface for querying the data.

For this implementation, I specifically crawled the [Red Hen Lab](https://www.redhenlab.org/) open-source research community website to demonstrate its effectiveness.


![RedHenLab](https://github.com/user-attachments/assets/d0b8fe29-1eaf-4cda-9d5e-02778d419f93)

In the image, you can see that Agentic RAG provides better results for Red Hen Lab compared to ChatGPT. It also delivers more recent information retrieving it from the database that ChatGPT cannot.

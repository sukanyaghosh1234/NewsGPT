NewsBot: News Research Tool 📈

NewsBot is a sophisticated tool designed to facilitate efficient research and analysis of news articles. Leveraging advanced natural language processing (NLP) techniques and state-of-the-art models, NewsBot enables users to input URLs of news articles and retrieve concise answers to their queries directly from the content.

Features:

URL Input: Users can input up to three URLs of news articles directly into the sidebar for processing.

Data Processing: Once URLs are submitted, NewsBot initiates the process of loading and analyzing the articles. It employs a Recursive Character Text Splitter to segment the text effectively for further analysis.

Embedding and Indexing: The tool generates embeddings using OpenAI's advanced language models to represent each segmented document. These embeddings are then indexed using the FAISS (Facebook AI Similarity Search) library, facilitating quick retrieval of relevant information.

Interactive Querying: Users can enter specific questions related to the news articles. NewsBot utilizes a sophisticated retrieval-based question answering model powered by OpenAI. It dynamically retrieves and presents the most relevant answers from the indexed articles.

Source Display: Alongside answers, NewsBot displays the sources from which the information was extracted. This feature provides transparency and allows users to verify the credibility of the information.

Technologies Used:

Streamlit: Front-end web application framework for Python, used for building the user interface.

OpenAI: Integration of advanced language models for question answering and text embeddings.

FAISS: Efficient similarity search library used for indexing embeddings and optimizing retrieval.

How to Use:

Input URLs: Enter URLs of news articles of interest in the sidebar and click "Process URLs" to initiate data loading and analysis.

Ask Questions: Type your queries into the text input field labeled "Question" to receive relevant answers from the indexed articles.

Explore Sources: View the sources cited to explore further details and confirm the validity of the retrieved information.

# Search Engine for News Category Dataset

This project focuses on implementing a search engine specifically designed for a news category dataset. The aim is to create an efficient and accurate system that allows users to search for relevant news articles based on their queries. The Search Engine for News Category Dataset project leverages a dataset containing a vast collection of news articles, each categorized based on its topic or subject matter. The objective is to develop a robust search engine that enables users to retrieve relevant news articles by entering keywords or phrases.

## Design of Search Engine

<img width="1028" alt="image" src="https://github.com/suman-rathaur/Search-Engine/assets/127435701/a6a13d54-3897-4c24-bb59-4c22f6c909b3">

- Preprocessing: The dataset undergoes preprocessing steps including lowercase conversion, punctuation and stopwords removal, tokenization, and filtering. These steps enhance the quality and relevance of search results.

- Language and Coding Platform: The project is implemented using Python programming language. Jupyter notebooks with Google Colab are used as the coding platform for development and experimentation.

- Indexing and Retrieval: Elastic Search is utilized for indexing the news dataset using the es.index() function. It enables efficient retrieval of relevant articles based on user queries. The search engine ranks the results based on scores assigned to each article.

- K-Nearest Neighbors (KNN): KNN is employed for training and testing, although due to longer execution times, it has been commented out in the Jupyter notebook. It can potentially enhance search accuracy and performance.

- Query Expansion: The search engine incorporates query expansion techniques to broaden the search scope and improve result relevance. This enhances the system's ability to retrieve relevant articles even when the query terms may not directly match the articles' contents.

- Command Interface: The search interface is implemented as a command-line interface, enabling users to enter their search queries and receive corresponding article results.

- Displayed Information: The search results include headlines, links to the articles, short descriptions, article IDs, and scores. This provides users with essential information to evaluate and select the most relevant articles.

- User Feedback: The search engine encourages user feedback to further improve the search results. Users can provide feedback on the relevance and usefulness of the displayed articles, helping to refine the search algorithms and enhance future search experiences.

 ## Results
 1. Search Query
 ![image](https://github.com/suman-rathaur/Search-Engine/assets/127435701/cbd5feb0-23f8-4a17-8bdc-bbbc8b7193cb)

2. User Feedback
<img width="585" alt="image" src="https://github.com/suman-rathaur/Search-Engine/assets/127435701/623660c0-ff8a-4f43-ad63-97511e6c9dae">

# Query-Product-Ranking-Product-Classification

### Background:<br>
This project aims to revolutionize product search relevance on e-commerce platforms by going beyond traditional binary classification methods. It introduces a multi-class categorization framework of Exact, Substitute, Complement and Irrelevant (ESCI) to capture the nuanced relevance between user search queries and products. The proposal encompasses three interconnected tasks - Query-Product Ranking to prioritize products using weighted probabilities across ESCI categories; Multiclass Product Classification to categorize products into one of the four relevance types; and Product Substitute Identification to surface relevant alternate options using substitute probability thresholds. These objectives aim to significantly enhance search precision, contextuality and user experience by understanding the complex dynamics of user intent and shopping behavior. 

### Data Description:<br>
The dataset used in this project is taken from the Amazon KDD Cup 2022 competition, consisting of multilingual search queries and product metadata sourced from Amazon's catalogs. It includes over 781 million queries mapped to around as Table 1: 883 thousand products, with detailed relevance judgments categorizing the products for each query as Exact matches, Substitutes, Complements or Irrelevant per the ESCI framework. The queries and products span three locales - predominantly English (United States), but also Spanish and Japanese languages - exhibiting class imbalance but capturing regional diversity. The rich dataset maps free-form, real-world user queries to products labeled granularly based on relevance, enabling advanced models to learn nuanced search behavior. 

### Methods and Intended Results Overview

This project utilizes a rich, multilingual dataset of actual customer search queries mapped to products with fine-grained relevance labels across four categories - Exact, Substitute, Complement and Irrelevant. Advanced pre-processing techniques like translation and vectorization are used to encode the textual data into numeric forms understandable by machine learning models. Transformer neural networks are combined with statistical methods like TF-IDF to create a sophisticated relevance framework trained on this dataset. The framework ranks search results by relevance, assigns subtype classification tags, and identifies alternate suggestions when no exact match exists. By leveraging complex models on real-world shopping data with nuanced judgments, the project aims to deliver highly targeted, contextual and satisfactory search experiences that truly understand user intent. The intended results are to revolutionize product search relevance on online shopping platforms. By categorizing relevance nuances into four precise classes and training advanced models on actual user search data mapped granularly to products, this project aims to:
Rank products intelligently in search results based on contextual relevance to the query rather than just       keywords. Assign accurate classification tags like "Substitute" and "Complement" to returned products depicting the subtype of match. Surface alternative product suggestions when no exact match product exists for the search query.
Through these focused objectives, the expected outcome is a sophisticated search experience that understands true user intent, provides results catered to search context, and overall delivers more precise, satisfactory recommendations - thereby enhancing customer experiences and loyalty.

### Contributors

Venkata Krishna Rao Chelumkuri, Ratan Sai Rohith Kokku, Harshitha Somala, Siva Akhil Kumar Reddy Nukala

# The-Golden-Spoon-Smart-Assistant
**Overview:**
This project introduces an intelligent virtual assistant designed to answer your questions about "The Golden Spoon," a restaurant in Varanasi, Uttar Pradesh. By harnessing the power of Google's Gemini large language model and a ChromaDB vector database, it delivers accurate and relevant information in response to your queries.

**Functionality:**
This assistant can provide details on various aspects of the restaurant, including its location, contact information, and website. It offers menu specifics and pricing across Indian, Chinese, Continental, South Indian, and Italian cuisines. You can also inquire about delivery services (availability, charges, and radius), reservation procedures and timings, food and service quality, and how to share feedback. Furthermore, it handles questions about dietary needs, allergies, ingredient sourcing, kitchen operations, efficiency measures, technology use, special offers, promotions, events, catering, allergens (planned), nutritional values (planned), sustainability efforts, staff details, and kitchen equipment.

**Code Demonstration:**
The provided Python code illustrates the assistant's core workings. It imports necessary libraries (pandas, numpy, sklearn, google-generativeai, chromadb), installs dependencies, configures the Gemini API using a Kaggle Secret, loads restaurant data, sets up a ChromaDB vector database using Gemini embeddings, and enables querying this database to retrieve relevant answers based on user input.

**Getting Started:**
To run this, ensure you have Python 3.6+ installed and a Google Cloud API key (as a Kaggle Secret if applicable). Install the required libraries: pip install google-generativeai chromadb.

**Usage:**
Replace the API key placeholder, run the Python script, and modify the query variable to ask your questions about "The Golden Spoon." The output will display the most relevant information found.

**Potential Enhancements:**
Future improvements include more advanced natural language processing, real-time data integration, a user-friendly interface, multi-turn conversation capabilities, integration with other services, a broader knowledge base, and sentiment analysis of feedback.

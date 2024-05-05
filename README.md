# Personalized-Real-Estate-Agent

# 1. Project Overview
### Project Introduction
Imagine you're a talented developer at "Future Homes Realty", a forward-thinking real estate company. In an industry where personalization is key to customer satisfaction, your company wants to revolutionize how clients interact with real estate listings. The goal is to create a personalized experience for each buyer, making the property search process more engaging and tailored to individual preferences.

### The Challenge
Your task is to develop an innovative application named "HomeMatch". This application leverages large language models (LLMs) and vector databases to transform standard real estate listings into personalized narratives that resonate with potential buyers' unique preferences and needs.

### Core Components of "HomeMatch"
__Understanding Buyer Preferences:__
- Buyers will input their requirements and preferences, such as location, property type, budget, amenities, and lifestyle choices.
- The application uses LLMs to interpret these inputs in natural language, understanding nuanced requests beyond basic filters.

__Integrating with a Vector Database:__
- Connect "HomeMatch" with a vector database, where all available property listings are stored.
- Utilize vector embeddings to match properties with buyer preferences, focusing on aspects like neighborhood vibes, architectural styles, and proximity to specific amenities.

__Personalized Listing Description Generation:__
- For each matched listing, use an LLM to rewrite the description in a way that highlights aspects most relevant to the buyer’s preferences.
- Ensure personalization emphasizes characteristics appealing to the buyer without altering factual information about the property.

__Listing Presentation:__
- Output the personalized listing(s) as a text description of the listing.


# 2. Files in the repository

- `HomeMatch.ipynb` : Main scripts of HomeMatch.
- `listings.csv` : Information of real estates.
- `requirements.txt` : Requirements packages for HomeMatch.

# 3. Instructions:

1. Clone this repository and install requirements.
   ```
   git clone https://github.com/soyaoki/GenAIND-Personalized-Real-Estate-Agent
   cd GenAIND-Personalized-Real-Estate-Agent
   uv venv
   source .venv/bin/activate
   uv pip install -r requirements.txt
   ```

2. Start Jupyter
   ```
   jupyter lab
   ```

4. Execute `HomeMatch.ipynb`

# 4. Libraries used

`pandas`, `langchain`, `chromadb`, etc.

For more detail, see [requirements.txt](/requirements.txt)

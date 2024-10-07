# GoTo Chicago Workshop: AI Blog Post Generator

There are an emerging set of components that have proven useful in solving the common problems you run into when building applications powered by generative AI. We discuss the generative AI stack and explain from first principles why each component exists, and when they are appropriate to use. You'll build a working prototype of an AI product by chaining multiple components together using LangChain. 

The application we'll build is an AI blog post generator, which researches a given topic and summarizes the search results, before generating a comprehensive post based on the research, written in your writing style rather than sounding like AI. We’ll cover advanced topics in applied AI, such as multimodal vision and image generation, open-source models like LLaMA 3, RAG (Retrieval Augmented Generation), as well as the basics like building a simple user interface for AI applications. 

Basic experience with Python programming and access to an OpenAI developer account with a payment method is required to follow along, as well as a free Replit account to avoid any dev environment setup issues. You'll get access to all of the code to use in your own applications.


# Setup

1. Create a new virtual environment:
   ```
   python3 -m venv venv
   ```

2. Activate the virtual environment:
   - On Windows:
     ```
     venv\Scripts\activate
     ```
   - On macOS and Linux:
     ```
     source venv/bin/activate
     ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```
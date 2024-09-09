# Steps to Set Up and Run the Project:
- Clone the Repo: Start by Cloning the Repo to your local machine.
  
# Set Up a Virtual Environment:
- Create and activate a virtual environment to manage dependencies effectively.

# Install Required Packages:
  ## Use the following command to install all dependencies listed in the requirements.txt file:
      pip install -r requirements.txt

# Create an .env file 
 - Inside the file create 2 vars  `MONGODB_URI` and `OPENAI_API_KEY`
 - Set `MONGODB_URI` = <your_mongodb_cluster_string>
 - Set `OPENAI_API_KEY` = <your_openai_API_KEY>

# Running the Chatbot:

- Open the `Langchain_chatbot.ipynb` file.
- Execute the first code block labeled “GUI + MongoDB” to launch the chatbot interface.
- If the code takes longer than expected, you may alternatively run the code block labeled “GUI Test Without MongoDB”, which operates directly from a CSV file instead of the MongoDB database.

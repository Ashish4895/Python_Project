# Python_Project

# Clone the repository:

Copy code--
git clone https://github.com/Ashish4895/Python_Project.git
cd Python_Project
Create and activate a virtual environment (optional but recommended):


# For Windows
python -m venv venv
venv\Scripts\activate

# For MacOS/Linux
python3 -m venv venv
source venv/bin/activate

# Install the required dependencies:

pip install -r requirements.txt
Dependencies

# The following packages are required to run the project:
streamlit: For building the interactive web app.
  pandas: For data manipulation and CSV handling
  textblob: For sentiment analysis
  matplotlib: For data visualization
  wordcloud: For generating the word cloud from reviews
  You can install them with:


Copy code ---
pip install streamlit pandas textblob matplotlib wordcloud

# How to Run

Start the Streamlit app:

Copy code
streamlit run (file_name).py
Upload your CSV file: Once the app starts, you'll be prompted to upload a CSV file. The file must contain the following columns:

Review: The text of the customer review.
Rating: The numeric rating given by the customer.app
Date: The date of the review in DD-MM-YYYY format.
Explore the data and visualizations:

View the sentiment analysis results, sentiment distribution chart, and a word cloud generated from customer reviews.

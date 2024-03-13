# Gemini SQL Query App

This project utilizes Streamlit, Google's GenerativeAI API, and SQLite to create a web application that can retrieve SQL queries based on user input questions.

# Setup

# 1. Clone the Repository

```bash
git clone https://github.com/sona3ms/Gemini_pro.git
cd Gemini_pro

$# 2. Install Dependencies

pip install -r requirements.txt

# 3. set Up Enviornment Variables
GOOGLE_API_KEY=your_api_key_here

# 4. Initialize SQLite Database
python sql.py

# 5. Running the App
streamlit run app.py

#Project Structure
app.py: Contains the Streamlit web application code.
sql.py: Initializes the SQLite database and inserts sample data.
.env: Stores environment variables (e.g., Google API key).
requirements.txt: Lists the Python dependencies.

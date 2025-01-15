# Gilgit-Baltistan FAQ Chatbot

## Project Overview
This project involves developing a chatbot to answer frequently asked questions (FAQs) about Gilgit-Baltistan, focusing on tourism, culture, geography, and challenges. The chatbot is powered by NLP techniques and trained on an extensive dataset with over 500 entries covering detailed information about various districts, villages, and landmarks in Gilgit-Baltistan.

## Features
- **Comprehensive Coverage:** Answers queries about Gilgit-Baltistan's tourism, culture, geography, and challenges.
- **District-Level Insights:** Provides detailed information about all major districts and villages, including Skardu, Ghanche, Khaplu, Gilgit, Shigar, Kharmang, and others.
- **Approximate Distance and Time:** Includes data on distances and travel times between key locations.
- **Temperature and Climate:** Shares temperature trends and climate information.
- **Landmarks and Attractions:** Highlights famous spots such as Deosai, Chaqchan Mosque, and Phander Valley.

## Dataset
- **Source:** Custom-built dataset using public domain information about Gilgit-Baltistan.
- **Key Statistics:**
  - Total Records: 500+
  - Categories: Tourism, Culture, Geography, Challenges
  - Features: District, Area, Location, Attractions, Challenges, Climate

## Model Architecture
- **Base Libraries:**
  - NLTK: For tokenization and natural language understanding.
  - Python: Core programming language for backend logic.
- **Frontend:** Gradio for an interactive user interface.

## Implementation Steps
1. **Environment Setup:**
   - Install required libraries: `nltk`, `gradio`, and others.
2. **Dataset Preprocessing:**
   - Cleaned and formatted data for better user query matching.
3. **Chatbot Development:**
   - Trained and tested the chatbot on the dataset.
4. **Frontend Integration:**
   - Developed a user-friendly interface using Gradio.
5. **Deployment:**
   - Hosted locally and accessible via Gradio UI.

## Requirements
### Hardware:
- **Minimum:** 4 GB RAM.
- **Recommended:** 8 GB RAM for smoother performance.

### Python Libraries:
- nltk
- gradio
- pandas
- numpy

### Installation:
```bash
pip install nltk gradio pandas numpy
```

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/Daniyal-DS/FAQ-Chatbot
   cd Gilgit-Baltistan-FAQ-Chatbot
   ```
2. Open the Python script or Jupyter Notebook:
   ```bash
   FAQ Chatbot.ipynb
   ```
3. Launch the Gradio interface and interact with the chatbot.

## Results
- **Accuracy:** High accuracy in providing relevant answers.
- **Sample Output:**
  - **Input:** "What are the famous places to visit in Skardu?"
  - **Output:** "Skardu is famous for Shangrila Resort, Upper Kachura Lake, and Deosai National Park."

## Challenges and Solutions
- **Data Scarcity:** Researched extensively to create a detailed dataset.
- **User Query Variations:** Used advanced preprocessing and tokenization to handle diverse queries.

## Files in the Repository
- `FAQ_Chatbot.ipynb`: Python script for running the chatbot.
- `dataset/`: Folder containing the FAQ dataset.
- `images/`: Includes screenshots of the interface.
- `README.md`: Project documentation file.

## Future Work
- Expand dataset to include more comprehensive information.
- Deploy the chatbot as a web or mobile application.
- Enhance NLP capabilities for better query understanding.

## Contributors
- **Daniyal Haider**  
  [GitHub Profile](https://github.com/Daniyal-DS) | [LinkedIn Profile](https://linkedin.com/in/Daniyal-Haider)



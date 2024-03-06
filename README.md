# Orangetheory Fitness - Customer Sentiment on Lift45 Course and Fitness Metrics

## About the Project
This project aimed to delve into customer sentiment and feedback surrounding the Lift45 course offered by Orangetheory Fitness (OTF), as well as OTF metrics related to fitness performance such as splat points, heart rate zones, and max heart rates. My focus platforms for data collection were Reddit and Facebook, as they boast significant Orangetheory Fitness communities.

#### Data Collection and Analysis:
To gather insights, I utilized the Reddit API to extract posts, comments, and replies pertaining to Lift45 and fitness metrics. Key data points including date, author, title, and text body were collected. Leveraging the ChatGPT API, I categorized feedback into top themes for both Lift45 and fitness metrics. Each Reddit post, comment, and reply was then analyzed with the ChatGPT API, generating essential data points such as sentiment (positive/negative/neutral), summary, and category of feedback.

#### Data Visualization:
The analyzed data was visualized using Tableau, presenting percentages of customers with positive, neutral, and negative sentiments toward Lift45 and OTF fitness metrics. Additionally, I quantified top feedback categories and their respective sentiments, highlighting areas necessitating attention and improvement.

#### Recommendations and Presentations:
Based on the insights uncovered, I crafted data-driven recommendations aimed at refining class structure, enriching course content, and optimizing metric tracking methodologies. Qualitative feedback, data visualizations, and actionable recommendations were consolidated into a comprehensive slide deck and delivered to the project supervisor. The goal was to catalyze positive change and elevate customer satisfaction through informed decision-making.

## Installation and Setup
### Prerequisites
* **Python** 3.8 or higher.
* **Anaconda**. [Download Anaconda](https://www.anaconda.com/download). This project uses several packages that are conveniently available through Anaconda. Alternatively, you can use pip to install the necessary packages.
* **Jupyter Notebook** for running .ipynb files. It comes pre-installed with Anaconda, or you can install it separately if using pip:
  ```bash
  pip install notebook
  ```
* **Required Python Packages**:
  * praw: a Python API for interacting with the Reddit API
  * time: a built-in Python module that provides various time-related functions.
  * json: for encoding and decoding JSON data.
  * requests: for making HTTP requests.
  * csv: for reading and writing CSV files.
  * pandas: data structures and data analysis tools.
  * datetime: a built-in module for working with dates and times.
  * codecs: provides functions for encoding and decoding data streams.
  * os: provides functions for interacting with the operating system.
  * dotenv: for loading environment variables from a .env file into Python script.
 
* **Setting Up a Virtual Environment (Optional but Recommended)**
  * To prevent potential conflicts with other Python projects or system-wide packages, consider using a virtual environment.
    * With Anaconda, create a new environment like this:
      ```bash
      conda create -n myenv python=3.8
      conda activate myenv
      ```
    * Install the necessary packages in this environment.
   
### Cloning the Repository
To get started with the project, you first need to clone the repository to your local machine. Follow these steps:
1. **Open Your Terminal or Command Line:** This can be the Terminal app on macOS or Linux, Command Prompt or PowerShell on Windows, or any other terminal application you prefer.
2. **Clone the Repository:** Run the following command.
   ```bash
   git clone https://github.com/jeanie-liu/orangetheory_sentiment.git
   ```
3. **Navigate to the Project Directory:** After cloning, move into the project directory with this command:
   ```bash
   cd orangetheory_sentiment
   ```
Once the repository is cloned, follow the instructions in the prerequisites section to install the necessary project dependencies.

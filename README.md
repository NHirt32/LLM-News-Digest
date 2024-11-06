# News Summarization and Categorization Project

This project leverages a news API and OpenAI's language model to fetch, analyze, and summarize current news articles from the United States. It categorizes articles into topics such as Politics, Economics, Social Issues, Environment, Technology, and Entertainment, providing both visualizations and detailed summaries for easy understanding of current trends.
Features

    Country Selection: Allows users to filter news by country. Currently limited to the United States due to API restrictions, but the project is adaptable for other countries.
    News Categorization: Summarizes articles and categorizes them under key topics.
    Data Visualization: Presents the category distribution with a pie chart and bar chart.
    Markdown Summaries: Displays structured, easy-to-read summaries of categorized articles.

## Technologies Used

    Python: Core programming language.
    OpenAI API: For language processing and article categorization.
    News API: Fetches the latest news articles.
    Dotenv: Manages environment variables securely.
    Ipywidgets: Adds interactivity within Jupyter Notebook.
    Matplotlib: Creates visualizations for data insights.

## Project Structure

The main components of this project include:

    API Configuration: Sets up and manages API keys.
    Data Retrieval: Fetches top news headlines based on country selection.
    Article Processing: Sends combined article text to OpenAI for categorization.
    Data Visualization: Generates pie and bar charts for category distribution.
    Summary Presentation: Displays categorized article summaries in Markdown.

## Setup Instructions

    Clone the repository:

git clone https://github.com/your-username/news-summarization-project.git
cd news-summarization-project

Install the required packages individually if they aren’t already installed:

pip install requests python-dotenv openai matplotlib ipywidgets jupyter-ui-poll

API Key Setup:

    Demo Version: For secure use, create a .env file in the project directory and add your API keys:

        OPENAI_API_KEY=your_openai_key
        NEWS_API_KEY=your_news_api_key

        Submission Version: The submitted version of this project includes API keys in plain text for accessibility during review.

    Run the Jupyter Notebook to explore and test the project features.

## Usage

    Country Selection: Use the dropdown menu to select the country (currently limited to "US").
    Retrieve News: The News API fetches top headlines.
    Process Articles: The OpenAI model categorizes and summarizes the articles by topic.
    View Visualizations: See the category distribution in pie and bar charts.
    Read Summaries: Access the categorized summaries for an in-depth look at each topic.

## Limitations

    Country Restriction: Due to the limitations of the News API used, only U.S. news stories are accessible. Future versions could expand to support more countries if the API allows.
    Plain Text API Keys in Submission: While the demo uses environment variables for security, the submission version includes plain text API keys as required for review.

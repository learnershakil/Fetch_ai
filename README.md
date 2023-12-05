# Daily News Agent using Fetch.ai's uAgents Library

## Overview

The Daily News Agent is a lightweight and customizable news aggregation tool built using Fetch.ai's uAgents library. It fetches top headlines from a news API, filters and selects significant news stories, and presents them to users in a concise and readable format every morning.

## Features

- Seamless integration with Fetch.ai's uAgents library.
- Customizable news categories (e.g., world news, technology, sports).
- Periodic fetching and presentation of news for a dynamic user experience.

## Getting Started

### Prerequisites

- Python 3.6 or higher
- Fetch.ai uAgents library
- News API key (e.g., [News API](https://newsapi.org/))

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/daily-news-agent.git
    cd daily-news-agent
    ```

2. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

3. **Set up your configuration:**

    - Replace `"your_news_api_key"` in the script with your actual News API key.
    - Adjust `NEWS_API_BASE_URL` based on your chosen news API.

4. **Run the agent:**

    ```bash
    python news_agent.py
    ```

## Configuration

- **Customize News Categories:**
  Modify the `USER_INTERESTS` list in the script to include the desired news categories.

## Usage

- The agent will automatically fetch and present news based on the specified intervals.
- Check the agent's logs for information on fetched and presented news.

## Contributing

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/my-feature`.
3. Commit your changes: `git commit -m 'Add my feature'`.
4. Push to the branch: `git push origin feature/my-feature`.
5. Submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Fetch.ai](https://fetch.ai/) for providing the uAgents library.

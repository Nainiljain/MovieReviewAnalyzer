# 🎬 Movie Review Analyzer

A powerful, AI-driven web application that helps users explore movies and analyze reviews using Sentiment Analysis. Built with Flask, vanilla JavaScript, and the TMDB API.

![Project Banner](https://via.placeholder.com/1200x500.png?text=Movie+Review+Analyzer+Screenshot)
*(Replace with an actual screenshot of your application)*

## 🌟 Key Features

-   **🔍 AI Powered Analysis**: Instantly analyzes the sentiment of movie reviews (Positive, Neutral, Negative) using Natural Language Processing.
-   **📊 Interactive Visualizations**: Dynamic charts and Word Clouds to visualize what users are saying.
-   **📱 Fully Responsive**: A seamless experience across Mobile, Tablet, and Desktop devices.
-   **🎥 Detailed Movie Data**: Fetches real-time data for thousands of movies via the TMDB API.
-   **🎙️ Voice Search**: Hands-free movie searching with "Okay Buddy" hotword activation.
-   **🌗 Dark Mode**: Toggle between light and dark themes for comfortable viewing.
-   **🔒 User Accounts**: Secure Login/Register functionality with watchlist management.
-   **🆚 Comparison Tool**: Compare two movies side-by-side.

## 🛠️ Tech Stack

-   **Frontend**: HTML5, CSS3 (Glassmorphism, Grid/Flexbox), JavaScript (ES6+).
-   **Backend**: Python (Flask).
-   **Database**: SQLite.
-   **APIs**: The Movie Database (TMDB).
-   **NLP**: TextBlob / NLTK.

## 🚀 Getting Started

Follow these instructions to set up the project locally.

### Prerequisites

-   Python 3.8+
-   A TMDB API Key (Get one [here](https://www.themoviedb.org/documentation/api))

### Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/Nainiljain/MovieReviewAnalyzer.git
    cd MovieReviewAnalyzer
    ```

2.  **Create a Virtual Environment**
    ```bash
    python -m venv venv
    # Windows
    venv\Scripts\activate
    # macOS/Linux
    source venv/bin/activate
    ```

3.  **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Configure Environment Variables**
    Create a `.env` file in the root directory and add your TMDB API Key:
    ```env
    TMDB_API_KEY=your_tmdb_api_key_here
    SECRET_KEY=your_secret_key
    ```

5.  **Run the Application**
    ```bash
    python app.py
    ```

6.  **Visit the App**
    Open your browser and navigate to `http://127.0.0.1:5000`.

## 📂 Project Structure

```
MovieReviewAnalyzer/
├── static/
│   ├── Css/        # Stylesheets (style.css)
│   ├── Js/         # Client-side logic (script.js)
│   └── Images/     # Assets
├── templates/      # HTML Templates (landing, movies, login, etc.)
├── app.py          # Main Flask Application
├── tmdb_utils.py   # TMDB API Helper Functions
├── database.db     # SQLite Database (Auto-generated)
├── requirements.txt
└── README.md
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 📄 License

This project is open-source and available under the information [MIT License](LICENSE).

---
*Created by [Nainil Jain](https://github.com/Nainiljain)*

# Lyrics Finder

A simple web application to search for song lyrics and discover top artists. Built with Flask and Bootstrap.

## Features
- Search for lyrics by artist and song title
- Display lyrics in a clean, readable format
- Show a curated list of top artists with images
- Responsive and modern UI

## Project Structure
```
LyricsApp/
├── app.py
├── requirements.txt
├── static/
│   ├── style.css
│   ├── artists.json
│   └── images/
│       ├── Adele.jpeg
│       ├── Beyonce.jpeg
│       ├── BurnaBoy.jpeg
│       ├── Drake.jpeg
│       └── TaylorSwift.jpeg
├── templates/
│   └── index.html
└── README.md
```

## Getting Started

### Prerequisites
- Python 3.7+
- pip

### Installation
1. Clone the repository or download the source code.
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. (Optional) Set up a `.env` file for API keys if required by your lyrics API.

### Running the App
```sh
python app.py
```
Visit [http://localhost:5000](http://localhost:5000) in your browser.

## Deployment

### Deploying on Render
1. Push your code to a GitHub repository.
2. Create a new Web Service on [Render](https://render.com/).
3. Set the build and start commands:
   - **Build Command:** `pip install -r requirements.txt`
   - **Start Command:** `gunicorn app:app`
4. Add any required environment variables (API keys, etc.) in the Render dashboard.
5. Deploy and access your app via the provided Render URL.

## License
MIT

---
Made with ❤️ for music lovers.

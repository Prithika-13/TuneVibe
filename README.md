# 🎵 TuneVibe

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)](https://www.python.org/)
[![Status: Prototype](https://img.shields.io/badge/status-prototype-lightgrey)]()

> **TuneVibe** is a Context-Aware and Trending Music Recommendation System that reimagines personalized music discovery by incorporating real-time environmental
and trend-based insights using a hybrid machine learning approach.

## 🚀 Overview

Traditional music recommenders often miss the mark by ignoring the context in which users consume music. TuneVibe enhances the recommendation experience by integrating:

- 🌍 *User Location*
- 🌦️ *Weather Conditions*
- 🕒 *Time of Day*
- 🏃 *User Activity*
- 📊 *Real-Time Trends*

By combining these dynamic inputs with machine learning techniques, TuneVibe delivers more **relevant**, **timely**, and **personalized** music recommendations.

---

## 🧠 Core Features

- 🎧 **Hybrid Recommendation Model**  
  Uses collaborative filtering, content-based filtering, and contextual modeling.

- 🌐 **Context-Awareness**  
  Adapts to your city, current weather, time, and activity.

- ⚡ **Real-Time Adaptability**  
  Generates live playlists based on dynamic user context.

- 💬 **Interactive Feedback**  
  Song previews, ratings, and preference inputs to refine recommendations.

- 📱 **Clean & Responsive UI**  
  Designed for a smooth and intuitive user experience.

---

## 🛠️ Tech Stack

- **Backend**: Flask, Python
- **ML Models**: Scikit-learn, Pandas, NumPy
- **Frontend**: HTML/CSS, JavaScript, Bootstrap
- **APIs**: OpenWeatherMap, GeoIP, Spotify API
- **Database**: SQLite

---
## 🧱 System Architecture 
<pre> 
  text [User Interface] 
         ↓ 
  [Flask Backend] 
         ↓ 
  [Context Collector] 
         ↓ 
  [Weather API, GeoIP, Time] 
         ↓ 
  [Hybrid Recommender] 
  ├── Collaborative Filtering 
  ├── Content-Based Filtering 
  └── Contextual Modeling 
         ↓ 
  [Dynamic Playlist Generator] 
         ↓ 
  [Frontend Display]  
</pre>

---

## 🧪 Installation & Setup

### Prerequisites

- Python 3.9+
- Git
- Virtualenv (optional)

### Steps

```bash
# Clone the repository
git clone https://github.com/your-username/tunevibe.git
cd tunevibe

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # on Windows use venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the application
python app.py
```
---
## 📸 Output
 ![login](image_url)
 ![signup](image_url)
 ![home](image_url)
 ![results](image_url)

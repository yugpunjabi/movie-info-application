# 🎬 Movie Info Application

A simple web application built using HTML, CSS, and JavaScript to fetch and display movie details using the [OMDb API](https://www.omdbapi.com/).

---

## 🚀 Features

- Search any movie by name  
- View movie poster, rating, genre, cast, plot, and more  
- Graceful error handling for unknown or incorrect movie names  
- Responsive and user-friendly layout  

---

## 🛠️ Tech Stack

- HTML  
- CSS  
- JavaScript (Vanilla)  
- OMDb API  

---

## 🔑 API Key Setup

To use this app, you need an OMDb API key:

1. Go to [http://www.omdbapi.com/apikey.aspx](http://www.omdbapi.com/apikey.aspx)  
2. Sign up and get your free API key  
3. Replace `key` in the script with your actual API key:

```javascript
let url = `http://www.omdbapi.com/?t=${movieName}&apikey=YOUR_API_KEY`;

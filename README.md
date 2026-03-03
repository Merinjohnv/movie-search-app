#  Movie Search App

A responsive Movie Search web application built using HTML, CSS, and Vanilla JavaScript.  
The app integrates with the OMDb API to fetch real-time movie data using `fetch` and `async/await`.

---

##  Features

-  Search movies by title (debounced input)
-  Filter by type (movie / series / episode)
-  Optional year filter
-  Display poster, title, year, and type
-  Fallback image for missing posters
-  Pagination support (OMDb returns 10 results per page)
-  Loading indicator during API requests
-  Friendly error and empty-state messages
-  Clear instructions to insert your own OMDb API key

---

##  Tech Stack

- HTML5
- CSS3 (Flexbox + Grid)
- JavaScript (ES6+)
- Fetch API
- Async/Await
- OMDb REST API

---

##  API Used

OMDb API  
Search endpoint: `s=`  
Type filter: `type=`  
Year filter: `y=`  
Pagination: `page=`

---

##  Demo Live

https://merinjohnv.github.io/movie-search-app/

---

## ⚙️ Setup Instructions

1. Clone the repository
2. Get a free API key from: http://www.omdbapi.com/apikey.aspx
3. Replace the API key in `script.js`:

```js
const API_KEY = 'YOUR_API_KEY';

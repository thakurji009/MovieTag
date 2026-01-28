MovieTag
========

MovieTag is a simple React app that lets you explore movies and organize them with your own tags.  
It uses **The Movie Database (TMDB)** API to fetch real movie data.

---

1. Features
-----------

- **Browse movies** from TMDB.
- **Search movies** by title.
- **Tag movies** (for example: “Favorites”, “Watch Later”, “Comedy”).
- **Simple and clean UI** that works on desktop and mobile.

*(Update this list as you add more features.)*

---

2. Tech Stack
-------------

- **Framework**: React  
- **Language**: JavaScript (or TypeScript, if you use it)  
- **API**: TMDB (The Movie Database)  

> Edit this section if you use tools like Vite, CRA, Tailwind, etc.

---

3. TMDB API Key Setup
---------------------

1. Go to the TMDB website and create an account.  
2. Create an API key from your TMDB account settings.  
3. In your project root, create a file named `.env` (if it doesn’t exist).  
4. Add your TMDB API key to the `.env` file, for example:

```env
VITE_TMDB_API_KEY=YOUR_TMDB_API_KEY_HERE
```

5. In your React code, read the key (example for Vite):

```js
const API_KEY = import.meta.env.VITE_TMDB_API_KEY;
```

> If you use Create React App instead of Vite, name it like `REACT_APP_TMDB_API_KEY` and use `process.env.REACT_APP_TMDB_API_KEY`.

**Important**: Never commit your real API key to GitHub. Keep `.env` in `.gitignore`.

---

4. Getting Started
------------------

1. **Install dependencies**

```bash
npm install
# or
yarn install
```

2. **Run the app**

```bash
npm run dev
# or
npm start
```

3. Open your browser at `http://localhost:3000` (or the port shown in your terminal).

---

5. Scripts (example)
--------------------

Common scripts in `package.json` (may vary):

- **`npm run dev` / `npm start`**: Start development server.
- **`npm run build`**: Build production bundle.
- **`npm test`**: Run tests (if configured).

---

6. Folder Structure (example)
-----------------------------

```text
src/
  components/
  pages/
  hooks/
  utils/
  assets/
README.md
package.json
```

Adjust this to match your actual structure.

---

7. License
----------

MIT License

Copyright (c) 2026 PRATIK KUMAR

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights  
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell  
copies of the Software, and to permit persons to whom the Software is  
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all  
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR  
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,  
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE  
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER  
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,  
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE  
SOFTWARE.

---
# My-Movie — Interactive Cinema Explorer
A dynamic React-based movie search platform that allows users to explore the OMDb database, curate personal watchlists, and provide custom ratings.

[Live Demo](https://kenneth183721.github.io/My-Movie/)

## 🚀 Project Overview
My-Movie focuses on the core principles of asynchronous data handling and user-driven state persistence. The goal was to create a fluid search experience where users can transition from global discovery to a personalized library seamlessly.

## 🛠 Tech Stack
- Frontend Framework: React.
- API: OMDb API (RESTful integration).
- State Management: React Hooks (useState, useEffect).
- Storage: LocalStorage (for persistent bookmarks).

## 💡 Key Engineering Highlights
Asynchronous Data Fetching: Implemented robust API integration with the OMDb API. I utilized useEffect and the AbortController (or similar pattern) to handle movie search requests, ensuring that the UI remains responsive and handles loading/error states gracefully during data retrieval.

User-Centric Rating System: Developed a custom star-rating component that allows users to assign personal scores to movies. This feature demonstrates the ability to manage complex internal component states and pass data back to the parent application for curation.

Persistent Bookmarking Logic: Built a bookmarking system that utilizes browser storage (LocalStorage). This ensures that a user’s "Favorite" list and ratings are preserved even after a page refresh, showcasing an understanding of client-side data persistence.

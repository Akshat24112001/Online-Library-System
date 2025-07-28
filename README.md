# BookHaven

BookHaven is a dynamic web application that lets users browse, search, and explore a curated collection of books categorized by genre. Built using **React**,**Vite**(as a bundler), **Redux**, and **Tailwind CSS**, BookHaven provides an intuitive and responsive interface for book enthusiasts.

---

## Features

- **Search Functionality**: Find books by title or author instantly.
- **Category Filtering**: Browse books by genre using a dropdown.
- **Popular Highlights**: Homepage displays top-rated books and trending categories.
- **Smart Filtering**: Dynamic updates as users search or change categories.
- **Local Persistence**: Book data is initialized from `localStorage` or default collection.
- **Responsive Design**: Mobile-first UI built with Tailwind CSS.

---

## 🛠 Tech Stack

- **Frontend**: React, Redux Toolkit, React Router DOM, Tailwind CSS
- **State Management**: Redux (with local storage fallback)
- **Icons**: React Icons
- **Build Tool**: Vite

---

## Folder Structure

```bash
src/
├── components/
│ ├── Book.jsx
│ ├── BrowseBooks.jsx
│ ├── CategoryDropdown.jsx
│ ├── AddBook.jsx
│ ├── BookDetail.jsx
│ ├── Error.jsx
│ ├── Header.jsx
│ └── HomePage.jsx
├── utils/
│ ├── booksCollection.js
│ ├── booksCollectionSlice.js
│ └── appStore.js
├── assets/
│ ├── placeholder.jpg
│ └── bookbgImage.jpg
├── index.css
├── main.jsx
└── App.jsx
```

---

## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/Akshat24112001/Online-Library-System
   cd bookhaven
   ```

2. **Install Dependencies**

```bash
npm install
```

3. **Start the development server**

```bash
npm run dev
```

4. **Usage**

- Browse popular books and categories on the homepage.

- Use the search bar to find specific books by title or author.

- Click on categories to filter books accordingly.

- Click "View Details" to see more information about a book (if implemented).

#### Project link:- [https://github.com/Akshat24112001/Online-Library-System](https://github.com/Akshat24112001/Online-Library-System)

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

This project is open-source and available under the MIT License.

## Author
Akshat Singh
akshatsinghrajput24@gmail.com

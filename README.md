```markdown
# Bookmark Manager

A simple web app to manage categorized bookmarks. Users can add, view, and delete bookmarks organized by categories. Data is stored in browser `localStorage` for persistence.

---

## Features

- **Add Bookmark**: Save bookmarks with a name, category, and URL.
- **View Bookmarks by Category**: Display bookmarks filtered by selected category.
- **Delete Bookmarks**: Remove bookmarks from the selected category.
- **Local Storage Persistence**: All bookmarks are saved locally in the browser.
- **Dynamic UI Updates**: Forms and lists toggle visibility smoothly without page reloads.
- **Input Validation**: Ensures bookmark name and URL are entered before saving.
- **Safe External Links**: Bookmarks open in new tabs securely.

---

## Installation and Usage

1. Clone or download this repository.
2. Open `index.html` in any modern web browser.
3. Use the dropdown to select a category.
4. Click **Add Bookmark** to add new bookmarks under the selected category.
5. Click **View Category** to see all bookmarks in the chosen category.
6. Select a bookmark and click **Delete Bookmark** to remove it.
7. Bookmarks are saved automatically in browser `localStorage`.

---

## Project Structure

``

/
├── index.html           # Main HTML page
├── style.css            # CSS styling
└── script.js            # JavaScript for bookmark management

``

---

## JavaScript Functions Overview

- `getBookmarks()`: Retrieves bookmarks array from `localStorage`. Returns empty array if data is missing or invalid.
- `displayOrCloseForm()`: Toggles visibility between the main section and the add bookmark form.
- `displayOrHideCategory()`: Toggles visibility between the main section and the bookmark list view.
- `updateCategoryName(category)`: Updates category name displays dynamically in the UI.
- Event listeners handle button clicks for adding, viewing, closing, and deleting bookmarks.

---

## Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript (ES6+)**
- Browser `localStorage` API

---

## Notes

- This app is designed for demonstration and personal use; it does not include user authentication or server-side storage.
- Clearing browser data will remove all saved bookmarks.
- Make sure URLs entered are valid to avoid broken links.

---

## License

This project is open-source and free to use under the MIT License.

---

## Author

Created by Jordan Leturgez
```

---

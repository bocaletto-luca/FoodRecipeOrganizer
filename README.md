# Food Recipe Organizer

A modern, responsive single-page web app to store, organize, and filter your recipes. Create, edit, or delete recipes with photos, ingredients, and instructions. Fully customizable categories and import/export via JSON. No build tools or external dependencies.

---

## 🔗 Live Demo

https://bocaletto-luca.github.io/FoodRecipeOrganizer/index.html

---

## 🚀 Features

- **Custom Categories**  
  Add, rename, or delete recipe categories on the fly. Changes persist across sessions.

- **Recipe Management**  
  • Create and edit recipes with name, category, ingredients (one per line), instructions, and an optional photo.  
  • Delete recipes with a single click.

- **Real-Time Filtering**  
  Instantly filter the recipe grid by any category or view all recipes.

- **Photo Preview**  
  Upload and preview images before saving. Photos are stored in LocalStorage as Base64 strings.

- **Import / Export JSON**  
  Back up or share your entire recipe collection in a JSON file. Easily restore or migrate between devices.

- **Responsive Design**  
  Mobile-first layout using CSS Grid and Flexbox. Works flawlessly on phones, tablets, and desktops.

- **Zero Dependencies**  
  Pure HTML5, CSS3 (Custom Properties), and vanilla JavaScript (ES6+). No external libraries or build steps.

---

## 🛠️ Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)

### Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/bocaletto-luca/FoodRecipeOrganizer.git
   ```
2. **Open the app**  
   Navigate into the project folder and open `index.html` in your browser.

No installation or build tools required.

---

## 🎯 Usage

1. **Manage Categories**  
   - Click **Manage Categories**.  
   - Add a new category, rename existing ones, or delete unused categories.  
   - Close the panel to apply changes.

2. **Filter Recipes**  
   - Use the **Filter by category** dropdown to show only recipes in that category.  
   - Select **All** to view every recipe.

3. **Add or Edit a Recipe**  
   - Fill out the **Add New Recipe** form with name, category, ingredients, instructions, and optionally upload a photo.  
   - Click **Save Recipe** to add or update.  
   - Click **Clear** to reset the form.

4. **Delete a Recipe**  
   - In the recipe grid, click **Delete** and confirm the prompt.

5. **Import / Export JSON**  
   - Click **Export JSON** to download your recipe collection.  
   - Click **Import JSON** and select a previously exported file to restore.

---

## 🧰 Built With

- HTML5 & CSS3 (Grid, Flexbox, Custom Properties)  
- Vanilla JavaScript (ES6+)  
- LocalStorage for data persistence  

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository  
2. Create a new branch  
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Commit your changes  
   ```bash
   git commit -m "Add some feature"
   ```
4. Push to your fork  
   ```bash
   git push origin feature/YourFeature
   ```
5. Open a Pull Request on GitHub

---

## 📄 License

This project is licensed under the [GPLv3 License](https://www.gnu.org/licenses/gpl-3.0.en.html).

---

## 👤 Author

**Bocaletto Luca**  
- GitHub: [@bocaletto-luca](https://github.com/bocaletto-luca)  
- Live Demo: https://bocaletto-luca.github.io/FoodRecipeOrganizer/index.html

# Google Search Frontend

A responsive front-end implementation of Google's search interfaces, including regular search, image search, and advanced search functionality. This project replicates Google's clean aesthetic while providing a functional search experience that redirects to actual Google search results.

## 🌟 Features

- **Regular Google Search** - Clean, centered search interface with "I'm Feeling Lucky" functionality
- **Google Image Search** - Dedicated interface for searching Google Images  
- **Advanced Search** - Multi-field search form with complex query options
- **Responsive Design** - Works seamlessly across desktop and mobile devices
- **Custom Styling** - Beautiful wallpaper background with modern UI elements
- **Bootstrap Integration** - Professional styling using Bootstrap 5.3

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and form structure
- **CSS3** - Custom styling and responsive design
- **Bootstrap 5.3** - UI framework for consistent styling
- **Google Search API** - Integration with actual Google search functionality

## 📁 Project Structure

```
google-search-frontend/
├── index.html              # Main Google Search page
├── imageSearch.html         # Google Image Search page  
├── advanced.html           # Google Advanced Search page
├── wallpaper.jpg           # Background image
└── README.md              # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection for Google search functionality

### Installation & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/google-search-frontend.git
   cd google-search-frontend
   ```

2. **Open in browser**
   - Simply open `index.html` in your web browser
   - Or use a local server for best experience:
     ```bash
     python -m http.server 8000
     # Navigate to http://localhost:8000
     ```

3. **Navigate between pages**
   - Use the navigation bar in the top-right corner
   - Switch between Regular Search, Image Search, and Advanced Search

## 🎯 Features Implemented

### ✅ Regular Search (index.html)
- Centered search bar with rounded corners
- "Google Search" button functionality
- "I'm Feeling Lucky" button (direct to first result)
- Navigation links to other search pages

### ✅ Image Search (imageSearch.html) 
- Text input for image queries
- Redirects to Google Image search results
- Uses `tbm=isch` parameter for image-specific searches

### ✅ Advanced Search (advanced.html)
- **All these words** - Pages containing all specified words
- **Exact word or phrase** - Pages with exact phrase matches
- **Any of these words** - Pages containing any of the specified words  
- **None of these words** - Exclude pages with specified words
- Left-aligned form layout matching Google's design
- Blue "Advanced Search" button with white text

## 🎨 Design Features

- **Custom Background** - Beautiful wallpaper image covering entire page
- **Bootstrap Navigation** - Professional navigation bar with active states
- **Responsive Layout** - Adapts to different screen sizes
- **Google-inspired Styling** - Clean, minimalist design matching Google's aesthetic
- **Enhanced Form Controls** - Custom styling for input fields and buttons

## 📝 How It Works

The project uses HTML forms with specific action URLs and parameters to redirect to Google's actual search endpoints:

- **Regular Search**: `https://google.com/search?q=query`
- **Image Search**: `https://google.com/search?tbm=isch&q=query` 
- **Advanced Search**: `https://google.com/search?as_q=all&as_epq=exact&as_oq=any&as_eq=none`

 

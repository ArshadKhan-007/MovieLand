# MovieLand 🎬
MovieLand is a React-based movie search application that allows users to search for movies and displays details like the movie's title, release year, type, and poster. The application fetches data from the OMDb API and features a responsive and visually appealing UI.

## Features
Search Movies: Enter keywords to search for movies.

Responsive Design: Optimized for different screen sizes.

Styled Components: Uses Roboto Slab and Raleway fonts and a modern UI design.

Interactive Movie Cards: Each movie card displays relevant information and highlights on hover.

Error Handling: Displays a "No Movies Found" message if the search doesn't return results.
Demo


## Technologies Used
React: Component-based UI library.
CSS: For styling the components.
OMDb API: Fetches movie data based on user search.
### Installation
Clone the repository:

### bash

Copy code
git clone https://github.com/yourusername/movieland.git
cd movieland
Install dependencies:

### bash

Copy code
npm install
Run the app:

### bash

Copy code
npm start
The app should now be running on http://localhost:3000.

## Usage
Open the Application: After running, open your browser and go to http://localhost:3000.

Search Movies: Type the movie title in the search box, then click the search icon.

View Movie Details: Browse through the results to view details like release year, type, and poster. If no movies are found, a message will appear.
### Code Structure
App.js: Main component that manages the application’s state, handles the search functionality, and displays results.

MovieCard.js: Sub-component that renders individual movie cards with information from the OMDb API.

App.css: Contains all the styles for the application, including responsive design adjustments and hover effects for the movie cards.
## Key Parts of the Code
## API Integration:
API_URL: The base URL for fetching data from the OMDb API.
searchMovies: An asynchronous function that fetches data and updates the movies state with the results.
### Hooks:


useState: Manages movies and searchTerm states.

useEffect: Initializes with a default search term ("Spiderman") on component load.
### CSS Styling:


Gradient and Shadows: Provides visual appeal with text gradients and shadow effects on components.

Responsive Design: Adjusts the layout and font sizes based on screen width.

### Environment Variables
To use the OMDb API, create a .env file in the root of your project and add your API key:

env
Copy code
REACT_APP_OMDB_API_KEY=your_api_key
Contributing
Contributions are welcome! Please follow these steps:

### Fork the project.
Create your feature branch (git checkout -b feature/NewFeature).

Commit your changes (git commit -m 'Add new feature').

Push to the branch (git push origin feature/NewFeature).

Open a pull request.
### License
Distributed under the MIT License. See LICENSE for more information.

Contact
Your Name - Arshadkahn627@outlook.com

Random GIF Generator
This is a simple React-based web application that generates random GIFs based on user-provided tags. The GIFs are fetched from the Giphy API using the provided tag. The application utilizes the useGif custom hook to manage the state and handle the API requests.

![Screenshot (4)](https://github.com/AdSinghh/Gif-Generator/assets/132607841/fcf5b135-2458-483a-ac51-538d23423c72)

## Prerequisites

Before using this component, make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- [React](https://reactjs.org/)

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repository.git
   
2. Install dependencies:

   bash

  npm install


3. Get a Giphy API Key:

   Visit Giphy Developers and sign up for an API key.

   Create a .env file in the root directory of the project and add your API key:

makefile

  REACT_APP_GIPHY_API_KEY=your-api-key

4. Start the development server:

   bash

   npm start

5. Open your browser and visit http://localhost:3000 to view the application.

 Features

    The default tag is set to 'Goku', and a random GIF related to this tag is displayed initially.

    You can input any tag in the provided input field and click the "Generate" button to fetch and display a random GIF related to the entered tag.

    A loading spinner is displayed while the GIF is being fetched.

Components

 Tag Component

  Displays a random GIF based on the provided tag.
 Allows users to input a custom tag and generate a random GIF accordingly.

 Spinner Component

  Displays a loading spinner while waiting for the GIF to be fetched.

  useGif Hook

 Custom hook for managing the state and handling API requests to Giphy.

 Feel free to customize and expand upon this application according to your needs!

NASA APOD Viewer

This is a React application that fetches and displays the Astronomy Picture of the Day (APOD) from NASA using the NASA API.

Features
- Fetches the APOD from NASA's API.
- Displays the APOD image, title, and description.
- Responsive design for easy viewing on all devices.

Technologies Used
- React
- Fetch API for API calls
- React Bootstrap (optional) for styling and responsiveness

NASA API Key
To fetch data from NASA's API, you will need to obtain a personal API key. You can request one from NASA's Open APIs.

Getting Started
Follow these steps to get the project up and running on your local machine.

Prerequisites
- Node.js and npm installed. You can download them from https://nodejs.org/en/.
- A NASA API key (get it here: https://api.nasa.gov/)

Installation
1. Clone the repository to your local machine:
git clone https://github.com/your-username/nasa-apod-viewer.git
2. Navigate to the project directory:
cd nasa-apod-viewer
3. Install the required dependencies:
npm install
4. Create a `.env` file in the root of your project and add your NASA API key:
REACT_APP_NASA_API_KEY=your_api_key_here
5. Start the development server:
npm start
6. Open the app in your browser at http://localhost:3000

Project Structure
```
├── public
├── src
│   ├── components
│   │   └── Footer.jsx      # The Footer component for displaying the Project Name and Title of the Image
│   │   └── Main.jsx        # The Main component for displaying the Image
│   │   └── SideBar.jsx     # The Side bar component for displaying the Title, Date and Description of the Image
│   ├── App.jsx             # Main app component
│   ├── index.css           # Main css
│   └── main.jsx            # Folder for API calls
├── .env                    # Environment variables ( contains the actual API Key )
├── package.json            # Project metadata and dependencies
└── README.md               # This file
```

Usage
Once the application is running, it will automatically fetch and display the NASA Astronomy Picture of the Day (APOD) along with its title and description. You can refresh the page to get the latest data each day.

Acknowledgments
- NASA for the APOD API.
- React for the awesome UI library.


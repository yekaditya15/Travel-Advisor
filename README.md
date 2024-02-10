# Travel Advisor App

## Deployed Version

Check out the Travel Advisor App [here](https://travel-buddy-advisor.netlify.app/).


## Overview

Welcome to the Travel Advisor App, a web application built with ReactJS, Rapid API, Google API, and Material UI. This application serves as a travel guide, providing users with information about various travel destinations, attractions, and recommendations.

## Features

- **Destination Search:** Users can search for their desired travel destinations using the integrated Google API for location suggestions.

- **Attractions:** Get information about popular attractions, landmarks, and points of interest at the selected destination.

- **Reviews and Ratings:** User reviews and ratings from Rapid API are displayed for attractions and destinations, giving users insights into the experiences of other travelers.

- **Responsive Design:** The application is designed with Material UI, ensuring a seamless and responsive user experience across different devices.

## Setup

To run the Travel Advisor App locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/your-username/travel-advisor-app.git
```

2. Navigate to the project directory:

```bash
cd travel-advisor-app
```

3. Install dependencies:

```bash
npm install
```

4. Set up API keys:

   - Obtain API keys for Google API and Rapid API.
   - Create a `.env` file in the project root.
   - Add the following lines to the `.env` file, replacing `YOUR_GOOGLE_API_KEY` and `YOUR_RAPID_API_KEY` with your actual API keys:

     ```env
     REACT_APP_GOOGLE_API_KEY=YOUR_GOOGLE_API_KEY
     REACT_APP_RAPID_API_KEY=YOUR_RAPID_API_KEY
     ```

5. Start the development server:

```bash
npm start
```

The application will be accessible at `http://localhost:3000` in your web browser.



## Technologies Used

- ReactJS: A JavaScript library for building user interfaces.
- Rapid API: Utilized for fetching travel-related data, including reviews and ratings.
- Google API: Used for location suggestions and retrieving additional details about destinations.
- Material UI: A React UI framework that provides pre-built components for a consistent and visually appealing design.

## Contributing

If you would like to contribute to the Travel Advisor App, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive messages.
4. Push your branch to your fork.
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

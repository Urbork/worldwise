# 🌍 WorldWise

- [Overview](#-overview)
- [Features](#-features)
- [Technologies Used](#-technologies-used)
- [Setup](#-setup)
- [Usage](#-usage)
- [Project Structure](#-project-structure)
- [Contributing](#-contributing)

## ▶ Overview

WorldWise is a travel logging application that allows users to mark cities they have visited, add notes, and keep track of their travels using local storage. The application provides an intuitive interface for logging travel experiences and revisiting past trips.

## ⭐ Features

- Add cities with geographical coordinates
- Automatically fetch city and country information
- Store visited cities
- Save and retrieve city data from local storage
- Edit and delete saved city entries
- Navigate between different pages using React Router

## ⚙ Technologies Used

- **React** - For building the user interface
- **React Router** - For client-side routing
- **React Context API** - For state management
- **Local Storage** - To persist data locally
- **Fetch API** - For geolocation data retrieval
- **React DatePicker** - For date selection
- **Vite** - For fast development and optimized builds

## 💻 Setup

### 1. Downloading the Source Code

Clone the repository to your local machine:

```sh
git clone https://github.com/your-username/worldwise.git
cd worldwise
```

### 2. Installing Dependencies

```sh
npm install
# or
yarn install
```

### 3. Running the Application

```sh
npm run dev
# or
yarn dev
```

The application will be available at `http://localhost:5173/`.

## 🚀 Usage

1. Click on a location on the map to add a city.
2. The app retrieves city details using reverse geocoding.
3. Enter additional notes and save the city.
4. View and manage saved cities from the list.
5. Edit or delete saved entries as needed.

## 📂 Project Structure

```
worldwise/
│── public/              # Static assets
│── src/
│   ├── components/      # Reusable UI components
│   ├── contexts/        # Context providers
│   ├── hooks/           # Custom React hooks
│   ├── pages/           # Application pages
│   ├── styles/          # CSS modules and styles
│   ├── App.jsx          # Main application component
│   ├── main.jsx         # Entry point
│── package.json         # Project dependencies
│── vite.config.js       # Vite configuration
│── README.md            # Project documentation
```

## 🤝 Contributing

Contributions are welcome! If you’d like to improve the project, feel free to fork the repository and submit a pull request.

# Solar Storm Prediction System - Front-end

This is the front-end for the Solar Storm Prediction System, a web application that allows users to predict solar storm events using machine learning algorithms and historical solar data.

## Features

The front-end consists of the following modules:

1. **Login Page**: Secure authentication for users to access the system.
2. **Dashboard**: Overview of the system with quick access to all modules.
3. **Solar Storm Prediction**: Predict solar storm events using machine learning models.
4. **Data Visualization**: Visualize solar data with interactive charts.
5. **Historical Data**: Browse and analyze historical solar storm data.
6. **User Profile**: Manage account settings and preferences.

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- The data files (labels.csv, satellite_pos.csv, solar_wind.csv, sunspots.csv) should be in the project's datasets directory

### Installation

1. No installation is required. Simply open the `index.html` file in your web browser.

### Usage

1. Open `index.html` in your web browser
2. Login with the following credentials:
   - Username: `admin`
   - Password: `admin123`
3. Navigate through the different modules using the navigation bar

## File Structure

```
frontend/
├── css/
│   └── styles.css
├── js/
│   └── main.js
├── images/
├── index.html (Login Page)
├── dashboard.html
├── prediction.html
├── visualization.html
├── historical.html
├── profile.html
└── README.md
```

## Dependencies

- [Chart.js](https://www.chartjs.org/) - For data visualization
- [DataTables](https://datatables.net/) - For enhanced table functionality
- [Font Awesome](https://fontawesome.com/) - For icons
- [jQuery](https://jquery.com/) - Required for DataTables

## Future Enhancements

- Integration with backend API for real-time data
- Advanced filtering and search capabilities
- User registration functionality
- Mobile-responsive design improvements
- Dark mode theme option

## Login Credentials

For demonstration purposes, use the following credentials:
- Username: `nakash`
- Password: `nakash123`

# Logistic Connector 3PL & Customer

## Project Overview
The Logistic Connector is a web-based landing page designed for a third-party logistics (3PL) service that connects customers with logistics solutions. This project aims to provide a user-friendly interface for potential clients to learn about services, news, and registration options.

## Project Structure
```
logistic-connector-landing
├── src
│   ├── index.html          # Main HTML document for the landing page
│   ├── components
│   │   ├── header.html     # Header section with logo and navigation
│   │   └── footer.html     # Footer section with copyright and links
│   ├── css
│   │   └── styles.css      # CSS styles for the landing page
│   └── js
│       └── main.js         # JavaScript for interactive features
├── assets
│   └── logo-placeholder.txt # Placeholder for the logo image
├── .gitignore              # Files and directories to ignore in version control
├── package.json            # npm configuration file
└── README.md               # Documentation for the project
```

## Features
- **Responsive Design**: The landing page is designed to be responsive and accessible on various devices.
- **Navigation Bar**: Easy access to Home, News, Services, Language Options, Registration, and Login.
- **Dynamic Content**: JavaScript functionality for interactive elements.

## Setup Instructions
1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install dependencies using npm:
   ```
   npm install
   ```
4. Open `src/index.html` in your web browser to view the landing page.

## Usage
- Modify the `assets/logo-placeholder.txt` file to replace the logo with an actual image.
- Update the `src/components/header.html` and `src/components/footer.html` files to customize the header and footer content as needed.
- Use `src/css/styles.css` to adjust styles and layout.
- Implement any interactive features in `src/js/main.js`.

## Todo
- [x] ID 1 – Update HTML with Translation Keys
- [x] ID 2 – Create Translation Dictionary in JS
- [x] ID 3 – Implement Translation Logic in JS
- [x] ID 4 – Ensure language applied on load

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for any enhancements or bug fixes.
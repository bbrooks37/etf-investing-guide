ETF Investing Guide
Project Description
The ETF Investing Guide is a multi-page web application designed to help average users learn about Exchange Traded Funds (ETFs) and how to interpret investment charts. This project aims to demystify financial concepts, making investing more accessible and empowering users to make informed decisions without requiring extensive prior knowledge or time commitment.

Features
Multi-Page Navigation: A clear and intuitive navigation bar allows users to easily switch between different sections.

What is an ETF?: Comprehensive explanation of ETFs, their benefits (diversification, lower costs, flexibility, transparency, tax efficiency), and common types (stock, bond, commodity, sector, international).

Reading Charts: An introduction to candlestick charts, including their components (body, wicks) and an explanation of trading volume. It also covers basic chart patterns like uptrends, downtrends, and consolidation, with visual examples.

Simulate & Quiz: An interactive quiz section to test user understanding of ETFs and chart reading, providing immediate feedback.

Glossary: A quick reference guide for common investment terms related to ETFs.

About & Contact: Information about the project's mission and contact details for feedback or inquiries.

Responsive Design: Built with Tailwind CSS to ensure optimal viewing and interaction across various devices (desktop, tablet, mobile).

Technologies Used
HTML5: For the core structure and content of the web pages.

Tailwind CSS: A utility-first CSS framework used for rapid and responsive styling.

JavaScript (Vanilla JS): For interactive elements, particularly the quiz logic on the "Simulate & Quiz" page.

Project Structure
etf-investing-guide/
├── index.html                  # Homepage
├── pages/                      # Directory for individual content pages
│   ├── what-is-etf.html
│   ├── reading-charts.html
│   ├── simulate-investing.html
│   ├── glossary.html
│   └── about.html
├── css/
│   └── style.css               # Custom CSS for general styles and animations
├── js/
│   └── script.js               # General JavaScript (currently for overall site, quiz logic is page-specific)
└── assets/                     # Directory for static assets
    └── images/                 # Contains images used throughout the site
        └── candlestick.png

How to Run Locally
To view and run this project on your local machine, follow these steps:

Clone the Repository:

git clone https://github.com/bbrooks37/etf-investing-guide.git

Navigate to the Project Directory:

cd etf-investing-guide

Serve with a Local Web Server:
Due to browser security restrictions (file:/// protocol), you cannot simply open index.html directly. You need a local web server.

Option 1: Using Python (Recommended for simplicity)
If you have Python installed, run:

python3 -m http.server
# Or for Python 2.x: python -m SimpleHTTPServer

Then, open your browser and go to http://localhost:8000.

Option 2: Using Node.js http-server
If you have Node.js and npm installed, first install http-server globally:

npm install -g http-server

Then, in your project directory, run:

http-server

Open your browser and go to http://localhost:8080.

Contributing
Contributions are welcome! If you have suggestions for improvements or find any issues, please feel free to:

Fork the repository.

Create a new branch (git checkout -b feature/your-feature-name or bugfix/issue-description).

Make your changes and commit them (git commit -m 'Add new feature').

Push to the branch (git push origin feature/your-feature-name).

Open a Pull Request.

License
This project is open-source and available under the MIT License.

Contact
For any questions or feedback, please contact:

Email: info@etfinsight.com (Placeholder)

GitHub: bbrooks37

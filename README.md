# Pokenea Application

## Description
The Pokenea Application is a simple web application built with Node.js and Express.js to showcase random information about Pokéneas. It generates random Pokéneas and displays their details either in JSON format or as an HTML page.

## Features
- Randomly generate Pokéneas data
- Display Pokéneas information in JSON format
- Render Pokéneas information in HTML format with images and text
- Responsive design using Bootstrap

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Jhonnathan93/Taller2.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Taller2
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

## Usage
1. Start the server:
   ```bash
   node main.js
   ```
2. Open your browser and go to [http://localhost:3000](http://localhost:3000) to view the application (or the port that you are using).

## Routes
- `/pokenea/Json`: Get a random Pokénea's information in JSON format.
- `/pokenea/HTML`: Get a random Pokénea's information rendered in HTML format.

## Directory Structure
```
pokenea-app/
├── controllers/
│   ├── pokeneaController.js
├── models/
│   ├── pokenea.js
│   └── pokeneas.js
├── public/
│   ├── css/
│   │   └── app.css
├── routes/
│   └── routes.js
├── views/
│   ├── layouts/
│   │   └── app.ejs
│   ├── home.ejs
│   └── pokenea.ejs
├── app.js
├── package.json
└── README.md
```

## Credits
- **Developer:** Your Name
- **Contact:** Your Email
- **GitHub Repository:** [Link to GitHub Repo](https://github.com/your-username/pokenea-app)

---

Feel free to customize the README file further by adding more details about the project, such as additional features, installation instructions for dependencies, usage examples, and any other relevant information.

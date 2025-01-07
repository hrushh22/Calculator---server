# 🧮 Calculator & BMI Calculator Web App

A simple web application built with Node.js and Express that provides both a basic calculator and BMI (Body Mass Index) calculator functionality.

## ✨ Features

- Basic arithmetic calculator
- BMI (Body Mass Index) calculator
- Simple and intuitive user interface
- Server-side calculations
- Responsive design

## 🛠️ Technologies Used

- Node.js
- Express.js
- HTML5
- Body-parser
- JavaScript

## 📋 Prerequisites

Before running this project, make sure you have the following installed:

- Node.js (v12 or higher)
- npm (Node Package Manager)

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/calculator-bmi-app.git
```

2. Navigate to the project directory:
```bash
cd calculator-bmi-app
```

3. Install dependencies:
```bash
npm install express body-parser
```

4. Start the server:
```bash
node app.js
```

## 💻 Usage

### Basic Calculator
1. Navigate to `http://localhost:5000/`
2. Enter two numbers in the input fields
3. Click "Calculate" to get the sum

### BMI Calculator
1. Navigate to `http://localhost:5000/bmiCalculator`
2. Enter your height (in meters)
3. Enter your weight (in kilograms)
4. Click "Calculate BMI" to get your BMI result

## 📁 Project Structure

```
├── app.js              # Main application file
├── index.html          # Basic calculator page
└── bmiCalculator.html  # BMI calculator page
```

## ⚙️ API Endpoints

- `GET /` - Serves the basic calculator page
- `POST /` - Handles basic calculator calculations
- `GET /bmiCalculator` - Serves the BMI calculator page
- `POST /bmiCalculator` - Handles BMI calculations

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🔍 Future Improvements

- Add input validation
- Include more calculator operations
- Add a more detailed BMI analysis
- Implement error handling
- Add CSS styling for better UI
- Add history of calculations
- Include unit conversion options

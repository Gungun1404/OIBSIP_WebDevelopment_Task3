# OIBSIP_WebDevelopment_Task3
🌡️ Temperature Converter
📌 Objective
This project is a Temperature Converter Web App that allows users to convert temperatures from Fahrenheit or Kelvin to Celsius. The result is dynamically displayed in the UI.

🧰 Tools Used
HTML5 – For creating the structure of the app

CSS3 – For styling the layout (linked via css/styles.css)

JavaScript – For handling the conversion logic and interactivity (js/app.js)

Boxicons & Font Awesome – For adding UI icons

🔄 Functionality Overview
Users can:

Input a temperature value using a number field.

Select the unit of input temperature (Fahrenheit or Kelvin).

Click the Convert button.

View the converted value in Celsius displayed on screen.

🧪 Conversion Logic (Implemented in app.js)
Fahrenheit → Celsius
(
°
𝐹
−
32
)
×
5
⁄
9
=
°
𝐶
(°F−32)×5⁄9=°C

Kelvin → Celsius
𝐾
−
273.15
=
°
𝐶
K−273.15=°C

The converted result is shown inside the <h2> element with ID celsius.

✅ Features
Validates that the input is a number

Uses semantic HTML for accessibility

Clean, mobile-friendly design

Styled icons for a polished look

🚀 Steps to Run the Project
Clone or download the repository.

Ensure the folder structure looks like this:

markdown
Copy
Edit
temperature-converter/
├── index.html
├── css/
│   └── styles.css
└── js/
    └── app.js
Open index.html in any modern web browser.

💡 Future Enhancements
Add bi-directional conversion (Celsius to Fahrenheit/Kelvin)

Add Kelvin → Fahrenheit and Fahrenheit → Kelvin

Allow users to choose both input and output units (e.g., dropdown for "From" and "To")

Include input error handling and visual feedback

Add a reset button

📷 Sample UI Elements
Input Field – For entering numeric temperature

Select Menu – To choose temperature type (Fahrenheit/Kelvin)

Convert Button – To trigger the conversion

Result Area – Displays the converted value in Celsius

👨‍💻 Author
Designed and developed using HTML, CSS, and JavaScript with icon libraries for aesthetics.


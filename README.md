# Temperature Converter

A simple and responsive **Temperature Converter** built with **HTML, CSS, and JavaScript**.

The application allows users to enter a temperature in **Celsius, Fahrenheit, or Kelvin** and instantly convert it into the other temperature units.

## Features

* Convert between Celsius, Fahrenheit, and Kelvin
* Three temperature input fields
* Instant temperature conversion
* Uses JavaScript `switch` statements for conversion logic
* Clean and simple interface
* Responsive design
* Lightweight and fast
* Accurate conversion formulas

## Technologies Used

* **HTML5** — Creates the structure of the temperature converter.
* **CSS3** — Handles the styling, layout, and responsive design.
* **JavaScript** — Handles the conversion logic and user interactions.

## Supported Units

The converter supports three temperature scales:

* **Celsius (°C)**
* **Fahrenheit (°F)**
* **Kelvin (K)**

## How It Works

The user can enter a temperature into any of the three input fields. JavaScript detects which temperature scale is being used and converts the value into the other two units.

### Celsius → Fahrenheit

```text
°F = (°C × 9/5) + 32
```

### Celsius → Kelvin

```text
K = °C + 273.15
```

### Fahrenheit → Celsius

```text
°C = (°F − 32) × 5/9
```

### Fahrenheit → Kelvin

```text
K = (°F − 32) × 5/9 + 273.15
```

### Kelvin → Celsius

```text
°C = K − 273.15
```

### Kelvin → Fahrenheit

```text
°F = (K − 273.15) × 9/5 + 32
```

## Switch Statements

The project uses JavaScript **switch statements** to determine which temperature conversion should be performed.

For example, the program can check the selected input unit and run the appropriate conversion logic:

```javascript
switch (unit) {
    case "celsius":
        // Convert Celsius
        break;

    case "fahrenheit":
        // Convert Fahrenheit
        break;

    case "kelvin":
        // Convert Kelvin
        break;
}
```

This keeps the conversion logic organized and makes it easier to add additional units later.

## Project Structure

```text
temperature-converter/
│
├── index.html
├── style.css
└── script.js
```

### `index.html`

Contains the structure of the converter, including the three temperature input fields.

### `style.css`

Controls the appearance of the application, including:

* Layout
* Colors
* Typography
* Input styling
* Spacing
* Responsive design

### `script.js`

Handles:

* User input
* Temperature conversions
* `switch` statements
* Updating the temperature fields
* Input/output logic

## Getting Started

No external libraries or dependencies are required.

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/temperature-converter.git
```

### 2. Open the project

```bash
cd temperature-converter
```

### 3. Run the application

Open `index.html` in your browser.

The converter will be ready to use.

## Preview


```markdown
<img width="688" height="473" alt="image" src="https://github.com/user-attachments/assets/3e324f76-1535-48b2-8aa0-167c9b44f85f" />

```

## Future Improvements

Possible improvements include:

* Add more temperature units
* Add a dedicated reset button
* Add dark mode
* Add temperature history
* Improve keyboard accessibility
* Add animations and transitions
* Further improve mobile responsiveness

## License

This project is open-source and available for learning and personal use.

---

### Built With

**HTML • CSS • JavaScript**

A beginner-friendly project created to practice **JavaScript logic, switch statements, mathematical formulas, DOM manipulation, and responsive frontend development**.

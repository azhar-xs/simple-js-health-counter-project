# Simple Health Tracker

A beautiful and interactive health tracking web application that displays animated counters for various health metrics.

## 🌟 Features

- **Heart Rate Monitoring**: Track your heart rate (BPM)
- **Sleep Tracking**: Monitor your sleep hours
- **Water Intake**: Keep track of daily water consumption
- **Step Counter**: Monitor your daily steps
- **Animated Counters**: Smooth counting animations for all metrics
- **Responsive Design**: Works on desktop and mobile devices
- **Modern UI**: Clean, colorful interface with Font Awesome icons

## 🎯 Health Metrics Tracked

| Metric | Target Value | Unit |
|--------|-------------|------|
| Heart Rate | 75 | BPM |
| Sleep | 8 | Hours |
| Water | 10 | Glasses |
| Steps | 11,000 | Steps |

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software installation required

### Installation

1. Clone or download this repository
2. Navigate to the project directory
3. Open `index.html` in your web browser

```bash
# If using a local server (optional)
# You can use Python's built-in server:
python -m http.server 8000

# Or Node.js http-server:
npx http-server

# Then open http://localhost:8000 in your browser
```

## 📁 Project Structure

```
simple-js-health-counter-project/
├── index.html          # Main HTML file
├── app.js             # JavaScript functionality
├── style.css          # Main stylesheet
├── css/
│   └── plugin.css     # Additional styles
└── README.md          # Project documentation
```

## 🛠️ Technologies Used

- **HTML5**: Structure and content
- **CSS3**: Styling and animations
- **JavaScript (ES6)**: Interactive functionality
- **Font Awesome**: Icons for health metrics
- **Google Fonts**: Typography (Roboto)

## 🎨 Color Scheme

The application uses a vibrant color palette:
- Heart Rate: Pink (`#ff0cf3`)
- Sleep: Yellow (`#ffea01`)
- Water: Cyan (`#00ffea`)
- Steps: Purple (`#4015dd`)

## ⚡ JavaScript Features

- **Animated Counters**: Smooth counting animation from 0 to target values
- **Dynamic Content**: Health status message updates after animation
- **Performance Optimized**: Uses `setTimeout` for smooth animations
- **Responsive Logic**: Adapts to different screen sizes

## 🎯 How It Works

1. **Page Load**: All counters start at 0
2. **Animation**: Counters animate to their target values over 300 steps
3. **Completion**: After 2 seconds, displays "You are Fit" message
4. **Visual Feedback**: Each metric has a unique color and icon

## 🔧 Customization

### Changing Target Values

Edit the `data-target` attributes in `index.html`:

```html
<span class="counter" data-target="75">0</span>
```

### Modifying Animation Speed

Adjust the `time` variable in `app.js`:

```javascript
let time = 300; // Lower = faster animation
```

### Updating Colors

Modify the CSS classes in `style.css`:

```css
.child_tracking:nth-child(1) {
    background-color: #your-color;
}
```

## 📱 Responsive Design

The application is fully responsive and works on:
- Desktop computers
- Tablets
- Mobile phones
- All modern browsers

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Internet Explorer 11+

## 🤝 Contributing

Feel free to contribute to this project by:
1. Forking the repository
2. Creating a feature branch
3. Making your changes
4. Submitting a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🎉 Demo

Simply open `index.html` in your browser to see the health tracker in action!

## 📞 Support

If you encounter any issues or have questions, please create an issue in the repository.

---

**Made with ❤️ for better health tracking**

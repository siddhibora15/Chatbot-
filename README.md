# 3D Chatbot Showcase Website 🤖

A modern, interactive single-page website designed to showcase AI chatbots with stunning 3D effects and animations. The website features a responsive design, interactive particle background, and smooth animations to create an engaging user experience.



## ✨ Features

- Interactive 3D particle background using Three.js
- Floating animated chatbot avatar with 3D rotation effects
- Responsive glass-morphism design
- Mouse-tracking particle animations
- Smooth scrolling and hover effects
- Cross-browser compatible
- Mobile-responsive layout

## 🚀 Technologies Used

- HTML5
- CSS3 (Advanced animations and 3D transforms)
- JavaScript (ES6+)
- Three.js (3D graphics)
- GSAP (Animations)

## 📦 Dependencies

```json
{
  "three.js": "^0.160.0",
  "gsap": "^3.12.2"
}
```

## 💻 Setup and Installation

1. Clone the repository:
```bash
git clone https://github.com/PIYUSH-JOSHI1/Chatbot-codesoft-.git
cd chatbot-showcase
```

2. Replace placeholder image:
- Navigate to the project directory
- Replace the placeholder URL in `style.css`:
```css
.bot-image {
    background: url('path/to/your/chatbot-image.png') center/cover;
}
```

3. Serve the website:
- Use a local development server (e.g., Live Server in VS Code)
- Or deploy to your hosting service

## 🛠️ Customization

### Changing Colors
Update the gradient colors in the CSS:
```css
body {
    background: linear-gradient(135deg, #your-color-1, #your-color-2, #your-color-3);
}
```

### Particle Settings
Modify particle density and animation in script.js:
```javascript
const particlesCount = 2000; // Adjust particle density
particlesMesh.rotation.y += 0.001; // Adjust rotation speed
```

### Content Updates
Replace the text content in index.html:
```html
<h1>Your Chatbot Name</h1>
<p class="description">Your custom description...</p>
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🌟 Credits

- Three.js for 3D graphics library
- GSAP for animation library
- Font Awesome for icons

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🚨 Known Issues

- Heavy particle animations might affect performance on low-end devices
- Safari might have slight variations in glass-morphism effects

## 💡 Performance Tips

1. Adjust particle count based on device performance
2. Optimize images before deployment
3. Consider lazy loading for better initial load time

## 📞 Support

For support, please open an issue in the repository or contact [piyushaundhekar@gmail.com]

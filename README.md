# Animotion - Frontend Animation Library

A modern, lightweight, and easy-to-use CSS animation library for web developers. Animotion provides a collection of carefully crafted animations that can be easily integrated into any web project.


![screencapture-zippy-squirrel-09cf8b-netlify-app-2025-04-05-11_54_25](https://github.com/user-attachments/assets/55e9c0d0-9d80-495d-80c2-fe166fbbf282)


## Features

- 🎨 20+ Beautiful CSS Animations
- 📱 Mobile-friendly and responsive
- ⚡ Performance optimized
- 🎯 Easy to implement
- 🎮 Interactive controls
- 📋 One-click code copying
- 🎭 Categorized animations
- 🌈 Customizable colors

## Categories

### Basic Animations

- Bouncing Ball
- Pulse
- Rotating Square
- Sliding Bar
- Fade
- Scale
- Floating
- Spinner

### Advanced Animations

- Wave
- Gradient
- Morphing
- Heartbeat
- Flip

### Effects

- Typing
- Shake
- Border
- Glitch
- Neon
- Ripple
- Shimmer

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/yourusername/animotion.git
```

2. Include the library in your HTML:

```html
<link rel="stylesheet" href="path/to/animotion.css" />
```

3. Use any animation in your HTML:

```html
<div class="bouncing-ball"></div>
```

## Usage

### Basic Implementation

1. Choose an animation from the library
2. Copy the CSS code
3. Apply the class to your element

Example:

```html
<!-- HTML -->
<div class="pulse"></div>

<!-- CSS -->
<style>
	.pulse {
		width: 60px;
		height: 60px;
		background-color: var(--primary);
		border-radius: 50%;
		animation: pulse 2s cubic-bezier(0.4, 0, 0.6, 1) infinite;
		box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
	}

	@keyframes pulse {
		0%,
		100% {
			transform: scale(1);
			opacity: 1;
		}
		50% {
			transform: scale(1.2);
			opacity: 0.8;
		}
	}
</style>
```

### Customization

You can customize animations by:

- Adjusting sizes
- Changing colors
- Modifying timing
- Adjusting animation parameters

Example:

```css
.pulse {
	/* Change size */
	width: 80px;
	height: 80px;

	/* Change color */
	background-color: #ff0000;

	/* Change timing */
	animation-duration: 1s;
}
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## Performance Optimization

- Uses CSS transforms for better performance
- Hardware-accelerated animations
- Optimized keyframes
- Minimal DOM manipulation

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by modern web design trends
- Built with performance in mind
- Thanks to all contributors

## Support

If you find this library helpful, please consider:

- ⭐ Starring the repository
- 🐛 Reporting bugs
- 💡 Suggesting new features
- 🤝 Contributing code

## Credits

Created with ❤️ by Bharath Kumar

---

Made with modern web technologies and a passion for beautiful animations.

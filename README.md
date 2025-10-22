# che-salon-web
https://cheshanminsara.github.io/che-salon-web/

# che-salon-web

## 🚀 Overview
Welcome to the **CHE Salon Web** project! This repository contains the HTML code for a premium beauty experience website. The site is designed to be visually stunning and engaging, featuring a unique blend of modern web technologies and design principles. Whether you're a beauty enthusiast or a web developer, this project offers a captivating experience that combines aesthetics with functionality.

### Key Features
- **Responsive Design**: Ensures a seamless experience across all devices.
- **Interactive Elements**: Utilizes Three.js for 3D visuals and GSAP for smooth animations.
- **Customizable Themes**: Tailwind CSS for easy styling and customization.
- **Engaging User Interface**: Playful animations and gradient effects to enhance user engagement.

### Who This Project Is For
- **Beauty Salons**: To create a professional and engaging online presence.
- **Web Developers**: To explore and learn modern web development techniques.
- **Design Enthusiasts**: To appreciate and utilize cutting-edge web design trends.

## ✨ Features
- 🌈 **Responsive Design**: Ensures a seamless experience across all devices.
- 🎨 **Customizable Themes**: Tailwind CSS for easy styling and customization.
- 🌟 **Interactive Elements**: Three.js for 3D visuals and GSAP for smooth animations.
- 🎬 **Engaging User Interface**: Playful animations and gradient effects to enhance user engagement.

## 🛠️ Tech Stack
- **Programming Language**: HTML
- **Frameworks, Libraries, and Tools**:
  - Tailwind CSS
  - Three.js
  - p5.js
  - GSAP
- **System Requirements**: Modern web browser (Chrome, Firefox, Safari, Edge)

## 📦 Installation

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of HTML and CSS

### Quick Start
1. Clone the repository:
   ```bash
   git clone https://github.com/cheshanminsara/che-salon-web.git
   ```
2. Open the `index.html` file in your web browser.

### Alternative Installation Methods
- **Docker**: If you prefer using Docker, you can set up a local development environment using Docker Compose.
- **Development Setup**: For developers, you can use a local development server like `http-server` to serve the files.

## 🎯 Usage

### Basic Usage
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>CHE Salon | Premium Beauty Experience</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/0.157.0/three.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.7.0/p5.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/ScrollTrigger.min.js"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        display: ['Playfair Display', 'serif'],
                    },
                    colors: {
                        primary: "#ec4899",
                        secondary: "#f9a8d4",
                        dark: "#9d174d",
                        light: "#fff1f2",
                        neutral: {
                            100: "#f5f5f5",
                            200: "#e5e5e5",
                            800: "#262626",
                            900: "#171717",
                        },
                    },
                    height: {
                        '128': '32rem',
                    },
                    animation: {
                        'float': 'float 6s ease-in-out infinite',
                    },
                    keyframes: {
                        float: {
                            '0%, 100%': { transform: 'translateY(0)' },
                            '50%': { transform: 'translateY(-10px)' },
                        }
                    }
                },
            },
        };
    </script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Playfair+Display:ital,wght@0,400;0,600;0,700;1,400&display=swap');

        .backdrop-blur-subtle {
            backdrop-filter: blur(8px);
        }

        .reveal {
            opacity: 0;
            transform: translateY(30px);
            transition: all 1s;
        }

        .reveal.active {
            opacity: 1;
            transform: translateY(0);
        }

        .three-canvas {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
        }

        .noise-overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            opacity: 0.03;
            pointer-events: none;
        }

        .gradient-text {
            background: linear-gradient(135deg, #ec4899 0%, #9d174d 100%);
        }
    </style>
</head>
<body>
    <!-- Your HTML content here -->
</body>
</html>
```

### Advanced Usage
- **Customizing Themes**: Modify the Tailwind CSS configuration to change colors, fonts, and other styles.
- **Adding 3D Elements**: Use Three.js to create and integrate 3D visuals into your web pages.
- **Enhancing Animations**: Utilize GSAP for complex animations and ScrollTrigger for scroll-based animations.

## 📁 Project Structure
```
che-salon-web/
│
├── index.html
└── README.md
```

## 🔧 Configuration
- **Tailwind CSS Configuration**: Customize the `tailwind.config.js` file to change themes, colors, and other styles.
- **Three.js and GSAP**: Configure these libraries as needed to integrate 3D visuals and animations.

## 🤝 Contributing
We welcome contributions! Here's how you can get involved:

### How to Contribute
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with clear messages.
4. Push your changes to your fork.
5. Open a pull request.

### Development Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/cheshanminsara/che-salon-web.git
   ```
2. Open the project in your preferred code editor.
3. Make your changes and commit them.

### Code Style Guidelines
- Follow the existing code style and conventions.
- Ensure your code is well-documented and easy to understand.

### Pull Request Process
- Ensure your pull request is well-described and includes relevant changes.
- Address any feedback from the maintainers.

## 📝 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 👥 Authors & Contributors
- **Maintainer**: [Your Name]
- **Contributors**: [List of contributors]

## 🐛 Issues & Support
- **Reporting Issues**: Please open an issue on the GitHub repository.
- **Getting Help**: Feel free to ask questions on the Issues tab or contact the maintainers directly.
- **FAQ**: [Link to FAQ]

## 🗺️ Roadmap
- **Planned Features**:
  - [ ] Add more interactive 3D elements.
  - [ ] Implement a blog section.
  - [ ] Enhance mobile responsiveness.
- **Known Issues**:
  - [ ] Some animations may not work on older browsers.
- **Future Improvements**:
  - [ ] Integrate a booking system.
  - [ ] Add more customizable themes.

---

**Badges:**
[![Build Status](https://travis-ci.org/cheshanminsara/che-salon-web.svg?branch=main)](https://travis-ci.org/cheshanminsara/che-salon-web)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

Thank you for your interest in the **CHE Salon Web** project! We hope you find it useful and engaging. If you have any questions or suggestions, please feel free to reach out. Happy coding! 🚀

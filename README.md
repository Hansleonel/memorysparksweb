# ✨ MemorySparks Web Platform

<div align="center">
  <img src="public/images/logo/app_icon.jpg" alt="MemorySparks Logo" width="120" />
  <br>
  <h3>Transform Your Memories Into Stories</h3>
  
  [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
  [![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
  [![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
  [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
  [![Clean Architecture](https://img.shields.io/badge/Clean%20Architecture-6DB33F?style=flat&logoColor=white)](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)
</div>

## 📱 About MemorySparks

MemorySparks is an innovative platform that helps you preserve and reimagine your precious memories through the power of AI storytelling. Transform your cherished moments into beautifully crafted stories across any genre - from adventure to romance, mystery to fantasy.

### ✨ Key Features

- **🤖 AI Story Generator**: Transform memories into captivating stories with advanced AI
- **🎭 Multiple Genres**: Choose from romance, adventure, mystery, fantasy, comedy, or drama
- **💾 Memory Preservation**: Secure cloud storage for your stories forever
- **📖 Beautiful Narratives**: AI that captures emotions and nuances perfectly
- **🌐 Multi-language Support**: Available in English and Spanish

## 🏗️ Project Architecture

This project follows **Clean Architecture** principles, ensuring a modular, maintainable, and testable codebase.

<div align="center">
  <img src="https://blog.cleancoder.com/uncle-bob/images/2012-08-13-the-clean-architecture/CleanArchitecture.jpg" alt="Clean Architecture Diagram" width="400" />
</div>

### 📂 Project Structure

```
MemorySparksWeb/
├── domain/               # Business entities and rules
│   ├── entities/         # Core business objects
│   ├── usecases/         # Application-specific business rules
│   └── repositories/     # Data access interfaces
├── infrastructure/       # External frameworks and tools
│   └── repositories/     # Data access implementations
├── interfaces/           # Adapters between layers
│   ├── controllers/      # Request/response handlers
│   └── presenters/       # Data formatters
├── presentation/         # UI components
│   ├── views/            # Application views
│   └── components/       # Reusable UI components
├── public/               # Static assets
│   ├── css/              # Stylesheets
│   ├── js/               # Client-side scripts
│   ├── images/           # Images and icons
│   └── fonts/            # Typography
└── index.html            # Main entry point
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic knowledge of HTML, CSS, and JavaScript
- Git (for cloning the repository)

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/MemorySparks/MemorySparksWeb.git
   cd MemorySparksWeb
   ```

2. **Serve the application**

   Since the application uses ES6 modules, you'll need to serve it through a local web server:

   Using Python:

   ```bash
   python -m http.server 8000
   ```

   Or using Node.js with a package like `serve`:

   ```bash
   npx serve
   ```

3. **Open in your browser**

   Navigate to `http://localhost:8000` (or the port provided by your server)

## 🎨 Design System

MemorySparks uses a modern, vibrant design system with carefully selected colors, typography, and components.

### 🎭 Typography

We use the **Clash Display** font family in various weights:

- Clash Display Extralight (200)
- Clash Display Light (300)
- Clash Display Regular (400)
- Clash Display Medium (500)
- Clash Display Semibold (600)
- Clash Display Bold (700)

### 🌈 Color Palette

- **Primary Colors**: Purple (#7c3aed), Pink (#ec4899), Amber (#f59e0b)
- **Secondary Colors**: Lavender (#a78bfa), Cyan (#06b6d4), Teal (#14b8a6)
- **Neutral Colors**: Slate grays for text and backgrounds
- **Gradients**: Beautiful multi-color gradients for visual interest

## 🌐 Internationalization

MemorySparks supports multiple languages:

- 🇺🇸 English (default)
- 🇪🇸 Spanish

The application automatically detects the user's browser language and applies the appropriate translations. Users can also manually switch between languages using the language selector in the header.

## 🎯 Use Cases

- **Personal Storytelling**: Transform your life memories into engaging narratives
- **Family Legacies**: Create beautiful stories to pass down through generations
- **Education**: Turn historical events into engaging stories for students
- **Professional Services**: Photography, wedding planning, travel blogging
- **Creative Writing**: Get inspiration and generate story ideas from real experiences

## 🧩 Clean Architecture Principles

1. **Framework Independence**: The application core doesn't depend on any external frameworks
2. **Testability**: Business rules can be tested without UI, database, or external elements
3. **UI Independence**: The interface can change without affecting the rest of the system
4. **Database Independence**: Storage technology can be swapped without affecting business rules
5. **External Agency Independence**: Business rules know nothing about the outside world

## 👨‍💻 Contributing

We welcome contributions to MemorySparks! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

<div align="center">
  <p>© 2025 MemorySparks.com All Rights Reserved</p>
  <p>
    <a href="https://github.com/MemorySparks">GitHub</a> •
    <a href="https://MemorySparks.com">Website</a> •
    <a href="mailto:help@memorysparks.com">Contact</a>
  </p>
</div>

# chmod.me

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

An interactive web tool for generating Unix file permissions (chmod) with real-time visual feedback. Direct URL: [chmod.me](https://chmodme.vercel.app)


## Features

- 🎛️ Visual permission toggles with animated feedback
- 🔢 Three output formats:
  - **Numeric** (octal) notation (e.g., `755`)
  - **Symbolic** representation (e.g., `rwxr-xr-x`)
  - **Alphabetic** command format (e.g., `u=rwx,g=rx,o=rx`)
- ⌨️ Keyboard shortcuts for quick adjustments
- 🌓 Dark mode interface
- 📋 Copy-ready command snippets
- 📚 Directory permission explanations
- 🔗 Shareable URLs with encoded permissions

## Usage

1. **Toggle permissions** using:
   - Category buttons (User/Group/Other)
   - Permission type buttons (Read/Write/Execute)
   - Individual permission switches
   - Keyboard shortcuts (`u`, `g`, `o`, `r`, `w`, `x`, `a`)

2. **Copy commands** from the generated code blocks:
   ```bash
   chmod 755 <file>       # Set permissions numerically
   chmod u=rwx,g=rx,o=rx <file>  # Set permissions symbolically
   chmod a+x <file>       # Add permissions
Share configurations using the URL hash (e.g., https://chmod.me/#644)

Installation
Local development setup:

bash
Copy
git clone https://github.com/your-username/chmod.me.git
cd chmod.me
# Open index.html in any modern browser
Development Setup
Technologies Used
Vanilla JavaScript (ES6)

Modern CSS Features:

CSS Grid/Flexbox

CSS Variables

Nested CSS

Transition animations

HTML5 Semantic Markup

File Structure
Copy
chmod.me/
├── index.html          # Main application
├── style.css           # All styling
└── README.md           # This documentation
Build & Deployment
No build required - works as static files! Deploy to any web server:

Upload all files to web host

Ensure proper MIME types for:

.html files as text/html

.css files as text/css

Contributing
Fork the repository

Create feature branch (git checkout -b feat/amazing-feature)

Commit changes (git commit -m 'Add amazing feature')

Push to branch (git push origin feat/amazing-feature)

Open a Pull Request

Style Guidelines:

Keep CSS nested maximum 3 levels deep

Use CSS variables for colors and sizes

Prefer functional-style JavaScript

Maintain keyboard accessibility

Documentation
For detailed permission explanations:

bash
man chmod  # Unix manual page


Browser Support:
Latest versions of Chrome, Firefox, Safari, and Edge
Resolution: Optimized for desktop and mobile screens
Accessibility: Keyboard-navigable interface

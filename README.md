<div align="center">
  <img height="150" src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExbGlrNzB4dDNkcDZrOWFrMTJmbHJob21jbmo5YmFlMDRrNW94MGp2NiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/6KirhLJyR7oMcwgJQk/giphy.gif"  />
</div>

# Sun Life Philippines Website

[![Website Status](https://img.shields.io/website?up_message=online&down_message=offline&url=https%3A%2F%2Fwww.sunlife.com.ph)](https://www.sunlife.com.ph)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Contributors](https://img.shields.io/github/contributors/yourusername/sunlife-ph-website)](https://github.com/yourusername/sunlife-ph-website/graphs/contributors)
[![Last Commit](https://img.shields.io/github/last-commit/yourusername/sunlife-ph-website)](https://github.com/yourusername/sunlife-ph-website/commits/main)

> The official website for Sun Life Philippines, offering comprehensive financial services including insurance, wealth management, and investment solutions to help Filipinos achieve financial security and healthier lifestyles.

## Table of Contents <a name="toc"></a>

- [✨ Features](#features)
- [🛠 Technologies Used](#technologies)
- [🚀 Getting Started](#getting-started)
  - [📋 Prerequisites](#prerequisites)
  - [⚙️ Installation](#installation)
  - [💻 Usage](#usage)
- [📂 Project Structure](#structure)
- [🤝 Contributing](#contributing)
- [📜 License](#license)
- [📞 Contact](#contact)

## ✨ Features <a name="features"></a>

✔ **Comprehensive Product Information**  
Detailed overview of life/health insurance and investment products with comparison tools  

📍 **Interactive Branch Locator**  
Google Maps integration with search functionality to find nearest branches  

🧮 **Financial Calculators**  
Interactive tools for retirement planning, education funding, and investment projections  

📢 **Client Success Stories**  
Video and written testimonials with filtering options  

👥 **Team Directory**  
Searchable profiles of the Scarlet Tanager Unit with contact options  

📝 **Smart Contact Form**  
AJAX-powered form with validation and CAPTCHA  

📱 **Responsive Design**  
Mobile-first approach with cross-device testing  

🔔 **Notification System**  
Alerts for important announcements and promotions  

## 🛠 Technologies Used <a name="technologies"></a>

**Frontend:**
- ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white)
- ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=white)
- ![Bootstrap 5](https://img.shields.io/badge/-Bootstrap-7952B3?logo=bootstrap&logoColor=white)
- ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black)

**Libraries:**
- ![AOS](https://img.shields.io/badge/-AOS-000000?logo=animate.css&logoColor=white) (Animate On Scroll)
- ![Swiper](https://img.shields.io/badge/-Swiper-6332F6?logo=swiper&logoColor=white)
- ![Chart.js](https://img.shields.io/badge/-Chart.js-FF6384?logo=chart.js&logoColor=white)

**Backend:**
- ![PHP](https://img.shields.io/badge/-PHP-777BB4?logo=php&logoColor=white)
- ![Google Maps API](https://img.shields.io/badge/-Google_Maps-4285F4?logo=google-maps&logoColor=white)

## 🚀 Getting Started <a name="getting-started"></a>

### 📋 Prerequisites <a name="prerequisites"></a>

- Node.js ≥ 14.x
- npm ≥ 6.x
- PHP ≥ 7.4 (for form handling)
- Composer (for PHP dependencies)

### ⚙️ Installation <a name="installation"></a>

1. Clone the repository:
```bash
git clone https://github.com/yourusername/sunlife-ph-website.git
cd sunlife-ph-website

```

2. Install dependencies:

```bash
npm install
composer install

```
3. Configure environment variables:

```bash
cp .env.example .env
Edit .env with your API keys (Google Maps, etc.)

```
4. Start development server:

```bash
npm run dev
💻 Usage <a name="usage"></a>

```

Development:

```bash
npm run dev

```
Production Build:
```bash
npm run build

```
Testing:

```bash
npm test

```

📂 Project Structure <a name="structure"></a>

```text
sunlife-philippines-website/
├── assets/
│   ├── css/               # SCSS/CSS files
│   │   ├── main.scss      # Main styles
│   │   └── components/    # Component-specific styles
│   ├── js/                # JavaScript modules
│   │   ├── main.js        # Entry point
│   │   └── modules/       # Feature modules
│   └── images/            # Optimized assets
│       ├── logo.svg       # Vector logo
│       └── testimonials/  # Client photos
├── includes/              # PHP partials
│   ├── header.php
│   └── footer.php
├── config/                # Configuration files
│   └── database.php       # DB connection
├── src/                   # PHP source
│   └── Contact/           # Form handlers
├── public/                # Document root
│   ├── index.php          # Main entry
│   └── assets/            # Compiled assets
├── .env.example           # Environment template
├── package.json           # Frontend deps
├── composer.json          # PHP deps
└── README.md              # This file

```
🤝 Contributing <a name="contributing"></a>
We welcome contributions! Please follow these steps:

1. Fork the project
2. Create your feature branch (git checkout -b feature/AmazingFeature)
3. Commit your changes (git commit -m 'Add some AmazingFeature')
4. Push to the branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

📜 License <a name="license"></a>
Distributed under the MIT License. See LICENSE for more information.

📞 Contact <a name="contact"></a>
Project Maintainer
Larren Joy D. Yumul - larrenellajoydizon@gmail.com

Sun Life Philippines
📞 Customer Service: 1800-10-225-5746
🌐 Official Website

https://img.shields.io/twitter/follow/SunLifePH?style=social
https://img.shields.io/badge/-Facebook-1877F2?logo=facebook&logoColor=white

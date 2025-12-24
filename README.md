# 🚍 Tumkur Transit

<div align="center">

**A Modern, Smart Public Transportation System for Tumkur City**

[![React](https://img.shields.io/badge/React-19.2.0-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-7.2.4-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![TailwindCSS](https://img.shields.io/badge/Tailwind-3.4.17-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

[Live Demo](#) • [Features](#-features) • [Installation](#-installation) • [Deployment](#-deployment)

</div>

---

## 📖 About

**Tumkur Transit** is a comprehensive web application designed to revolutionize public transportation in Tumkur city. It provides real-time bus route information, intelligent journey planning, and an AI-powered assistant to help commuters navigate the city efficiently.

### 🎯 Purpose

- **Simplify Commute**: Help residents and visitors find the best bus routes
- **Real-time Information**: Access up-to-date bus schedules and routes
- **Smart Planning**: AI-powered journey recommendations
- **Accessibility**: User-friendly interface with dark mode support

---

## ✨ Features

### 🗺️ **Smart Journey Planning**
- Search for bus routes by source and destination
- View detailed route information including:
  - All intermediate stops
  - Departure and arrival times
  - Ticket prices
  - Bus types (KSRTC Sarige, Express, Local, Shuttle)
  - Distance and duration
- Google Maps integration for navigation

### 🤖 **Tumkur Yatre - AI Assistant**
- Intelligent chatbot for transit queries
- Natural language processing for route suggestions
- Quick answers to common questions
- Personalized journey recommendations

### 🏙️ **Smart Sectors**
- Explore different areas of Tumkur
- Discover landmarks and points of interest
- Interactive sector information

### 🎨 **Modern UI/UX**
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile
- **Dark Mode**: Eye-friendly theme toggle
- **Accessibility Features**: WCAG compliant design
- **Smooth Animations**: Enhanced user experience with micro-interactions
- **Clean Interface**: Modern, intuitive navigation

### 🚌 **Comprehensive Bus Database**
- 7+ major bus routes covering Tumkur city
- Regular updates to route information
- Multiple bus types and services

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **React 19.2** | Frontend framework |
| **Vite 7.2** | Build tool & dev server |
| **React Router 7.11** | Client-side routing |
| **Tailwind CSS 3.4** | Utility-first styling |
| **Lucide React** | Modern icon library |
| **ESLint** | Code quality & linting |

---

## 🚀 Installation

### Prerequisites

- **Node.js** (v18 or higher)
- **npm** or **yarn**

### Quick Start

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/tumkur-transit.git

# Navigate to project directory
cd tumkur-transit

# Install dependencies
npm install

# Start development server
npm run dev
```

The app will be running at **http://localhost:5173/**

---

## 📜 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server with hot reload |
| `npm run build` | Build for production (outputs to `dist/`) |
| `npm run preview` | Preview production build locally |
| `npm run lint` | Run ESLint to check code quality |

---

## 📁 Project Structure

```
tumkur-transit/
├── public/              # Static assets
├── src/
│   ├── components/      # React components
│   │   ├── Header.jsx          # Navigation header
│   │   ├── Hero.jsx            # Landing hero section
│   │   ├── PlanJourney.jsx     # Route search & display
│   │   ├── SmartSectors.jsx    # City sectors info
│   │   └── TumkurYatre.jsx     # AI chatbot assistant
│   ├── data/
│   │   └── busRoutes.json      # Bus route database
│   ├── pages/
│   │   └── Home.jsx            # Main landing page
│   ├── App.jsx          # Root component
│   ├── main.jsx         # Entry point
│   └── index.css        # Global styles
├── index.html           # HTML template
├── vite.config.js       # Vite configuration
├── tailwind.config.js   # Tailwind configuration
└── package.json         # Dependencies
```

---

## 🌐 Deployment

### Deploy to Vercel (Recommended)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/YOUR_USERNAME/tumkur-transit)

```bash
# Build the project
npm run build

# The dist/ folder is ready for deployment
```

### Deploy to Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/YOUR_USERNAME/tumkur-transit)

### Deploy to GitHub Pages

See [DEPLOYMENT.md](DEPLOYMENT.md) for detailed deployment instructions.

---

## 🗺️ Bus Routes

The application currently includes **7 major bus routes**:

| Route | Source | Destination | Distance | Type |
|-------|--------|-------------|----------|------|
| 000883 | Tumkur | Kundur | 45 km | KSRTC Sarige |
| 000704 | Goolarive | Narasapura | 32 km | KSRTC Local |
| 000502 | Shettihalli | Yellapurapb | 18 km | KSRTC City |
| 000521 | Tumkur | SS Mutt | 12 km | KSRTC Shuttle |
| 000071 | Dabaspete | Tumakuru | 25 km | KSRTC Express |
| 000601 | Tumkur | Haagalavadi | 38 km | KSRTC Sarige |
| 000516 | Tumkur | Swandenahal | 15 km | KSRTC Local |

---

## 🎨 Features in Detail

### Journey Planning
1. Select your **source** and **destination**
2. View available bus routes
3. See detailed information:
   - Complete stop list
   - Timings and duration
   - Fare information
4. Navigate using Google Maps integration

### AI Assistant (Tumkur Yatre)
- Ask questions in natural language
- Get route recommendations
- Learn about Tumkur city
- Receive personalized travel tips

### Accessibility
- Keyboard navigation support
- Screen reader compatible
- High contrast mode
- Adjustable font sizes

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### Areas for Contribution
- [ ] Add more bus routes
- [ ] Implement real-time bus tracking
- [ ] Add multi-language support
- [ ] Improve AI assistant capabilities
- [ ] Add user authentication
- [ ] Create mobile app version

---

## 🐛 Bug Reports

Found a bug? Please open an issue with:
- Description of the bug
- Steps to reproduce
- Expected vs actual behavior
- Screenshots (if applicable)

---

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Your Name**
- GitHub: [@YOUR_USERNAME](https://github.com/YOUR_USERNAME)
- Email: your.email@example.com

---

## 🙏 Acknowledgments

- **KSRTC** for public transportation data
- **Tumkur City** for inspiration
- **React Community** for amazing tools
- **Contributors** who help improve this project

---

## 📞 Support

Need help? Have questions?

- 📧 Email: support@tumkurtransit.com
- 💬 Discord: [Join our community](#)
- 📖 Documentation: [Read the docs](#)
- 🐦 Twitter: [@TumkurTransit](#)

---

## 🗺️ Roadmap

### Version 2.0 (Upcoming)
- [ ] Real-time bus GPS tracking
- [ ] Push notifications for bus arrivals
- [ ] User accounts and saved routes
- [ ] Offline mode support
- [ ] Multi-language support (Kannada, Hindi, English)
- [ ] Integration with payment systems
- [ ] Mobile app (React Native)

### Version 1.5
- [ ] Enhanced AI capabilities
- [ ] More bus routes
- [ ] User feedback system
- [ ] Route favorites

---

<div align="center">

**Made with ❤️ for Tumkur City**

⭐ Star this repo if you find it helpful!

[Report Bug](https://github.com/YOUR_USERNAME/tumkur-transit/issues) • [Request Feature](https://github.com/YOUR_USERNAME/tumkur-transit/issues)

</div>

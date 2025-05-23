# MNHS Scout Portal

![GitHub](https://img.shields.io/github/license/CyberSphinxxx/MNHS-Scout-portal)
![GitHub last commit](https://img.shields.io/github/last-commit/CyberSphinxxx/MNHS-Scout-portal)
![GitHub issues](https://img.shields.io/github/issues/CyberSphinxxx/MNHS-Scout-portal)

The **MNHS Scout Portal** is a web application designed to promote the activities, mission, and community of the MNHS Senior Scouts, established in 2018. This portal serves as a digital hub for scouts, parents, and community members to explore scouting programs, view past events, and get involved. Built with HTML, CSS, and JavaScript, the site features a responsive design, interactive navigation, and a vibrant aesthetic inspired by the scouting spirit.

![Opera Snapshot_2024-12-08_163320_127 0 0 1](https://github.com/user-attachments/assets/0971f785-663d-4569-acd7-416ac0029356)

## Table of Contents
- [Features](#features)
- [Screenshots](#screenshots)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [Future Enhancements](#future-enhancements)
- [License](#license)
- [Contact](#contact)

## Features
- **Responsive Design**: Fully optimized for mobile, tablet, and desktop devices, with a hamburger menu for mobile navigation.
- **Interactive Navigation**: Smooth scrolling and a fixed header that changes style on scroll.
- **Dynamic Content**: Sections for About Us, Activities, Past Events, and Contact, with fade-in animations for engagement.
- **External Integrations**: Links to the MNHS Scouts Facebook page and Font Awesome icons for visual appeal.
- **Accessibility**: ARIA attributes for the mobile menu and descriptive alt text for images.
- **Extensible**: Ready to add pages like Events Calendar, Gallery, or Membership forms (see [Future Enhancements](#future-enhancements)).

## Screenshots
| Homepage | Activities Section |
|----------|--------------------|
| ![Opera Snapshot_2024-12-08_163320_127 0 0 1](https://github.com/user-attachments/assets/0971f785-663d-4569-acd7-416ac0029356) | ![image](https://github.com/user-attachments/assets/009297f1-26f1-446f-9686-ad70b0d72c3a)|

## Installation
To run the MNHS Scout Portal locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/CyberSphinxxx/MNHS-Scout-Portal.git
   cd mnhs-scout-portal
   ```

2. **Install Dependencies**:
   No server-side dependencies are required, as the project uses static HTML, CSS, and JavaScript. However, ensure you have a local web server or use a browser to view the site.

3. **Serve the Project**:
   Use a local server (e.g., Live Server in VS Code, or Python’s HTTP server):
   ```bash
   python -m http.server 8000
   ```
   Alternatively, open `index.html` directly in a browser (note: some features like smooth scrolling may require a server).

4. **Access the Site**:
   Navigate to `http://localhost:8000` in your browser.

*Dependencies*:
- [Font Awesome 6.4.0](https://cdnjs.com/libraries/font-awesome) (included via CDN)
- [Swiper 9](https://swiperjs.com/) (included via CDN, used for potential carousel features)

## Usage
- **Explore the Site**: Visit the homepage (`index.html`) to view sections like About Us, Our Activities, Activities Joined, and Contact.
- **Mobile Navigation**: On mobile devices (≤768px), click the hamburger menu to access navigation links.
- **Smooth Scrolling**: Click navigation links to smoothly scroll to sections like `#about` or `#activities`.
- **Contact**: Use the Facebook link in the Contact section to reach out to MNHS Scouts.
- **Extend the Site**: Add new pages (e.g., `/pages/events.html`) by copying the `index.html` structure and updating the navigation links.

To add new content:
1. Update images in `/assets/` (e.g., `/assets/events/` for new event photos).
2. Modify `/js/hero-page.js` for additional interactivity (e.g., Swiper carousel initialization).
3. Create new HTML files in `/pages/` for additional sections like Gallery or Join Us.

## Project Structure
```
mnhs-scout-portal/
├── assets/
│   ├── imgs/                # Logos and images (e.g., mnhs-logo.png)
│   ├── jota-joti-2024/      # Event-specific images
│   ├── macasandig-parade/
│   ├── first-aid-training/
│   └── screenshots/         # Screenshots for README
├── css/
│   ├── hero-page.css        # Additional styles (if used)
│   └── main-styles.css      # Main CSS (currently inline in index.html)
├── js/
│   └── hero-page.js         # JavaScript for navigation, animations, and Swiper
├── pages/
│   ├── PrivacyPolicy/       # Privacy Policy page
│   └── TermsOfService/      # Terms of Service page
├── index.html               # Homepage
└── README.md                # This file
```

## Contributing
Contributions are welcome to enhance the MNHS Scout Portal! To contribute:

1. **Fork the Repository**: Click the "Fork" button on GitHub.
2. **Create a Branch**:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make Changes**: Add new pages, improve responsiveness, or fix bugs.
4. **Test Locally**: Ensure the site works across devices and browsers.
5. **Commit Changes**:
   ```bash
   git commit -m "Add your feature description"
   ```
6. **Push to Your Fork**:
   ```bash
   git push origin feature/your-feature-name
   ```
7. **Open a Pull Request**: Submit a PR with a clear description of your changes.

## License
This project is licensed under the [MIT License](LICENSE). See the LICENSE file for details.

## Contact
For questions or feedback, reach out via:
- **Facebook**: [MNHS Scouts Facebook Page](https://www.facebook.com/profile.php?id=61557115374649)
- **GitHub Issues**: [Open an issue](https://github.com/yourusername/mnhs-scout-portal/issues)
- **Email**: johnlemargonzales@gmail.com

Join us in building a vibrant digital home for MNHS Senior Scouts! 🌲⚜️

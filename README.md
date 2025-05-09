# COEMAB GLOBAL CONSULT - Empowering Africans Through Education

COEMAB GLOBAL CONSULT is a website designed to provide personalized academic guidance and international opportunities for African students and professionals. The platform offers a range of services, including study abroad consultations, visa assistance, test preparation, career counseling, and more.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [File Structure](#file-structure)
- [Setup Instructions](#setup-instructions)
- [Customization](#customization)
- [Contact Information](#contact-information)

---

## Overview

The website aims to empower African students by bridging educational gaps and creating pathways to global opportunities. It features a modern, responsive design with smooth animations and interactive elements to enhance user experience.

### Key Sections:
1. **Hero Section**: Highlights the mission of ACE Global with a call-to-action.
2. **About Section**: Provides information about the organization's mission, vision, and values.
3. **Services Section**: Details the services offered, such as study abroad consultation, visa assistance, and mentorship programs.
4. **Why Choose Us Section**: Showcases the organization's achievements, expert team, and testimonials.
5. **Contact Section**: Allows users to get in touch via a form or find office locations and contact details.
6. **Footer**: Contains quick links, social media icons, and a newsletter subscription form.

---

## Features

- **Responsive Design**: Optimized for all devices, including desktops, tablets, and mobile phones.
- **Smooth Animations**: Includes scroll animations and hover effects for an engaging user experience.
- **Interactive Elements**:
  - Mobile menu toggle.
  - Smooth scrolling for anchor links.
  - Animated counters for statistics.
- **Customizable Theme**: Tailwind CSS configuration allows easy customization of colors, fonts, and other design elements.

---

## Technologies Used

- **HTML5**: For structuring the content.
- **CSS3**: For styling, including Tailwind CSS for utility-first design.
- **JavaScript**: For interactivity and animations.
- **External Libraries**:
  - [Tailwind CSS](https://tailwindcss.com) for styling.
  - [Remixicon](https://remixicon.com) for icons.
  - [ECharts](https://echarts.apache.org/) for potential data visualization.

---

## File Structure

```
ACE GLOBAL/
├── index.html          # Main HTML file
├── .vscode/
│   └── settings.json   # VS Code settings for Live Server
```

### Key Files:
- **`index.html`**: Contains the entire structure and content of the website.
- **`.vscode/settings.json`**: Configures the Live Server to run on port 5501.

---

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd ACE-GLOBAL
   ```

2. **Open in VS Code**:
   Open the project folder in Visual Studio Code.

3. **Run the Website**:
   - Install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension in VS Code.
   - Right-click on `index.html` and select **"Open with Live Server"**.
   - The website will be available at `http://127.0.0.1:5501/`.

---

## Customization

### Tailwind CSS Configuration
The Tailwind CSS configuration is embedded in the `<script>` tag in the `<head>` section of `index.html`. You can modify the theme by updating the `tailwind.config` object:
```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                primary: '#1a237e',
                secondary: '#2196f3',
            },
            borderRadius: {
                button: '8px',
            },
        },
    },
};
```

### Adding New Sections
To add new sections, follow the structure of existing sections in `index.html`. Use Tailwind CSS classes for styling and ensure consistency with the overall design.

---

## Contact Information

For any inquiries or support, you can reach out to ACE Global through the following channels:

- **Email**: [info@aceglobal.com](mailto:info@aceglobal.com)
- **Phone**: +234 800 ACE GLOBAL, +254 700 ACE GLOBAL
- **Office Locations**:
  - Lagos, Nigeria: 15 Marina Street, Victoria Island
  - Nairobi, Kenya: Westlands Business Park, 3rd Floor
  - Accra, Ghana: 25 Independence Avenue

---

## License

This project is licensed under the MIT License. Feel free to use and modify it for your own purposes.

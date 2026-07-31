# Terms of Service Modal

A clean, minimalist Terms of Service (ToS) agreement page built using pure HTML, CSS, and JavaScript. The project demonstrates a user-friendly modal that requires users to read (scroll through) the Terms of Service before they can agree and continue.

## Features

- Minimalist black-and-white interface
- Automatic modal popup after page load
- Scroll detection to ensure the user reaches the bottom
- Agreement checkbox remains disabled until the document is fully read
- Proceed button activates only after:
  - Scrolling to the bottom
  - Checking the agreement box
- Smooth fade and slide animations
- Responsive design for desktop and mobile devices
- No external libraries or frameworks required

---

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript

---

## Project Structure

```
project/
│
├── index.html        # Main application
├── tos_icon.ico      # Browser favicon
└── README.md
```

---

## How It Works

1. The webpage loads normally.
2. After a 3-second delay, the Terms of Service modal appears.
3. The user must scroll to the bottom of the agreement.
4. Reaching the bottom unlocks the agreement checkbox.
5. Once the checkbox is selected, the **Proceed** button becomes active.
6. Clicking **Proceed** closes the modal.

---

## User Flow

```
Page Loads
      │
      ▼
3 Second Delay
      │
      ▼
Terms Modal Opens
      │
      ▼
User Scrolls to Bottom
      │
      ▼
Checkbox Unlocks
      │
      ▼
User Accepts Terms
      │
      ▼
Proceed Button Enables
      │
      ▼
Modal Closes
```

---

## Design Philosophy

This project follows a minimalist design inspired by modern software interfaces:

- High contrast black-and-white color scheme
- Clean typography
- Simple user interactions
- Distraction-free interface
- Accessibility-focused layout

---

## Future Improvements

Potential enhancements include:

- Persistent acceptance using Local Storage
- Dark/Light mode toggle
- Custom Terms loaded from an external file
- Multiple language support
- Animated progress indicator while reading
- Accessibility improvements (ARIA support)
- Keyboard navigation
- PDF export of Terms
- Backend integration for user acceptance logging

---

## Browser Support

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari
- Opera

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/terms-of-service-modal.git
```

Navigate to the project:

```bash
cd terms-of-service-modal
```

Open `index.html` in your preferred web browser.

---

## License

This project is available under the MIT License.

---

## Author

Created by **Boikobo Metsing**

---

## Acknowledgements

Built as a front-end project to demonstrate:

- Modal design
- Scroll detection
- User interaction validation
- Responsive UI development
- Vanilla JavaScript event handling

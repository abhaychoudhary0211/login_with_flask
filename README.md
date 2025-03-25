# Animated Login & Signup System

A beautiful and interactive login and signup system built with Flask, featuring smooth animations and responsive design.

## Features

- 🎨 Beautiful gradient background with dynamic animations
- ⚙️ Interactive gear animations that respond to form input
- 📱 Fully responsive design for all screen sizes
- 🔒 Secure password hashing
- ✨ Smooth transitions and hover effects
- 🎯 Floating label animations
- 💫 3D transform effects
- 🔄 Dynamic form validation

## Prerequisites

- Python 3.7 or higher
- pip (Python package installer)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/abhaychoudhary0211/login_with_flask.git
cd login-system
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install the required packages:
```bash
pip install -r requirements.txt
```

## Running the Application

1. Start the Flask server:
```bash
python app.py
```

2. Open your web browser and navigate to:
```
http://localhost:5000
```

## Project Structure

```
login-system/
├── app.py              # Main Flask application
├── requirements.txt    # Python dependencies
├── templates/         # HTML templates
│   ├── base.html      # Base template with common styles
│   ├── login.html     # Login page template
│   └── signup.html    # Signup page template
└── instance/         # Database files (created automatically)
    └── users.db      # SQLite database
```

## Features in Detail

### Login Page
- Username and password fields
- Animated gear icons that appear on focus
- Smooth transitions between states
- Error handling for invalid credentials

### Signup Page
- First name, last name, username, email, and password fields
- Real-time validation
- Animated gear icons for each field
- Duplicate username/email checking

### Security Features
- Password hashing using Werkzeug
- SQLite database for user storage
- Form validation and sanitization
- Flash messages for user feedback

### Responsive Design
- Adapts to all screen sizes
- Mobile-friendly interface
- Touch-friendly input fields
- Optimized for tablets and desktops

## Customization

### Colors
You can customize the color scheme by modifying the CSS variables in `base.html`:
- Primary color: `#23a6d5`
- Secondary color: `#23d5ab`
- Background gradient colors

### Animations
Adjust animation timings and effects in `base.html`:
- Gear rotation speed
- Button hover effects
- Form field transitions
- Background gradient animation

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Flask framework
- SQLAlchemy for database management
- Modern CSS animations and transitions 
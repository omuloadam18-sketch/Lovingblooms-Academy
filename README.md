LovingBloomsAcademy/
├── html/
│   ├── index.html         Home page (hero, growth path, why-us, stats)
│   ├── about.html         About page — has its own swappable background image
│   ├── facilities.html    Facilities list + Photo Gallery
│   ├── contact.html       Contact page with working inquiry form
│   └── location.html      Map + directions to the Embakasi campus
├── css/
│   └── style.css          All styling: blue + red theme, dark/light mode, animations
├── js/
│   ├── main.js             Navigation, dark/light toggle, scroll animations, data loader
│   ├── gallery.js          Renders + filters the photo gallery, lightbox viewer
│   └── contact.js          Validates and submits the contact form
├── api/
│   └── contact-api.js      Bridges the contact form to a Google Apps Script "API"
├── googlestorage/
│   └── gallery-config.js   <-- ADD YOUR SCHOOL PHOTOS HERE (see instructions inside)
├── data/
│   └── school-data.json    Site "database": stats, contact info, facility list
└── assets/images/          Local images (e.g. about-hero.jpg)

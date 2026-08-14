# Hotel Booking System
A responsive, multi-page hotel booking website with room browsing, a login/register flow, and a full-page layout built on Bootstrap.

# Overview
Hotel-Booking-System is a front-end web application for a fictional hotel, covering the core flows a real hotel site needs: a landing page, room listings, a booking/contact flow, and user authentication modals — all fully responsive across devices.

## Features
- Responsive multi-page layout (Home, Rooms, About, Contact) with a sticky navbar
- Login and Register modals with form validation UI
- Room listing and gallery pages showcasing amenities (pool, gym, Wi-Fi, AC, parking)
- Image carousel/slider for featured rooms and reviews
- Mobile-first design using the Bootstrap grid system

## Tech Stack
HTML5, CSS3, [Bootstrap 5](https://getbootstrap.com/), [Bootstrap Icons](https://icons.getbootstrap.com/), [Swiper.js](https://swiperjs.com/) (carousels), Google Fonts (Poppins)

## Project Structure

VK hotel/
├── index.html        # Home page
├── Rooms.html         # Room listings
├── About.html
├── Contact.html
├── style.css
├── images/             # Site imagery
└── Rooms/              # Room-specific imagery


## Setup

No build step required — this is a static site.
git clone <https://github.com/Shah-Kavya-03/Hotel-Booking-System>
cd "Hotel-Booking-System"

Then simply open `index.html` in a browser, or serve the folder with any static file server, e.g.:
npx serve 

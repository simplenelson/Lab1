# Pawsitive Care Vet Clinic – Application Overview

This web application allows pet owners to book virtual appointments, view services, and contact the clinic online. It is a static HTML/CSS/JS app with no backend, designed for easy deployment and use.

## Features
- **Landing Page:** Overview of the clinic, testimonials, and navigation.
- **Book Appointment:** Book a virtual appointment with a vet. Dynamic doctor/slot selection, input validation, and confirmation feedback.
- **Services:** Detailed descriptions of all services offered.
- **Contact:** Dedicated contact page with a form and clinic details.

## How to Use
1. **Open the app in your browser.**
2. **Navigate using the top menu:**
   - Home: Main landing page
   - Services: See all available services
   - Book Appointment: Fill out the form to book a virtual visit
   - Contact: Send a message or find clinic contact info
3. **Book an appointment:**
   - Select a doctor and available time slot
   - Enter your details and a description (max 500 characters)
   - Submit to receive confirmation
4. **Contact the clinic:**
   - Use the Contact page for inquiries or support

## Technical Notes
- All data is stored in-memory (appointments are not persistent)
- No authentication or backend integration
- Responsive and accessible design

## File Structure
- `vet-landing-prototype.html` – Main landing page
- `services.html` – Services page
- `book-appointment.html` – Appointment booking
- `contact.html` – Contact form and info
- `playwright.config.js`, `tests/` – Automated test setup (optional)

---
For requirements and planning, see `PRD.md`.

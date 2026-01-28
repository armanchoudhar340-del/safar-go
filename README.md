# TravelGo - Travel Booking Website

A responsive travel booking website similar to MakeMyTrip, built with HTML5 and CSS3 only (no JavaScript).

## 🎯 Project Overview

TravelGo is a modern, fully responsive travel booking platform that allows users to search and book flights, trains, buses, and hotels. The project emphasizes clean design, semantic HTML, and CSS-only interactive components.

---

## ✅ Completed Features

### 1. **Main Landing Page (`index.html`)**
- ✅ **Responsive Navigation Bar**
  - Logo with icon
  - Navigation links (Flights, Trains, Buses, Hotels)
  - Login/Sign Up buttons
  - Mobile-friendly design

- ✅ **Hero Section**
  - Full-width background with overlay
  - Compelling headline and tagline
  - CSS-only tabbed booking widget

- ✅ **Booking Widget (CSS-Only Tabs)**
  - Four tabs: Flights, Trains, Buses, Hotels
  - Tab switching using radio buttons (no JavaScript)
  - Individual forms for each booking type:
    - **Flights**: From, To, Departure Date
    - **Trains**: From, To, Departure Date
    - **Buses**: From, To, Departure Date
    - **Hotels**: Location, Check-in, Check-out
  - All forms submit to `listings.html` with GET parameters

- ✅ **Popular Routes Section**
  - Grid layout with 4 route cards
  - Each card displays:
    - Background image (Unsplash)
    - Badge (Flights/Trains/Buses)
    - Route name
    - Starting price
  - Responsive grid (4 columns → 2 → 1)

- ✅ **Why Choose Us Section**
  - Three feature cards:
    - Best Price Guarantee
    - 24/7 Customer Support
    - Instant Booking
  - Icon-based design with descriptions

- ✅ **Footer**
  - Four columns: Company, Support, Services, Social Media
  - Social media icons (Facebook, Twitter, Instagram, LinkedIn)
  - Legal links (Privacy Policy, Terms of Service)
  - Copyright notice

### 2. **Search Results Page (`listings.html`)**
- ✅ **Header Navigation**
  - Consistent with main page
  - Back links to home page sections

- ✅ **Sidebar Filters**
  - Price range slider
  - Stops filter (Non-stop checkbox)
  - Responsive (moves to top on mobile)

- ✅ **Results List**
  - Three mock flight results:
    - Airline name
    - Departure/arrival times
    - Duration and stops
    - Price
    - "Book Now" button
  - Card-based layout with left accent border

- ✅ **Footer**
  - Simplified footer with About, Contact, Social sections

### 3. **Styling (`style.css`)**
- ✅ **CSS Variables**
  - Color scheme (primary, secondary, text colors)
  - Consistent spacing and sizing

- ✅ **Responsive Design**
  - Mobile-first approach
  - Breakpoints for tablet and desktop
  - Flexible layouts using Flexbox and Grid

- ✅ **Modern UI Elements**
  - Smooth transitions and hover effects
  - Box shadows and border radius
  - Custom button styles
  - Icon integration with FontAwesome

- ✅ **Typography**
  - Google Fonts (Poppins)
  - Proper heading hierarchy
  - Readable font sizes and line heights

### 4. **Technical Implementation**
- ✅ **Semantic HTML5**
  - Proper use of `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`
  - Accessible form labels and inputs
  - SEO-friendly structure

- ✅ **CSS-Only Interactions**
  - Tab switching without JavaScript
  - Hover effects
  - Responsive navigation

- ✅ **Form Functionality**
  - GET method for search forms
  - Required field validation
  - Proper input types (text, date)

---

## 🚧 Pending Features & Improvements

### High Priority
- [ ] **JavaScript Integration**
  - Dynamic search results based on form inputs
  - Real-time price filtering
  - Date validation (prevent past dates)
  - Form data persistence using localStorage

- [ ] **Enhanced Search Results**
  - Display actual search parameters from URL
  - Filter functionality (price range, stops, timing)
  - Sort options (price, duration, departure time)
  - Pagination for results

- [ ] **Booking Flow**
  - Detailed booking page
  - Passenger information form
  - Payment gateway integration (mock)
  - Booking confirmation page

### Medium Priority
- [ ] **User Authentication**
  - Login/Sign Up modal or page
  - User profile page
  - Booking history

- [ ] **Additional Pages**
  - About Us page
  - Contact Us page with form
  - Help/FAQ page
  - Terms & Conditions page
  - Privacy Policy page

- [ ] **Enhanced Features**
  - Round-trip vs One-way toggle
  - Multi-city search option
  - Passenger count selector
  - Class selection (Economy, Business, First)
  - Hotel star rating filter
  - Map integration for hotels

### Low Priority
- [ ] **Performance Optimization**
  - Image optimization
  - Lazy loading for images
  - Minified CSS
  - Critical CSS inlining

- [ ] **Accessibility Improvements**
  - ARIA labels
  - Keyboard navigation
  - Screen reader optimization
  - Color contrast compliance (WCAG)

- [ ] **Additional Enhancements**
  - Dark mode toggle
  - Multi-language support
  - Currency converter
  - Reviews and ratings system
  - Travel blog section
  - Newsletter subscription

---

## 📁 Project Structure

```
SafarGo/
├── index.html          # Main landing page
├── listings.html       # Search results page
├── style.css          # Main stylesheet
├── assets/            # Images and media (currently using Unsplash)
└── README.md          # Project documentation
```

---

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Styling and layout
  - Flexbox for flexible layouts
  - CSS Grid for card layouts
  - CSS Variables for theming
  - Media queries for responsiveness
- **FontAwesome 6.4.0** - Icons
- **Google Fonts (Poppins)** - Typography
- **Unsplash** - Placeholder images

---

## 🚀 Setup & Usage

1. Clone or download the repository
2. Open `index.html` in your web browser
3. No build process or dependencies required!

### For Development:
- Use a local server (e.g., Live Server in VS Code) for better development experience
- Modify `style.css` for styling changes
- Update HTML files for content changes

---

## 📱 Browser Compatibility

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ⚠️ IE11 (limited support)

---

## 📝 Notes

- Currently uses Unsplash placeholder images
- Search functionality is simulated (forms submit to listings page)
- No backend or database integration yet
- Designed as a frontend template/prototype

---

## 🎨 Design Decisions

1. **CSS-Only Tabs**: Demonstrates advanced CSS techniques without JavaScript dependency
2. **Mobile-First**: Ensures optimal experience on all devices
3. **Semantic HTML**: Improves SEO and accessibility
4. **Modular CSS**: Easy to maintain and extend
5. **Modern Color Palette**: Professional blue theme with good contrast

---

## 👨‍💻 Future Development Roadmap

### Phase 1: Core Functionality (Current)
- ✅ Static pages with responsive design
- ✅ CSS-only interactive components

### Phase 2: Dynamic Features (Next)
- Add JavaScript for interactivity
- Implement real search functionality
- Add form validation

### Phase 3: Backend Integration
- Connect to API for real data
- User authentication
- Database for bookings

### Phase 4: Advanced Features
- Payment integration
- Email notifications
- Admin dashboard

---

## 📄 License

This project is open source and available for educational purposes.

---

**Last Updated**: January 28, 2026

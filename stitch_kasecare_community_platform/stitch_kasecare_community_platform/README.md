# KacheCare Community Platform

A modern, responsive web platform connecting caregivers with families in need of care services.

## 🌟 Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Built with Tailwind CSS and Material Symbols icons
- **Smooth Navigation**: Interconnected pages with intuitive user flow
- **Verified Caregivers**: Trust and safety badges for all care providers
- **Interactive Elements**: Hover effects, transitions, and micro-interactions

## 📁 Project Structure

```
stitch_KacheCare_community_platform/
├── index.html                          # Entry point (redirects to home)
├── KacheCare_home/
│   ├── code.html                       # Home/Landing page
│   └── screen.png                      # Screenshot
├── join_KacheCare/
│   ├── code.html                       # Sign up/Sign in page
│   └── screen.png                      # Screenshot
├── find_care_dashboard/
│   ├── code.html                       # Care seeker dashboard with caregiver listings
│   └── screen.png                      # Screenshot
├── caregiver_profile_amina_rahman/
│   ├── code.html                       # Individual caregiver profile page
│   └── screen.png                      # Screenshot
├── circular_embrace/
│   └── DESIGN.md                       # Design system documentation
└── design.md                           # Overall design documentation
```

## 🚀 Getting Started

### Option 1: Open Directly
1. Open `index.html` in your web browser
2. You'll be automatically redirected to the home page

### Option 2: Start from Home
1. Navigate to `KacheCare_home/code.html` to view the landing page

### Option 3: Use a Local Server (Recommended)
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using PHP
php -S localhost:8000
```
Then open `http://localhost:8000` in your browser.

## 🗺️ Page Navigation Flow

```
index.html (Entry Point)
    ↓
KacheCare_home/code.html (Landing Page)
    ↓
    ├─→ join_KacheCare/code.html (Sign Up/Sign In)
    │       ↓
    │       └─→ find_care_dashboard/code.html (After registration)
    │
    └─→ find_care_dashboard/code.html (Find Care)
            ↓
            └─→ caregiver_profile_amina_rahman/code.html (View Profile)
```

## 📱 Navigation Elements

### Desktop Navigation (Top Bar)
- **Home**: Returns to landing page
- **Find Care**: Browse available caregivers
- **Find Jobs**: Job listings (placeholder)
- **About**: About page (placeholder)
- **Sign In**: Opens join/sign in page
- **Join Community**: Opens registration page

### Mobile Navigation (Bottom Bar)
- **Home**: Landing page
- **Find Care**: Caregiver dashboard
- **Jobs**: Job listings (placeholder)
- **Profile**: User profile/sign in

## 🎨 Design System

### Color Palette
- **Primary (Forest Green)**: `#00452a` - Trust, safety, growth
- **Secondary (Vibrant Gold)**: `#785900` - Warmth, community
- **Surface (Cream)**: `#fcf9f8` - Clean, approachable background
- **Accent Colors**: Various shades for depth and hierarchy

### Typography
- **Headlines**: Sora (600-800 weight)
- **Body Text**: Inter (400-600 weight)
- **Font Sizes**: Responsive scaling from mobile to desktop

### Key Design Principles
1. **Circular Embrace**: Organic, rounded shapes throughout
2. **Neighborhood Warmth**: Approachable, human-centered design
3. **Verified Trust**: Clear safety indicators and badges
4. **Accessibility**: WCAG compliant color contrasts and interactions

## 🔗 Interactive Features

### Home Page
- Hero section with call-to-action buttons
- Value pillars showcase
- Community testimonials
- Smooth scroll animations
- Parallax background effects

### Join Page
- Role selection (Care Seeker vs Care Provider)
- Dynamic form display
- Password strength indicator
- Social login options
- Form validation ready

### Find Care Dashboard
- Search functionality
- Filter chips for care types
- Caregiver cards with ratings
- Responsive grid layout
- Click-through to profiles

### Caregiver Profile
- Detailed caregiver information
- Trust & safety badges
- Experience timeline
- Service offerings
- Weekly availability calendar
- Client reviews

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom styles and animations
- **Tailwind CSS**: Utility-first CSS framework (via CDN)
- **JavaScript**: Interactive functionality
- **Google Fonts**: Sora & Inter typefaces
- **Material Symbols**: Icon library

## 📝 Notes

- All pages are fully functional with working navigation
- External links (social media, legal pages) are placeholders (`#`)
- Images are loaded from Google's CDN
- No backend required - pure frontend implementation
- Forms are UI-only (no actual submission handling)

## 🎯 Future Enhancements

- Backend integration for user authentication
- Real-time search and filtering
- Booking/scheduling system
- Payment integration
- Messaging between users
- Review and rating system
- Admin dashboard
- Mobile app version

## 📄 License

This project is part of the KacheCare platform. All rights reserved.

---

**KacheCare** - Neighborhood warmth, verified trust. 💚

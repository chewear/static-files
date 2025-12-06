# Koodi - AI Automation & Business Services Website

A modern, responsive website built with Tailwind CSS featuring a Bento-style layout design.

## 📁 Project Structure

```
static-site/
├── index.html                          # Homepage
├── contact.html                        # Contact page with form
├── blog.html                          # Case studies & blog page
├── services/
│   ├── ai-automation.html             # AI & Workflow Automation service
│   ├── integration-api.html           # System Integration & API service
│   ├── web-cms.html                   # Web & CMS Modernization service
│   └── digital-transformation.html    # Digital Transformation Advisory service
└── assets/
    ├── js/
    │   └── main.js                    # JavaScript for interactions
    └── images/                        # Image assets folder
```

## 🎨 Design Features

- **Bento-Style Layout**: Modular grid sections with smooth shapes and generous spacing
- **Accent Color**: #F3BF00 (yellow-gold) used throughout for highlights and CTAs
- **Gradients**: Soft, modern gradients combining #F3BF00 with neutrals
- **Responsive Design**: Mobile-first approach with breakpoints at 480px, 768px, and 1200px+
- **Smooth Animations**: Fade-in effects and hover transitions

## 🚀 Getting Started

### Testing Locally

1. **Open any HTML file directly in your browser**:
   - Navigate to the `static-site` folder
   - Double-click `index.html` to open the homepage
   - All links and navigation work without a server

2. **Test Responsive Behavior**:
   - Desktop: View at 1200px+ width
   - Tablet: View at ~768px width
   - Mobile: View at ≤480px width
   - Use browser DevTools (F12) to test different viewports

3. **Test Mobile Menu**:
   - Resize browser to mobile width (<768px)
   - Click hamburger menu icon (☰)
   - Verify menu opens and closes properly
   - Check all navigation links work

## 📱 Pages Overview

### Homepage (`index.html`)
- Hero section with main value proposition
- Problems section highlighting pain points
- Solutions section with 4 key benefits
- Services overview with 4 service cards
- Why Work With Us section (5 differentiators)
- Case Studies placeholder
- Lead Magnet section
- Final CTA

### Service Pages
Each service page includes:
- Hero with problem statement
- Solutions/services breakdown
- Process steps (5-stage methodology)
- Use cases
- Technical capabilities or features
- FAQ section
- Final CTA

### Contact Page (`contact.html`)
- Contact form (ready for backend integration)
- Why Work With Koodi highlights
- What Happens Next timeline
- Trust indicators

### Blog Page (`blog.html`)
- Featured case study placeholder
- Filter buttons by category
- Case study cards grid
- Placeholder content for future posts

## 🎯 Key Features

### Navigation
- Sticky header that stays visible on scroll
- Dropdown menu for services
- Mobile-responsive hamburger menu
- Active page highlighting

### Forms
- Static HTML forms ready for backend integration
- Client-side validation
- Visual feedback on submission
- Required field indicators

### Interactions
- Smooth scroll for anchor links
- Fade-in animations on scroll
- Hover effects on cards and buttons
- Mobile menu toggle

## 🎨 Tailwind CSS Classes Used

### Layout
- Grid: `grid`, `grid-cols-1`, `md:grid-cols-2`, `lg:grid-cols-3`
- Flex: `flex`, `flex-col`, `items-center`, `justify-center`
- Spacing: `gap-6`, `gap-8`, `space-y-6`, `p-6`, `p-8`, `p-10`

### Bento Style Elements
- Rounded corners: `rounded-2xl`, `rounded-3xl`
- Shadows: `shadow-md`, `shadow-lg`, `shadow-xl`
- Hover effects: `hover:shadow-xl`, `hover:scale-[1.015]`
- Transitions: `transition`, `transition-all`

### Colors
- Accent: `bg-[#F3BF00]`, `text-[#F3BF00]`
- Gradients: `bg-gradient-to-br from-[#F3BF00] to-yellow-200`
- Neutrals: `bg-neutral-50`, `bg-neutral-100`, `text-neutral-700`

## ✅ Acceptance Criteria Compliance

- ✅ Bento-style theme applied consistently
- ✅ All pages open as plain HTML files (no PHP/Laravel needed)
- ✅ All content from PDF document mapped correctly
- ✅ No Lorem ipsum or demo content
- ✅ Working navigation between all pages
- ✅ Responsive at mobile (≤480px), tablet (~768px), and desktop (≥1200px)
- ✅ No horizontal scrolling on mobile
- ✅ Mobile menu functional
- ✅ CTAs and important content readable at all sizes

## 🔧 Customization

### Changing the Accent Color
To change from #F3BF00 to another color:
1. Find/replace `#F3BF00` in all HTML files
2. Update gradient combinations accordingly
3. Adjust hover effects if needed

### Adding Backend to Forms
The contact form is ready for integration:
1. Add `action` attribute to `<form>` tag
2. Set `method="POST"`
3. Configure server endpoint
4. Or integrate with services like Formspree, Netlify Forms, etc.

### Adding Real Content
Replace placeholder sections in:
- Case studies on homepage and blog page
- Team photos or company images in `assets/images/`
- Update text content as needed

## 📞 Support

For questions or support, contact the Koodi team through the contact form on the website.

## 📄 License

© 2025 Koodi. All rights reserved.


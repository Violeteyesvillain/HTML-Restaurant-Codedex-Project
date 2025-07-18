# Violeteyes' - Interstellar Cuisine Website Documentation

A detailed documentation for the space-themed restaurant website, created as a final project for the Codedex HTML course.

## 🎨 Design Overview

### Color Scheme
- **Deep Purple** (`#4a148c`): Headers, footers, primary elements
- **Medium Purple** (`#6a1b9a`): Gradient elements
- **Bright Purple** (`#9c27b0`): Accents, borders
- **Pink** (`#e91e63`): Call-to-action elements
- **Light Gray** (`#f5f5f5`): Background
- **White**: Text and content areas

### Typography
- **Primary Font**: Arial (system font)
- **Headings**: 
  - H1: 1.8em with 2px letter spacing
  - H2: Purple accent with border
  - H3: Deep purple for menu items

### Animations
1. **Rotating Background**
   ```css
   @keyframes rotate {
       0% { transform: rotate(0deg); }
       100% { transform: rotate(360deg); }
   }
   ```
   - 20-second duration
   - Creates cosmic background effect

2. **Fade In Up**
   ```css
   @keyframes fadeInUp {
       from { opacity: 0; transform: translateY(30px); }
       to { opacity: 1; transform: translateY(0); }
   }
   ```
   - Used for header elements
   - Staggered timing for visual interest

3. **Pulse Effect**
   ```css
   @keyframes pulse {
       0%, 100% { transform: scale(1); }
       50% { transform: scale(1.05); }
   }
   ```
   - Applied to profile image
   - 3-second breathing effect

## 🏗️ Core Components

### Page Structure
- **Header**: Animated logo, title, and navigation
- **Menu**: 6 space-themed items with images
- **Order Form**: Interactive form with various inputs
- **Footer**: Simple credit attribution

### Order System
- **Quantity Selection**: Number inputs (min=0)
- **Sides**: 3 options (limit: 3 selections)
- **Delivery**: 3 pricing tiers ($0 - $15.99)
- **Special Requests**: Textarea for instructions

## 🎯 Technical Highlights

### Layout
- CSS Grid for form (2 columns)
- Flexbox for menu (responsive)
- Glass-morphism effects on nav and form
- Mobile-friendly without media queries

### Features
- Form validation
- Responsive images
- Smooth animations
- Accessible inputs

## 🚀 Future Plans

### Immediate Improvements
1. Backend integration
2. Payment processing
3. Order confirmation system
4. Local image storage

### Long-term Features
1. User accounts
2. Order history
3. Real-time tracking
4. Admin dashboard

## 📊 Project Stats
- Size: ~15KB
- Components: 6 menu items, 12 inputs
- Images: Unsplash API
- Animations: 3 custom effects

---

*Created by Violeteyes with support from AI tools as part of the Codedex HTML course final project.*

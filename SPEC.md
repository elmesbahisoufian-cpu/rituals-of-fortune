# Rituals of Fortune - Book Website Specification

## Project Overview
- **Project Name**: Rituals of Fortune (طقوس الحظ) - Poetry Collection Website
- **Type**: Cinematic portfolio/marketing site for a poetry book
- **Core Functionality**: Showcase the poetry collection with immersive Arabic typography and modern design
- **Target Users**: Poetry enthusiasts, literary critics, potential readers

## UI/UX Specification

### Layout Structure
- **Hero Section**: Full viewport cinematic intro with animated Arabic calligraphy
- **About the Book**: Dramatic book description with floating elements
- **The Poet**: Poet's biography with artistic presentation
- **Quotes Gallery**: Floating quote cards with parallax effect
- **Reader Preview**: Interactive book preview section
- **Contact/Get Copy**: Call-to-action for obtaining the book
- **Footer**: Minimal social links and copyright

### Responsive Breakpoints
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

### Visual Design

#### Color Palette
- **Primary**: #1a1a2e (Deep Midnight Blue)
- **Secondary**: #16213e (Dark Navy)
- **Accent**: #e94560 (Crimson Red)
- **Text Primary**: #eaeaea (Off White)
- **Text Secondary**: #a0a0a0 (Muted Gray)
- **Gold Accent**: #d4af37 (Classic Gold)

#### Typography
- **Display Font**: "Aref Ruqaa" (for Arabic headlines) - Google Fonts
- **Body Font**: "IBM Plex Arabic" (for body text) - Google Fonts
- **English Accent**: "Playfair Display" (for English elements)

#### Spacing System
- Section padding: 100px vertical, 5% horizontal
- Component gaps: 2rem standard, 4rem large
- Margins: responsive 1rem - 2rem - 4rem

#### Visual Effects
- Smooth cubic-bezier transitions (0.25, 0.46, 0.45, 0.94)
- Floating/parallax animations on scroll
- Text reveal animations with staggered delays
- Glow effects on accent elements
- Grain texture overlay for artistic depth

### Components

#### 1. Hero Section
- Animated Arabic title: "طقوس الحظ"
- Subtitle: "ديوان شعر للشاعر رشيد الصويلحي"
- Scroll indicator with pulse animation
- Background: Abstract geometric patterns with slow movement

#### 2. Book Description Card
- Book cover image (floating, rotating slightly on hover)
- Descriptive text with Arabic calligraphy borders
- Tags: Poetry, Morocco, Contemporary

#### 3. Poet Section
- Profile image with artistic frame
- Biography text in Arabic and English
- Social media links

#### 4. Quotes Gallery
- 3-5 floating quote cards
- Random rotation (-3deg to 3deg)
- Hover: lift and glow effect
- Staggered entrance animations

#### 5. Preview/Reader Section
- "Read a excerpt" button
- Modal or expandable section with sample poems

#### 6. CTA Section
- "Get Your Copy" button
- Links to: Noor Book, Contact Publisher
- Urgency element: "Limited Edition"

## Functionality Specification

### Core Features
1. Smooth scroll navigation
2. Scroll-triggered animations (fade-in, slide-up, floating)
3. Interactive quote cards with hover effects
4. Book preview modal/expander
5. External links to purchase platforms

### User Interactions
- Scroll: triggers section animations
- Hover on cards: lift + glow + slight rotation
- Click "Read More": expands content
- Click external links: opens in new tab

### Animations (GSAP-style with vanilla JS)
- Hero text: typewriter or letter-by-letter reveal
- Sections: fade-up with stagger
- Floating elements: continuous gentle movement
- Quote cards: parallax on scroll

## Technical Stack
- **Structure**: Semantic HTML5
- **Styling**: Modern CSS3 with CSS Variables
- **Animations**: Vanilla JavaScript with CSS transitions
- **Hosting**: Ready for Vercel/Netlify/GitHub Pages

## Acceptance Criteria
- [ ] Hero section loads with animated Arabic title
- [ ] All sections visible and properly styled
- [ ] Responsive on mobile, tablet, desktop
- [ ] Animations trigger on scroll
- [ ] All external links functional
- [ ] No console errors
- [ ] Page load under 3 seconds
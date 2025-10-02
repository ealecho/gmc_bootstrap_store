# tees&more - Online Store Landing Page

A responsive landing page for an online apparel store featuring modern design, smooth animations, and mobile-first approach.

## Screenshots

### Desktop View
![Desktop Header](screenshots/Screenshot%202025-10-02%20at%2015.16.00.png)
*Hero section with gradient background and navigation*

![Desktop Products](screenshots/Screenshot%202025-10-02%20at%2015.16.09.png)
*Product grid showing 3-column layout*

![Desktop Footer](screenshots/Screenshot%202025-10-02%20at%2015.16.15.png)
*Footer with contact information and links*

### Mobile View
![Mobile View 1](screenshots/Screenshot%202025-10-02%20at%2015.27.11.png)
*Mobile responsive design with hamburger menu*

![Mobile View 2](screenshots/Screenshot%202025-10-02%20at%2015.28.08.png)
*Mobile product cards in single column layout*

## Design Choices

### 1. **Color Scheme**
- **Primary Gradient**: Purple to indigo gradient (`#667eea` to `#764ba2`)
  - Creates a modern, vibrant look that stands out and is applied to header, buttons, and accent elements for brand consistency
- **Neutral Background**: Light gray (`#f8f9fa`) for products section that provides contrast and makes product cards pop
- **Dark Footer**: Charcoal gray (`#2d3748`) 
  - Grounds the design and separates content sections clearly

### 2. **Typography**
- **Font Family**: Public Sans from Google Fonts
  - Modern, geometric sans-serif designed for legibility
  - Professional appearance with excellent readability at all sizes
  - Loaded via Google Fonts CDN for optimal performance
  - Weights used: 300 (Light), 400 (Regular), 600 (Semi-Bold), 700 (Bold)
- **Responsive Font Sizes**: 
  - Desktop: Large, impactful headings (3rem for hero)
  - Mobile: Scaled down appropriately (1.5rem for hero)
  - Ensures readability across all devices

### 3. **Layout & Structure**

#### Header Section
- **Sticky Navigation**: Easy access to menu items while scrolling
- **Hero Section**: Large, centered welcome message with call-to-action
- **Mobile-First Navigation**: Collapsible hamburger menu for small screens (from bootstrap)

#### Products Section
- **Grid System**: Bootstrap's responsive grid (col-12, col-sm-6, col-lg-4)
  - 1 column on mobile (< 576px)
  - 2 columns on tablet (576px - 991px)
  - 3 columns on desktop (> 992px)
- **Card-Based Design**: Uniform product cards with images, descriptions, and pricing
  - Equal height cards using flexbox for visual consistency
  - Clear hierarchy: Image → Title → Description → Price → Call to action

#### Footer
- **3-Column Layout**: About, Quick Links, Contact Info
- **Responsive Stacking**: Columns stack vertically on mobile for better readability

### 4. **Interactive Elements**

#### Hover Effects
- **Product Cards**: Lift up effect (-10px) with shadow on hover providing visual feedback and depth
- **Product Images**: Zoom effect (scale 1.1) on hover
  - Creates engaging, dynamic interaction
- **Navigation Links**: Opacity change for subtle feedback
- **Buttons**: Scale (1.05) and opacity change to makes CTAs feel clickable and responsive

#### Animations
- **Hero Section**: Fade-in-up animation for content
  - Staggered timing (0.8s, 1s, 1.2s) creates elegant entrance draws attention

### 5. **Responsive Design Strategy**

#### Breakpoints
1. **Desktop** (> 992px): Full 3-column layout
2. **Tablet** (768px - 991px): 2 columns, slightly reduced font sizes
3. **Mobile** (< 767px): Single column, optimized spacing
4. **Small Mobile** (< 576px): Further size adjustments for very small screens

#### Mobile Optimizations
- Reduced padding and margins for better utilization of space
- Smaller font sizes to prevent text overflow
- Full-width buttons for easier tapping
- Hamburger menu replaces horizontal navigation (from bootstrap)

### 6. **Framework Integration**

#### Bootstrap 5
- **Grid System**: Powerful responsive layout without custom media queries
- **Navigation Components**: Pre-built, accessible navbar with mobile toggle
- **Utility Classes**: Spacing (g-4), margin auto (ms-auto), responsive columns
- **Benefits**: 
  - Faster development
  - Cross-browser compatibility
  - Accessibility features built-in

#### Custom CSS
- **Visual Identity**: Custom gradients and color scheme
- **Unique Interactions**: Hover effects and animations
- **Fine-tuning**: Precise control over spacing and typography
- **Balance**: Bootstrap for structure, custom CSS for personality

### 7. **User Experience Considerations**

- **Visual Hierarchy**: Clear focal points guide users through content
- **Whitespace**: Generous spacing prevents cluttered appearance
- **Contrast**: High contrast for text ensures readability
- **Touch Targets**: Buttons sized appropriately for mobile touch (min 44px height)
- **Loading Performance**: 
  - Optimized image sources from Unsplash
  - Minimal custom CSS keeps page lightweight

### 8. **Accessibility**

- **Semantic HTML**: Proper use of header, nav, section, footer tags
- **Alt Text**: Descriptive alternative text for all images
- **Color Contrast**: Text meets WCAG standards for readability
- **Keyboard Navigation**: All interactive elements are keyboard accessible
- **Responsive Meta Tag**: Ensures proper rendering on mobile devices


## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom styling with animations and transitions
- **Bootstrap 5**: Responsive framework
- **Google Fonts**: Public Sans font family for modern typography
- **Unsplash**: High-quality product images


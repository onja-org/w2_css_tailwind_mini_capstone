# 🎨 SoundWave Festival 2025 - Design Guidelines

Welcome to the design guidelines for SoundWave Festival! These specifications will help you create a beautiful, cohesive website that celebrates both modern web design and Malagasy culture.

## 🌈 Color Palette

### Primary Colors
- **Festival Red**: `#DC2626` (from the Malagasy flag)
  - Use for: Primary buttons, highlights, "Most Popular" badges
  - Tailwind class: `bg-festival-red`

- **Festival Green**: `#059669` (representing Madagascar's lush nature)
  - Use for: Secondary buttons, success states, accent elements
  - Tailwind class: `bg-festival-green`

- **Festival Orange**: `#EA580C` (like a beautiful Malagasy sunset)
  - Use for: Hover effects, warm accents, special highlights
  - Tailwind class: `bg-festival-orange`

### Neutral Colors
- **Text**: Use `text-gray-900` for headings, `text-gray-700` for body text
- **Backgrounds**: `bg-white`, `bg-gray-50`, `bg-gray-100`
- **Borders**: `border-gray-200`, `border-gray-300`

## 📝 Typography Scale

### Headings
- **Main Title (Hero)**: `text-6xl md:text-8xl font-bold` (very large, bold)
- **Section Titles**: `text-4xl md:text-5xl font-bold` (large, prominent)
- **Subsection Titles**: `text-2xl md:text-3xl font-semibold` (medium, clear)
- **Card Titles**: `text-xl font-semibold` (readable, emphasized)

### Body Text
- **Hero Subtitle**: `text-xl md:text-2xl text-gray-200`
- **Section Descriptions**: `text-lg text-gray-600`
- **Card Text**: `text-base text-gray-700`
- **Small Text**: `text-sm text-gray-500`

### Font Weight
- **Bold**: Headlines, artist names, prices
- **Semibold**: Section titles, button text
- **Regular**: Body text, descriptions

## 📱 Responsive Breakpoints

### Mobile First Approach
Always design for mobile first, then enhance for larger screens.

### Screen Sizes
- **Mobile**: 375px - 767px (base styles, no prefix)
- **Tablet**: 768px - 1023px (use `md:` prefix)
- **Desktop**: 1024px - 1279px (use `lg:` prefix)
- **Large Desktop**: 1280px+ (use `xl:` prefix)

### Grid Systems
- **Artist Cards**: `grid-cols-1 md:grid-cols-2 lg:grid-cols-4`
- **Schedule**: `grid-cols-1 md:grid-cols-3`
- **Pricing**: `grid-cols-1 md:grid-cols-3`
- **Footer**: `grid-cols-1 md:grid-cols-4`

## 🎭 Cultural Elements to Include

### Malagasy Artists (Must Include)
- **Rossy** - Salegy master
- **Tarika** - Traditional fusion
- **Jaojoby** - The King of Salegy
- **Erick Manana** - Contemporary Malagasy
- **Samoëla** - Modern folk

### International Mix
- Balance with global artists to show Madagascar's place in world music
- Genres: Afrobeat, Pop, Electronic, World Music

### Cultural References
- **Venue**: Nosy Be beaches (paradise setting)
- **Language**: Include Malagasy phrases like "Tongasoa" (welcome)
- **Nature**: Reference baobab trees, lemurs, ocean views
- **Heritage**: Celebrate traditional music styles

## 🖼️ Image Specifications

### Hero Background
- **Size**: Minimum 1920x1080px
- **Subject**: Festival crowd or Malagasy beach scene
- **Overlay**: Dark gradient for text readability
- **Suggested URL**: `https://images.unsplash.com/photo-1493225457124-a3eb161ffa5f?ixlib=rb-4.0.3&auto=format&fit=crop&w=2000&q=80`

### Artist Photos
- **Size**: 300x300px (square format)
- **Style**: Professional performance or portrait shots
- **Quality**: High resolution, good lighting
- **Consistency**: Similar style across all cards

### Placeholder Images
Use Unsplash for high-quality placeholders:
- Artist photos: `https://images.unsplash.com/photo-[ID]?w=300&h=300&fit=crop`
- Background: `https://images.unsplash.com/photo-[ID]?w=2000&h=1000&fit=crop`

## 🎨 Visual Effects

### Hover States
- **Cards**: Scale up slightly (`hover:scale-105`)
- **Buttons**: Darken background (`hover:bg-red-700`)
- **Links**: Change color (`hover:text-festival-orange`)
- **Images**: Add subtle glow (`hover:shadow-xl`)

### Transitions
- Always include smooth transitions: `transition-all duration-300`
- Use for: hover effects, color changes, transforms

### Shadows
- **Cards**: `shadow-lg` (default), `shadow-xl` (hover)
- **Navigation**: `shadow-md`
- **Buttons**: `shadow-sm`

## 📐 Spacing & Layout

### Container Widths
- **Main Content**: `max-w-6xl mx-auto` (centered, max width)
- **Text Content**: `max-w-4xl mx-auto` for better readability

### Padding & Margins
- **Sections**: `py-16 px-4` (generous vertical, minimal horizontal)
- **Cards**: `p-6` (comfortable internal spacing)
- **Buttons**: `px-8 py-3` (clickable area)

### Gaps
- **Grid Items**: `gap-6` or `gap-8`
- **Vertical Spacing**: `space-y-4` or `space-y-6`

## 🎯 Interactive Elements

### Buttons
```html
<!-- Primary Button -->
<button class="bg-festival-red hover:bg-red-700 text-white font-semibold px-8 py-3 rounded-lg transition-all duration-300 shadow-sm hover:shadow-md">
    Get Tickets
</button>

<!-- Secondary Button -->
<button class="bg-festival-green hover:bg-green-700 text-white font-semibold px-6 py-2 rounded-lg transition-all duration-300">
    Learn More
</button>
```

### Cards
```html
<div class="bg-white rounded-lg shadow-lg hover:shadow-xl transform hover:scale-105 transition-all duration-300 overflow-hidden">
    <!-- Card content -->
</div>
```

### Links
```html
<a href="#" class="text-gray-700 hover:text-festival-orange transition-colors duration-200">
    Link Text
</a>
```

## ✅ Quality Checklist

### Visual Quality
- [ ] Consistent color usage throughout
- [ ] Proper typography hierarchy
- [ ] Adequate white space
- [ ] Professional image quality
- [ ] Smooth hover effects

### Responsive Design
- [ ] Mobile layout works well
- [ ] Tablet breakpoint functions properly
- [ ] Desktop layout is optimal
- [ ] Text remains readable at all sizes
- [ ] Images scale appropriately

### Cultural Authenticity
- [ ] Malagasy artists prominently featured
- [ ] Cultural references feel natural
- [ ] Color scheme honors flag colors
- [ ] Local venue (Nosy Be) highlighted
- [ ] Respectful representation of culture

### Technical Standards
- [ ] Valid HTML structure
- [ ] Semantic markup used
- [ ] Accessible color contrast
- [ ] Fast loading times
- [ ] Clean, organized code

## 🌟 Pro Tips

1. **Test Early and Often**: Check your design on different screen sizes frequently
2. **Use Real Content**: Replace placeholder text with realistic festival information
3. **Be Consistent**: Stick to the established patterns throughout
4. **Performance Matters**: Optimize images and avoid overly complex layouts
5. **Cultural Sensitivity**: Research Malagasy culture to ensure respectful representation
6. **User Experience**: Think about what festival-goers actually need to know

## 🚀 Stretch Goal Ideas

### Advanced Styling
- CSS gradients for more dynamic backgrounds
- Creative use of Tailwind's transform utilities
- Advanced grid layouts for complex sections

### Enhanced Interactivity
- CSS-only accordions for FAQ section
- Smooth scroll behavior between sections
- Creative button hover animations

### Additional Content
- Artist bio sections with expandable content
- Venue information with maps
- Sustainability and social impact information
- Photo galleries from previous festivals

Remember: The goal is to create a website that makes people excited about attending SoundWave Festival while showcasing the beauty and culture of Madagascar! 🇲🇬
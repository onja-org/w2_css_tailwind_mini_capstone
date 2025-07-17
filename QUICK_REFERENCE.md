# 🚀 SoundWave Festival - Quick Reference Guide

## Getting Started in 3 Steps

1. **Open** `starter-files/index.html` in your text editor
2. **Open** the same file in your web browser
3. **Follow** the instructions in the HTML comments

## 🎯 Your Mission
Build a stunning festival website for SoundWave Festival 2025 in Madagascar using only HTML and Tailwind CSS!

## 📋 Section Checklist

### ✅ Phase 1: Hero Section (45 min)
- [ ] Full-screen background image
- [ ] Dark overlay for text readability
- [ ] Festival title and subtitle
- [ ] Date and location
- [ ] Call-to-action button

### ✅ Phase 2: Navigation (30 min)
- [ ] Sticky navigation bar
- [ ] Logo on the left
- [ ] Menu items on the right
- [ ] Responsive design

### ✅ Phase 3: Artist Lineup (60 min)
- [ ] Section title and description
- [ ] Responsive grid of artist cards
- [ ] Include Malagasy artists (Rossy, Tarika, Jaojoby)
- [ ] Hover effects on cards

### ✅ Phase 4: Festival Schedule (45 min)
- [ ] Three-day schedule
- [ ] Multiple stages/times
- [ ] Mobile-friendly layout
- [ ] Color-coded time slots

### ✅ Phase 5: Ticket Pricing (45 min)
- [ ] Three ticket tiers
- [ ] Prices in Ariary and USD
- [ ] "Most Popular" badge on VIP
- [ ] Feature lists for each tier

### ✅ Phase 6: Footer (30 min)
- [ ] Festival information
- [ ] Quick links
- [ ] Social media links
- [ ] Partners and sponsors

## 🎨 Color Palette

```css
/* Already configured in your HTML! */
festival-red: #DC2626    /* Primary buttons, highlights */
festival-green: #059669  /* Secondary elements */
festival-orange: #EA580C /* Hover effects */
```

## 📱 Responsive Breakpoints

- **Mobile**: No prefix (default)
- **Tablet**: `md:` (768px+)
- **Desktop**: `lg:` (1024px+)
- **Large**: `xl:` (1280px+)

## 🔧 Essential Tailwind Classes

### Layout
```css
/* Containers */
max-w-6xl mx-auto          /* Centered container */
px-4 py-16                 /* Section padding */

/* Grid */
grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4
gap-6                      /* Grid with gaps */

/* Flexbox */
flex items-center justify-center
flex justify-between items-center
```

### Typography
```css
/* Headings */
text-6xl md:text-8xl font-bold     /* Hero title */
text-4xl md:text-5xl font-bold     /* Section titles */
text-xl font-semibold              /* Card titles */

/* Body text */
text-lg text-gray-600              /* Descriptions */
text-base text-gray-700            /* Regular text */
```

### Styling
```css
/* Backgrounds */
bg-white bg-gray-50 bg-gray-900

/* Shadows & Borders */
shadow-lg hover:shadow-xl
rounded-lg
border-l-4 border-festival-red

/* Colors */
text-white text-gray-900
bg-festival-red hover:bg-red-700
```

### Interactive Effects
```css
/* Hover effects */
hover:scale-105
hover:shadow-xl
hover:bg-red-700
hover:text-festival-orange

/* Transitions */
transition-all duration-300
transform
```

## 🇲🇬 Malagasy Cultural Elements

### Featured Artists
- **Rossy** - Salegy Master
- **Tarika** - Traditional Fusion
- **Jaojoby** - King of Salegy
- **Erick Manana** - Contemporary
- **Samoëla** - Modern Folk

### Phrases to Include
- **Tongasoa** - Welcome
- **Misaotra betsaka** - Thank you very much
- **Soa aman-tsara** - Good luck/Congratulations

### Cultural References
- **Location**: Nosy Be beaches
- **Music**: Salegy, Tsapiky, Hiragasy
- **Colors**: Red and green from Madagascar flag

## 🆘 Common Issues & Solutions

### Problem: Text not readable over background image
**Solution**: Add dark overlay with `bg-black/50`

### Problem: Layout breaks on mobile
**Solution**: Use responsive prefixes (`md:`, `lg:`)

### Problem: Images different sizes
**Solution**: Use `w-full h-48 object-cover`

### Problem: No hover effects
**Solution**: Add `hover:` classes with `transition-all duration-300`

## 🔍 Testing Your Work

### Browser Testing
1. Open browser dev tools (F12)
2. Click device icon for mobile view
3. Test different screen sizes
4. Check for console errors

### Visual Checklist
- [ ] Looks good on phone (375px)
- [ ] Looks good on tablet (768px)
- [ ] Looks good on desktop (1024px+)
- [ ] All text is readable
- [ ] Images load properly
- [ ] Hover effects work

## 💡 Pro Tips

1. **Save frequently** - Refresh browser to see changes
2. **Mobile first** - Start with mobile layout, then enhance
3. **Use comments** - Follow the instructions in HTML comments
4. **Test early** - Check responsive design as you build
5. **Be creative** - Add your own touches while meeting requirements

## 🎉 When You're Done

1. **Take screenshots** of your finished website
2. **Test on different devices** if possible
3. **Share with friends and family** - be proud!
4. **Use the checklist** in `tests/visual-checklist.md`

## 🆘 Need Help?

1. **Read the comments** in your HTML file
2. **Check `guidelines.md`** for design specs
3. **Look at solution** (only if really stuck!)
4. **Ask your instructor** - they're here to help!

---

**Remember**: This is YOUR festival website. Make it amazing! 🌟

**Tongasoa sy soa aman-tsara!** (Welcome and good luck!)
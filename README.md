# Coreli Personality Test

A responsive personality type assessment application that works on both mobile (360x800) and desktop (1920x1080) devices.

## Features

- **40 Personality Questions** covering 4 trait dimensions:
  - Justice vs Victory (JV)
  - Stability vs Chaos (SC) 
  - Radiator vs Absorber (RA)
  - Consistency vs Burst (KB)

- **16 Personality Types** with detailed descriptions and insights

- **Responsive Design** optimized for:
  - Mobile devices (360x800 pixels)
  - Desktop screens (1920x1080 pixels)
  - Tablet devices (481px-1024px)

- **Interactive UI** with:
  - Animated progress bars
  - Smooth transitions
  - Modern design elements
  - Accessibility features

## How to Run

1. **Start the local server:**
   ```bash
   # Using Python (Windows PowerShell)
   cd F:\coreli
   python -m http.server 8000
   
   # Or using Python (Command Prompt)
   cd F:\coreli
   python -m http.server 8000
   ```

2. **Open in browser:**
   - Navigate to: `http://localhost:8000`
   - The test will start automatically

## File Structure

- `index.html` - Main test interface (50KB, 1164 lines)
- `result.html` - Results display page (66KB, 1472 lines)
- `images/` - Directory for avatar images (optional)
- `README.md` - This documentation file

## Testing

### Mobile Testing (360x800)
- Use browser developer tools
- Set viewport to 360x800
- Test all interactive elements
- Verify responsive behavior

### Desktop Testing (1920x1080)
- Test on full desktop screen
- Verify larger UI elements
- Check all animations and transitions

### Cross-browser Testing
- Chrome/Chromium
- Firefox
- Safari
- Edge

## Personality Types

The test generates 16 different personality types based on the 4 trait dimensions:

**Justice Seekers (J):**
- JSRK: The Steady Light
- JSRB: The Flare of Hope
- JSAK: The Silent Guardian
- JSAB: The Grounded Spark
- JCRK: The Empathic Leader
- JCRB: The Emotional Beacon
- JCAK: The Thoughtful Idealist
- JCAB: The Gentle Flame

**Victory Seekers (V):**
- VSRK: The Ambitious Organizer
- VSRB: The Dynamic Achiever
- VSAK: The Tactical Thinker
- VSAB: The Quiet Competitor
- VCRK: The Intense Charmer
- VCRB: The Wildfire
- VCAK: The Sharp Recluse
- VCAB: The Unpredictable Force

## Technical Details

- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **Styling:** Bootstrap 5.3.0, Tailwind CSS, Custom CSS
- **Animations:** AOS (Animate On Scroll), Animate.css
- **Icons:** FontAwesome 6.4.0
- **Storage:** LocalStorage for test data persistence
- **Responsive:** CSS Media Queries for device optimization

## Browser Compatibility

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## Performance

- Optimized for fast loading
- Minimal external dependencies
- Efficient CSS and JavaScript
- Responsive images and animations

# Birthday Card Website Specification

## Project Overview
- **Project Name**: Happy 28th Birthday bunda Ojik
- **Type**: Interactive Birthday Card Website
- **Core Functionality**: A celebratory birthday page with animated cake, background music, and heartfelt wishes
- **Target Users**: Birthday celebrant (bunda Ojik) and well-wishers

## UI/UX Specification

### Layout Structure
- **Single Page Design** with centered content
- **Sections**:
  1. Hero Section - Title and greeting
  2. Cake Section - Animated cake with blowing candles
  3. Wishes Section - Clickable area to reveal wishes
  4. Hidden Wishes Modal - Content from Canva link

### Visual Design

#### Color Palette
- **Primary**: #FF6B9D (Pink)
- **Secondary**: #FFE66D (Golden Yellow)
- **Accent**: #4ECDC4 (Teal)
- **Background**: #1A1A2E (Dark Navy) with gradient to #16213E
- **Text Primary**: #FFFFFF (White)
- **Text Secondary**: #F7F7F7 (Off-white)
- **Candle Flame**: #FF9500 (Orange) to #FFD700 (Gold)

#### Typography
- **Title Font**: 'Great Vibes', cursive (elegant handwritten)
- **Body Font**: 'Poppins', sans-serif (modern readable)
- **Title Size**: 4rem (mobile: 2.5rem)
- **Subtitle Size**: 1.8rem
- **Body Size**: 1rem

#### Spacing System
- Section padding: 40px 20px
- Element margins: 20px
- Card padding: 30px

#### Visual Effects
- Floating particles/confetti animation
- Glowing text effect on title
- Pulsing candle flames
- Smooth fade-in animations
- Hover effects on interactive elements

### Components

#### 1. Header/Title Section
- "Happy 28th Birthday" in decorative font
- "bunda Ojik" with special styling
- Subtle floating animation

#### 2. Cake Component (from cake-blow reference)
- Layered cake design (3 tiers)
- Candles on top with animated flames
- "Blow" interaction - click to blow out candles
- Smoke effect when candles are blown out
- Cake decorations (sprinkles, stars)

#### 3. Music Control
- Auto-play background music (Sal Priadi - Bahagia)
- Music note animation
- Mute/unmute toggle button

#### 4. Wishes Section
- Text: "wishes dan yappingnyaaa ada semuanya yaaa, kilik sini heheh"
- Clickable link/button that opens the Canva wishes

#### 5. Footer
- Simple celebration message

## Functionality Specification

### Core Features
1. **Background Music**
   - Auto-play "Bahagia" by Sal Priadi on page load
   - User can mute/unmute
   - Visual indicator of music playing

2. **Cake Animation**
   - Candles with flickering flame animation
   - Click/tap to blow out candles
   - Celebration animation when blown out
   - "Make a wish!" prompt

3. **Wishes Link**
   - Click on wishes text opens Canva design in new tab
   - https://www.canva.com/design/DAG_cRISyOM/9U4nFlaMyNQU3Mo6exLFqA/edit

4. **Visual Effects**
   - Confetti/particle animation
   - Smooth scroll behavior
   - Loading animation

### User Interactions
- Click cake to blow candles
- Click music button to toggle sound
- Click wishes link to view Canva design
- Hover effects on all interactive elements

### Edge Cases
- Handle autoplay restrictions (show play button)
- Responsive on mobile devices
- Graceful fallback if music fails to load

## Acceptance Criteria

1. ✅ Page loads with title "Happy 28 bunda Ojik"
2. ✅ Cake is displayed with animated candles
3. ✅ Clicking cake blows out candles with animation
4. ✅ Background music plays (Sal Priadi - Bahagia)
5. ✅ Music can be muted/unmuted
6. ✅ Wishes text is displayed with link to Canva
7. ✅ Confetti/celebration effects are visible
8. ✅ Responsive on mobile and desktop
9. ✅ All animations are smooth (60fps)
10. ✅ No console errors on page load


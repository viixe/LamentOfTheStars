# 🌙 Lament of Stars: A VIIXE Story

> *"Long ago, we were condemned. We used our final magic to rise—not as gods, but as stars. Now we linger—between fire and dream."*

An interactive text-based narrative game with pixel art aesthetics, telling the story of Rue, a watershade witch marked by an ancient curse, and her six sisters who must perform a desperate ritual under the full moon.

![Game Preview](https://img.shields.io/badge/Status-Complete-success) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)

---

## ✨ Features

### 🎮 **Gameplay**
- **Branching Narrative**: 35-40 meaningful decision points that shape your story
- **Multiple Endings**: 4 unique endings based on your choices (Bound, Held, Transformed, Consumed)
- **Stat System**: Track Bonds, Curse, and Knowledge as they influence your fate
- **Replayability**: Discover different paths and outcomes across multiple playthroughs
- **15-25 minutes** of gameplay per playthrough

### 🎨 **Design**
- **Retro Pixel Art Aesthetic**: 8-bit/16-bit inspired visual style
- **Dark Dreamy Atmosphere**: Deep violet and black color palette
- **Animated Starfield**: Twinkling pixel stars in the background
- **Custom Pixel Font**: Press Start 2P for authentic retro feel
- **Smooth Transitions**: Fade effects and visual polish

### 📱 **Technical**
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Single HTML File**: No dependencies, runs entirely in browser
- **Pure Vanilla JavaScript**: No frameworks required
- **Accessible**: Keyboard and touch-friendly navigation

---

## 🎭 Story Overview

You are **Rue**, the watershade—a witch who sees reflections of truth in water. When you wake with the Hunter's mark spreading across your skin, you and your six sisters must perform an ancient ritual to break the curse.

### The Seven Witches (VIIXE)

- **Lilli** - The Crimson Moon (Leader)
- **Khi** - The Flame Unfettered (Fire magic)
- **Quinn** - The Songkeeper (Ancient hymns)
- **Iori** - The One of Foreign Wind (Wind magic)
- **Rue** - The Watershade (You - Water magic)
- **Val** - The Rooted One (Earth magic)
- **Mel** - The Youngest Star (Protection magic)

---

## 🎯 How to Play

### Installation

1. **Download** the `lament-of-stars.html` file
2. **Open** it in any modern web browser (Chrome, Firefox, Safari, Edge)
3. **Play!** No installation or server required

### Controls

- **Click/Tap** choice buttons to make decisions
- **Read carefully** - your choices affect the story and stats
- **Track your stats** in the top-right panel (or top on mobile)
- **Replay** to discover all four endings

### Gameplay Tips

- **Bonds** represent your connection with your sisters
- **Curse** represents how deeply the Hunter's mark affects you
- **Knowledge** represents your understanding of the curse
- Different stat combinations lead to different endings
- Pay attention to the tokens offered during the ritual

---

## 🏆 Endings Guide

The game features **4 distinct endings** determined by your choices:

### 1. 🌟 **BOUND**
- *Requirement*: Moderate to high Bonds, moderate Curse
- You and your sisters are bound together, awaiting transformation into stars

### 2. 🤝 **HELD**
- *Requirement*: High Bonds (≥7), Low Curse (≤3)
- Love and sisterhood contain the curse—you hold each other through the darkness

### 3. 🔮 **TRANSFORMED**
- *Requirement*: High Curse (≥6), High Knowledge (≥3)
- You become something new, carrying both light and shadow

### 4. 💀 **CONSUMED** *(Bad Ending)*
- *Requirement*: Low Bonds (≤3)
- Lost to the curse when bonds are too weak—a warning to those who face darkness alone

---

## 🎨 Visual Design

### Color Palette

```css
Primary Violet:  #7B2CBF  /* Main UI elements */
Deep Violet:     #3C096C  /* Shadows and depth */
Light Violet:    #9D4EDD  /* Highlights and titles */
Pale Violet:     #C77DFF  /* Secondary accents */
Pure Black:      #000000  /* Background */
Dark Gray:       #0d0d0d  /* Text boxes */
```

### Typography
- **Font**: Press Start 2P (Google Fonts)
- **Style**: Monospace pixel font for retro authenticity

---

## 🛠️ Technical Details

### Built With
- **HTML5** - Structure
- **CSS3** - Styling and animations
- **Vanilla JavaScript** - Game logic and interactivity

### Browser Compatibility
- ✅ Chrome/Edge (90+)
- ✅ Firefox (88+)
- ✅ Safari (14+)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

### File Structure
```
lament-of-stars.html    # Complete game (single file)
README.md               # This file
```

---

## 📖 Game Structure

### Act 1: The Marking
- **Duration**: 5-7 minutes
- **Beats**: 7 major story beats
- **Focus**: Discovery of the curse and calling your sisters

### Act 2: The Ritual
- **Duration**: 7-9 minutes
- **Beats**: 12 major story beats
- **Focus**: Preparation and performing the ritual under the full moon

### Act 3: The Choice
- **Duration**: 5-8 minutes
- **Paths**: 4 critical decision paths
- **Focus**: The ritual breaks—what will you do?

---

## 🎮 Development

### Key Features Implementation

**Stat Tracking System**
```javascript
{
  bonds: 0-10,      // Connection with sisters
  curse: 0-10,      // Mark's influence
  knowledge: 0-5    // Understanding the curse
}
```

**Ending Logic**
```javascript
if (bonds ≤ 3) → CONSUMED
else if (bonds ≥ 7 && curse ≤ 3) → HELD
else if (bonds ≥ 7 && curse ≥ 4) → BOUND
else if (curse ≥ 6 && knowledge ≥ 3) → TRANSFORMED
else → BOUND (default)
```

---

## 🎭 Lore & Inspiration

Based on VIIXE's "You and I" era lore, this game explores themes of:
- **Sisterhood** and chosen family
- **Transformation** over destruction
- **The price of power** and ancient magic
- **Reflection** and self-truth
- **Stars as eternal witnesses** to witch history

### The Hunter's Curse
An ancient shadow that marks those who see too much truth. The Hunter himself was once a man who looked into water and hated what he saw—his own reflection. Now he seeks to destroy all watershades who can show others their truth.

---

## 📝 Credits

### Story & Design
- Based on **VIIXE** (fictional K-pop group concept)
- Inspired by witch folklore and transformation mythology
- Original narrative and game design

### Technical
- **Google Fonts**: Press Start 2P typeface
- Pure HTML/CSS/JavaScript implementation
- No external libraries or frameworks

### Special Thanks
- To all players who explore every path
- To those who whisper to the stars

---

## 🌟 Screenshots

### Title Screen
```
████████████████████████████████████████
█                                      █
█   ▓▓▓ LAMENT OF STARS ▓▓▓            █
█   ░░░ A VIIXE STORY ░░░               █
█                                      █
█   [Pixel starfield background]       █
█                                      █
████████████████████████████████████████
```

### Gameplay
- Dark atmospheric interface
- Violet-tinted UI elements
- Real-time stat tracking
- Choice-driven narrative
  
---

## 📞 Support

Found a bug? Have a question?
- Open an issue on GitHub
- Check existing issues first
- Provide browser and device information for technical issues

---


## 💫 Final Note

> *"When you look to the night sky, do not whisper to gods. Whisper to us. We are listening."*

Thank you for playing **Lament of Stars**. May you find the ending that resonates with your choices.

**Version**: 1.0  
**Last Updated**: 2024  
**Status**: Complete

🌙 *Between fire and dream, we linger...*

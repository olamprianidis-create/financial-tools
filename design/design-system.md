# Design System — Financial Tools

## Brand Identity
Futuristic, bold, edgy, and accessible. High contrast.
Light blue base with deep navy structure and electric yellow CTAs.
Sharp, elegant edges — modern and confident, never bubbly or soft.

---

## Color Palette

### Backgrounds
- Primary Background:   #B4CFE4  (light blue — base for all tools)
- Secondary Background: #476C89  (medium blue — cards, secondary surfaces)
- Surface / Card:       #18476B  (dark blue — primary result boxes, elevated cards)

### Brand Accents
- Yellow (Primary CTA): #E8FF00  (electric yellow — buttons, highlights)
- Green (Positive):     #39FF14  (neon green — positive results, affordable)
- Red (Negative):       #FF3B3B  (red — over budget, unaffordable)

### Text
- Primary Text:         #18476B  (dark blue — body text on light blue background)
- Headers / Labels:     #FFFFFF  (white — section titles, input labels)
- Text on Yellow:       #0D0D0D  (black — text placed on yellow button)
- Text on Dark Blue:    #FFFFFF  (white — text inside dark blue result boxes)
- Text on Medium Blue:  #FFFFFF  (white — text inside medium blue secondary boxes)

### Semantic Colors
- Positive / Good:      #39FF14  (green — affordable, within budget)
- Warning:              #E8FF00  (yellow — borderline, caution)
- Negative / Bad:       #FF3B3B  (red — over budget, unaffordable)

---

## Typography

### Font
- Family: Montserrat (Google Fonts)
- Import: https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700;900&display=swap

### Scale
- Hero / Display:   900 weight, 3rem+    (large title text)
- Section Header:   700 weight, 1.75rem  (tool title, section names) — WHITE
- Label / Input:    600 weight, 1rem     (input field labels) — WHITE
- Body / Helper:    400 weight, 0.95rem  (descriptions, helper text) — DARK BLUE
- Result Output:    700 weight, 2rem+    (calculated result numbers) — WHITE

### Text on Color Rules
- On #B4CFE4 light blue  — use #18476B (dark blue) for body text
- On #18476B dark blue   — use #FFFFFF (white)
- On #476C89 medium blue — use #FFFFFF (white)
- On #E8FF00 yellow      — use #0D0D0D (black — always)
- On #39FF14 green       — use #0D0D0D (black — always)

---

## Border Radius
- Cards / Containers:   border-radius: 12px
- Buttons:              border-radius: 8px   (sharp, elegant — NOT pill-shaped)
- Input Fields:         border-radius: 8px
- Badges / Tags:        border-radius: 6px
- Result Boxes:         border-radius: 10px

---

## Spacing
- Page max-width:       800px, centered
- Section padding:      40px 32px
- Card padding:         28px
- Input gap:            16px
- Between sections:     48px

---

## Components

### Buttons (Primary CTA)
- Background:     #E8FF00
- Text:           #0D0D0D, 700 weight, uppercase
- Border-radius:  8px  (sharp elegant edge — NOT pill)
- Padding:        14px 40px
- Display:        inline-block  (never full width — content-sized + padding)
- No border
- NOT full width on mobile — generous horizontal padding creates breathing room

### Input Fields
- Background:     #FFFFFF  (white — clean contrast against light blue page)
- Border:         1px solid #476C89
- Focus border:   1px solid #18476B
- Text:           #18476B
- Label:          #FFFFFF, 600 weight
- Border-radius:  8px
- Padding:        14px 16px

### Primary Result Box (Featured Number)
- Background:     #18476B  (dark blue)
- Text:           #FFFFFF
- Number color:   #E8FF00  (yellow — makes the key figure pop)
- Border-radius:  10px
- Padding:        28px
- Alignment:      centered

### Secondary Result Boxes
- Background:     #476C89  (medium blue)
- Text:           #FFFFFF
- Border-radius:  10px
- Padding:        20px

### Input Section Card
- Background:     #18476B  (dark blue — groups inputs clearly against light bg)
- Border:         none
- Border-radius:  12px
- Padding:        28px
- Box-shadow:     0 4px 24px rgba(24, 71, 107, 0.2)

### Section Dividers
- Use a 1px solid rgba(24,71,107,0.3) horizontal rule after every section header
- 8px spacing between the header and the rule
- 12px spacing between the rule and the content below
- 40px spacing above each new section
- HTML pattern:
  <h2>Section Title</h2>
  <hr style="border:none; border-top:1px solid rgba(24,71,107,0.3); margin:8px 0 12px 0;">
  [content]

---

## Mobile-First Rules
- Design for mobile viewport first, scale up for desktop
- All layouts single column on small screens
- Buttons: inline-block with padding — never stretch full width on mobile
- Input fields: full width on mobile is fine
- Cards: full width on mobile, max 800px centered on desktop
- Font sizes scale down slightly on mobile (use rem units)
- Touch targets minimum 44px height for all interactive elements

---

## Aesthetic Rules
- Light blue base creates a clean, professional, trustworthy feel
- Dark navy cards and result boxes create depth and hierarchy
- Electric yellow is reserved for the ONE most important action per page
- Green = good financial outcome, Red = bad financial outcome
- Sharp 8px radius on buttons — elegant and confident, never bubbly
- Typography is bold and large — numbers should feel powerful
- Less is more — no clutter, no decoration for decoration's sake
- Section dividers use both a visible line AND spacing for clear hierarchy
- White text on all blue surfaces — never dark text on dark backgrounds

# Project Memory — The Cozy Table by Kâpé Tayo

## What This Site Is
- Restaurant website for Houston's first Filipino coffee shop
- Single `index.html`, all styles inline, Tailwind CDN
- **Dark matcha green aesthetic** — Cormorant Garamond (display) + Jost (body)
- Color scheme changed from brown/espresso to matcha green + gold + cream (May 2026)
- **Image prices always override pasted text prices. Ask user before applying any conflict.**

## Business Info
- **Name:** The Cozy Table by Kâpé Tayo
- **Phone:** (713) 701-2826 — `href="tel:7137012826"`
- **Email:** kapetayohouston@gmail.com
- **Address:** 12012 Wickchester Ln, Suite 110, Houston, TX 77079 (Energy District)
- **Instagram:** @thecozytablehouston
- **DoorDash:** https://www.doordash.com/store/kape-tayo-cafe-energy-district-usa---12012-wickchester-ln-houston-34727841/

## Hours
Mon–Fri: 8:00 AM–4:00 PM · Sat–Sun: Closed

## Menu (7 Tabs — as of May 2026)

### Coffee
Kâpé Filipino $4.99 · Pinoy Cappuccino $5.25 · Cold Brew Coffee $5.25 · Vanilla Iced Coffee $5.50 · MJ's Salted Caramel Latte $5.99 · Vincent's Vanilla Latte $5.99 · Caramel Macchiato $5.99 · Pumpkin Spice Latte $5.99 · Caramel Mocha Iced Coffee $5.99 · Matcha Latte $6.99 · Coffee Frappé $7.99 · Osmena's Ube Coffee Frappé $7.99 *(New)*

### Specialty Drinks
Calamansi Juice $5.99 · Strawberry Matcha Strato Frappé $7.99 · Ube Latte $7.99 · Mango Matcha $7.99

### Smoothies & Shakes *(no powder, no sugar added)*
Blueberry Smoothie $6.99 · Strawberry Smoothie $6.99 · Blueberry Strawberry Smoothie $6.99
Mango Shake $7.99 · Buko Shake $7.99 · Avocado Shake $8.50

### Filipino Breakfast *(served w/ garlic fried rice & egg — all $14.99)*
Longsilog · Tapsilog · Cornsilog · Bangsilog · Tocilog

### Lunch Specials
Shrimp Fried Rice $3.99 · French Fries $4.25 · Egg McMuffin $4.99 · Avocado Toast $6.99 · Spaghetti w/Toast Bread $6.99 · Egg & Sausage Tacos $6.99 · Beef Tacos $6.99 (3 for $12.99) · Oven-Baked Pork Ribs $7.99 · Stir-Fried Noodles & Egg Rolls $10.99 · Chicken Alfredo Pasta $11.99 · Grilled Chicken Avocado Salad $12.99 *(Best Seller)*

### Sandwiches & Burgers *(served w/ regular fries)*
Oven Roasted Chicken Breast Sandwich $6.99 · Smoked Ham Sandwich $6.99 · Cheeseburger $7.99 · BLT Sandwich $8.99 · Smoked Turkey Sandwich $8.99 *(Customer's Fave)* · Grilled Chicken Sandwich $8.99 · Tuna Sandwich $8.99 · Hot & Spicy Baked Buffalo Wings 8pc $8.99

### Desserts & Pastries
Halo-Halo $12.99 · UBE Banana Pancake (ask) · Crema de Fruta $5.99 · Mango Cheesecake $7.99

## Fan Favorites Photo Cards (`#dishes` section)
Images go in `images/` folder — currently show gradient fallback until photos are added:
`ube-frappe.jpg` · `silog-plate.jpg` · `mj-latte.jpg` · `avocado-salad.jpg` · `buffalo-wings.jpg` · `halo-halo.jpg`

## Color Palette (current — Matcha Green + Gold + Cream)
```
--esp:    #0C1A0D   darkest bg
--esp-md: #111F12   medium bg
--esp-lt: #182E1A   lighter surface (dishes section)
--amb:    #CC8030   gold accent (primary)
--amb-lt: #DFA058   gold light
--amb-dk: #A86020   gold dark
--crm:    #F5EAD0   cream text
footer:   #070F08   near-black green
```
Inline rgba channels: bg `rgba(12,26,13,x)` · mid `rgba(17,31,18,x)` · lt `rgba(24,46,26,x)` · gold `rgba(204,128,48,x)` · cream `rgba(245,234,208,x)`

## Tech Notes
- IntersectionObserver scroll-reveal (`.reveal` → `.vis`)
- Live Open/Closed badge uses `America/Chicago` timezone
- Mobile-first; tabs scroll horizontally on small screens
- Server: `node serve.mjs` (port 3000) · Screenshots: `node screenshot.mjs http://localhost:3000`
- Puppeteer: `./node_modules_temp/node_modules/puppeteer`

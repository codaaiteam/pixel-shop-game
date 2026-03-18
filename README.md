# Pixel Shop Game

A Stardew Valley-inspired pixel art clothing shop management game. Build, decorate, and run your own boutique store in a cozy village outlet shopping area.

**Play now:** https://codaaiteam.github.io/pixel-shop-game/

## Gameplay

### Getting Started
1. **Create your character** - customize skin, eyes, hair, shirt, pants, and accessories
2. **Watch the intro cutscene** - the old shopkeeper hands you the keys to the store
3. **Customize your shop** - choose wall and floor colors/styles
4. **Decorate** - place furniture (shelves, racks, mannequins, register, tables, plants, etc.)
5. **Design clothing** - create t-shirts, hoodies, and jackets with colors and graphics
6. **Open for business** - stand near the register to serve customers

### Daily Routine
- Each day lasts a minimum of **1 minute**
- A random number of customers visit each day (not every day sells out)
- Stand near the **cash register** to process payments (10-second timer per customer)
- Leftover clothes stay on display for the next day
- After each day, design more clothes or buy upgrades in the Store

### Customer Types
- **Buyers** - walk to clothing, pick it up, and bring it to the register
- **Browsers** - walk around the store looking at displays, then leave without buying
- **Angry customers** - enter when store is sold out, show a mad face, and walk out
- **Elderly customers** - white-haired customers walk slower with a slight stoop; they prefer solid colors and floral prints

### Special Character: Alyssa
- **Appearance:** Black woman, white hair in a bun, red reading glasses, mint green cardigan, cream undershirt
- Visits the store every other day starting Day 2
- On Day 3, a **mail system** unlocks with a message from `Alyssa_SewingClub@pix.wow`
- If you've made solid/floral clothing, she sends a happy message; otherwise she requests them
- Once known, her name label appears above her sprite in the store

### Mail System
- Unlocks on Day 3 with a tutorial tooltip
- Red notification badge shows unread count
- Email-style interface with sender list and message view
- Alyssa's profile picture is a black cat

### Store System
Buy upgrades with earned money:
- **Supplies** - unlock new graphics (star, heart, skull, lightning, crown) and clothing types (hoodie, jacket)
- **Furniture** - additional shelves and racks (appear in Decor tab after purchase)
- **Decor** - plants, flowers (appear in Decor tab)
- **Clothing** - extra design slots, avatar accessories

### Save Design
- Save clothing designs as reusable templates (unlimited use)
- Name your saved designs
- Access them from the **Saved** tab in inventory
- Click a saved design to produce a copy into your inventory

### Clothing on Mannequins
- T-shirts, hoodies, and jackets each render differently on mannequins
- Clothing fits the mannequin body shape (not just hanging on it)
- Hoodies show hood, kangaroo pocket, and drawstrings
- Jackets show collar, lapels, zipper, and pockets

## Save System
- Progress saves automatically every 30 seconds, after each day, and on page close
- Saves to browser localStorage
- On return: **CONTINUE** (green) or **NEW GAME** (gray)
- Forward compatible - game updates add new content without breaking saves

### What saves:
- Player character and avatar
- Shop layout and furniture placement
- Clothing on shelves/racks/mannequins
- Money, day count, inventory
- Unlocked graphics and clothing types
- Store purchases, decor, avatar clothes
- Mail messages and Alyssa's state
- Saved clothing designs

## Controls
- **Arrow keys** or **WASD** - move player
- **Mouse drag** - move furniture, drag clothing from inventory to furniture
- **Click** - place items, interact with UI

## Tech
- Pure HTML5 Canvas + vanilla JavaScript
- Single `index.html` file (~3500+ lines)
- Procedural pixel art sprite generation with auto-outline
- No dependencies, no build tools

## License
MIT

## Chat History
<img width="372" height="419" alt="Screenshot 2026-03-18 at 10 32 35 AM" src="https://github.com/user-attachments/assets/11fafebe-cd21-4acf-9b25-5d7fc67dfcb7" />
<img width="381" height="466" alt="Screenshot 2026-03-18 at 10 32 46 AM" src="https://github.com/user-attachments/assets/8a782b7b-d298-4dcf-84b1-de8dec513812" />
<img width="380" height="468" alt="Screenshot 2026-03-18 at 10 33 00 AM" src="https://github.com/user-attachments/assets/522fc1e2-c910-4632-82e3-0fbf6990c4db" />



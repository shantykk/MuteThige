# Susan Mute & Co Advocates — Website

Professional single-page website for **Susan Mute & Co Advocates**, a client-centred law firm based in Kiambu, Kenya.

This project combines the best content and structure from the existing Odoo and Hercules sites into a clean, modern, fully editable codebase you can open and modify in VS Code.

---

## Sections

| Section        | Description                                      |
|----------------|--------------------------------------------------|
| **Home**       | Hero with firm positioning, CTA, and key stats   |
| **About**      | Firm story, philosophy, and managing partner     |
| **Practice Areas** | Employment, Corporate Compliance, Family, Litigation, Property, Data Privacy |
| **Expertise**  | Core competencies and values                     |
| **Contact**    | Phone, email, office location + contact form     |

---

## Tech Stack

- **HTML5** — semantic, accessible structure
- **CSS3** — custom properties, responsive grid/flex, no frameworks
- **Vanilla JavaScript** — navigation, smooth scroll, form handling, animations
- **Google Fonts** — Playfair Display (headings) + Inter (body)
- **Font Awesome 6** — icons

No build tools required. Open `index.html` in a browser or use any local server.

---

## Getting Started (VS Code)

1. Unzip the project folder.
2. Open the folder in VS Code:
   ```bash
   code susan-mute-advocates
   ```
3. Install the **Live Server** extension (recommended) and click **Go Live**,  
   or simply open `index.html` in your browser.
4. Edit freely:
   - Content → `index.html`
   - Styles / colours → `css/styles.css`
   - Behaviour → `js/main.js`

---

## Colour Palette

| Token        | Value     | Usage                  |
|--------------|-----------|------------------------|
| Navy         | `#0a1628` | Primary background     |
| Gold         | `#c9a227` | Accents, CTAs, highlights |
| Cream        | `#f8f5f0` | Soft backgrounds       |
| White        | `#ffffff` | Text on dark, cards    |

---

## Contact Details Used

- **Phone:** 0796 416 617 / 0750 448 075  
- **Email:** susanmutelaw@gmail.com  
- **Office:** Kikinga House, 6th Floor, Kiambu Town, Kenya  

Update these in `index.html` (hero, contact section, and footer) as needed.

---

## Form Behaviour

The contact form currently opens the user’s default email client with a pre-filled message addressed to `susanmutelaw@gmail.com`.  

To connect it to a backend (Formspree, Netlify Forms, your own API, etc.), replace the submit handler in `js/main.js`.

---

## File Structure

```
susan-mute-advocates/
├── index.html          # Main page
├── css/
│   └── styles.css      # All styles
├── js/
│   └── main.js         # Interactivity
├── images/             # Place photos / logos here
└── README.md
```

---

## Next Steps You May Want

- Add a professional headshot of Susan Mute in the About or Hero section
- Add a firm logo (replace the text logo)
- Connect the form to a real backend
- Deploy to Netlify, Vercel, GitHub Pages, or your preferred host
- Add Google Analytics / Meta Pixel if desired

---

Built for easy editing and professional presentation.

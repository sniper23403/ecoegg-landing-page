# Eco-Egg COLLAGEN — Landing Page

Single-page site for **Eco-Egg COLLAGEN**, a French-language dietary supplement for joints and tendons (collagen from egg membrane, hyaluronic acid, elastine, chondroitin, vitamin C).

## Preview

Open `index.html` in any browser. No build step, no dependencies.

## Structure

```
.
├── index.html   # standalone build — HTML + CSS + JS + product image all inlined
```

Single-file version: styles, script, and the product photo (base64-encoded JPEG) are embedded directly in `index.html`. Drop it anywhere and it just works — no `assets/`, no `styles.css`, no `script.js` needed.

## Sections

- Hero w/ product shot, CTA to Instagram
- Trust strip (GMP, ISO 22000, HACCP, Made in Algeria)
- Bénéfices (4 benefit cards)
- Formule (ingredient breakdown table + "science card")
- Utilisation / conservation / allergen warning
- FAQ (native `<details>` accordions)
- CTA section
- Footer

## Tech

- Plain HTML5 / CSS3 / vanilla JS — no framework
- Mobile nav toggle, scroll-reveal via `IntersectionObserver`
- Responsive breakpoints at 980px and 640px

## Customization

- Colors/tokens: CSS custom properties in `:root` (`--green-*`, `--gold-*`)
- Contact / CTA link: search for the Instagram URL, replace as needed
- Product image: swap the base64 `src` on the `<img>` in `.hero__visual`, or point it back to a normal file path

## License

Add your license here.

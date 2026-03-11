https://femsigh.github.io/comp484-hw7basehw8-main/

HW6 CheckList

- 1. Populate index.html: Personalized with bio, work experience, education, languages.
- 2. Folders: css/ and images/ are present and correctly linked.
- 3. External stylesheet: <link rel="stylesheet" href="css/styles.css"> in <head>.
- 4. Color palette: Five colors documented at top of CSS and applied to header, footer, sections.
     /\* Color Palette
     tangerine dream: #ff9861ff; (warm orange) - Accent color
     dry sage: #bdcc9bff; (soft green) - Section backgrounds
     aquamarine: #7affd5ff; (mint green) - Header/Footer backgrounds
     pale slate: #bdb0b4ff; (soft mauve) - Body background
     rose kiss: #ff6193ff; (pink) - Secondary accent
     i may of played with it to make it look better on the eyes

\*/

- 5. Google Fonts: Montserrat (headings) and Open Sans (body) loaded with weights 400,600,700.
     /_ href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&family=Open+Sans:wght@400;600;700&display=swap"
     rel="stylesheet" _/
- 6. Font sizes: h1: 4em, h2: 2.2em, h3: 1.5em.
- 7. Font weights: 700 for headings, 600 for company names & nav links, 400 for body text.

HW7 CheckList

- 1. Content wrappers: .content-wrap added to header, work, education, and footer.
- 2. CSS for .content-wrap: max-width:980px, margin:0 auto, padding:50px, overflow:hidden.
- 3. Padding & spacing: h2 { margin-top:0; }, body { margin:0; }, footer text-align:center.
- 4. Contact link styling: .contact-links a with padding:10px; display:inline-block;.
- 5. Box model fix: html { box-sizing: border-box; } at top of CSS.
- 6. Floats in header: Image uses column-narrow; text uses column-wide. Header image has border-radius:50%, aspect-ratio:1/1 for perfect circle, and margin-right:5px.
- 7. Two‑column layout: .column-narrow (40%) and .column-wide (60%) applied to header, job items, and education items.
- 8. Responsive: Media query stacks columns on mobile.

HW8 CheckList

- 1. Fixed navigation menu: <nav class="fixed-nav"> with position:fixed. Links to #home, #experience, #education, #contact. Download link to resumehw8.pdf. No list used.
- 2. Font Awesome icons: CDN included; envelope, LinkedIn, GitHub icons added to footer links. Spacing with .contact-links i { margin-right:20px; }.

/_ rel="stylesheet"
href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" _/

- 3. Background image + gradient: .work-section uses linear-gradient(rgba(189,204,155,0.9), ...) overlay and url("../images/bgkhw8.jpg") center/cover no-repeat. (not working yet)

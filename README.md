# Gabriel Sanchez // Cyberpunk Cybersecurity Portfolio

A responsive, AI-assisted academic portfolio with a cybersecurity operations center aesthetic. Its content focuses on Microsoft Purview, Microsoft 365 data protection, and topics from the **SC-401 learning path**. **The author does not claim to hold SC-401 certification.**

## Features

- Matrix animation implemented with JavaScript Canvas, behind page content
- Accessible Dark/Light toggle with localStorage persistence
- Responsive navigation, hero/profile image, technology stack, and footer
- **9 academic concept projects** with All/Web/App/Design filters (3 per category)
- 3 **explicitly labeled fictional role simulations**, not actual work history
- 3 responsive YouTube videos from Microsoft learning channels + 9 additional commented cards
- HTML5 validated contact form, EmailJS integration prepared for real activation
- SEO descriptions, semantic headings, alt text, reduced-motion support

## Technologies

**HTML5 · CSS3 · Bootstrap 5 · Vanilla JavaScript**. The website's HTML, CSS and JS are all implemented in a single `index.html`. Supporting profile photography is stored in `assets/`.

## Local preview

Open `index.html` in a browser. Keep the `assets/gabriel-profile.png` file at the indicated relative path. Online resources (fonts, Bootstrap, icons, video iframes) require internet access.

## EmailJS configuration REQUIRED before functional-form validation

1. Sign up at https://www.emailjs.com/ and add an email service.
2. Create an EmailJS template with `{{from_name}}`, `{{reply_to}}`, `{{phone}}` and `{{message}}`. Configure the recipient **within EmailJS** to the professor's address `juancito.pena@gmail.com` for the academic test, with his consent.
3. In `index.html`, replace the three placeholder values of `EMAILJS_CONFIG`: `publicKey`, `serviceId` and `templateId`.
4. In EmailJS dashboard, set the approved domains / anti-abuse settings when available; restrict allowed origins appropriately.
5. Publish and send an actual test; verify receipt. No confirmation of real delivery has been obtained yet.

**Never add an SMTP password, API secret or private email credential to the public repository.** EmailJS public keys are designed to appear in client-side code but sending limits and anti-spam controls still matter.

## GitHub Pages

1. Create a public repository `cyberpunk-portfolio-sc401` via GitHub's website; add a README and MIT license or upload the included versions.
2. In **Add file > Upload files**, drag `index.html` and the `assets` folder contents, preserving the relative path `assets/gabriel-profile.png`. Commit from the browser interface.
3. Under **Settings > Pages > Build and deployment**, choose **Deploy from a branch**, `main`, `/(root)`, and Save.
4. Validate the real deployed link and then update the URL below.

**Expected GitHub repository URL (not created yet):** `https://github.com/Gabriel-Sanchez-CB/cyberpunk-portfolio-sc401`

**Expected Pages URL (not live yet):** `https://gabriel-sanchez-cb.github.io/cyberpunk-portfolio-sc401/`

## Vercel

Go to https://vercel.com, log in with GitHub, import the repository and deploy as a static site. Record the final Vercel URL only after deployment.

| Factor | GitHub Pages | Vercel |
|---|---|---|
| Hosting of HTML/CSS/JS | Yes | Yes |
| GitHub integration | Native | Yes |
| Deployment on pushes | Yes | Yes |
| Preview deployments | Limited | Strong preview workflow |
| Serverless features | No built-in backend | Available, not needed for this project |
| Project fit | Main academic deployment | Secondary comparison |

## Screenshots / documentation

The academic PDF file is included with an implementation record and **clearly marked spaces for real browser screenshots and final URLs**. Screenshots and live link evidence must be completed after publishing and testing; they are not fabricated.

## AI tools comparison

ChatGPT (code development) vs. a second platform such as Gemini or Claude (still to be tested). Record real prompt, result, time, outcome and cost; do not claim tests not performed.

## Credits

Microsoft Purview educational videos belong to their original Microsoft creators. Additional online icons/fonts are served from their respective CDNs. The image of Gabriel Sanchez is supplied by the user.

## License

MIT - see [LICENSE](LICENSE).

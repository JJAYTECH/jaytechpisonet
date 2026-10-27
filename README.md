# JAYTECH PISONET WEBSITE (Bisaya Version)

Static multi-page website: HTML + CSS + vanilla JavaScript. Compatible with GitHub Pages. 7 pages: index.html, repairs.html, pisowifi.html, printing.html, shop.html, about.html, contact.html.

## Mga hulagway: JPG tanan

Ang tanang content images anaa sa `assets/images/` ug `.jpg` file tanan. Ang `favicon.svg` kay gamay nga vector icon para sa browser tab, DILI content photo. Kung gusto nimo tanan JPG bisan favicon, pwede ka mag-ilis sa favicon ug iyang `<link rel="icon">`.

**Ilisi lang ang JPG file gamit ang eksaktong parehas nga filename.** Recommended image: 1200x760 (landscape), JPG, under 300 KB kung mahimo. Dili kinahanglan usbon ang HTML.

- hero.jpg — first screen shop/workspace photo
- repairs.jpg, pisowifi.jpg, printing.jpg, shop.jpg, about.jpg — main categories
- documents.jpg, stickers.jpg, souvenirs.jpg, sublimation.jpg, awards.jpg — print categories
- workshop.jpg, computers.jpg, phones.jpg, machines.jpg — service/product categories
- gallery1.jpg, gallery2.jpg, gallery3.jpg — actual sample projects

## Direktang contacts

Gmail: jayrcanete123@gmail.com
Facebook: https://www.facebook.com/bordz.jay.119011

**Inquiry form:** opens the visitor's DEFAULT email client via `mailto:` with prepared subject/body. It **does not automatically send email** because GitHub Pages is static. Some visitors have no default email app; the direct email link and Facebook link are alternatives. For direct Gmail compose without default mail client, replace `mailto:` with a Gmail compose URL or add a form service.

## Upload sa GitHub Pages

1. Create a public GitHub repository (example: `jaytech-website`).
2. Upload **the contents inside this folder** into the root of the repository (not an extra nested folder).
3. Go to Settings > Pages > Build and deployment > Deploy from a branch > main / (root) > Save.
4. Under GitHub Pages Custom domain, enter `jaytechpisonet.com` and Save.
5. Sa Cloudflare DNS, add A records for root (`@`) to the current GitHub Pages IP addresses per GitHub documentation and CNAME `www` to `YOURUSERNAME.github.io` (DNS only first until validated). GitHub's DNS recommendations can change; verify the latest before setup.
6. Wait for DNS validation and enable Enforce HTTPS after GitHub provisions the certificate.

## Customize

- Shop address, cellphone number, hours = wala giimbento; add after verified.
- About page biography/achievements = placeholder text until you provide genuine personal details.
- Product prices, stock, warranty terms = not invented; contact for updated info.
- Edit `assets/css/style.css` to customize theme.
- Any static HTML page will work without server-side PHP or database.
- Test by opening `index.html` locally; email handoff may depend on browser/email settings.

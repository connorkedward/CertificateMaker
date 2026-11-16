# Gift Certificate Maker

A self-contained, single-page tool for creating gift certificates.

Fill in **To**, **From**, **Treatment**, and the issue/expiry dates (expiry defaults to six months after issue), then download the certificate as a **PDF** or **PNG**.

The **Price List** tab makes an A4 price list with the Sole Stories logo. Each treatment is a card with a name, a length in minutes and a price; treatments can be added, removed and reordered (up to 20). **Save list** stores the list in the browser (`localStorage`), and the saved list is loaded automatically the next time the page is opened on that device. Download the list as a **PDF** or **PNG** from the preview.

The saved list belongs to one browser on one device: saving on the iPhone does not change the list on a laptop, and on iPhone the Home Screen icon and Safari each keep their own copy.

## Usage

**Online (works on iPhone/iPad):** https://connorkedward.github.io/CertificateMaker/ — open it in Safari, then Share → Add to Home Screen for an app-style icon. Hosted with GitHub Pages from the `main` branch; pushing to `main` updates the site.

**Offline:** open `index.html` in any modern desktop browser. No install or build step is needed — everything (including [jsPDF](https://github.com/parallax/jsPDF) 2.5.1 and the certificate artwork) is bundled into the one file. An internet connection is only used to load the Google Fonts (Lora, Mulish).

## License notes

jsPDF is included under the MIT license (see the header comment in the HTML file).

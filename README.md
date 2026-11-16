# Gift Certificate Maker

A self-contained, single-page tool for creating gift certificates.

Fill in **To**, **From**, **Treatment**, and the issue/expiry dates (expiry defaults to six months after issue), then download the certificate as a **PDF** or **PNG**.

The **Price List** tab makes an A4 price list with the Sole Stories logo. Edit the ten treatment lines (each one starts with the length and ends with the price, e.g. `60 minutes Swedish Massage full body £50`), then download it as a **PDF** or **PNG**.

## Usage

**Online (works on iPhone/iPad):** https://connorkedward.github.io/CertificateMaker/ — open it in Safari, then Share → Add to Home Screen for an app-style icon. Hosted with GitHub Pages from the `main` branch; pushing to `main` updates the site.

**Offline:** open `index.html` in any modern desktop browser. No install or build step is needed — everything (including [jsPDF](https://github.com/parallax/jsPDF) 2.5.1 and the certificate artwork) is bundled into the one file. An internet connection is only used to load the Google Fonts (Lora, Mulish).

## License notes

jsPDF is included under the MIT license (see the header comment in the HTML file).

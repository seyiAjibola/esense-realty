E-SENSE REALTY WEBSITE

FILES
- index.html: website structure and content
- styles.css: visual design and responsive layout
- app.js: Google Sheets catalogue, filters, mobile navigation and interactions
- assets/: official supplied E-Sense logo, locally stored Nigerian-inspired property images and fallback property image

GOOGLE SHEETS CATALOGUE
1. Create a Google Sheet with these exact column headings in row 1:
   title, location, price, price_display, type, category, bedrooms, specs, status, image
2. Add one property per row.
3. In Google Sheets, use File > Share > Publish to web; select the property sheet and CSV format.
4. Copy the published CSV URL.
5. In app.js, paste it into GOOGLE_SHEET_CSV_URL.

Use transaction values: For Sale, For Rent, Joint Venture.
Suggested category values: Residential, Land, Commercial, Development.
For a property without a public price, use price=0 and price_display=Price on enquiry.
Use full image URLs in the image column.

IMPORTANT BEFORE LAUNCH
The initial catalogue is a concept preview based on publicly visible E-Sense Realty social posts; it does not confirm that any property remains available. Confirm current availability, pricing, title information and all listing details with E-Sense Realty.
The property photographs are illustrative placeholders, not verified images of the listed properties. Replace them with approved property photographs.
Confirm the public telephone/WhatsApp number before publishing as the official company website.

HOSTING
Upload the complete folder to GitHub Pages or another static host. Keep index.html, styles.css, app.js and assets together.

BRAND AND IMAGE UPDATE
----------------------
The header and footer now use the supplied E-Sense Realty logo. The colour theme is based on the logo green and orange. The hero, feature section and sample catalogue use locally stored Lagos/Nigerian-inspired property visuals generated for this demo. Replace demo visuals with the company's approved property photographs before presenting them as actual listings.

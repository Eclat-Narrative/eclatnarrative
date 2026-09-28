# Pending

Open items on the Éclat Narrative site. Remove each entry once it's done.

## Footer "Work" link removed

- **Where:** every footer: all pages plus `sections/footer.html`.
- **Why:** `about.html` and `contact.html` pointed the link to `work.html`, a page that doesn't exist. The link was taken out of all footers for now to keep them consistent.
- **To do:** decide where the link should go, then add it back. Most pages used `index.html#work`, the Work section on the home page, and that link works.

## Privacy Policy and Terms & Conditions need a legal review

- **Where:** `privacy-policy.html` and `terms-and-conditions.html`, linked from every footer.
- **Written from:** how the site actually works: the contact form goes through FormSubmit to Gmail, fonts load from Google, and there are no analytics or cookies. They also cover India's DPDP Act 2023 and name the courts at Lucknow for disputes.
- **To do:** have a lawyer review both pages before relying on them.
- **To do:** update both pages if the site changes: analytics, cookies, ads or a new form service would each need a new line in the Privacy Policy.

## Home page contact section shows a misspelled email

- **Where:** `sections/contact.html`, line 20.
- **Problem:** it displays `eclanarrative@gmail.com`, with the "t" missing. The form itself sends to the correct `eclatnarrative@gmail.com`.

## Rameshwaram Dosa: reel links point to Pista House

- **Where:**
  - `rameshwaram-dosa.html`, Reels tab.
  - `sections/work.html`, home page Work section → Food & Beverage → Rameshwaram Dosa → Reels.
- **Current links:** these came from the Figma file and belong to Pista House reels:
  - `https://www.instagram.com/reel/DWWX6_mkxX5/`
  - `https://www.instagram.com/reel/DW_gBwrEwR7/`
  - `https://www.instagram.com/p/DWyvyIYivoG/`
- **To do:** replace them with the Rameshwaram Dosa reel URLs. Update both files.

## Rameshwaram Dosa: page text written without client input

- **Where:** `rameshwaram-dosa.html`:
  - The two lines under the tabs.
  - The "Authentic. Straight Off the Tawa" section.
  - The "South India, Served Fresh." section.
- **To do:** review the text with the team or client.
- **Stats card:** it shows "100% pure veg, cooked in pure ghee", taken from the brand's own signage and posts. No campaign results were available, so there is no reach or engagement figure. When real numbers exist, change it to match the other brand pages (for example "X accounts reached").

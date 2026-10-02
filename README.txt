MODERN DHARMA - CORRECTED KINDLE LINK PACKAGE

FILES
- index.html
- style.css
- _data/book.yml

WHAT WAS FIXED
1. Restored the missing opening <a> tag.
2. The Amazon URL is now used only as the href and is not displayed as text.
3. The visible label is rendered in the existing Modern Dharma gold micro-navigation style.
4. The link opens in a new tab with rel="noopener noreferrer".
5. book.yml is correctly placed inside the _data folder.

DEPLOYMENT
Copy all three included paths into the repository root, preserving `_data/book.yml`.

For the temporary test, the current URL is:
https://www.amazon.de

When the Kindle listing is live, replace it in `_data/book.yml` with the direct ASIN URL, for example:
https://www.amazon.de/dp/B0XXXXXXXX

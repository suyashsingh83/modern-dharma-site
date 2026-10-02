MODERN DHARMA - KINDLE LINK UPDATE

FILES
- index.html: Updated Book section with a conditional Kindle CTA.
- style.css: Existing CSS plus the new .book-cta styles.
- _data/book.yml: Single source of truth for the Amazon URLs and availability text.

TO ACTIVATE THE KINDLE LINK
1. Open _data/book.yml.
2. Paste the live Amazon Kindle URL into amazon_kindle_url.
   Example:
   amazon_kindle_url: "https://www.amazon.com/dp/XXXXXXXXXX"
3. Change release_note when the Kindle edition is live, for example:
   release_note: "KINDLE EDITION AVAILABLE NOW"
4. Commit and deploy.

If amazon_kindle_url is empty, the Kindle CTA remains hidden and the site continues to show the release note.

FUTURE PAPERBACK
The YAML already includes amazon_paperback_url for the later paperback release. It is not rendered yet, so no extra button appears before that implementation is added.

Added
Responsive image next to the "Our History" section on the homepage (index.html), with a fallback source if the local farm photo isn't available.
CHANGELOG.md to track project history.
Checklist-style "Current Improvements" section in README.md to track completed vs. pending features.
"Project Structure" section in README.md documenting the site's files and folders.
Changed
Extracted all inline <style> blocks from index.html, about.html, services.html, enquiries.html, and contact.html into a single shared stylesheet, styles.css.
Standardized .container max-width to 1200px across all pages (previously 1100px on the homepage only).
Updated the Location section in README.md from future to present tense, since Google Maps integration is now live on the Enquiries and Contact pages.
Updated the domain reference in README.md from www.1Nestpoultry.co.za to www.1nestpoultry.co.za to match the lowercase email address used on the Contact page.
Fixed
Corrected object-position on the new homepage history image so the subject isn't cropped at the top.
Removed a mobile-only order: -1 rule that was pushing the history image above the text on smaller screens.
Fixed a mismatched CSS selector on about.html (footer.site-footer) that didn't correspond to any class in the markup, preventing it from sharing footer styles with the other pages.

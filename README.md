# LapuGo Travel & Tours — Revision 6

Responsive multi-page Cebu tourism website prototype using HTML, CSS, JavaScript and JSON.

## New tour packages

1. Kawasan Canyoneering & Pescador Island Hopping
2. Cebu Safari Day Tour Package
3. Bantayan Island Tour Package — 3 Days / 2 Nights

## Tour buttons

Every tour card has two separate buttons:

- **View Itinerary** → complete itinerary page
- **Inquire** → Book Now / inquiry form

## Media

Revision 6 removes Wikipedia/Wikimedia image URLs from the website and adds Vercel deployment configuration.
New images are sourced from travel blogs/articles/travel photography pages and are shown
with courtesy/source credits and links.

## Videos

- YouTube cards use reliable thumbnail + original-video links to avoid the previous
  YouTube configuration error.
- Bantayan YouTube video supplied by LapuGo is included in the Gallery and Bantayan
  itinerary.
- The homepage uses the supplied TikTok through TikTok's official Embed Player. It uses
  muted autoplay/loop plus viewport play/pause behavior, with a manual Play button as a
  fallback when a browser blocks autoplay.

## Dark mode

The website defaults to dark mode. Use the sun/moon button in the navigation to switch
between dark and light mode. The preference is stored in localStorage.

## Backgrounds

The header and page hero areas use Cebu travel photography. Contact, About, Gallery and
Tour Packages each have a distinct photo-backed hero treatment. The footer also remains
photo-based.

## Vercel deployment

This is a static multi-page website and includes `vercel.json`. Upload the entire project
folder to Vercel (or connect the Git repository) with no build command and no output
directory required. The `.html` page links, JSON data file, CSS, JavaScript, images and
query-string tour pages are all intended to work as static Vercel assets.

The TikTok itself is hosted by TikTok, so Vercel only serves the page/player iframe;
TikTok's own availability and browser autoplay rules still apply.

## Run in VS Code

1. Extract the ZIP.
2. Open the folder in VS Code.
3. Install Live Server.
4. Right-click `index.html`.
5. Choose **Open with Live Server**.

Do not open the website directly using `file://` because the JSON data is loaded with fetch().

## Important

The booking/inquiry forms are front-end prototypes. Connect them to a real email/CRM/backend
before production use.

Third-party photographs remain the property of their respective creators/sites. Credits and
source links are included, but permission/license requirements must be checked before any
commercial/public launch.

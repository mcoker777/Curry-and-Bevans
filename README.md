# Curry and Bevans Ltd. website — Option A

Static multi-page site (Purrfect Sitting layout, recoloured navy / Columbia blue / gold).
No build step needed: upload the contents of this folder to GitHub Pages as-is.

## Pages
- index.html (Home)
- about.html
- services.html
- our-work.html
- contact.html
- privacy.html
- 404.html, robots.txt, sitemap.xml

## Contact details (live)
Phone 01782 596109, info@curryandbevans.com, Unit 2, Willow Row, Longton, Stoke-on-Trent, ST3 2PU, company no. 05643474 (taken from Companies House and the current website). Office hours are Mon to Thu 8:30am to 5pm and Fri 8am to 4:30pm. Please confirm these are still current.

## Still to do before launch
- **Testimonials**: four real client quotes are on the home page, with one repeated on Services. Names and job titles only; client company names are deliberately left out at the client's request, so don't add them.
- **Six sample projects** on Our work: replace with real case studies.
- **Sectors list** on the home page: confirm accuracy.
- **Privacy policy**: review before launch.
- **Social links**: Facebook and Instagram (@curry_and_bevans_ltd) are in the footer on every page and on the Contact page.
- **Stoke City FC**: the Gold Business Club Partner graphic (`images/stoke-city-gold-business-club.jpg`, from the 2024-25 season) is on the Home and About pages, with a mention in the trust strip and footer. Confirm the partnership is current each season.
- **Accreditations**: all 13 logos are shown on the home and About pages from `images/accreditations/`. Confirm every scheme is current before going live (lapsed logos can cause problems with scheme bodies).

## Map
The contact page embeds Google Maps for Unit 2, Willow Row. No API key is needed.

## Photos
Any photo slot without a matching JPG shows the logo badge as a placeholder. To add or swap a photo, drop a JPG into `/images` with the exact filename below and it appears automatically, no code changes needed. Landscape photos around 1600px wide work best. Camera location data has been stripped from the supplied photos.

| Filename | Used on | Current photo |
|---|---|---|
| `hero.jpg` | Home hero | Van side (branding and website) |
| `how-we-work.jpg` | Home, "How we work" | Van front |
| `about-story.jpg` | Home "Since 1986" + About "Our story" | Team photo at darts event (2026) |
| `about-team.jpg` | About, "Our team" | Van front (swap for a team or on-site photo when available) |
| `about-workshop.jpg` | About, "Why clients choose us" | Van side (swap for a project photo when available) |
| `community-match-day.jpg` | About, community strip | Pitchside boards at the bet365 Stadium |
| `community-darts.jpg` | About, community strip | Darts event (2024) |
| `stoke-city-gold-business-club.jpg` | Home + About partnership | Gold Business Club graphic (2024-25) |
| `services-control.jpg`, `services-power.jpg`, `services-install.jpg`, `services-maint.jpg`, `services-data.jpg` | Services, one per group | Branded illustration (swap for real photos when available) |
| `work-1.jpg` to `work-6.jpg` | Our work + home projects | Branded illustration matching each sample project (replace with real project photos) |

## Deploying to GitHub Pages
1. Create a repository and upload everything in this folder (not the folder itself) to the root.
2. Settings > Pages > Deploy from branch > `main` / root.
3. For the custom domain, add it under Settings > Pages (creates a CNAME file) and point the domain's DNS at GitHub Pages.

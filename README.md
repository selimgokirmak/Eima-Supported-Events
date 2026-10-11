## 🤖 [Eima Exhibitor List Scraper](https://apify.com/skython/eima-exhibitor-list-scraper) — Trade Shows, Expos, Fairs & Exhibition Directories

Extract complete exhibitor lists from Eima trade shows — including Eima, Eimacomponenti, Eimadigital, Eimaenergy, Eimagreen, Eimaidrotech — agricultural and gardening machinery, parts, spare parts, and accessories, digital systems, artificial intelligence, and robotics, bioenergy, and water management industries. Scrape company profiles including company details, websites, email, social media links, and product categories. Ideal for B2B lead generation, sales prospecting, market research, event networking, and competitive analysis.

---

## Contents

- [Features](#features)

- [Use Cases](#use-cases)

- [Supported Eima Events (Exhibitor Lists)](#supported-eima-events-exhibitor-lists)

- [Testing Exhibitor List URLs](#testing-exhibitor-list-urls-for-free)

- [Exhibitor List Scraper - All-In-One Version](#exhibitor-list-scraper---all-in-one-version)

- [Data Fields](#data-fields)

- [Example Output](#example-output)

- [My Other Exhibitor List Scrapers](#my-other-exhibitor-list-scrapers)

---

## Features

- Scrape all exhibitor profiles from supported Eima websites

- Extract detailed data from every exhibitor profile page

- Company primary information (address, country, website, email, phone)

- Social media links (LinkedIn, Facebook, Instagram, Twitter)

- Contact person details

- Two output formats (Single-Row & Multi-Row)

- Multi-Row format for Excel-friendly product category filtering

- Export to JSON, CSV, and Excel

---

## Use Cases

- **B2B Lead Generation:** Build targeted contact lists for marketing and sales outreach. 

- **Market Research:** Analyze exhibitors by product categories, brands, and sectors.  

- **Event Networking:** Familiarize yourself with exhibitors before attending trade fairs.  

- **Competitive Analysis:** Track competitor participation and product focus areas.

---

## Supported Eima Events (Exhibitor Lists)

- The following partial list includes Eima exhibitor directory URLs that have been tested so far. Other Eima events or different events with the same website structure may also be supported.

- Some event URLs may have been updated or canceled entirely; please check them before using.

- [Eima International 2026 Exhibitor List – eima.it](https://www.eima.it/en/elenco_espositori.php)

- [Eima Components 2026 Exhibitor List – eimacomponenti.it](https://www.eimacomponenti.it/en/elenco_espositori.php)

- [Eima Digital 2026 Exhibitor List – eimadigital.it](https://www.eimadigital.it/en/elenco_espositori.php)

- [Eima Energy 2026 Exhibitor List – eimaenergy.it](https://www.eimaenergy.it/en/elenco_espositori.php)

- [Eima Green 2026 Exhibitor List – eimagreen.it](https://www.eimagreen.it/en/elenco_espositori.php)

- [Eima Idrotech 2026 Exhibitor List – eimaidrotech.it](https://www.eimaidrotech.it/en/elenco_espositori.php)

---

## Testing Exhibitor List URLs for FREE

- Since I have multiple exhibitor list scraper actors for different types of trade event websites, it might be hard to find the correct actor for your exhibitor list URL.

- Use [**Exhibitor List Scrapers URL Tester**](https://apify.com/skython/exhibitor-list-scrapers-router) actor to test your exhibitor list URLs **for FREE** and see which scraper can process them.

---

## Exhibitor List Scraper - All-In-One Version

- I also provide an **All-In-One** version that combines **my 30+ exhibitor list scrapers** into a single actor.

- Instead of searching for the correct scraper for each event URL, simply provide the event URL and the actor automatically selects the appropriate scraper.

- ➡️ [Exhibitor List Scraper - All-In-One](https://apify.com/skython/exhibitor-list-scraper)

---

## Data Fields

<table>
  <thead>
    <tr>
    <th><span style="font-size:14px;">Company</span></th>
    <th><span style="font-size:14px;">Social</span></th>
    <th><span style="font-size:14px;">Additional</span></th>
    </tr>
  </thead>
    <tbody>
        <tr>
            <td>Profile URL</td>
            <td>LinkedIn</td>
            <td>Hall Stands</td>
        </tr>
        <tr>
            <td>Company Name</td>
            <td>Facebook</td>
            <td>Product Categories</td>
        </tr>
        <tr>
            <td>Address</td>
            <td>Instagram</td>
            <td>Description</td>
        </tr>
        <tr>
            <td>Email</td>
            <td>Twitter / X</td>
            <td>Contact Persons</td>
        </tr>
        <tr>
            <td>Website</td>
            <td></td>
            <td>Represents</td>
        </tr>
        <tr>
            <td>Phone</td>
            <td></td>
            <td></td>
        </tr>
    </tbody>
</table>

---

## Example Output

```json
{
  "___exhibitor_profile_url": "https://www.eima.it/en/92448/argo-tractors-spa",
  "__company_name": "ARGO TRACTORS SpA",
  "_company_address": "Via Matteotti 7, 42042, Fabbrico, (RE), ITALIA",
  "_company_website": "www.argotractors.com",
  "_company_phone": "+39-0522-656111",
  "_company_email": "Federica.galli@argotractors.com",
  "_hall_stands": "Hall 16 - Stand A/9",
  "_social_url_linkedin": "https://it.linkedin.com/company/argotractors",
  "_social_url_facebook": "https://www.facebook.com/argotractorsofficial",
  "_social_url_twitter": "https://x.com/i/flow/login?redirect_after_login=%2FArgoTractors",
  "description": "Argo Tractors is an important industrial Group family owned that designs...",
  "contact_persons": [
    {
      "name": "Antonio Salvaterra",
      "title": "Marketing director",
      "email": "Antonio.salvat****@argotractors.com"
    },
    {
      "name": "Federica Galli",
      "title": "Marketing and Communication dpt",
      "email": "Federica.g****@argotractors.com"
    }
  ],
  "product_categories": [
    "Articulated four-wheel drive tractors",
    "Four-wheel drive tractors, rigid frame",
    "Tractors with rear or four-wheel drive",
    "Tractors with steel tracks",
    "Two-wheel drive tractors"
  ]
}
```

---

## My Other Exhibitor List Scrapers

- [Exhibitor List Scraper - All-In-One](https://apify.com/skython/exhibitor-list-scraper)

- [Koelnmesse Exhibitor List Scraper](https://apify.com/skython/koelnmesse-exhibitor-list-scraper)

- [Messe Frankfurt Exhibitor List Scraper](https://apify.com/skython/messe-frankfurt-exhibitor-list-scraper)

- [Map Your Show Exhibitor List Scraper](https://apify.com/skython/map-your-show-exhibitor-list-scraper)

- [Messe Düsseldorf Exhibitor List Scraper](https://apify.com/skython/messe-duesseldorf-exhibitor-list-scraper)

- [Xporience Exhibitor List Scraper](https://apify.com/skython/xporience-exhibitor-list-scraper)

- [Reed Expo Exhibitor List Scraper](https://apify.com/skython/reed-expo-exhibitor-list-scraper)

- [Messe München Exhibitor List Scraper](https://apify.com/skython/messe-muenchen-exhibitor-list-scraper)

- [Xporience Exhibitor List Scraper V2](https://apify.com/skython/xporience-exhibitor-list-scraper-2)

- [Nürnberg Messe Exhibitor List Scraper](https://apify.com/skython/nuernberg-messe-exhibitor-list-scraper)

- [GSMA MWC Exhibitor List Scraper](https://apify.com/skython/gsma-mwc-exhibitor-list-scraper)

- [Messe Berlin Exhibitor List Scraper](https://apify.com/skython/messe-berlin-exhibitor-list-scraper)

- [AFAG Messe Exhibitor List Scraper](https://apify.com/skython/afag-messe-exhibitor-list-scraper)

- [Messe Stuttgart Exhibitor List Scraper](https://apify.com/skython/messe-stuttgart-exhibitor-list-scraper)

- [Messe Essen Exhibitor List Scraper](https://apify.com/skython/messe-essen-exhibitor-list-scraper)

- [Informa Markets Exhibitor List Scraper](https://apify.com/skython/informa-markets-exhibitor-list-scraper)

- [Informa Markets Exhibitor List Scraper V2](https://apify.com/skython/informa-markets-exhibitor-list-scraper-2)

- [Ungerboeck Exhibitor List Scraper](https://apify.com/skython/ungerboeck-exhibitor-list-scraper)

- [A2Z Events Exhibitor List Scraper](https://apify.com/skython/a2z-events-exhibitor-list-scraper)

- [Deutsche Messe Exhibitor List Scraper](https://apify.com/skython/deutsche-messe-exhibitor-list-scraper)

- [Newfront Exhibitor List Scraper](https://apify.com/skython/newfront-exhibitor-list-scraper)

- [Goeshow Exhibitor List Scraper](https://apify.com/skython/goeshow-exhibitor-list-scraper)

- [EasyFairs Exhibitor List Scraper](https://apify.com/skython/easyfairs-exhibitor-list-scraper)

- [IEG Expo Exhibitor List Scraper](https://apify.com/skython/ieg-expo-exhibitor-list-scraper)

- [The Smarter E Exhibitor List Scraper](https://apify.com/skython/the-smarter-e-exhibitor-list-scraper)

- [Schall Messen Exhibitor List Scraper](https://apify.com/skython/schall-messen-exhibitor-list-scraper)

- [Messe München Exhibitor List Scraper V2](https://apify.com/skython/messe-muenchen-exhibitor-list-scraper-2)

- [Comexposium Exhibitor List Scraper](https://apify.com/skython/comexposium-exhibitor-list-scraper)

- [IME Events Exhibitor List Scraper](https://apify.com/skython/ime-events-exhibitor-list-scraper)

- [ANDMORE Exhibitor List Scraper](https://apify.com/skython/andmore-exhibitor-list-scraper)

- [Comexposium Exhibitor List Scraper V2](https://apify.com/skython/comexposium-exhibitor-list-scraper-2)

- [Informa Markets Exhibitor List Scraper V3](https://apify.com/skython/informa-markets-exhibitor-list-scraper-3)

- [LIVEBUZZ Exhibitor List Scraper](https://apify.com/skython/livebuzz-exhibitor-list-scraper)

- [ASP Events Exhibitor List Scraper](https://apify.com/skython/asp-events-exhibitor-list-scraper)

- [Fortem Exhibitor List Scraper](https://apify.com/skython/fortem-exhibitor-list-scraper)
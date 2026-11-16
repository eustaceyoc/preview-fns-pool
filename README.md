# FNS Pool Service and Repairs, LLC: sample site

A one-page sample site I put together for FNS Pool Service and Repairs, LLC (Flower Mound, TX). It's a concept, not their official website, and it says so at the top of the page and in the footer.

Live preview: https://preview-fns-pool.vercel.app

The request form doesn't send anything to a server. It just opens your own email app with a message addressed to chris@fnspoolservicetx.com, and the phone buttons dial (214) 515-2313. There's no tracking or analytics, and the fonts are self-hosted.

## What's on the page

Only details from FNS Pool Service and Repairs, LLC's own website and public listings: business name, Flower Mound, owner Chris Welch, phone, email, street address, the repair and remodel services and equipment brands listed on fnspoolservicetx.com, and its listed service area. Anything I couldn't confirm is left out or marked to be confirmed. There are no reviews, ratings, prices, years in business or team photos.

## Photos

Stock photos from Pexels, used under the Pexels License (https://www.pexels.com/license/). They're there for mood. None of them shows FNS Pool Service and Repairs, LLC, its people or its work.

- `equipment-gauge.jpg`: "Industrial Pressure Gauge and Piping System" by Kamil Čičila on Pexels (https://www.pexels.com/photo/industrial-pressure-gauge-and-piping-system-39353208/)
- `drained-pool.jpg`: "Empty Swimming Pool" by Stefano Zanet on Pexels (https://www.pexels.com/photo/empty-swimming-pool-10612454/)
- `pool-steps.jpg`: "Sunlit Swimming Pool" by Jan van der Wolf on Pexels (https://www.pexels.com/photo/sunlit-swimming-pool-6952877/)

Fonts: Barlow Condensed, IBM Plex Sans (Google Fonts, SIL Open Font License). Full details are in `assets/provenance.json`.

## Indexing

The page has `noindex, nofollow` in a meta tag and in the `X-Robots-Tag` header (`vercel.json`), and `robots.txt` disallows everything, so it shouldn't turn up in search.

Eustace Crentsil

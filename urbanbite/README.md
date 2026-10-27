# UrbanBite — Restaurant Management System

Enhanced static website created for Hitesh Narula (Thapar College).

## Netlify deployment

This folder is ready to be used as the Netlify base directory. In the existing Netlify project `hiteshnarula-urbanbite`, connect the GitHub repository `hiteshnarula539-droid/consultancy.github.io`, choose branch `main`, and set the **Base directory** to `urbanbite`. The `netlify.toml` in this folder sets the publish directory to `.`. No build command is required for this static HTML site.

## Notes

- Payment integration currently shows a demo/test warning. Do not use it to collect real payments.
- Cart and order history are saved in browser local storage; they are not shared across devices or a central kitchen.

## Enhanced release

- Refined responsive layout and food-card presentation.
- Added menu search, category filters, veg-only filtering, favourites and price sorting.
- Improved cart interactions, saved cart state, order history and print-friendly billing.
- Added About/creator details for Hitesh Narula.

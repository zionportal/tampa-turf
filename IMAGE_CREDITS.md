# Photography sources

Retrieved and license-checked 2026-10-12. No client-owned photos were present in the checkout. These are stock inspiration, not completed Tampa Turf projects, verified products, or endorsements. The lawn and putting surface show grass; they are not evidence of artificial-turf installation or performance.

All three selected photographs were offered as free downloads under the [Unsplash License](https://unsplash.com/license), which permits downloading, modifying, and commercial use. No Unsplash+ or paid assets are included. Attribution is provided voluntarily.

| Local asset | Photographer | Source | Placement |
| --- | --- | --- | --- |
| lawn.webp | Sam Davis | https://unsplash.com/photos/lush-green-lawn-leading-through-a-vibrant-garden-DGQiWCe-xu4 | Hero and residential-lawns card |
| pet.webp | Janosch Jost | https://unsplash.com/photos/a-small-white-dog-running-across-a-grass-covered-field-Z8iaX8woGvY | Pet-friendly-spaces card |
| green.webp | Mick De Paola | https://unsplash.com/photos/LUPJoR3OfEg | Putting-greens card |

The free Mick De Paola download was verified on https://unsplash.com/s/photos/golf-green and resolves to https://images.unsplash.com/photo-1532508583690-538a1436f423 . The other original image endpoints are https://images.unsplash.com/photo-1758922565071-014462d53878 and https://images.unsplash.com/photo-1715329499545-f57d711c8209 .

Local derivatives were auto-oriented, resized without enlargement (1440px hero source; 960px card sources), converted to WebP quality 80, and stripped of source metadata using the existing Sharp dependency. Next.js Image generates responsive srcsets with explicit sizes; the hero is prioritized and card images load lazily. No image host is contacted by the browser for source photos. Existing frames control layout and crop, with no layout-shifting dimensions.

The source photos were visually inspected. Live browser interaction checks were not performed; no local preview server was started.

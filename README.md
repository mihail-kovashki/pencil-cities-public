# Seoul in Pencil

Live at [miko-pencil-cities.vercel.app](https://miko-pencil-cities.vercel.app)

Central Seoul, from Seoul Plaza to Bukchon, drawn as an isometric architectural pencil sheet from open map data. You can turn it, slice the buildings floor by floor, open the close-ups and watch the street life.

This repository holds only the published site: static files, with no build step. Vercel deploys every push to `main`.

- `index.html`: the landing page
- `map/`: the interactive map (`index.html` plus one script per sheet in `map/tiles/`), rendered with three.js r128 (MIT, loaded from cdnjs)
- `vercel.json`: headers for hosting on Vercel

The map is made in a separate private workspace, and each reviewed version is copied here.

## Credits

- Map data © [OpenStreetMap contributors](https://www.openstreetmap.org/copyright), distributed by the Overture Maps Foundation, under the [ODbL](https://opendatacommons.org/licenses/odbl/)
- Some building footprints: Qian Shi et al. 2023, *A first high-quality vector data of buildings in East Asian countries*, [doi:10.5281/zenodo.8174931](https://doi.org/10.5281/zenodo.8174931), [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
- Floors and heights: the building register of the Korean Ministry of Land, Infrastructure and Transport (건축HUB), and measurements in S-Map, Seoul Metropolitan Government
- Some floor counts are estimated

## Licences

- The data inside `map/tiles/` is a derived database of OpenStreetMap and is available under the ODbL. See [DATA-LICENSE.md](DATA-LICENSE.md).
- The drawing, landing page and code are © MiKo. All rights reserved unless a licence file says otherwise.

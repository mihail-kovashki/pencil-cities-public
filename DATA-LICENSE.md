# Data licence

The scene data embedded in `map/tiles/*.js` (building footprints and parts, roads and lanes, land use, street furniture and the attributes derived from them) is a derived database of OpenStreetMap data, obtained through Overture Maps (release 2026-09-23.1).

It is made available under the **Open Database License (ODbL) v1.0**: https://opendatacommons.org/licenses/odbl/1-0/

Any rights in individual contents of the database are licensed under the Database Contents License: https://opendatacommons.org/licenses/dbcl/1-0/

Attribution: © OpenStreetMap contributors, Overture Maps Foundation.

Some footprints come from Qian Shi et al. 2023, doi:10.5281/zenodo.8174931, under CC BY 4.0. Floors and heights were added from the Korean building register (MOLIT 건축HUB, published with no restriction on use) and from measurements in S-Map (Seoul Metropolitan Government).

The data is in the JavaScript files as published. Each `map/tiles/<sheet>.js` file assigns that sheet's scene object.

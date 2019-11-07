## Overview

This document should link to all work happening at the sprint. Links to PR's and proposals

* [Aligned STAC-specific endpoints more with OAF](https://github.com/radiantearth/stac-spec/pull/632) - also mentioned in a related [OAF issue](https://github.com/opengeospatial/ogcapi-features/issues/154).
* [Franklin](https://github.com/azavea/franklin) work ongoing around filling in OFeat / STAC endpoints and an importer. Endpoint progress is visible in the README, open work is visible in the [PRs](https://github.com/azavea/franklin/pulls)
* [Converted search metadata to context object](https://github.com/radiantearth/stac-spec/pull/633) - consolidated search metadata into a context object that the root level of the FeatureCollection. Slimmed down property names.
* [CRUD Extension](https://github.com/radiantearth/stac-spec/pull/634) - Proposal for adding some bulk CRUD capabilities to the `/collections/{collectionId}/items` endpoint. The STAC Transaction extension as it existed before is not quite in alignment with the current OAF proposal for "Simple Transactions" (JSON Merge vs. JSON Patch for PATCHing a single item). Still some discussion/consensus building required.

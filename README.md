# Trove lists metadata

[![Frictionless](https://github.com/GLAM-Workbench/trove-lists-metadata/actions/workflows/frictionless.yaml/badge.svg)](https://repository.frictionlessdata.io/report?user=GLAM-Workbench&repo=trove-lists-metadata&flow=frictionless) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6827077.svg)](https://doi.org/10.5281/zenodo.6827077)

Current version: [v1.2](https://github.com/GLAM-Workbench/trove-lists-metadata/releases/tag/v1.2)

Trove users can create collections of resources using Trove's 'lists'. Metadata describing public lists is available via the Trove API. This dataset was created by harvesting this metadata. To reduce file size, the details of the resources collected by each list are not included, just the total number of resources.

The data was extracted from the Trove API using [this notebook](https://glam-workbench.net/trove-lists/#harvest-summary-data-from-trove-lists) from the [Trove lists and tags](https://glam-workbench.net/trove-lists/) section of the GLAM Workbench.

The data is available as a CSV file entitled `trove-lists.csv` and contains the following fields:

- `created` – date the list was created
- `id` – Trove's unique list identifier
- `number_items` – number of resources in list
- `title` – the title of this list
- `updated` – date the list was last updated

----

This repository is part of the [GLAM Workbench](https://glam-workbench.net/).  
If you think this project is worthwhile, you might like [to sponsor me on GitHub](https://github.com/sponsors/wragge?o=esb).
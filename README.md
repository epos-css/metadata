# Controlled Source Seismics metadata repository

Controlled Source Seismic data are key to understanding the structure and composition of the lithosphere at different scales. They are highly valuable both in their own right and as input to multidisciplinary studies and Earth system modelling. The CSS metadata model provides broad, transnational integration of distributed CSS data through a universal approach to describing controlled source seismic data sets. Developed by a community of experts, it seeks to bring CSS data to the [European Plate Observing System (EPOS)](https://www.epos-eu.org) data research infrastructure. Its comprehensive set of attributes provides a rich description of CSS data sets, allowing the user to _discover_ data sets and to decide whether a data set is fit for the intended re-use purpose or not. To ensure inclusivity, obligatory attributes are limited to essential information, preventing incompatibilities that could exclude potential data providers or legacy data.

The metadata model's implementation, the CSS metadata catalogue, provides [FAIR](https://www.go-fair.org/fair-principles/) and Open scientific metadata for both open and closed CSS data, including details on licensing and legal constraints. For the purpose of maintaining and publishing a metadata catalogue, the model is implemented as [GeoJSON](https://datatracker.ietf.org/doc/rfc7946/), defined by a [JSON-schema](https://json-schema.org/). This initial publication focusses on the metadata model and includes only example data for the metadata catalogue. Future publications will be based on the content of the CSS metadata catalogue and include an up-to-date data model, documentation and quality assurance.

For the purpose of providing data discovery through the EPOS Platform, the metadata model is implemented as a geodatabase with an associated data service. Once the first metadata catalogue is published and the service integrated into the EPOS Platform, the geodatabase will supply its content to the EPOS infrastructure for cross-disciplinary data discovery and integration.

For a detailed account of the motivation, community, and development, refer to the journal publication (DOI: UPDATE BEFORE PUBLICATION).

Files in this release/publication:
- [epos-css-documentation.pdf](./epos-css.schema.json): Documentation of the metadata model.
- [epos-css-schema.json](./epos-css.schema.json): JSON-schema (https://json-schema.org/draft/2020-12) implementing the EPOS-CSS metadata model in GeoJSON.
- [controlled_vocabularies](./controlled_vocabularies/): Folder containing SKOS Turtle files for controlled vocabularies.
- [metadata_catalogue](./metadata_catalogue/): Folder with the EPOS-CSS metadata catalogue in GeoJSON format. This first release includes example metadata for six data instances only.
- [metadata_submission](./metadata_submission/): Folder with two GeoJSON files containing example metadata for one and two data instances, respectively, as expected for new submissions. These files act as standalone metadata catalogues, which are quality-controlled and merged into the main catalogue.

# Support

For questions and support regarding the EPOS-CSS metadata model and catalogue, please submit an issue or
contact the [repository administrator](https://github.com/daoane).

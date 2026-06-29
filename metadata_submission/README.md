# Metadata submission to the metadata catalogue

### How to submit metadata to the Controlled Source Seismic (CSS) metadata catalogue:
1) Compile your metadata according to the CSS metadata model. \
   This can be done directly in GeoJSON with the help of a suitable code editor, or in a spreadsheet or a database. \
   Tip: LLMs can help you to transform your data to GeoJSON if you provide clearly structured input data with unambiguous attribute naming (best to follow the naming of the data model) and a link to the [JSON-schema](../epos-css-schema.json). \
   For existing databases, map their data model to the metadata model and export to the mapped attribute names. In case you have questions, ask for help or guidance (see contact information on the repository page.) 
2) Create a new branch with the name "metadata_<your_individual_name>". Use this branch only for the submission of metadata.
3) Commit your metadata file(s) to the this folder ("metadata_submission") and create a pull request when you are
   satisfied and done with all files.

### After submission, the following will happen:
1) Quality Control (QC). In case there are issues, these will be taken up with you and solved.
2) Your branch will be merged and deleted upon successful QC.
3) Your metadata will be added to the CSS metadata catalogue and the submitted metadata file will be deleted from this folder.
4) The metadata will become "official" and part of associated data service with the next release (publication) of the metadata catalogue.

If you have questions, need help or require submission in a different format (in particular for large data sets), please contact us via the contact information on the repository's main page.
# sampleIngests
Here are some representative sample xml files that were ingested into a Fedora 3 repo via the MIRA batch ingest interface.
The files I selected show the range of content standards we manage.  This includes DCRM(b) for rare books, AARC2 for most digitized books as well as mappings into DC elements from other content providers.

One of the issues to pay attention to is that the dcadesc namespace was used specifically for mapping MARC 6xx. That is, these elements map to traditional subject analysis--the “aboutness” of an item.

Other points to call out—Tisch use the source element for digitized books per the recommendation of Steven J. Miller “The source field should be used only for information identifying the original object from which a digital reproduction was created.”

We use temporal as a subject analysis and spatial to create a geographic name while dcadesc:geogname maps to the 651 and is a subject analysis of the geographic name. i.e., Mexico City (Mexico)--Buildings, structures, etc.



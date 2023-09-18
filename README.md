# Awesome ArchivesSpace

> [ArchivesSpace](http://archivesspace.org/) is an open source, web application for managing archives information. The application is designed to support core functions in archives administration such as accessioning; description and arrangement of processed materials including analog, hybrid, and born-digital content; management of authorities (agents and subjects) and rights; and reference service. The application supports collection management and functions as a metadata authoring tool.

## What is this list?

Awesome ArchivesSpace is an [awesome list](https://github.com/sindresorhus/awesome). It points to resources (code, blog posts, anything with a URL, really) regarding ArchivesSpace created by the community that are dispersed around the web. Resources are loosely categorized by broad topic.

The intended audience for the list is those who have decided to adopt or have already implemented ASpace, both ASpace members and non-members, and need some help on where to go next in a specific area.

This list is not intended to be an exhaustive roadmap to ArchivesSpace implementation, but more as a "resource guide". Inclusion on the list is not an endorsement of any kind.

## Table of Contents

* [Migrations](#migrations)
* [Trainings and Documentation](#trainings-and-documentation)
* [Plug-ins](#plug-ins)
* [Integrations](#integrations)
* [Implementation](#implementation)
* [APIs and Scripts](#apis-and-scripts)

### Contributing to the list

Please help us continue to collect and add relevant sources to Awesome ArchivesSpace. See the [Contributing Guidelines](./contributing.md) for information on how to update this page. 

Awesome ArchivesSpace was initially populated with three categories of resources: Migrations, Plug-ins, and Integrations. Through that work, additional categories of interest were identified:  Implementation, Scripts, and Trainings and Documentation. We encourage the ArchivesSpace community to add links to these categories as well as welcome new category suggestions.

### Not seeing what you need?

Here are some other helpful links:
* For technical details regarding installation of ArchivesSpace, see the [archivesspace GitHub repository](https://github.com/archivesspace/archivesspace).
* ArchivesSpace is supported by a membership community. Learn more: [Why Become a Member of ArchivesSpace?](https://archivesspace.org/community/why-become-a-member), [Member Benefits](https://archivesspace.org/community/member-benefits), and [How to Become a Member](https://archivesspace.org/community/how-to-become-a-member).

### Ownership and credits

The ArchivesSpace community has ownership over Awesome ArchivesSpace. TAC Vice Chair has responsibility for the ongoing maintenance of the list which includes: responding to all pull requests, monitoring the ASpace user group listserv for new content and adding it to the list, taking care of any administrative issues, and initiating an in-depth review of the list by TAC as needed with a minimum recommendation of every two years. Please reach out to the TAC Vice Chair if you have any further questions or suggestions that cannot be handled via a pull request or issue. 

Awesome ArchivesSpace was initially populated by the [Awesome ArchivesSpace Ad Hoc Working Group](https://archivesspace.atlassian.net/wiki/spaces/AC/pages/266797087/Awesome+ArchivesSpace+Working+Group), under the aegis of the Technical Advisory Council, in 2018. The working group was comprised of: Justin Dalton, Christina Luers, Anne Marie Lyons, and Maggie Hughes.

## Migrations
The links below relate to ArchivesSpace migration projects. Resources are loosely grouped by the systems or tools organizations were coming from when migrating to ArchiveSpace. Some links may appear in multiple categories.

### Any legacy database
Links that can be useful for any legacy database:
* ArchivesSpace Tools:
    - [Migration Tools & Data Mapping](https://archivesspace.org/using-archivesspace/migration-tools-and-data-mapping/): Includes the Archivists' Toolkit and Archon migration tools, as well maps and templates for importing and exporting data into and from ArchivesSpace.
    - [Archon Migration Tool](https://github.com/archivesspace/archon-migration): ArchivesSpace Github
    - [Archon Migration Data Mapping](https://docs.google.com/spreadsheets/d/13soN5djk16QYmRoSajtyAc_nBrNldyL58ViahKFJAog/edit?usp=sharing): ArchivesSpace multi-sheet Google Doc
* Yale University ArchivesSpace Migration:
    - [ArchivesSpace @ Yale](https://campuspress.yale.edu/yalearchivesspace/) -- [Migration, step by step](https://campuspress.yale.edu/yalearchivesspace/2015/06/14/migration-step-by-step/) (Maureen Callahan, Yale University): Report of the ArchivesSpace migration at Yale University, including tools that were used, how the migration was organized, and lessons learned.
    - [Yale ArchivesSpace migrationSQL](https://github.com/YaleArchivesSpace/migrationSQL) (Yale University): SQL scripts to help support Yale&#39;s migration to ArchivesSpace.
* [Migrating to ArchivesSpace at UAlbany](https://github.com/UAlbanyArchives/aspacemigration) (Greg Wiedeman, SUNY Albany): Detailed description of, and repository of scripts for, Albany's migration to ASpace.
* Smith College resources:
    - [Smith College Github Aspace Data Remediation](https://github.com/smith-special-collections/aspace-data-remediation): Files, tools, and plans for remediating data for migration to ArchivesSpace at Smith. 
    - [Smith College Github ASpace Migration - Files, tools, and plans](https://github.com/smith-special-collections/aspace-migration): Files, tools, and plans for bringing legacy data into ArchivesSpace at Smith.
* [Columbia University Libraries Migration to ArchivesSpace](https://journal.code4lib.org/articles/14871) (David W. Hodges and Kevin Schlottmann, CUL): Article describing a data migration from several sources - EADs, MARC records, Archivists Toolkit - to ArchivesSpace using Python scripts and API processes.
* [Michigan State University Libraries Repository Migration](https://gitlab.msu.edu/msu-libraries/public/archivesspace-merger) (MSU Libraries): A SQL script and process documentation for migrating a repository from one ArchivesSpace instance into another instance.

### Archivists' Toolkit
* Yale University ArchivesSpace Migration:
    - [ArchivesSpace @ Yale](https://campuspress.yale.edu/yalearchivesspace/) -- [Migration, step by step](https://campuspress.yale.edu/yalearchivesspace/2015/06/14/migration-step-by-step/) (Maureen Callahan, Yale University): Report of the ArchivesSpace migration at Yale University, including tools that were used, how the migration was organized, and lessons learned.
    - [Yale ArchivesSpace migrationSQL](https://github.com/YaleArchivesSpace/migrationSQL) (Yale University): SQL scripts to help support Yale's migration to ArchivesSpace.
* [Migration Tools & Data Mapping](https://archivesspace.org/using-archivesspace/migration-tools-and-data-mapping/): Includes the Archivists' Toolkit and Archon migration tools, as well maps and templates for importing and exporting data into and from ArchivesSpace.
* Bits & Bytes (Patrick Galligan, Rockefeller Archive Center): RAC blog posts about ArchivesSpace migration
    - [From AT to ArchivesSpace Part 1: Installation and Cleaning Data for Migration](http://blog.rockarch.org/?p=1265)
    - [From AT to ArchivesSpace Part 2: Migrations and Error Reporting](http://blog.rockarch.org/?p=1289)
    - [From AT to AS Part 3: Training and Customization](http://blog.rockarch.org/?p=1300)
* [Migrating from Archivists' Toolkit to ArchivesSpace](https://sites.google.com/site/ccdarchivesspace/pacifics-migration-from-at--as) (Eva Guggemos, Pacific University): Report of the stages of Pacific University's migration from AT to ArchivesSpace
* [Migrating to ArchivesSpace](https://teaspoon-consulting.com/articles/migrating-to-archivesspace.html) (Mark Triggs, Teaspoon Consulting): Migration from Archivists' Toolkit to ArchivesSpace
* [Archivists' Toolkit Cleanup and Migration Preparation](https://www.orbiscascade.org/programs/ulc/archives-and-manuscripts-collections/archivesspace/at-migration-preparation/) (Orbis Cascade Alliance): Detailed review of preparing Archivists&#39; Toolkit data for migration to ArchivesSpace. Click on the 'AT Cleanup and Migration Preparations' link to access the document.
    
### Archon
* Yale University ArchivesSpace Migration:
    - [ArchivesSpace @ Yale](https://campuspress.yale.edu/yalearchivesspace/) -- [Migration, step by step](https://campuspress.yale.edu/yalearchivesspace/2015/06/14/migration-step-by-step/) (Maureen Callahan, Yale University): Report of the ArchivesSpace migration at Yale University, including tools that were used, how the migration was organized, and lessons learned.
    - [Yale ArchivesSpace migrationSQL](https://github.com/YaleArchivesSpace/migrationSQL) (Yale University): SQL scripts to help support Yale's migration to ArchivesSpace.
* ArchivesSpace Tools:
    - [Migration Tools & Data Mapping](https://archivesspace.org/using-archivesspace/migration-tools-and-data-mapping/): Includes the Archivists' Toolkit and Archon migration tools, as well maps and templates for importing and exporting data into and from ArchivesSpace.
    - [Archon Migration Tool](https://github.com/archivesspace/archon-migration): ArchivesSpace Github
    - [Archon Migration Data Mapping](https://docs.google.com/spreadsheets/d/13soN5djk16QYmRoSajtyAc_nBrNldyL58ViahKFJAog/edit?usp=sharing): ArchivesSpace multi-sheet Google Doc
* University of Houston Reports:
    - [Data in Flight: Preparing Legacy Finding Aids for Migration](http://www.bluetoad.com/publication/?i=469794#%7B%22issue_id%22:469794,%22page%22:0) (Matthew Richardson, Houston Public Library, and Bethany Scott, University of Houston): Discussion of the challenges with migrating from Archon to ArchivesSpace.
    - [Migration as motivation: upgrading legacy finding aids in preparation for ArchivesSpace](https://uh-ir.tdl.org/uh-ir/bitstream/handle/10657/2014/RichardsonScott_SAA_2017_ASpace_poster_final.pdf?sequence=1&amp;isAllowed=y) (R. Matthew Richardson and Bethany Scott, University of Houston): Poster presentation on migrating from Archon.

### Re:Discovery
* Yale University ArchivesSpace Migration:
    - [ArchivesSpace @ Yale](https://campuspress.yale.edu/yalearchivesspace/) -- [Migration, step by step](https://campuspress.yale.edu/yalearchivesspace/2015/06/14/migration-step-by-step/) (Maureen Callahan, Yale University): Report of the ArchivesSpace migration at Yale University, including tools that were used, how the migration was organized, and lessons learned.
    - [Yale ArchivesSpace migrationSQL](https://github.com/YaleArchivesSpace/migrationSQL) (Yale University): SQL scripts to help support Yale&#39;s migration to ArchivesSpace.
* [Migration Scripts](https://github.com/duspeccoll/migration_scripts) (University of Denver): Migration scripts from Re:Discovery to ArchivesSpace.

### EAD or Homegrown database
If you are migrating from  EAD or a Home Grown database, you may find these links useful:

* Yale University ArchivesSpace Migration:
    - [ArchivesSpace @ Yale](https://campuspress.yale.edu/yalearchivesspace/) -- [Migration, step by step](https://campuspress.yale.edu/yalearchivesspace/2015/06/14/migration-step-by-step/) (Maureen Callahan, Yale University): Report of the ArchivesSpace migration at Yale University, including tools that were used, how the migration was organized, and lessons learned.
     - [Yale ArchivesSpace migrationSQL](https://github.com/YaleArchivesSpace/migrationSQL) (Yale University): SQL scripts to help support Yale's migration to ArchivesSpace.
* [Legacy EAD Import into ArchivesSpace](http://archival-integration.blogspot.com/2015/04/legacy-ead-import-into-archivesspace.html) (Dallas Pillen, Bentley Historical Library): Review of the trial-and-error actions taken to import legacy data EADs into ArchivesSpace.
* Migrating to ArchivesSpace Blog Series on Chaos → Order (Cassie Schmitt): Discusses mapping and cleaning data
    - [Beast tables and relationships](https://icantiemyownshoes.wordpress.com/2014/02/24/beast-tables-and-relationships/)
    - [Accession record mapping](https://icantiemyownshoes.wordpress.com/2014/03/04/accession-record-mapping/)
    - [Clean up: Inclusive and bulk dates comparison](https://icantiemyownshoes.wordpress.com/2014/03/12/clean-up-inclusive-and-bulk-dates-comparison/)
    - [Date formats](https://icantiemyownshoes.wordpress.com/2014/03/19/date-formats/)
    - [Clean up: Date instructions for accession records](https://icantiemyownshoes.wordpress.com/2014/03/25/clean-up-date-instructions-for-accession-records/)
    - [Cleanup: Dates and OpenRefine](https://icantiemyownshoes.wordpress.com/2014/04/24/clean-up-dates-and-openrefine/)
* [Migrating to ArchivesSpace at UAlbany](https://github.com/UAlbanyArchives/aspacemigration) (Greg Wiedeman, SUNY Albany): Detailed description of, and repository of scripts for, Albany's migration to ASpace.
* [The Devil's Shoehorn: A case study of EAD to ArchivesSpace migration at a large university](http://journal.code4lib.org/articles/12239) (Dave Mayo and Kate Bowers, Harvard University): Case study about Harvard University&#39;s migration of over two decades' worth of EAD files into ArchivesSpace.
* [Archivists' Toolkit Cleanup and Migration Preparation](https://www.orbiscascade.org/archivists-toolkit-cleanup-and-migration-preparation) (Orbis Cascade Alliance): Detailed review of preparing Archivists&#39; Toolkit data for migration to ArchivesSpace. Click on the 'AT Cleanup and Migration Preparations' link to access the document.
* [From Silos to (Archives)Space: Moving Legacy Finding Aids Online as a Multi-Department Library Collaboration](http://readingroom.lib.buffalo.edu/readingroom/PDF/vol1-issue2/From-Silos-to-Archives-Space.pdf) (Paromita Biswas and Elizabeth Skene, Western Carolina University): "Prior to 2014, finding aids from Hunter Library's Special Collections did not have a publicly accessible online presence and resided as Microsoft Word documents on an internal library server. In 2014, Hunter Library began transferring these finding aids to ArchivesSpace, an open source archives information management application. ArchivesSpace allowed librarians to publish and export EAD finding aids on the web. This article discusses the project as an interdepartmental collaboration among Special Collections, Cataloging, and Digital Projects. The authors consider this paper useful as a workflow model for libraries which lack technical infrastructure but want to transfer legacy collection descriptions to ArchivesSpace."
* [Olivia and the Great Migration](https://docs.google.com/presentation/d/1cBrd8qzHK4i8S6SQ_vDlScERixX95lAbE__hd48yIDg/edit#slide=id.g23ed42e943_0_176) (Olivia Solis, Briscoe Center for American History): Briscoe Center for American History migration to ArchivesSpace from EADs and internal accession records.
* Bria Parker, University of Maryland: Migration from an Access Database
    - [Managing Archival Metadata Migration (is Maddening)](https://drum.lib.umd.edu/handle/1903/19210): Presentation about migrating records from an Access database into ArchivesSpace.
    - [How I learned to stop worrying and love the API](https://icantiemyownshoes.wordpress.com/2015/11/20/how-i-learned-to-stop-worrying-and-love-the-api/): Discusses migrating from a local MS Access database to ArchivesSpace using the CSV importer and API.
* Smith College resources:
    - [Smith College Github Aspace Data Remediation](https://github.com/smith-special-collections/aspace-data-remediation): Files, tools, and plans for remediating data for migration to ArchivesSpace at Smith.
    - [Smith College Github ASpace Migration - Files, tools, and plans](https://github.com/smith-special-collections/aspace-migration): Files, tools, and plans for bringing legacy data into ArchivesSpace at Smith.
* [Steady converts CSV into EAD XML](http://steady2.herokuapp.com/) (Jason Ronallo, NCSU Libraries): This tool converts CSV resource records into EAD XML.
* [Columbia University Libraries Migration to ArchivesSpace](https://journal.code4lib.org/articles/14871) (David W. Hodges and Kevin Schlottmann, CUL): Article describing a data migration from several sources - EADs, MARC records, Archivists Toolkit - to ArchivesSpace using Python scripts and API processes.
    
## Plug-ins
The links below relate to ArchivesSpace plug-in projects. Resources are loosely grouped by whether the plug-in involves importing or exporting data, searching, administration, authentication, and additional front-end and back-end functionality. Some links may appear in multiple categories.

### Import/Export Data

* [Plugins and Scripts from UNLV](https://github.com/UNLV-Libraries/ArchivesSpace-authority-project) (University of Nevada, Las Vegas Libraries): Includes plugins to use custom PDFs for different repositories, [customization of the default MARCXML export](https://github.com/l3mus/ArchivesSpace-authority-project/tree/master/unlv_marc_exporter), spawn a number of accession records at once into resource records, and an overlay function that that allows for more granular record merging.
* [Harvard ASpace Excel Import plugin](https://github.com/harvard-library/aspace-import-excel) (Harvard Library): Supports the bulk uploading via Excel Spreadsheet of Archival Objects and (optionally) their associated Creator Agents, Top Containers, Subjects, Digital Objects, etc.
* [Import Agent Records with LCNAF Import Plug-in](https://docs.archivesspace.org/Default.htm#AgentsImportLCNAF.htm) (ArchivesSpace): Information from the ArchivesSpace membership documentation about creating agent records using the Library of Congress Name Authority File plugin.
* [ArchivesSpace @ NYU: Local Development](https://guides.nyu.edu/archivesspace/development) (New York University): Provides information and access to locally-developed plugins, including an EAD export customization plugin, a plugin for location management (pre-ArchivesSpace v.1.5.0), a MARC record export plugin, and a digitization work order plugin and digital object creation tool.
* [MOMA EAD Importer](https://github.com/quoideneuf/moma-ead-importer) (Brian Hoffman): Custom ArchivesSpace EAD Importer for MOMA EADs. Theses customizations are specific to version 1.0.9 of ArchivesSpace and may not work with later versions.
* [Yale EAD Exporter Plugin Example](https://github.com/archivesspace-labs/yale-ead-exporter) (Developer house at code4lib 2015): It shows how to tweak the EAD converter. In this example, Yale wanted to add container barcode\_1 to the EAD container @label attribute with the convention of "LABEL BARCOD" (e.g., "text 1234").
* [OCLC Import](https://github.com/hudmol/aspace_oclc) (Hudson Molonglo): Search OCLC records and choose which ones to import into ArchivesSpace as Accession records.
* [Custom MARC Exporter](https://github.com/lorawoodford/custom-marc-exporter) (Lora Woodford): Sample custom MARC exporter demonstrated at the 2018 Code4Lib pre-conference workshop. Enables customizations to MARC exporter for country codes, descriptive cataloging forms, cataloging sources, dates, and locations.

### Search

* [NCSU Search Title Boost](https://github.com/NCSU-Libraries/archivesspace_search_title_boost) (NCSU Libraries): Boosts exact matches on title field - improves precision of search queries from linked record fields (linked agents, subjects, etc.). Note that this functionality can now be implemented by customizing the Solr parameters via the ArchivesSpace config file.
* Search Identifier plugins:
    - [Search Identifier](https://github.com/duke-libraries/archivesspace-duke-plugins/tree/master/plugins/aspace-search-identifier) (Duke University Libraries): Adds the identifier column to search and advanced search results pages for a number of different records.
    - [Search Identifier](https://github.com/lyrasis/aspace-search-identifier) (LYRASIS): Adds an identifier column to search and advanced search results pages in the staff interface.
    - [ArchivesSpace Advanced Search Extension](https://github.com/hudmol/extended_advanced_search) (Hudson Molonglo): This is an ArchivesSpace plugin to extend the advanced search to index and allow searching on a series of record fields as specified by Yale University.

### Administration

* [ArchivesSpace System Performance Monitor](https://github.com/hudmol/system_performance_monitor) (Hudson Molongo): This plugin detects configuration issues that might be causing your ArchivesSpace instance to be running a little more sluggishly than it should.
* [ArchivesSpace Data Checker plugin](https://github.com/hudmol/asck) (Hudson Molonglo): This plugin introduces a new background job that checks the data in an ArchivesSpace instance. It reports on the number of records found and how many are invalid or throw errors.
* [A Plug-in Manager Plug-in for ArchivesSpace](https://github.com/hudmol/plugman) (Hudson Molonglo): Lists installed plugins and provides a directory listing of published plugins.
* [Accessions summary reports](https://github.com/hudmol/accessions_summary_reports) (Hudson Molonglo): An ArchivesSpace plugin that provides summary reports on Accessions.
* [Extended Reports](https://github.com/quoideneuf/extended_reports) (Brian Hoffman): Add customized reports to ArchivesSpace.

### Authentication

* [Oauth plug-in](https://github.com/lyrasis/aspace-oauth) (Mark Custer/LYRASIS): Configure ArchivesSpace as a service provider for oauth user authentication.
* [ArchivesSpace authentication with OmniAuth/CAS](https://github.com/dartmouth-dltg/aspace-omniauth-cas) (Dartmouth University): An ArchivesSpace plugin to provide OmniAuth/CAS single-sign-on authentication.

### Additional Back-end Functionality

* [NCSU Delete Button Context Plugin](https://github.com/NCSU-Libraries/archivesspace_delete_button_context_plugin) (NCSU Libraries): Changes the label on the 'Delete' button in the record toolbar to indicate the type of record being deleted.
* [Payments Module](https://github.com/hudmol/payments_module) (Hudson Molonglo): Payments subrecord for accession records.
* [Alma/ArchivesSpace Integrations Plugin](https://github.com/duspeccoll/alma_integrations) (University of Denver): Based on the resource record provided by the user, this integration will perform API calls to check for a BIB with the Resource's MMS ID, check for holdings associated with the BIB identified by that MMS ID, and add new holdings. If no MMS ID is present, a new BIB will be created. Additionally, users can sync changes to a Resource in ArchivesSpace.  Built on the Top Container functionality.
* Generating Accession identifiers:
    - [Custom Accession Identifiers](https://github.com/quoideneuf/aspace_yale_accessions) (Brian Hoffman): Creating custom accession identifiers. Users with &quot;Manage Repository&quot; permissions will see a new menu item in the Repository settings menu (click the gear icon to the right of the selected repository). Use the "Department Codes" setting to add and remove codes for your Repository. Department codes will appear in a dropdown for the second part of the Accession identifier. The first and third sections of the identifier will be system-generated upon saving the record. The fourth section will be removed.
    - [Custom Accession Identifiers](https://github.com/uvalib/generate_accession_identifiers) (University of Virginia, forked from Yale/Hudson Molonglo plugin): This is a modification of the original generate-accession-identifiers plugin with two significant differences.
    - [Next Resource Identifier plugin](https://github.com/duspeccoll/next_resource) (University of Denver Libraries): ArchivesSpace plugin to determine the next collection number in a sequence.
* [University of Denver's local ArchivesSpace plugins](https://github.com/duspeccoll/plugins_local) (University of Denver Libraries): Includes branding; extending the resource\_tree content model to display the component IDs in the third column, for easier tree navigation for our archivists; extending the public search result summary to provide additional metadata about Resources, Archival Objects, and Digital Objects; adding rows to the component toolbar for Archival Objects to allow for MODS export and linking to digital objects.
* [Timewalk plug-in](https://github.com/alexduryee/timewalk) (Alex Duryee): An automated date parser plugin for ArchivesSpace.
* [ArchivesSpace Assets Reroute Plugin](https://github.com/archivesspace-labs/assets_reroute) (Mark Triggs, Hudson Molonglo): This is a plugin to reroute the Rails asset pipeline in the ASpace frontend and public UI to use plugin assets. It's specifically designed to allow plugin assets to be served by Tomcat7.
* [Container Management](https://github.com/hudmol/container_management) (Hudson Molonglo): ArchivesSpace plugin to add a new container type to ArchivesSpace. This plugin is compatible with ArchivesSpace v1.1.x.
* [Yale ArchivesSpace ILS Integration](https://github.com/hudmol/aspace_yale_ils_integration) (Hudson Molonglo): ArchivesSpace plugin to add support for integrating Yale's ILS.
* [Yale Accessions plugin](https://github.com/quoideneuf/aspace_yale_accessions) (Brian Hoffman): Creates custom accession identifiers for Yale.
* [Yale MARC XML](https://github.com/hudmol/yale_marcxml2accession_extras) (Hudson Molonglo): Additional MARC XML for accession mappings for Yale.
* [Default text for notes](https://github.com/hudmol/default_text_for_notes) (Hudson Molonglo): ArchivesSpace plugin to specify default text for selected fields. This plugin was developed for the National Library of Australia.
* [Yale Materials Types](https://github.com/hudmol/material_types) (Hudson Molonglo): When this plugin is installed, you will see a new Material Types subrecord form in the Accessions form. After adding a Material Types subrecord to an Accession, you can check the material types that apply to the Accession. You can set default Material Types by clicking 'My Repository Preferences'; in the user dropdown menu. Checked Material Type preferences will be checked by default when a new Material Types record is created.
* [ASpace Yale Container Operations](https://github.com/hudmol/aspace_yale_container_operations) (Hudson Molonglo): Plugin for bulk container operations.
* [Item linker](https://github.com/duspeccoll/item_linker) (Denver University Libraries): This ArchivesSpace plugin allows a user to create a Digital Object record directly from an Archival Object (i.e. for digital surrogates of a physical object), and automatically link that Digital Object to the item upon its creation. If a Digital Object is already linked to the item record, the user can push updates from the item to its Digital Object.
* [Archival Object\_MODS](https://github.com/duspeccoll/ao_mods) (Denver University Libraries): This plugin allows users to download MODS representations of Archival Objects in ArchivesSpace. On the backend, there is an API call allowing the direct download of a MODS representation of any Archival Object as well as the metadata for that MODS representation, similar to the MODS export for Digital Object records.
* [Autogenerate DOIDs](https://github.com/lorawoodford/autogenerate-doid) (Lora Woodford): This plugin auto-generates an identifier for Digital Objects created in staff mode (frontend).
* [Manager User Defined Fields](https://github.com/osulibraries/manage_user_defined_fields) (Ohio State University): This ArchivesSpace plugin hides any user defined fields that are default or not used for the specific type of item being created/edited.
* [PBSpace](https://github.com/WGBH-MLA/pbspace) (Jason Corum, WGBH Media Library and Archives): This plugin adds new properties and object relationships in the application so that PBCore structure, elements, and attributes can be better represented in ArchivesSpace. PBCore is a data model for the description of audiovisual content.  
* [css stylesheet](https://github.com/YaleArchivesSpace/print) (Yale University): for the staff interface.
* [Donor Details Plugin](http://archival-integration.blogspot.com/2015/07/archivesspace-donor-details-plugin.html) (Bentley Historical Library): Blog post that discusses the Bentley's Donor Details plugin. Includes links to the plugin code.
* [Accession Identifier Generator](https://github.com/UNC-Libraries/aspace-accession-identifiers) (UNC Chapel Hill Libraries): Creates controlled value list for accession identifier component 1 and auto-generates accession identifier component 2.
* [Publish Partial Trees](https://gitlab.developers.cam.ac.uk/lib/dev/ams/publish_partial_trees) (University of Cambridge): Allows publication and unpublication of parts of record trees. When active, a "Publish All" and "Unpublish All" button will appear in the resource and archival object toolbars for users with appropriate permissions, and will affect the open record as well as all descendant records.
* [Check URLs Custom Report](https://github.com/uga-libraries/uga-archivesspace-reports) (University of Georgia Libraries): A custom report to capture URLs in notes and digital object file versions and check them for bad requests (404, 500, etc.). Redirected links check the destination URL for errors.

### Additional Front-end Functionality
* [Implementing the ArchivesSpace PUI: A Before Action Review](http://campuspress.yale.edu/yalearchivesspace/2017/09/12/a-before-action-review/) (Yale University): Blog post that explains the purposes of this Before Action Review (BAR): identify what would be accomplished, what would change, and what would indicate success by moving to the ArchivesSpace public user interface.
* [Fixes title tag rendering bug in ArchivesSpace v1.5.4](https://github.com/jhu-archives-and-manuscripts/aspace_plugin-title_render) (Tim DiLauro/Johns Hopkins University): This plugin remedies the worst of the ArchivesSpace v1.5.4 Public User Interface (PUI) *<title>* tag rendering bugs, which resulted in missing title text in fields and component tree, partially rendered pages, and bracketed <tags> in browser tabs/window headings. It currently does not address similar issues in staff mode (frontend) and is not applicable to the 2.x versions of ArchivesSpace.
* [Creating a static page for the PUI](https://github.com/hudmol/static_pages) (James Bullen, Hudson Molonglo): Can be used to create a static page for the PUI, such as an FAQ, instructions for searching, information about the archive, etc.
* [Create a sitemap for the PUI](https://github.com/dartmouth-dltg/aspace_sitemap) (Joshua Shaw, Dartmouth College): Adds a job to the staff interface that generates a sitemap for the PUI.

### General Information about Plugins
* [Information about Plugins](https://github.com/archivesspace/archivesspace/blob/master/plugins/PLUGINS_README.md) (ArchivesSpace): ReadMe file from ArchivesSpace plugins page on Github.
* [Writing an ArchivesSpace plugin](https://teaspoon-consulting.com/articles/archivesspace-plugins.html) (Mark Triggs, Teaspoon Consulting): "ArchivesSpace allows you to write custom code to add new features, or change the behaviour of existing features. This code takes the form of a _plugin_: you structure your code according to certain conventions and it is automatically loaded when the ArchivesSpace system starts up. This article looks at the source code behind a plugin for generating accession identifiers."
* [Writing plugins for ArchivesSpace](https://osf.io/jdru2/) (Laney McGlohon and Lora Woodford): Workshop at Code4Lib 2018 that aimed to demystify plugins through examples and hands-on activities, along with tips and tools for participants to build their own plugins.
* [ArchivesSpace Developer Screencasts: 20. Writing an importer plugin](https://www.youtube.com/watch?v=hWP430Q5EWM) (Mark Triggs, Hudson Molonglo): Youtube video that demonstrates how to write a plugin that adds an importer to ArchivesSpace.
* [Turning an ArchivesSpace Plugin into Core Code](https://archivesspace.atlassian.net/wiki/spaces/ADC/pages/349995159/Turning+an+ArchivesSpace+Plugin+into+Core+Code) (ArchivesSpace program team): One of the simplest and quickest ways to begin writing for the ArchivesSpace core code is to take an existing plugin and convert it into a pull request to the master branch of ArchivesSpace.

## Integrations
The links below relate to ArchivesSpace integrations projects. Resources are loosely grouped by the type of system being integrated with ArchivesSpace such as digital preservation systems, content publication systems, import/export integrations, etc. Some links may appear in multiple categories.

* General resources on integrations (ArchivesSpace)
    - [What are integrations?](https://archivesspace.atlassian.net/wiki/spaces/ADC/pages/102471723/What+are+Integrations)
    - [Why integrate with ArchivesSpace?](https://archivesspace.atlassian.net/wiki/spaces/ADC/pages/102471809/Why+Integrate+with+ArchivesSpace)
    - [How to integrate with ArchivesSpace?](https://archivesspace.atlassian.net/wiki/spaces/ADC/pages/102471870/How+to+Integrate+with+ArchivesSpace)
    - [Integrations with ArchivesSpace](https://archivesspace.atlassian.net/wiki/spaces/ADC/pages/17137746/Integrations)

### Aggregated Discovery Layers
Many ArchivesSpace institutions have implemented multiple ways of searching across the variety of resources that they maintain, such as the ArchivesSpace public UI and published finding aids. Some would like to consolidate their data into a single search interface/discovery layer so that their patrons can search all of their collections in a single place.
* [ArcLight](https://github.com/projectblacklight/arclight) ( Stanford University, with assistance from a number of contributing institutions, including University of Michigan, Princeton University, Duke University, Indiana University, the National Library of Medicine, Georgia Tech, the Chemical Heritage Foundation, and the Rockefeller Archives Center.): According to its website, ArcLight is “a [Blacklight](https://projectblacklight.org/)-based environment to support discovery and delivery for archives and special collections, initiated by Stanford University Libraries in late 2014. The vision for ArcLight has been to support discovery and delivery of archives and special collections (both physical and digital), to improve presentation and usability for archival description, and to enable integration with systems like Samvera, ArchivesSpace, and request management systems.” [ArcLight wiki](https://samvera.atlassian.net/wiki/spaces/samvera/pages/405211890/ArcLight), [ArcLight Google Group](https://groups.google.com/g/arclight-community?pli=1), [ArcLight YouTube](https://www.youtube.com/channel/UCbSaP93HdypsW6hXy7V1nFQ)
### Digital Asset Management
Metadata for digital objects can exist in both ArchivesSpace and a digital asset management or repository system. This leads to a duplication of metadata between these systems. System integration offers an opportunity to record metadata in one system, relying on the integration to automatically duplicate it in the other.
* Starchive (American Song Archives): The objective is to create a digital asset management system with a creative and kinetic interface, allowing for private user workspaces, plus the added benefits of professional archival standards built into the system. This system will allow both staff and users to work within this virtual space in a visually engaging and fun way while also providing a strong and secure backend control offered by ArchivesSpace. The system will ultimately benefit both museum, public history and archives by providing virtual workspace for curation, digital exhibit layouts, archival processing, digital asset metadata projects and virtual research rooms.

### Digital Preservation Systems
Some ArchivesSpace institutions make use of digital preservation systems for ingests. The descriptive information in ArchivesSpace should be able to aid in appraisal and arrangement, and can replicate this data in digital preservation systems. Furthermore, institutions can write “location” information for digital objects back to ArchivesSpace. In fact, a number of digital preservation integrations already exist.
* [Archivematica](https://www.archivematica.org/en/docs/archivematica-1.10/admin-manual/installation-setup/integrations/archivesspace-setup/)(Artefactual): Archivematica includes functionality that allows users to associate objects in Archivematica to related objects in ArchivesSpace. Supports ArchivesSpace 1.5.3 and later versions. Tested with 2.5, but not yet tested with 2.7+. User community and/or support provided by Artefactual based on service agreement. (Including the Rockefeller workflow). Due to the nature of the integration involving three systems, Artefactual does rely on the archivists at Bentley to test and report problems. (The Bentley is also active in fixing issues as community contributors). Artefactual tests the ArchivesSpace integration but does not test the DSpace integration.
* [ArchivesSpace-Archivematica Integration](https://github.com/hudmol/archivematica_plugin) (Rockefeller Archive Center): Integration endpoints for Archivematica.
* [ArchivesSpace Integration documentation from Archivematica](https://wiki.archivematica.org/ArchivesSpace_integration) (Archivematica): Includes mapping samples between ArchivesSpace and Archivematica.
* [Caltech Archives Integration Tools](https://github.com/caltechlibrary/cait) (Caltech Library): A collection of tools utilities and services for integrating ArchivesSpace with other systems.
* [Bridging Technologies to Efficiently Arrange and Describe Digital Archives: the Bentley Historical Library&#39;s ArchivesSpace-Archivematica-DSpace Workflow Integration Project](http://journal.code4lib.org/articles/12105) (Max Eckard, Dallas Pillen, and Mike Shallcross): "The integration of ArchivesSpace and Archivematica in an end-to-end workflow that will include the automated deposit of content into a DSpace repository. This article provides context of the project and offers an in-depth exploration of the project's key development tasks, all of which were provided by Artefactual Systems, the developers of Archivematica."
* [ArchivesSpace Integration Use Cases](https://wiki.duraspace.org/display/samvera/ArchivesSpace+Integration+Use+Cases) (Samvera Archivists Interest Group - formerly the Hydra Archivists Working Group): Contains links to user stories from various institutions about how they would like to integrate ArchivesSpace with their Samvera-(formerly, Hydra)-based repositories.
* [Archive-It - ArchivesSpace Integration](https://archive-it.org/blog/post/archivesspace-integration/) (Archive-It): Blog post about the new Archive-It integration with ArchivesSpace. Includes link to [documentation and plugins](https://support.archive-it.org/hc/en-us/articles/115004287686).
* [Islandora ArchivesSpace](https://github.com/lyrasis/islandora_aspace) (LYRASIS): Includes modules, scripts, forms, and a plugin to integrate ASpace with Islandora metadata and digital objects.
* [Preservica](https://preservica.com/) (Preservica): Preservica includes functionality that allows users to associate objects in Preservica to related objects in ArchivesSpace. Documentation is available for registered Preservica users and a brief [overview of the integration](https://preservica.com/resources/knowledge-centre/archivesspace-connector-overview) is available. [Recorded webinar](https://www.youtube.com/watch?v=xOEGbBlBdAM). Supports ArchivesSpace 1.5.0 and later versions. Tested with 2.6, but not yet tested with 2.7+. Support provided through Preservica's support desk as specified in the user agreement.

### Import/Export

* [Link (Archive-It) Seeds to related ArchivesSpace collections](https://support.archive-it.org/hc/en-us/articles/115004287686-Link-seeds-to-related-ArchivesSpace-collections) (Mary Haberle, Archive-It): The "Related Archival Materials" metadata field makes it possible for partners using ArchivesSpace to integrate non-web collections in their holdings into seed-level Archives-It records.
* [ArchivesSpace Batch Exporter](https://github.com/uga-libraries/ASpace_Batch_Export-Cleanup-Upload) (University of Georgia Libraries): A program to batch export EAD, PDF, MARCXML, and Container Labels of resources from ArchivesSpace. Additionally, you can select cleanup options for EAD.xml files and upload resources to XTF-built finding aid websites.
* [ArchivesSpace DAO Links to DSpace Item Records](https://github.com/Georgetown-University-Libraries/File-Analyzer/wiki/Archival-Object-Workflows) (Georgetown University Library): Workflow to export and re-purpose ArchivesSpace metadata as a DSpace item description. Workflow to create ArchivesSpace DAO records from DSpace metadata.
* [ArchivesSpace Preprocessor](https://github.com/harvard-library/archivesspace-preprocessor) (Harvard Library): The ArchivesSpace Preprocessing system processes EAD files and applies changes (fixes) to them to allow for successful ingest into [ArchivesSpace](https://github.com/archivesspace/archivesspace).
* Atlas Systems: Aeon/ArchivesSpace Plugins
    - [ArchivesSpace-Aeon Fulfillment Plugin](https://github.com/hudmol/ArchivesSpace-Aeon-Fulfillment-Plugin): Replaces the default request button in the ArchivesSpace PUI to allow patrons to submit requests from the PUI to Aeon. Developed by Atlas Systems.
    - [ArchivesSpace-Aeon Fulfillment Plugin Customization](https://github.com/umd-lib/umd_aeon_fulfillment): A version of the Atlas plugin modified by the University of Maryland to place the request button on the Top Container page, so that the details sent to Aeon are of the box.
    - [ArchivesSpace-Aeon Fulfillment Plugin](https://github.com/harvard-library/request_list): Implements a shopping-basket-style request list in the ArchivesSpace PUI. Developed by Hudson-Molonglo for Harvard University.
    - [Aeon ArchivesSpace Client Addon](https://github.com/AtlasSystems/AeonArchivesSpaceClientAddon): This addon is used to integrate the ArchivesSpace staff interface into the Aeon Client request form so that staff can search the records of their ArchivesSpace instance and import details into Aeon requests.
* [Circa](https://github.com/NCSU-Libraries/circa) (NCSU Libraries): Request and workflow management for archives and special collections. A web-based system for managing requests for special collections materials. The application includes a JSON API, built in Ruby on Rails, and a default front end written in Angular.js (v. 1.6.x). Circa provides close integration with ArchivesSpace, upon which the application depends for managing containers associated with specific collection components, as well as the location of those containers. It can also support requests for materials described in an ILS. Circa allows users to import data from ArchivesSpace via the AS API. Currently this requires the user to copy/paste the AS record URI into Circa, which it then uses to make the API request. Supports ArchivesSpace 2.5+; not tested with 2.7.0.
* [EADChecker](https://github.com/harvard-library/archivesspace-checker) (Harvard Library): Import/export integration for checking EADs against local standards via schematron. This is a small website intended to allow Harvard Archivists to check their EAD files prior to ingest by ArchivesSpace.
* [OnBase](https://github.com/dartmouth-dltg/aspace_onbase) (Dartmouth College): Allows staff users to add documents classified as records to be uploaded to OnBase and associated/attached to records in ArchivesSpace. The documents can be retrieved from within the ArchivesSpace staff interface or viewed in OnBase. Requires ROBI API endpoints to be configured in ArchivesSpace. Keyword definitions and rules for associating document types are very much institution dependent and will require additional development to conform to a specific institution's OnBase environment and needs. Supports ArchivesSpace 2.7.0+.
* [Repurposing ArchivesSpace Metadata for Original MARC Cataloging](https://www.tandfonline.com/doi/abs/10.1080/19386389.2017.1285143) (Carol Ou, Katherine L. Rankin, Cyndi Shein): "UNLV...completed a pilot project exploring the repurposing of descriptive metadata for archival collections stored in ArchivesSpace for the creation of original MAchine-Readable Cataloging (MARC) records contributed to OCLC WorldCat."

### Content Publication
For ArchivesSpace users that do not use the ArchivesSpace public UI, integration helps them to publish finding aids or other descriptive data to external systems. A number of content publication integrations already exist.
* [staticAid](https://github.com/helrond/staticAid) (Hillel Arnold): A [Jekyll](http://jekyllrb.com/) static site generator for archival description serialized in JSON, generated via the [ArchivesSpace](http://archivesspace.org) REST API, or by other modular backends which can be added to the system.
* [AS2D8: ArchivesSpace-to-Drupal 8 integration](https://github.com/jasloe/archivesspace-drupal) (Jason Loeffler): AS2D8 is a series of Drupal modules for harvesting data from ArchviesSpace. AS2D8 extends the Drupal core Migrate API with plugins, provides sensible defaults for displaying ArchivesSpace resources in Drupal and all of the usual Drupal content and website management tools.
* [Aviary](https://www.aviaryplatform.com/) (Aviary): Using ArchivesSpace as the master metadata for your archives, Aviary can provide a synchronized access point for audiovisual content in your collections. Aviary maps metadata from ArchivesSpace and follows digital object version links to construct accessible digital objects for your users to interact with your collections. Aviary completes the process by creating a new digital object in ArchivesSpace so your users can navigate between Aviary and ArchivesSpace with ease. [Webiner, slides, recording, etc.](https://archivesspace.org/archives/5796)
* [Caltech Archives Integration Tools](http://github.com/caltechlibrary/cait) (Caltech Library): cait is a go library wrapping the ArchivesSpace REST API. Includes support for content export and static website generation tools Manage your content in ArchivesSpace but read and search the public content independent of the status of ArchivesSpace itself. Gives you more options for deployment as well as providing a clean separation of concerns for public/admin uses.

### Case Studies
* [Open-Source Opens Doors: A Case Study on Extending ArchivesSpace Code at UNLV Libraries](https://elischolar.library.yale.edu/cgi/viewcontent.cgi?article=1039&amp;context=jcas) (Cyndi Shein, Carol Ou, Karla Irwin, Carlos Lemus): "UNLV is in its third year of implementing...ArchivesSpace, and is sharing UNLV-developed code that extends ArchivesSpace's built-in function. The case study demonstrates how adopting and building upon community-created code and developing original local code is improving critical workflows that support creating collection descriptions, cleaning up metadata, and disseminating finding aids that are easier for researchers to comprehend."

## Trainings and Documentation
The links below relate to ArchivesSpace training resources and/or documentation. 

* [Training and Resources](https://guides.nyu.edu/archivesspace/training) (New York University): NYU's staff training materials for ArchivesSpace.
    - [Local Usage Manual](https://guides.nyu.edu/archivesspace/manual) (NYU)
* [List of links to a variety of ArchivesSpace training manuals](https://www2.archivists.org/groups/collection-management-section/cmt-documentation-portal) (Hosted by SAA's Collection Management Section)
* [Archival Collection Management Documentation](https://www.orbiscascade.org/archival-collection-management-documentation) and [ArchiveSpace Training](https://www.orbiscascade.org/archival-collection-management-training): The training offers an interactive overview of ArchivesSpace. The training is a combination of recorded webinars to watch anytime and live one-hour web-based workshops.
* [ArchivesSpace Documentation](https://duspeccoll.github.io/archivesspace) (University of Denver)

## Implementation
The links below relate to ArchivesSpace implementation projects. 

* [Implementing ArchivesSpace at Arizona State University](http://www.ingentaconnect.com/content/hsp/jdmm/2016/00000004/00000003/art00009#Metr) (Elizabeth Dunham): Arizona State University Libraries became charter members of ArchivesSpace, an "open source archives information management application for managing and providing web access to archives, manuscripts and digital objects", in early 2013. This case study discusses the Libraries' migration of its Archives and Special Collections (ASC) from Microsoft Access, Archivists' Toolkit and FileMaker Pro to ArchivesSpace.
* [Implementing ArchivesSpace at NYPL: Part 1](https://www.nypl.org/blog/2017/03/08/implementing-archivesspace-nypl-part-1) (New York Public Library): "In 2014, the Archives Unit at The New York Public Library began its evaluation of ArchivesSpace. Following a rigorous review of the application, we began implementation in earnest in 2016, and started using it in production earlier this year. Historically, Special Collections developed its own systems for collection/data management, which could be developed and tailored to suit our needs. As such, moving from a homegrown data management system/model to a community-designed one represented a major shift in how the Library evaluates and implements systems. Instead of being able to build to our wants/needs from the ground up, ArchivesSpace required us to meet the application halfway in its assumptions and practices."
* [Customization Layer for ArchivesSpace 2.x](https://github.com/Georgetown-University-Libraries/GUArchivesspace) (Georgetown University Libraries): Repository with Georgetown's branding and configuration customizations for ArchivesSpace.
* [Implementing ArchivesSpace with Docker](https://gitlab.msu.edu/msu-libraries/public/archivesspace-docker) (Michigan State University Libraries): A comprehensive example for implementing ArchivesSpace using Docker with documentation for setting up and customizing it.

## APIs and Scripts
The links below relate to ArchivesSpace scripts and APIs. 

* [Getting things done with in ArchivesSpace, or, Fun with APIs](https://blogs.library.duke.edu/bitstreams/2016/09/21/archivesspace-api-fun/) (Noah Huffman, Duke University): Explains how to use APIs in ArchivesSpace, along with specific examples.
* [Python for Archivists: breaking down barriers between systems](https://practicaltechnologyforarchives.org/issue7_wiedeman/) (Greg Wiederman, SUNY Albany): Article about working with the Python scripting language, which can be used to create APIs for ArchivesSpace.
* [ArchivesSpace Export Service](https://github.com/hudmol/archivesspace_export_service) (Hudson Molonglo): Created for Yale University; "provides a framework for scheduled EAD export and publication."
* [ArchivesSpace scripts](https://github.com/duke-libraries/archivesspace-duke-scripts) (Duke University Libraries): Various scripts to process ArchivesSpace EAD exports, interact with the ArchivesSpace API, or query backend ASpace SQL database for reports.
* [ArchivesSpace Data Export Scripts](https://github.com/RockefellerArchiveCenter/scripts/tree/master/archivesspace) (Rockefeller Archive Center): Various scripts to export different data records (i.e. locations, containers, archival objects, etc.) from ArchivesSpace in a variety of formats (i.e. METS, EADs, etc.)
* [Automated exports for ArchivesSpace](https://github.com/RockefellerArchiveCenter/asExportIncremental) (Rockefeller Archive Center): These scripts export updated data from ArchivesSpace and version all data in git.
* [Cross-Origin Resource Sharing for ArchivesSpace](http://blog.rockarch.org/?p=1610) (Rockefeller Archive Center): Implements Cross-Origin Resource Sharing
* [DACSspace](https://github.com/RockefellerArchiveCenter/DACSspace) (Rockefeller Archive Center): A simple Python script to evaluate your ArchivesSpace instance for [DACS single-level minimum](http://www2.archivists.org/standards/DACS/part_I/chapter_1) required elements. DACSspace utilizes the ArchivesSpace API to check resources for DACS compliance and produces a csv containing a list of evaluated resources. If a DACS field is present its content will be written to the csv, if a field is missing the csv will read &quot;FALSE&quot; for that item.
* Digital Media Logging Tools:
  - [NYU Libraries Media Log](https://github.com/NYU-ACM/medialog) (New York University): This is a basic app for capturing information about media being imaged.
  - [Rockefeller Archive Center&#39;s Digital Media Log](https://github.com/RockefellerArchiveCenter/dm_log): A Rails app that uses ArchivesSpace's API to quickly inventory digital media items and log disk imaging.
* [ArchivesSnake](https://github.com/archivesspace-labs/ArchivesSnake) (ArchivesSpace Labs): A client library for working with the ArchivesSpace API.
* [ArchivesSpace API Cheatsheet](https://pobocks.github.io/aspace_api_cheatsheet/) (Dave Mayo): A cheatsheet for ASpace's API with routes, methods, and descriptions.
* [Using Python, FFMPEG, and the ArchivesSpace API to Create a Lightweight Clip Library](https://saaers.wordpress.com/2018/10/30/using-python-ffmpeg-and-the-archivesspace-api-to-create-a-lightweight-clip-library/) (Bonnie Gordon, Rockefeller Archive Center): Explains how the Center created a Python script that "uses the ArchivesSpace API to gather descriptive metadata and output it to a spreadsheet, and also uses the command line tool ffmpeg to automate [audio/visual] clip creation."
* [ArchivesSpace API Toolkit](https://github.com/uoregon-libraries/archivesspace-api-toolkit) (University of Oregon Libraries): A command-line interface (CLI) tool built to wrap the ArchivesSpace API in a user friendly menu.
* [Large-Scale Date Normalization in ArchivesSpace with Python, MySQL, and Timetwister](https://journal.code4lib.org/articles/14443) (Alicia Detelich, Yale University): Describes a recent effort by a group of Yale University archivists to add ISO 8601-compliant dates to nearly 1 million unstructured date records in ArchivesSpace, using a combination of Python, MySQL, and Timetwister, a Ruby gem developed at the New York Public Library (NYPL).
* [Using R to Migrate Box and Folder Lists into EAD](https://saaers.wordpress.com/2019/04/09/using-r-to-migrate-box-and-folder-lists-into-ead/) (Andy Meyer): A case study about using statistical programming language R to help export, transform, and load data from legacy finding aids into ArchivesSpace. This approach could be generalized for other issues facing archives.
* [Step By Step Instructions for Batch Editing Barcodes in ArchivesSpace](https://www2.archivists.org/groups/research-libraries-section/step-by-step-instructions-for-batch-editing-barcodes-in-archivesspace) (Vakil Smallen, George Washington University):  This is a step-by-step guide for batch posting barcodes to ArchivesSpace through the API.

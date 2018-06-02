# Awesome ArchivesSpace

> [ArchivesSpace](http://archivesspace.org/) is an open source, web application for managing archives information. The application is designed to support core functions in archives administration such as accessioning; description and arrangement of processed materials including analog, hybrid, and born-digital content; management of authorities (agents and subjects) and rights; and reference service. The application supports collection management and functions as a metadata authoring tool. 

## What is this list?

Awesome ArchivesSpace is an [awesome list](https://github.com/sindresorhus/awesome). It points to resources (code, blog posts, anything with a URL, really) regarding ArchivesSpace created by the community that are dispersed around the web. Resources are loosely categorized by broad topic.

The intended audience for the list is those who have decided to adopt ArchivesSpace (or already have implemented ASpace) and need some help on where to go next in a specific area, both ArchivesSpace members and non-members.

This list is not intended to be an exhaustive roadmap to ArchivesSpace implementation, but more as a "resource guide". Inclusion on the list isn't an endorsement of any kind.

## Contributing to the list

Please help us continue to collect and add relevant sources to Awesome ArchivesSpace. See the Contribution Guidelines [add link to contributing.md] for information on how to update this page. 

Awesome ArchivesSpace was initially populated with three categories of resources: Migrations, Plug-ins, and Integrations. Through that work, additional categories of interest were identified:  Implementation, Scripts, and Trainings and Documentation. We encourage the ArchivesSpace community to add links to these categories as well as welcome new category suggestions.

## Not seeing what you need?

Here are some other helpful links:
* For technical details regarding installation of ArchivesSpace, see the [archivesspace GitHub repository](https://github.com/archivesspace/archivesspace).
* ArchivesSpace is supported by a membership community. Learn more: [Why Become a Member of ArchivesSpace?](https://archivesspace.org/community/why-become-a-member), [Member Benefits](https://archivesspace.org/community/member-benefits), and [How to Become a Member](https://archivesspace.org/community/how-to-become-a-member).

## Table of Contents

* [General Resources](#General-Resources)
* [Implementation](#Implementation)
* [Integrations](#Integrations)
* [Migrations](#Migrations)
* [Plug-ins](#Plug-ins)
* [APIs and Scripts](#APIs-and-Scripts)
* [Trainings and documentation](#Trainings-and-documentation)

## Credits and ownership

Awesome ArchivesSpace was initially populated by the [Awesome ArchivesSpace Ad Hoc Working Group](https://archivesspace.atlassian.net/wiki/spaces/AC/pages/266797087/Awesome+ArchivesSpace+Working+Group), under the aegis of the Technical Advisory Council, in 2018. The working group was comprised of: Justin Dalton, Christina Luers, Anne Marie Lyons, and Maggie Hughes.

The ArchivesSpace community has ownership over Awesome ArchivesSpace. TAC Vice Chair has responsibility for the ongoing maintenance of the list and any administrative issues. Please reach out to them if you have any further questions or suggestions that cannot be handled via a pull request. 

## General Resources

The General Resources category is meant to highlight links that may have broad appeal/applicability, beginning information, or particularly thorough information. General Resources is a good place to start browsing and further familiarizing yourself with ArchivesSpace. Many of these links will also appear in the other, more specific categories.

* ArchivesSpace Tools:
    - [Migration Tools & Data Mapping](https://archivesspace.org/using-archivesspace/migration-tools-and-data-mapping/): Includes the Archivists' Toolkit and Archon migration tools, as well maps and templates for importing and exporting data into and from ArchivesSpace.
    - Archon Migration Tool](https://github.com/archivesspace/archon-migration): ArchivesSpace Github
    - Archon Migration Data Mapping](https://docs.google.com/spreadsheets/d/13soN5djk16QYmRoSajtyAc_nBrNldyL58ViahKFJAog/edit?usp=sharing): ArchivesSpace muti-sheet Google Doc
* Yale University ArchivesSpace Migration:
    - [ArchivesSpace @ Yale](https://campuspress.yale.edu/yalearchivesspace/) -- [Migration, step by step](https://campuspress.yale.edu/yalearchivesspace/2015/06/14/migration-step-by-step/) (Maureen Callahan, Yale University): Report of the ArchivesSpace migration at Yale University, including tools that were used, how the migration was organized, and lessons learned.
    - [Yale ArchivesSpace migrationSQL](https://github.com/YaleArchivesSpace/migrationSQL) (Yale University): SQL scripts to help support Yale's migration to ArchivesSpace.
* Bits & Bytes (Patrick Galligan, Rockefeller Archive Center): RAC blog posts about ArchivesSpace migration
    - [From AT to ArchivesSpace Part 1: Installation and Cleaning Data for Migration](http://blog.rockarch.org/?p=1265)
    - [From AT to ArchivesSpace Part 2: Migrations and Error Reporting](http://blog.rockarch.org/?p=1289)
    - [From AT to AS Part 3: Training and Customization](http://blog.rockarch.org/?p=1300)
* Migrating to ArchivesSpace Blog Series on Chaos → Order (Cassie Schmitt): Discusses mapping and cleaning data
    - [Beast tables and relationships](https://icantiemyownshoes.wordpress.com/2014/02/24/beast-tables-and-relationships/)
    - [Accession record mapping](https://icantiemyownshoes.wordpress.com/2014/03/04/accession-record-mapping/)
    - Clean up: Inclusive and bulk dates comparison](https://icantiemyownshoes.wordpress.com/2014/03/12/clean-up-inclusive-and-bulk-dates-comparison/)
    - [Date formats](https://icantiemyownshoes.wordpress.com/2014/03/19/date-formats/)
    - [Clean up: Date instructions for accession records](https://icantiemyownshoes.wordpress.com/2014/03/25/clean-up-date-instructions-for-accession-records/)
    - [Cleanup: Dates and OpenRefine](https://icantiemyownshoes.wordpress.com/2014/04/24/clean-up-dates-and-openrefine/)
* [Migrating to ArchivesSpace at UAlbany](https://github.com/UAlbanyArchives/aspacemigration) (Greg Wiedeman, SUNY Albany): Detailed description of, and repository of scripts for, Albany's migration to ASpace.

## Migrations

The links below relate to ArchivesSpace migration projects. Resources are loosely grouped by the systems or tools organizations were coming from when migrating to ArchiveSpace. Some links may appear in multiple categories.

### Any legacy database
Links that can be useful for any legacy database:
* ArchivesSpace Tools:
    - [Migration Tools &amp; Data Mapping](https://archivesspace.org/using-archivesspace/migration-tools-and-data-mapping/): Includes the Archivists' Toolkit and Archon migration tools., as well maps and templates for importing and exporting data into and from ArchivesSpace.
    - [Archon Migration Tool](https://github.com/archivesspace/archon-migration): ArchivesSpace Github
    - [Archon Migration Data Mapping](https://docs.google.com/spreadsheets/d/13soN5djk16QYmRoSajtyAc_nBrNldyL58ViahKFJAog/edit?usp=sharing): ArchivesSpace muti-sheet Google Doc
* Yale University ArchivesSpace Migration:
    - [ArchivesSpace @ Yale](https://campuspress.yale.edu/yalearchivesspace/) -- [Migration, step by step](https://campuspress.yale.edu/yalearchivesspace/2015/06/14/migration-step-by-step/) (Maureen Callahan, Yale University): Report of the ArchivesSpace migration at Yale University, including tools that were used, how the migration was organized, and lessons learned.
    - [Yale ArchivesSpace migrationSQL](https://github.com/YaleArchivesSpace/migrationSQL) (Yale University): SQL scripts to help support Yale&#39;s migration to ArchivesSpace.
* [Migrating to ArchivesSpace at UAlbany](https://github.com/UAlbanyArchives/aspacemigration) (Greg Wiedeman, SUNY Albany): Detailed description of, and repository of scripts for, Albany's migration to ASpace.
* Smith College resources:
    - [Smith College Github Aspace Data Remediation](https://github.com/smith-special-collections/aspace-data-remediation): Files, tools, and plans for remediating data for migration to ArchivesSpace at Smith. 
    - [Smith College Github ASpace Migration - Files, tools, and plans](https://github.com/smith-special-collections/aspace-migration): Files, tools, and plans for bringing legacy data into ArchivesSpace at Smith.

### Archivists' Toolkit
If you are migrating from Archivists Toolkit, you may find these links useful:
* Yale University ArchivesSpace Migration:
    - [ArchivesSpace @ Yale](https://campuspress.yale.edu/yalearchivesspace/) -- [Migration, step by step](https://campuspress.yale.edu/yalearchivesspace/2015/06/14/migration-step-by-step/) (Maureen Callahan, Yale University): Report of the ArchivesSpace migration at Yale University, including tools that were used, how the migration was organized, and lessons learned.
    - [Yale ArchivesSpace migrationSQL](https://github.com/YaleArchivesSpace/migrationSQL) (Yale University): SQL scripts to help support Yale's migration to ArchivesSpace.
* ArchivesSpace Tools:
    - [Migration Tools &amp; Data Mapping](https://archivesspace.org/using-archivesspace/migration-tools-and-data-mapping/): Includes the Archivists' Toolkit and Archon migration tools, as well maps and templates for importing and exporting data into and from ArchivesSpace.
* Bits & Bytes (Patrick Galligan, Rockefeller Archive Center): RAC blog posts about ArchivesSpace migration
    - [From AT to ArchivesSpace Part 1: Installation and Cleaning Data for Migration](http://blog.rockarch.org/?p=1265)
    - [From AT to ArchivesSpace Part 2: Migrations and Error Reporting](http://blog.rockarch.org/?p=1289)
    - [From AT to AS Part 3: Training and Customization](http://blog.rockarch.org/?p=1300)
* [Migrating from Archivists' Toolkit to ArchivesSpace](https://sites.google.com/site/ccdarchivesspace/pacifics-migration-from-at--as) (Eva Guggemos, Pacific University): Report of the stages of Pacific University's migration from AT to ArchivesSpace
* ArchivesSpace Tools:
    - [Migration Tools & Data Mapping](https://archivesspace.org/using-archivesspace/migration-tools-and-data-mapping/): Includes the Archivists' Toolkit and Archon migration tools, as well maps and templates for importing and exporting data into and from ArchivesSpace.
    - [Migrating to ArchivesSpace](https://teaspoon-consulting.com/articles/migrating-to-archivesspace.html) (Mark Triggs, Teaspoon Consulting): Migration from Archivists' Toolkit to ArchivesSpace

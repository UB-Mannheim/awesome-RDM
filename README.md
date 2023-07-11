# Awesome RDM

"Awesome Research Data Management" is  a curated list of awesome RDM resources for researchers and organizations.

## Definitions

"**Research data** are objects that you use and produce during your research life cycle, encompassing datasets, software, code, workflow, models, figures, tables, images and videos, interviews, articles. Data are your research asset." [The Turing Way / Guide for Reproducible Research / Research Data Management / Research Data](https://the-turing-way.netlify.app/reproducible-research/rdm/rdm-data.html)

**Research "data management** refers to the storage, access and preservation of data produced from a given investigation. Data management practices cover the entire lifecycle of the data, from planning the investigation to conducting it, and from backing up data as it is created and used to long term preservation of data deliverables after the research investigation has concluded. Specific activities and issues that fall within the category of data management include: File naming (the proper way to name computer files); data quality control and quality assurance; data access; data documentation (including levels of uncertainty); metadata creation and controlled vocabularies; data storage; data archiving and preservation; data sharing and reuse; data integrity; data security; data privacy; data rights; notebook protocols (lab or field)." [CODATA RDM-Terminology / RDM](https://codata.org/rdm-terminology/research-data-management)

In a wider sense research data management include also research information management and research knowledge management.

## Table of contents

* [General resources](#general-resources)
    * [Registries](#registries)
    * [Courses](#courses)
    * [Books](#books)
    * [Games](#games)
    * [Wikis](#wikis)
    * [FAIR principles](#fair-principles)
    * [Research data centers](#research-data-centers)
* [RDM for researchers](#rdm-for-researchers)
    * [Planning a project](#planning-a-project)
        * [Motivation for RDM](#motivation-for-rdm)
        * [Costing RDM](#costing-rdm)
        * [Data management coordination](#data-management-coordination)
        * [Data management planning](#data-management-planning)
        * [Data policies](#data-policies)
        * [Reusing data](#reusing-data)
    * [Executing a project](#executing-a-project)
        * [Collecting data](#collecting-data)
        * [Organizing data](#organizing-data)
        * [Data storage](#data-storage)
        * [Data backup](#data-backup)
        * [Cleaning data](#cleaning-data)
        * [Data exploration](#data-exploration)
        * [Data interpretation](#data-interpretation)
        * [Anonymising data](#anonymising-data)
        * [Data protection](#data-protection)
    * [Finishing a project](#finishing-a-project)
        * [Sharing data](#sharing-data)
        * [Publishing data](#publishing-data)
        * [Presenting data](#presenting-data)
        * [Data licensing](#data-licensing)
        * [Archiving data](#archiving-data)
    * [Domain-specific resources](#domain-specific-resources)
        * [Social and economic data](#social-and-economic-data)
        * [Digital humanities](#digital-humanities)
* [RDM for organizations](#rdm-for-organizations)
    * [How to develop RDM services](#how-to-develop-rdm-services)
    * [Persistent identifiers](#persistent-identifiers)
* [Discipline-specific repositories](#discipline-specific-repositories)

## General resources

### Registries

* [Research data management (RDM) open training materials](https://zenodo.org/communities/dcc-rdm-training-materials) ZENODO Community
* [Data Management Training (DMT) Clearinghouse](https://dmtclearinghouse.esipfed.org) is a registry for online learning resources focusing on RDM
* [Data Management Skillbuilding Hub](https://dataoneorg.github.io/Education/) is a repository for open educational resources regarding data management
* [FAIRsharing](https://fairsharing.org) is a curated, informative and educational resource on data and metadata standards, inter-related to databases and data policies
* [re3data](https://www.re3data.org) is a registry of research data repositories

### Toolkits

* [Elixir RDMkit](https://rdmkit.elixir-europe.org) is a RDM toolkit for Life Sciences [[git](https://github.com/elixir-europe/rdmkit)]
* [JISC RDM Toolkit](https://www.jisc.ac.uk/guides/rdm-toolkit)
* [RDMtoolkit](https://guides.library.uwa.edu.au/RDMtoolkit) of the library at the University of Western Australia
* [Data Management Toolkit @ UNH](https://libraryguides.unh.edu/datamanagement) at University of New Hampshire
* [LEARN Toolkit of Best Practice for RDM](https://www.fosteropenscience.eu/content/learn-toolkit-best-practice-research-data-management) by [fosteropenscience](https://www.fosteropenscience.eu)
* [Research Data Toolkit](https://guides.lib.unc.edu/researchdatatoolkit) at UNC library

### Courses

* [Data Management Expert Guide CESSDA](https://dmeg.cessda.eu/Data-Management-Expert-Guide) is an advanced guide designed by European experts for social science researchers
* [Essentials 4 Data Support](https://datasupport.researchdata.nl/en/) is an introductory course
* [MANTRA Research Data Management Training](https://mantra.ed.ac.uk) is a classic online course
* [Datatree - Data Training Engaging End-users](https://datatree.org.uk/course) is a course for research students and early career researchers in the environmental sciences.
* [Research Data Management and Sharing](https://www.coursera.org/learn/data-management) is a Coursera course by Helen Tibbo & Sarah Jones
* [Carpentries-style lesson on Research Data Management](https://scienceparkstudygroup.github.io/research-data-management-lesson) [[git](https://github.com/ScienceParkStudyGroup/research-data-management-lesson)]
* [McMaster RDM Webinars](https://scds.github.io/intro-rdm) [[git](https://github.com/scds/intro-rdm)]
* [Research Data Management with DataLad](https://psychoinformatics-de.github.io/rdm-course) [[git](https://github.com/psychoinformatics-de/rdm-course)]
* [RDM at Griffith Uni Library](https://griffithunilibrary.github.io/research-data-management/) is short guide for self paced RDM [[git](https://github.com/GriffithUniLibrary/research-data-management)]
* [RDM E-Learning Platform](https://www.researchdatamanagement.ch) ist eine E-learning-Webseite zum Thema Forschungsdatenmanagement der HTW Chur und der HEG Genf
* [PARTHENOS training](https://training.parthenos-project.eu/training-modules/) is a set of training modules in digital humanities and research infrastructures
    * [Manage, improve and open up your research and data](http://training.parthenos-project.eu/sample-page/manage-improve-and-open-up-your-research-and-data/)
* [FOSTER open science courses](https://www.fosteropenscience.eu/courses)
    * [Managing and Sharing Research Data](https://www.fosteropenscience.eu/node/2328) is an introductory course
* [Research data bootcamp](https://data.blogs.bristol.ac.uk/bootcamp) is a general online course from University of Bristol
* [Data Management Short Course for Scientists](https://commons.esipfed.org/datamanagementshortcourse) by the ESIP Federation in cooperation with NOAA and the Data Conservancy
* [RDM Knowledge Base](https://www.ruhr-uni-bochum.de/researchdata/index.html) by Uni Bochum
* [EUDAT Training](https://eudat.eu/training/research-data-management)
* [EOSC-Pillar: RDM Training and support catalogue](https://www.eosc-pillar.eu/rdm-training-and-support-catalogue)
* [Library Carpentry: FAIR Data and Software](https://librarycarpentry.org/lc-fair-research/) [[git](https://github.com/LibraryCarpentry/lc-fair-research)]

### Books

* [The Turing Way: a how to guide for reproducible data science](https://the-turing-way.netlify.app/welcome.html) [[git](https://github.com/alan-turing-institute/the-turing-way)]
  * [RDM chapter](https://the-turing-way.netlify.app/reproducible-research/rdm.html)
* [A Research Data Management Handbook OpenAIRE](https://www.openaire.eu/rdm-handbook)
* [Research Data Management Handbook](https://www.organisatiegids.universiteitleiden.nl/binaries/content/assets/archeologie/organisatie/icto/rdm-handbook-fda.pdf) by Leiden University Faculty of Archaeology
* [Research Data Management and Data Literacies](https://shop.elsevier.com/books/research-data-management-and-data-literacies/tibor/978-0-12-824475-3) by Koltay Tibor
* [The Data Book: Collection and Management of Research Data](https://www.routledge.com/The-Data-Book-Collection-and-Management-of-Research-Data/Zozus/p/book/9780367736088) by Meredith Zozus
* [Hand-book of the modern development specialist](https://responsibledata.io/resources/handbook) is a Complete, Illustrated Guide to Responsible Data Usage, Manners, and General Deportment
* [Data Management for Social Scientists](https://doi.org/10.1017/9781108990424) by Nils B. Weidmann

### Games

* [RDM Adventure game](https://rdm-games.gitlab.io/rdm-adventure/)
* [Data Horror Escape Room](https://sites.google.com/vu.nl/datahorror/home?pli=1)
* [Research Data Scarytales](https://forschungsdaten-thueringen.de/rdm-scarytales/articles/overview.html)
* [Data Management: The Game](https://sites.google.com/view/data-management-the-game/)

### Wikis

* [www.forschungsdaten.org](https://www.forschungsdaten.org)
* [forschungsdaten.info](https://forschungsdaten.info)

### FAIR principles

* [The FAIR Guiding Principles for scientific data management and stewardship](https://doi.org/10.1038/sdata.2016.18) is a classic paper on FAIR principles
* [FAIR principles](https://www.go-fair.org/fair-principles) at go-FAIR.org with detailed descriptions
* [The FAIR Cookbook](https://faircookbook.elixir-europe.org) [[git](https://github.com/FAIRplus/the-fair-cookbook)]
* [Three-point FAIRification Framework "How to go FAIR"](https://www.go-fair.org/how-to-go-fair) at go-FAIR.org
* [FAIR Maturity Indicators and Tools](https://github.com/FAIRMetrics/Metrics)

### Research data centers

* [List of RDC in Germany](https://www.forschungsdaten.org/index.php/FDM-Kontakte)

## RDM for researchers

_Use case:_ a researcher wants to plan, run and finish a research project.

### Planning a project

#### Motivation for RDM

* [Benefits of data management](https://dmeg.cessda.eu/Data-Management-Expert-Guide/1.-Plan/Benefits-of-data-management) by CESSDA
* [Benefits of RDM](https://library.up.ac.za/c.php?g=356288&p=2420384) by UP
* [Advantages of research data management](https://ub.fau.de/en/research/data-and-software-in-research/advantages-of-research-data-management) by UB Erlangen-Nürnberg
* [Benefits of good data management](https://www.st-andrews.ac.uk/research/support/open-research/research-data-management/working-with-data/benefits-of-good-data-management) by the University of St Andrews
* [What are the advantages of managing research data?](https://www.ub.tum.de/en/what-are-the-advantages-of-managing-research-data) by UB TUM
* [Benefits of Data Management](https://libguides.ucd.ie/data/benefits) by UCDL
* [Benefits of RDM](https://www.fu-berlin.de/en/sites/forschungsdatenmanagement/ueber-forschungsdaten/vorteile/index.html) by FU Berlin
* [Benefits of Open Data](https://sco.library.emory.edu/research-data-management/open-data/benefits-research.html) by Emory Library

#### Costing RDM

Check out research data center at your university. They will guide you in RDM for free.

* [Data management costing tool and checklist](https://ukdataservice.ac.uk/app/uploads/costingtool.pdf) by UK Data Service
* [Guide on research data management costs](https://www.lcrdm.nl/files/lcrdm/2020-04/RDM%20and%20Costs_v20160218_EN.pdf) by LCRDM
* [How to identify and assess RDM costs](https://www.openaire.eu/how-to-comply-to-h2020-mandates-rdm-costs) is an OpenAIRE guide for H2020 grants

#### Writing a project proposal and searching funding

#### Data management coordination

It makes sense only in big research projects.

* [Data management coordination](https://rdmkit.elixir-europe.org/dm_coordination) in RDMkit

#### Data management planning

* [RDMO Research Data Management Organiser](https://rdmorganiser.github.io) is funded by DFG
* [DMPonline](https://dmponline.dcc.ac.uk) is created by Digital Curation Centre (DCC), UK
* [Data Stewardship Wizard](https://ds-wizard.org) is created by ELIXIR CZ and NL
* [DMPTool](https://dmptool.org) by CDL, USA
* [Data Management Plan Catalogue](https://libereurope.eu/dmpcatalogue) by the LIBER Research Data Management Working Group
* [Practical Guide to the International Alignment of Research Data Management](https://www.scienceeurope.org/our-resources/practical-guide-to-the-international-alignment-of-research-data-management) [[zenodo](https://doi.org/10.5281/zenodo.4915862)]
* [Creating a data management plan (DMP) document](https://help.osf.io/article/144-creating-a-data-management-plan-dmp-document) by OSF

#### Data policies

#### Reusing data

* [Existing data](https://rdmkit.elixir-europe.org/existing_data) in RDMkit
* [Reusing existing data](https://www.ugent.be/en/research/datamanagement/before-research/data-reuse.htm) by Ghent University

First, find it.
* Search in a suitable data repository which you can find in [Registries](#registries).
* Search at
    * [DataCite](https://search.datacite.org)
    * [OpenAIRE](https://explore.openaire.eu/search/find)
    * [Google Dataset Search](https://datasetsearch.research.google.com)
* Check the links in data papers:
    * list of data journals at [Forschungsdaten.org](https://www.forschungsdaten.org/index.php/Data_Journals)
    * list of data journals at [GitHub repo data-journals](https://github.com/MaxiKi/data-journals/blob/main/data_journals_characteristics.csv)
    * list of data journals at [Wikidata](https://w.wiki/6$vi)
    * examples of data journals:
          1. [Data](https://www.mdpi.com/journal/data) by MDPI
          2. [Scientific Data](https://www.nature.com/sdata) by Nature
          3. [Data in brief](https://www.sciencedirect.com/journal/data-in-brief) by ScienceDirect

Check quality of the data. Check licenses. If you reuse data, cite it.

### Executing a project

#### Collecting data

* [Data collecting](https://rdmkit.elixir-europe.org/collecting) in RDMkit

Reusing existing data
Collecting new data

#### Organizing data

* [Data organization](https://rdmkit.elixir-europe.org/data_organisation) in RDMkit

File naming

File versioning

Folder structure

#### Data storage

Separate storage for sensitive data

#### Data backup

#### Cleaning data

#### Data exploration

#### Data interpretation

#### Anonymising data

Data Masking
Pseudonimisation
Aggregation
Derived Data

#### Data protection

#### Data provenance

* [Data provenance](https://rdmkit.elixir-europe.org/data_provenance) in RDMkit

### Finishing a project

The [difference between sharing, publishing & archiving](https://datacarpentry.org/rr-publication/01-publication) is:
* sharing: any way of sharing information, could mean also emailing. It means also making research data available throughout the research lifecycle, especially during the active research phase, typically via cloud storage.
* publishing: citable artifact, discoverable.
* archiving: long-term preservation.

#### Sharing data

There are many benefits to sharing data.

You can share the data via GitHub

#### Publishing data

Data journals:
* list of data journals at [Forschungsdaten.org](https://www.forschungsdaten.org/index.php/Data_Journals)
* list of data journals at [GitHub repo data-journals](https://github.com/MaxiKi/data-journals/blob/main/data_journals_characteristics.csv)
* list of data journals at [Wikidata](https://w.wiki/6$vi)

#### Presenting data

"from infographics to narrative reports, case studies and long form investigative articles, to graffiti or conceptual art"

#### Data licensing

* [License chooser](https://creativecommons.org/choose)
* [RDA & CODATA Legal Interoperability Of Research Data: Principles And Implementation Guidelines](https://www.rd-alliance.org/rda-codata-legal-interoperability-research-data-principles-and-implementation-guidelines-now)

#### Archiving data

### Domain-specific resources

#### Social and economic data

* [Auffinden-Zitieren-Dokumentieren](https://auffinden-zitieren-dokumentieren.de) by ZBW, GESIS and RatSWD

#### Digital humanities

* [Ending principles for digital humanities projects](https://endings.uvic.ca/principles.html)

## RDM for organizations

### How to develop RDM services

* [Engaging Researchers with Data Management: The Cookbook](https://library.oapen.org/handle/20.500.12657/24568) [[pdf](https://library.oapen.org/bitstream/handle/20.500.12657/24568/9781783747993.pdf?sequence=1&isAllowed=y)]
* [How to Develop RDM Services - a guide for HEIs](https://www.dcc.ac.uk/guidance/how-guides/how-develop-rdm-services)
* [The Realities of Research Data Management. Part Four: Sourcing and Scaling University RDM Services](https://www.oclc.org/content/dam/research/publications/2018/oclcresearch-rdm-part-four-sourcing-scaling.pdf)

### How to choose a RDM repository

* [Evaluation of data repositories based on the FAIR Principles for IDCC 2017 practice paper](https://doi.org/10.4121/uuid:5146dd06-98e4-426c-9ae5-dc8fa65c549f)

### Persistent Identifiers

* [DOI registration agencies](https://www.doi.org/registration_agencies.html) is a list of current DOI registration agencies
* [URN](https://www.iana.org/assignments/urn-namespaces/urn-namespaces.xml) is a list of all registered namespaces provided by the Internet Assigned Numbers Authority (IANA)

### Others

* [LEARN Project resources](https://learn-rdm.eu/en/about) are resources to help Research Performing Institutions manage their research data
* [Paper: Digitale Werkzeuge zur textbasierten Annotation, Korpusanalyse und Netzwerkanalyse in den Geisteswissenschaften](https://tuprints.ulb.tu-darmstadt.de/17850/1/Digital_Philology__Working_Papers_in_Digital_Philology_vol002.pdf] that sums up and explains different tools
* [The Programming Historian](https://programminghistorian.org/) provides tutorials about DH topics for humanists 

## Tools

* [OpenMethods.Dariah](https://openmethods.dariah.eu) is a list of digital humanities tools and methods
* [CLARIN-D](https://www.clarin-d.net/de/) is a is a research infrastructure that helps researchers of Humanities, Cultural and Social Sciences with accessing, preparing and analysing of research data
* [TAPoR](https://tapor.ca/tools) is a list of reasearch tools for text analysis
* [SSH Open Market Place](https://marketplace.sshopencloud.eu/) is a place for resources for research in Social Sciences and Humanities
* [BAS](https://clarin.phonetik.uni-muenchen.de/BASWebServices/interface) is a set of tools for speech sciences and technology
* [TextGrid](https://textgrid.de/en/) is a virtual research environment for the humanities that is optimised for working with TEI-coded resources 

## Registries of Terminologies, Vocabularies, Ontologies

* [BARTOC registry of terminology registries](https://bartoc.org/registries)
* [The Basel Register of Thesauri, Ontologies and Classifications (BARTOC)](http://bartoc.org) includes all types of KOS in any format, across all subject areas. 
* [FAIRsharing](https://fairsharing.org) is a curated, informative and educational resource on data and metadata standards, inter-related to databases and data policies
* [Linked Open Vocabularies (LOV)](https://lov.okfn.org/dataset/lov) is a directory of RDF vocabularies 

## Discipline-specific repositories

### Digital editions

* [Patrick Sahle's Catalog of Digital Scholarly Editions](https://v3.digitale-edition.de)
* [RIDE – A review journal for digital editions and resources](https://ride.i-d-e.de)
* [TEI Publisher](https://teipublisher.com) is a software for publishing digital editions
* [ediarum](https://www.ediarum.org) is a software for creating and publishing digital editions
* [KONDE - Kompetenzzentrum Digitale Edition](https://www.digitale-edition.at/context:konde) is a guideline to publish a digital edition
* [Dig-Ed-Cat](https://dig-ed-cat.acdh.oeaw.ac.at/) is a Catalogue of Digital Editions

# openNotebook launched at elifeSprint Cambridge 2019
This toplevel resurce supports both the general concept of literature-based OpenNoteBook Science and also 3
specific projects (climate, plant oils, computational chemistry). For anyone at the sprint this is the first place to come.
We will also use the [Issues](issues) to create a general discourse and report errors.

## Dedication
This site is dedicated to Jean-Claude Bradley (v.i.), and also to my father (David Murray-Rust) headmaster at [Sidcot School](http://en.wikipedia.org/wiki/Sidcot_school) for 11 years. David gave me a love of science, teaching and collaboration. My brother Hammond is giving the Darwen lecture in 2 weeks time and I'll introduce the `climate` part of this site to the school then and invite collaboration. 
## Opennotebook science
The term ["OpenNotebookScience"](https://en.wikipedia.org/wiki/Open-notebook_science) (ONS)  was conceived and popularised by [Jean-Claude Bradley](https://en.wikipedia.org/wiki/Jean-Claude_Bradley). This site is jointly dedicated to him. Jean-Claude showed that can and almost always should be fully Open, where everything is visible on the public web as soon as it is created (i.e. within minutes). J-C's phrase was "no insider knowledge", i.e. everybody reading the site can know what experiments, data, discourse, computation has taken place. It may or may not mean that anyone can take part.
In this OpenNoteBook everyone can, in principle, take part but they need a basic knowledge of the technology, and a collaborative approach, with a certain amount of discipline and will need to be invited to be part of the repo.

## motivation for this site
Catalyzed by three projects but adaptable to any subject with open access papers and an enthusiastic community:

### quantum chemistry
Leonie Mueck suggested this topic for the eLifeSprint in Cambridge 20190904. PMR emphasis in QChem is computation of chemical properties
(mainly molecules and crystals) using Schroedinger's equation. 
(BTW QChem is used to compute the properties of many biological molecules, including proteins and nucleic acids so it's mainstream bioscience!)

See https://github.com/petermr/quantumchem which has a good example of how to create a dictionary from Wikipedia page.

(**20190912: This is currently on hold - until Leonie wants to re-activate.**)

### climate change
PeterMR and Simon Worthington met virtually and are creatin a shared OpenScience project for mining papers on climate chane - EPMC has > 65K open access papers.

See https://github.com/petermr/climate which has a good example of how to create a dictionary of 230+ terms from Wikipedia page.

(climate is critically part of bioscience!)

### medicinal plants
Work with Gita Yadav (NIPGR India and Cambridge) and Emanuel Faria (Verriclear) on essential oils and their reported activities.

See https://github.com/petermr/CEVOpen which will use recent semantic plant and chemical dictionaries from the EssoilDB project in NIPGR..

## shared resources
These projects will all be using the same resources and so documentation can be done here and shared. 

## TIGR2ESS
The tools were developed for and used in the [TIGR2ESS workshop in New Delhi 20190228](https://github.com/petermr/tigr2ess/). We'll often point to the tutorials there, but rememebr they were developedfor a particular, real-life,  occasion and a specific subject (crops (rice, wheat, millets)).

### EuropePubMedCentral
[Tutorial](https://github.com/petermr/tigr2ess/blob/master/epmcSearches/eupmc_documentation.md) from Vinita Lamba. Shows what EPMC does, how to search it manually.

### ContentMine software
ContentMine has two main tools, the first for searching/downloading; the second for analysing

#### getpapers
[Tutorial](https://github.com/petermr/tigr2ess/blob/master/getpapers/TUTORIAL.md) from Ambarish Kuamr. Shows how to automatically search and download from EPMC.

#### ami
[Tutorial](https://github.com/petermr/tigr2ess/blob/master/search/TUTORIAL.md) from Amit Yadav. Start here to analyze downloaded papers.

### dictionaries
[Tutorial](https://github.com/petermr/tigr2ess/blob/master/dictionaries/TUTORIAL.md) on dictionary structure, how to create them manually and programmatically from lists and pages, especially Wikipedia.

### Wikimedia 
[Wikipedia](https://github.com/petermr/tigr2ess/blob/master/wikimedia/Wikipedia.md) rather truncated.

[Wikidata](https://github.com/petermr/tigr2ess/blob/master/wikimedia/wikidata.md) introduction.

[WikiFactMine](https://github.com/petermr/tigr2ess/blob/master/wikimedia/WikiFactMine.md) ContentMine's dictionaries created from 
Wikidata, and searchable via SPARQL.

## other tools
### Crossref
Crossref holds metadata on "every" published  article submmited by publishers (but not theses, etc.). This normally holds a DOI which can be used to find the article on a publisher's site (or through Unpaywall). [Crossref resources](tools/Crossref.md)
### Unpaywall
Unpaywall holds the addresses and metadata of "most" articles which are "freely available legally". This is a difficult task and depends on getting metadata from repositories and other sites that hold them. 
[Unpaywall resources](tools/Unpaywall.md/)





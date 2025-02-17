<p>
<image src="images/Wikidata-logo-en.png" hspace="10" width="200"/>
<image src="images/KB_Nationale-Bibliotheek_Logo_RGB-Zwart-EN.jpg" width="400" align="top"/>
</p>
  
# Wikidata general overview
*General overview of the Wikidata universe for newcomers to get more familiar and self-reliant in this (sometimes) confusing ecosystem. Collected and curated by KB, national library of the Netherlands.* 
 
<image src="images/Wegwijzer_in_Wikidata,_Introductiecurus_Wikidata_-_Koninklijke_Bibliotheek,_6_juni_2023.jpg" width="250" align="right"/>

This page is a textual summary of 
1. the (Dutch language) course *Guide to Wikidata* for employeees of [KB, national library of the Netherlands](https://www.kb.nl) on 6th June 2023. The (rather long) full slidedeck for this course is available on [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Wegwijzer_in_Wikidata,_Introductiecurus_Wikidata_-_Koninklijke_Bibliotheek,_6_juni_2023.pdf) and [Zenodo]( https://zenodo.org/record/8006441) as PDFs.

2. In October 2024 the section on [Wikidata for research, science and cultural heritage](#wikidata-for-research-science-and-cultural-heritage) was expanded, based on the content from [the corresponding section](https://commons.wikimedia.org/w/index.php?title=File:Wikidata_Workshop_-_Theoretical_part_-_Maastricht_University_-_15_October_2024.pdf&page=73) in the presentation *[Wikidata Workshop - Theoretical part - Maastricht University - 15 October 2024](https://commons.wikimedia.org/w/index.php?title=File:Wikidata_Workshop_-_Theoretical_part_-_Maastricht_University_-_15_October_2024.pdf)* (also see [Zenodo](https://zenodo.org/records/13837957)).

**Contact**

This page is maintained by Olaf Janssen, Wikimedia coordinator of KB. See his [Wikidata user page](https://www.wikidata.org/wiki/User:OlafJanssen) and [expert page on kb.nl](https://www.kb.nl/over-ons/experts/olaf-janssen) for contact details.

**Reuse and licensing**

This overview can be reused freely and openly, it is available under the [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/) license, so attribution is required. Use something like 

*Wikidata general overview, Olaf Janssen & KB national library of the Netherlands, https://github.com/KBNLwikimedia/Wikidata-General-Overview/* 

<kbd><img src="images/cc-by.png" width="100"/></kbd>

**See also**

For more in-depth insights into how Wikidata is used specifically by/in/for the services of KB, national library of the Netherlands, see 
* the (Dutch language) slide deck [In-depth: Wikidata and KB](https://commons.wikimedia.org/wiki/File:Verdieping_Wikidata_en_de_KB_-_Koninklijke_Bibliotheek,_14_november_2023.pdf) of 14 November 2023, or 
* the equivalent textual summary in English available from [Wikidata & KB national library of the Netherlands, an overview](https://github.com/KBNLwikimedia/Wikidata-KB-Overview) here on Github. 

**Latest updates**

Latest update: 12 October 2024 (updated section 'Wikidata for research, science and cultural heritage')
<hr>

### Objectives of this page
1) To provide a broad overview of the Wikidata landscape, including both the technical and non-technical (social, community) aspects.
2) To foster and stimulate more self-reliance in exploring the Wikidata universe

### Contents
- [1) What is Wikidata?](#1-what-is-wikidata)
- [2) The principles of Wikidata](#2-the-principles-of-wikidata)
- [3) How things are described in Wikidata](#3-how-things-are-described-in-wikidata)
- [4) How to discover Qs and Ps in Wikidata](#4-how-to-discover-qs-and-ps-in-wikidata)
- [5) How to request data from Wikidata](#5-how-to-request-data-from-wikidata)
    + [1) Searching in a web browser](#1-searching-in-a-web-browser)
    + [2) HTML content in web browser](#2-html-content-in-web-browser)
    + [3)  Non-HTML content in web browser](#3--non-html-content-in-web-browser)
    + [4) Enriched web browser interfaces](#4-enriched-web-browser-interfaces)
    + [5) MediaWiki Action API](#5-mediawiki-action-api)
    + [6) Wikidata REST API](#6-wikidata-rest-api)
    + [7) Datadumps](#7-datadumps)
    + [8) Wikidata Query Service](#8-wikidata-query-service)
- [6) How to add data to Wikidata](#6-how-to-add-data-to-wikidata)
    + [1) Single item - via GUI](#1-single-item---via-gui)
    + [2) Single item - via API](#2-single-item---via-api)
    + [3) In Bulk - OpenRefine](#3-in-bulk---openrefine)
    + [4) In Bulk - QuickStatements](#4-in-bulk---quickstatements)
- [7) Who creates Wikidata?](#7-who-creates-wikidata)
- [8) Wikidata community Tools & Projects](#8-wikidata-community-tools--projects)
  * [Tools](#tools)
  * [Projects](#projects)
- [9) How to stay informed](#9-how-to-stay-informed)
    + Articles: [Wikidata for research, science and cultural heritage](#wikidata-for-research-science-and-cultural-heritage)
- [10) Where to find help (passively and actively)](#10-where-to-find-help-passively-and-actively)
- [11) How to proceed?](#11-how-to-proceed)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>

## 1) What is Wikidata?

<image src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/90/Wegwijzer_in_Wikidata%2C_Introductiecurus_Wikidata_-_Koninklijke_Bibliotheek%2C_6_juni_2023.pdf/page4-800px-Wegwijzer_in_Wikidata%2C_Introductiecurus_Wikidata_-_Koninklijke_Bibliotheek%2C_6_juni_2023.pdf.jpg?20230605132149" width="200" align="right"/>

* Various answers: A collection of structured data - A linked open database - Something to do with the sematic web? - Data for people and machines - A sister/brother of Wikipedia - Data for everyone - Public counterpart to commercial big tech data collections - A hub for 1000s of other databases - A free public utility for LOD - A worldwide enthusiastic community - The coolest LOD project ever! - Linked data, but understandable - LOD, but without the complexity of LOD - A training tool to develop yourself in the field of (linked open) data - An (academic) research object
* Prompts for ChatGTP, 2023-05-02: "What can you tell me about Wikidata?" and "Can you give me 7 perspectives on Wikidata?"
* [Random Wikidata items](https://www.wikidata.org/wiki/Special:Random).  Prompts for ChatGTP, 02-05-2023: "Can you give me 50 random 'obscure' things described in Wikidata"
* In addition to being a broad database, Wikidata can also be very specific, e.g. [892 Van Gogh paintings](https://www.wikidata.org/wiki/Wikidata:WikiProject_sum_of_all_paintings/Creator/Vincent_van_Gogh) (d.d. 04-10-2024)
* Wikidata contains structured descriptions of 114M things, starting from October 2012 ([source](https://www.wikidata.org/wiki/Wikidata:Statistics), per 5 Oct 2024)
* Things included in Wikidata: Scientific articles - People - Animals and plants - Events - Countries, provinces, municipalities, cities, villages - Streets, roads, squares - Buildings - Vehicles - Companies and institutions - Works of art (film, music, paintings, etc.) - Chemical substances - Astromic objects - Genes - etc. etc.
* [Wikidata items with geo locations](https://commons.wikimedia.org/wiki/File:Wikidata-map-2023-06-26-items-intensity-100.png), June 2023. Addshore, CC0, via Wikimedia Commons

## 2) The principles of Wikidata

<image src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/90/Wegwijzer_in_Wikidata%2C_Introductiecurus_Wikidata_-_Koninklijke_Bibliotheek%2C_6_juni_2023.pdf/page15-800px-Wegwijzer_in_Wikidata%2C_Introductiecurus_Wikidata_-_Koninklijke_Bibliotheek%2C_6_juni_2023.pdf.jpg?20230605132149" width="200" align="right"/>

See [Wikidata:Introduction](https://www.wikidata.org/wiki/Wikidata:Introduction) and [Wikidata:Philosophy](https://www.wikidata.org/wiki/Wikidata:Philosophy) 

1. Structured descriptions of things
2. Central storage (vs distributed), no data silos
3. Multilingual (200+ languages): [Description of the Eiffel Tower](https://www.wikidata.org/wiki/Q243), check the [Dutch](https://www.wikidata.org/wiki/Q243?uselang=nl), [English](https://www.wikidata.org/wiki/Q243?uselang=en), [Portuguese](https://www.wikidata.org/wiki/Q243?uselang=pt) and [Japanese](https://www.wikidata.org/wiki/Q243?uselang=ja) interfaces.
4. Linked data
   - Things, not strings - No plain text, but clickable links
   - Interconnected: [Eiffel Tower](https://www.wikidata.org/wiki/Q243) and [Gustave Eiffel](https://www.wikidata.org/wiki/Q20882) 
   - Connected to external databases (external IDs): https://www.skyscrapercenter.com/building/wd/9410
5) Open & free
   - Free, no trackers, no ads
   - No copyright or database rights, [CC0 license](https://creativecommons.org/publicdomain/zero/1.0/)
   - Everyone can reuse data: query, share, copy, edit, download, sell, etc. 
   - Everyone may contribute/edit data, add, improve, delete, merge, etc. --> Community, see below
6) Community
   - International, 23K editors (Oct 2024)
   - Under the banner of the [Wikimedia Foundation](https://en.wikipedia.org/wiki/Wikimedia_Foundation) --> sister project of Wikipedia, Commons etc. 
   - More in [section 7: Who creates Wikidata?](#7-who-creates-wikidata)
7) For humans and machines
   - Human readable, human writable --> Data available via GUIs in HTML, https://www.wikidata.org/wiki/Q1526131 (KB)
   - Machine readable, machine writable --> Data available via APIs in JSON, XML/RDF, CSV etc., 
       - https://www.wikidata.org/w/api.php?action=wbgetentities&ids=Q1526131&format=json  
       - https://www.wikidata.org/w/api.php?action=wbgetentities&ids=Q1526131&props=labels&format=xml
8) Or, formulated slightly differently: a free public utility for data - One stop shop for Linked open data - LOD, but understandable

## 3) How things are described in Wikidata

<image src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/90/Wegwijzer_in_Wikidata%2C_Introductiecurus_Wikidata_-_Koninklijke_Bibliotheek%2C_6_juni_2023.pdf/page33-800px-Wegwijzer_in_Wikidata%2C_Introductiecurus_Wikidata_-_Koninklijke_Bibliotheek%2C_6_juni_2023.pdf.jpg?20230605132149" width="200" align="right"/>

Overview: [Help:About data](https://www.wikidata.org/wiki/Help:About_data)

* "Mount Everest is the highest point in the world" : Earth (Q2) (*item*) --> highest point (P610) (*property*) --> Mount Everest (Q513) (*value*)
* Triple: [Earth (Q2)](http://www.wikidata.org/entity/Q2)  --> [highest point (P610)](http://www.wikidata.org/entity/P610)  --> [Mount Everest (Q513)](http://www.wikidata.org/entity/Q513)  
* KB on Wikidata: Concept URI: http://www.wikidata.org/entity/Q1526131 (http: and /entity/), redirecting to https://www.wikidata.org/wiki/Q1526131 (https: and /wiki/)
    1) Unique identifier (Qxxxxxx)
    2) Multilingual fingerprint: Label, Description, Aliases (Also known as)
    3) Statements
    4) Qualifiers
    5) Source references
    6) External identifiers: descriptions of KB in external databases
* In summary: [Simplified Wikidata data model](https://www.mediawiki.org/wiki/Wikibase/DataModel/Primer) 
* Version history of [Koninklijke Bibliotheek (Q1526131)](https://www.wikidata.org/wiki/Q1526131): https://www.wikidata.org/w/index.php?title=Q1526131&action=history  --> Every mutation is stored! And can be rolled back. Everything is public, for ever!
* Further reading & help: [How does Wikidata work?](https://www.wikidata.org/wiki/Wikidata:Introduction#How_does_Wikidata_work?) + [Wikidata:Glossary](https://www.wikidata.org/wiki/Wikidata:Glossary)  
* Wikidata intro videos on Youtube: Searches for [Introduction Wikidata](https://www.youtube.com/results?search_query=introduction+wikidata), [Wikidata 101](https://www.youtube.com/results?search_query=wikidata+101) and [Wikidata help](https://www.youtube.com/results?search_query=wikidata+help)  

## 4) How to discover Qs and Ps in Wikidata

<image src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/90/Wegwijzer_in_Wikidata%2C_Introductiecurus_Wikidata_-_Koninklijke_Bibliotheek%2C_6_juni_2023.pdf/page47-800px-Wegwijzer_in_Wikidata%2C_Introductiecurus_Wikidata_-_Koninklijke_Bibliotheek%2C_6_juni_2023.pdf.jpg?20230605132149" width="200" align="right"/>

* Wikidata contains 103M Qitems + 11K Properties (dated 25-05-2023)
* Searching for Qs en Ps: [Special:Search](https://www.wikidata.org/wiki/Special:Search) + [search results for 'konink'](https://www.wikidata.org/w/index.php?fulltext=1&search=konink&title=Special%3ASearch&ns0=1&ns120=1) (Ps and Qs)
* Browsing all Items (Qs): [Special:AllPages](https://www.wikidata.org/wiki/Special:AllPages) (but not very useful for 103M items)
* Browsing all Properties (Ps): [List of all Properties](https://www.wikidata.org/w/index.php?title=Special:ListProperties/&limit=500&offset=0)  + [All pages (Property namespace)](https://www.wikidata.org/wiki/Special:AllPages?from=P610&to=&namespace=120)  + [List of properties/all](https://www.wikidata.org/wiki/Wikidata:Database_reports/List_of_properties/all) + [Properties by theme](https://www.wikidata.org/wiki/Wikidata:Property_navboxes) (Anatomy, Ancient world, Astronomical objects etc.) + [Properties summary table](https://www.wikidata.org/wiki/Wikidata:List_of_properties/Summary_table)
* [Search properties by keyword](https://www.wikidata.org/wiki/Wikidata:List_of_properties)
* Wikidata as hub of [9.045 external databases](https://hay.toolforge.org/propbrowse/) (select 'External identifiers') (dd 05-10-2024)

## 5) How to request data from Wikidata

<image src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/90/Wegwijzer_in_Wikidata%2C_Introductiecurus_Wikidata_-_Koninklijke_Bibliotheek%2C_6_juni_2023.pdf/page54-800px-Wegwijzer_in_Wikidata%2C_Introductiecurus_Wikidata_-_Koninklijke_Bibliotheek%2C_6_juni_2023.pdf.jpg?20230605132149" width="200" align="right"/>

Overview: [Wikidata:Data access](https://www.wikidata.org/wiki/Wikidata:Data_access)  

#### 1) Searching in a web browser 
* https://www.wikidata.org/wiki/Wikidata:Data_access#Search - based on ElasticSearch
* [Special:Search](https://www.wikidata.org/wiki/Special:Search) - [Search results for 'koninklijke bibliotheek'](https://www.wikidata.org/w/index.php?search=koninklijke+bibliotheek&title=Special:Search&profile=advanced&fulltext=1&ns0=1&ns120=1) (Qs and Ps)  

#### 2) HTML content in web browser
* [Linked Data Interface (URI)](https://www.wikidata.org/wiki/Wikidata:Data_access#Linked_Data_Interface_(URI)): provides access to individual Q-entities via URI: http://www.wikidata.org/entity/Q??? 
* Concept URI = the reference to the 'thing' in the real world. For instance Koninklijke Bibliotheek (Q1526131): http://www.wikidata.org/entity/Q1526131 (note 'http' and 'entity' instead of 'https' and 'wiki')
* Content negotiation: https://wikidata.org/wiki/Special:EntityData/Q1526131. When accessing a resource in the Special:EntityData namespace, the special page applies [content negotiation](https://en.wikipedia.org/wiki/content_negotiation) to determine the output format. 
* Result in web browser: the reference to *the description of* the KB: https://www.wikidata.org/wiki/Q1526131 (note the 'https' and 'wiki')

#### 3)  Non-HTML content in web browser
* See https://www.wikidata.org/wiki/Wikidata:Data_access#Details_2 
* Request full Wikidata items in various output formats directly from the Qnumber via a [Special:EntityData](https://www.mediawiki.org/wiki/Wikibase/EntityData) URL.
* The ouput can be obtained in seven different formats: HTML, JSON, JSON-LD, RDF, NT, TTL or N3 and PHP
* If you don't want to depend on content negotiation (e.g. view non-HTML content in a web browser), you can actively request alternative formats by appendig a *format suffix* to the URL, eg. to retrieve JSON: [https://www.wikidata.org/wiki/Special:EntityData/Q1526131.json](https://www.wikidata.org/wiki/Special:EntityData/Q1526131.json). 
* Other available formats are [JSON-LD](https://www.wikidata.org/wiki/Special:EntityData/Q1526131.jsonld), [RDF](https://www.wikidata.org/wiki/Special:EntityData/Q1526131.rdf), [NT](https://www.wikidata.org/wiki/Special:EntityData/Q1526131.nt), [TTL or N3](https://www.wikidata.org/wiki/Special:EntityData/Q1526131.ttl) and [PHP](https://www.wikidata.org/wiki/Special:EntityData/Q1526131.php). 
* Equivalant URLs for these requests use the *format argument*, e.g. : [Special:EntityData?id=Q1526131](https://www.wikidata.org/wiki/Special:EntityData?id=Q1526131&format=rdf)[*&format=rdf*](https://www.wikidata.org/wiki/Special:EntityData?id=Q1526131&format=rdf).

#### 4) Enriched web browser interfaces
* Regular Wikidata interface (KB): http://www.wikidata.org/entity/Q1526131 
* Reasonator Wikidata GUI: https://reasonator.toolforge.org/?q=Q1526131  
* SQID Wikidata GUI: https://sqid.toolforge.org/#/view?id=Q1526131 

#### 5) MediaWiki Action API
* [MediaWiki Action API](https://www.wikidata.org/wiki/Wikidata:Data_access#MediaWiki_Action_API) - the common API for all Wikimedia projects (Wikidata, Wikipedia, Wikimedia Commons etc.)
* Base URL/API endpoint: https://wikidata.org/w/api.php
* [Examples of API calls](https://www.wikidata.org/w/api.php?action=help&modules=wbgetentities) (bottom of the page)
* Examples KB (Q1526131):
    - [All info about KB in all available languages](https://www.wikidata.org/w/api.php?action=wbgetentities&ids=Q1526131), as JSON
    - [Labels of KB  in all available languages](https://www.wikidata.org/w/api.php?action=wbgetentities&ids=Q1526131&props=labels&format=xml), as XML 

#### 6) Wikidata REST API
* [Wikidata REST API](https://www.wikidata.org/wiki/Wikidata:REST_API) - a specialized API for Wikidata
* Advantage: Cleaner, flatter structure in response data
* Base URL/API endpoint: https://www.wikidata.org/w/rest.php/wikibase/v0/
* [Documentation (OpenAPI Swagger)](https://doc.wikimedia.org/Wikibase/master/js/rest-api/) --> GET to request data 
* Examples KB (Q1526131):
    - [Entire item about KB](https://www.wikidata.org/w/rest.php/wikibase/v0/entities/items/Q1526131), as JSON
    - [Lat-long of KB](https://www.wikidata.org/w/rest.php/wikibase/v0/entities/items/Q1526131/statements?property=P625), as JSON

#### 7) Datadumps
* [Wikidata:Database download](https://www.wikidata.org/wiki/Wikidata:Database_download) 
* [Weekly Wikidata full dumps](https://dumps.wikimedia.org/wikidatawiki/entities) 
* [WDumper](https://wdumps.toolforge.org/) - create custom Wikidata RDF dumps

#### 8) Wikidata Query Service
Wikidata principles = Central data storage + all kinds of topics + everything connected --> Ask anything with SPARQL
* SPARQL = Language to search in Wikidata (and other LOD databases)
* SPARQL query examples: 
    - [Images of domestic cats](https://w.wiki/xKz)
    - [Cases named after French presidents, outside France](https://w.wiki/87M), taken form [this article](https://blog.wikimedia.de/2016/10/30/10-cool-queries-for-wikidata-that-will-blow-your-mind-number-7-will-shock-you/)
    - [Causes of Death of US Presidents](https://ramiro.org/notebook/us-presidents-causes-of-death/)
    - [Dutch nominated for Nobel Prize, but never won](https://w.wiki/7tg). See also [The Man Who Was Nominated for the Nobel Prize 84 Times, But Never Won](https://web.archive.org/web/20190912110336/http://www.todayifoundout.com/index.php/2017/11/man-nominated-nobel-prize-84-times-never-won/)
    - [Paintings with alliterative titles](https://w.wiki/87S)
    - [10 largest cities with female mayors](https://w.wiki/6kCQ)
    - [Birthday calendar of women who studied at Oxford](https://w.wiki/7tn)
    - [Birthplaces of deceased economists, by time period](https://w.wiki/87T)
    - [More SPARQL examples](https://www.wikidata.org/wiki/Wikidata:SPARQL_query_service/queries/examples)
        - [Queries about people](https://www.wikidata.org/wiki/Wikidata:SPARQL_query_service/queries/examples/human)
        - [Query of the week](https://www.wikidata.org/wiki/Wikidata:SPARQL_query_service/qotw)
* Want to get started with SPARQL in Wikidata yourself?
    - SPARQL basic videos: [SPARQL in 11 minutes](https://www.youtube.com/watch?v=FvGndkpa4K0) + [Querying Wikidata with SPARQL for Absolute Beginners](https://commons.wikimedia.org/wiki/File:Querying_Wikidata_with_SPARQL_for_Absolute_Beginners.webm)  
    - [Wikidata Query Service tutorial](https://wdqs-tutorial.toolforge.org/) + [Wikidata:SPARQL tutorial](https://www.wikidata.org/wiki/Wikidata:SPARQL_tutorial) 
    - [Help portal for Wikidata Query Service](https://www.wikidata.org/wiki/Wikidata:SPARQL_query_service/Wikidata_Query_Help) + [A gentle introduction to the Wikidata Query Service](https://www.wikidata.org/wiki/Wikidata:SPARQL_query_service/A_gentle_introduction_to_the_Wikidata_Query_Service) 
    - [Wikidata related questions](https://stackoverflow.com/questions/tagged/wikidata) on StackOverflow

## 6) How to add data to Wikidata

<image src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/90/Wegwijzer_in_Wikidata%2C_Introductiecurus_Wikidata_-_Koninklijke_Bibliotheek%2C_6_juni_2023.pdf/page91-800px-Wegwijzer_in_Wikidata%2C_Introductiecurus_Wikidata_-_Koninklijke_Bibliotheek%2C_6_juni_2023.pdf.jpg?20230605132149" width="200" align="right"/>

#### 1) Single item - via GUI
* [Create new Qitem](https://www.wikidata.org/wiki/Special:NewItem) + [Help: Creating a new item](https://www.wikidata.org/wiki/Help:Items#Creating_a_new_item) + [Wikidata:Tours](https://www.wikidata.org/wiki/Wikidata:Tours), shows how Wikidata works and teach you how to add data. 
* [Help: Adding to an existing item page](https://www.wikidata.org/wiki/Help:Items#Adding_to_an_existing_item_page)

#### 2) Single item - via API
* [MediaWiki Action API](https://wikidata.org/w/api.php): wbcreateclaim, wbsetaliases, wbsetclaim, wbsetclaimvalue, wbsetdescription, wbsetlabel, wbsetqualifier, wbsetreference - and further methods to add/modify data. 
* [Wikidata REST API](https://www.wikidata.org/wiki/Wikidata:REST_API) : [REST API endpoint](https://www.wikidata.org/w/rest.php/wikibase/v0/) + [REST API testbench](https://doc.wikimedia.org/Wikibase/master/js/rest-api) (OpenAPI Swagger documentation --> PUT, POST and PATCH to add/modify data) 

#### 3) In Bulk - OpenRefine
* OpenRefine: "From Excel sheet to Wikidata"
* https://www.openrefine.org
* See the dedicated KB [OpenRefine-Wikidata Introduction Workshop](https://github.com/KBNLwikimedia/OpenRefine-Introduction-Workshop), a practical 90 minutes workshop (in Dutch) to learn how to work with OpenRefine and Wikidata at a basic level.

#### 4) In Bulk - QuickStatements
* QuickStatements (QS): "From (formatted) .txt to Wikidata"
* [QuickStatements tool](https://quickstatements.toolforge.org)  + [QuickStatements help](https://www.wikidata.org/wiki/Help:QuickStatements) 

## 7) Who creates Wikidata?

<image src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/90/Wegwijzer_in_Wikidata%2C_Introductiecurus_Wikidata_-_Koninklijke_Bibliotheek%2C_6_juni_2023.pdf/page99-800px-Wegwijzer_in_Wikidata%2C_Introductiecurus_Wikidata_-_Koninklijke_Bibliotheek%2C_6_juni_2023.pdf.jpg?20230605132149" width="200" align="right"/>

* [Photo of ±1% of all people globally working on Wikidata](https://commons.wikimedia.org/wiki/File:WikidataCon_2019_-_2019-10-26_-_2636_-_Group_Photo.jpg), Pierre-Selim Huard, CC BY 4.0 via Wikimedia Commons. 
* Prompts for ChatGPT: 
  * "What can you tell me about the Wikidata community?" - 02-05-2023
  * “What can you tell me about the mindset of/behind the Wikidata community?” - 04-10-2024
* Wikidata = Sister project/community of Wikipedia, Wikimedia Commons etc.: Common core values are: Open/free knowledge, Collaboration, Knowledge sharing for the benefit of all
* [Wikidata in other Wikimedia projects](https://www.wikidata.org/wiki/Wikidata:Sister_projects)
* [Wikidata Statistics](https://www.wikidata.org/wiki/Wikidata:Statistics): 114M items (since Oct 2012) - 2.25B edits - 23K editors (dated 05-10-2024)
* [Roles within the Wikidata community](https://www.wikidata.org/wiki/Wikidata:Contribute) can include: Data editor - Data modeler - Writer of documentation/howtos - Bug reporter - Content domain expert - Software & tools developer - SPARQL expert - Translator - Ambassador - Event organizer/supporter - Writer of project proposals/funding - Conflict mediator - Liaison between community and GLAMs - Communication/outreach - Teacher/trainer/speaker - And many more. --> It’s not only about the ‘hard data’ roles!
* [Wikidata community events](https://www.wikidata.org/wiki/Wikidata:Events) + [Events archive](https://www.wikidata.org/wiki/Wikidata:Events/archive) + [Media files related to Wikidata events](https://commons.wikimedia.org/wiki/Category:Wikidata_events). See also [Category:Wikidata Events](https://www.wikidata.org/wiki/Category:Wikidata_Events) 
* [WikidataCon](https://www.wikidata.org/wiki/Category:WikidataCon): [WikidataCon 2021](https://www.wikidata.org/wiki/Wikidata:WikidataCon_2021) + [WikidataCon 2019](https://www.wikidata.org/wiki/Wikidata:WikidataCon_2019) + [Media files related to WikidataCon](https://commons.wikimedia.org/wiki/Category:WikidataCon).
* Wikidata workshops &  trainings examples: [Atelier Wikidata à Montréal](https://www.wikidata.org/wiki/Wikidata:Events/Atelier_Wikidata_%C3%A0_Montr%C3%A9al) - [Wikidata and Wikibase Workshop 2019](https://www.wikidata.org/wiki/Wikidata:Events/Belgium/Universiteit_Gent/Wikidata_and_Wikibase_Workshop/2019) - [Wikidata for beginners](https://www.wikidata.org/wiki/Wikidata:Events/Wikidata_for_beginners) - [EuropeanaTech 2018 Wikidata workshop day](https://www.wikidata.org/wiki/Wikidata:Events/EuropeanaTech_2018_Wikidata_workshop_day) 
* Wikidata hackathon & editathon examples: [Wiki Techstorm 2018](https://www.mediawiki.org/wiki/Wiki_Techstorm_2018) - [Wikidata Zurich Hackathon 2019](https://www.wikidata.org/wiki/Wikidata:Events/Wikidata_Zurich_Hackathon2019) - [GLOW Edithaton](https://www.wikidata.org/wiki/Wikidata:Events/GLOW_Edithaton)  
* [Wikidata Birthdays](https://www.wikidata.org/wiki/Category:Wikidata_birthday): [Wikidata's 10th birthday homepage](https://www.wikidata.org/wiki/Wikidata:Tenth_Birthday) - [Events to celebrate Wikidata's 10th birthday worldwide](https://www.wikidata.org/wiki/Wikidata:Tenth_Birthday#Events_calendar) - [Wikidata 7th birthday presents](https://www.wikidata.org/wiki/Wikidata:Seventh_Birthday/Presents)
* Wikidata swag: T-shirts, socks, caps, pens, wallets, stickers, beer openers, key chains etc.
 
## 8) Wikidata community Tools & Projects

<image src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/90/Wegwijzer_in_Wikidata%2C_Introductiecurus_Wikidata_-_Koninklijke_Bibliotheek%2C_6_juni_2023.pdf/page111-800px-Wegwijzer_in_Wikidata%2C_Introductiecurus_Wikidata_-_Koninklijke_Bibliotheek%2C_6_juni_2023.pdf.jpg?20230605132149" width="200" align="right"/>

### Tools
* [What is a tool?](https://meta.wikimedia.org/wiki/Coolest_Tool_Award#What_is_a_tool?) 
* Discover Wikidata tools: [Wikidata:Tools](https://www.wikidata.org/wiki/Wikidata:Tools) + [on Toolhub](https://toolhub.wikimedia.org/search?q=wikidata) + [in Hay's Tools Directory](https://hay.toolforge.org/directory/?search=wikidata#/search/wikidata)
* Tool examples:
  - [Duplicate items](https://www.wikidata.org/wiki/Wikidata:Tools/Enhance_user_interface#Userscripts_to_add_basic_editing_features_that_Wikibase_lacks)
  - [VizQuery](https://hay.toolforge.org/vizquery) to build SPARQL queries visually - via [Wikidata:Tools/Query data](https://www.wikidata.org/wiki/Wikidata:Tools/Query_data)
  - [Histropedia](http://histropedia.com/), Wikidata powered timelines. Eg. a [timeline of Apollo missions](http://histropedia.com/timeline/7c00jg84kn/Apollo-missions) - via [Wikidata:Tools/Visualize data](https://www.wikidata.org/wiki/Wikidata:Tools/Visualize_data)
  - [Wikidata Firefox add-ons](https://addons.mozilla.org/en-US/firefox/search/?q=wikidata)
  - [Wikidata for Google Sheets](https://workspace.google.com/marketplace/app/wikipedia_and_wikidata_tools/595109124715) 
* [Coolest Tool Awards](https://meta.wikimedia.org/wiki/Coolest_Tool_Award) + [2019 awards](https://meta.wikimedia.org/wiki/Coolest_Tool_Award/2019) + [more background info](https://wikimania.wikimedia.org/wiki/2019:Technology_outreach_%26_innovation/Coolest_Tool_Award_2019)   

### Projects
* A WikiProject (on Wikidata) is a group of contributors who want to work together as a team to improve Wikidata. Editors join WikiProjects to improve specific areas of Wikidata and build the community.
* [Wikidata professional training module about WikiProjects](https://dashboard.wikiedu.org/training/wikidata-professional/wikidata-wikiprojects) 
* Wikidata projects examples: [COVID-19](https://www.wikidata.org/wiki/Wikidata:WikiProject_COVID-19) - [Books](https://www.wikidata.org/wiki/Wikidata:WikiProject_Books) - [Tennis](https://www.wikidata.org/wiki/Wikidata:WikiProject_Tennis) - [Sum of all paintings](https://www.wikidata.org/wiki/Wikidata:WikiProject_sum_of_all_paintings), to make a LOD description for every notable painting in the world (excellent project, check ik out!!!) 
* Wikidata projects overviews:
    - [Current WikiProjects on Wikidata](https://www.wikidata.org/wiki/Wikidata:WikiProjects)
    - [List of Wikidata projects](https://www.wikidata.org/wiki/Wikidata:WikiProjects/List)
    - [Category:WikiProjects](https://www.wikidata.org/wiki/Category:WikiProjects)
* [Cultural Wikiprojects](https://www.wikidata.org/wiki/Category:Cultural_WikiProjects), [GLAM WikiProjects](https://www.wikidata.org/wiki/Category:GLAM_WikiProjects) and [Library WikiProjects](https://www.wikidata.org/wiki/Category:Library_WikiProjects)  
* KB: [Current Wikidata projects](https://www.wikidata.org/wiki/Wikidata:GLAM/Koninklijke_Bibliotheek_Nederland/CurrentProjects) + [Category:WikiProjects National Library of the Netherlands](https://www.wikidata.org/wiki/Category:WikiProjects_National_Library_of_the_Netherlands)

## 9) How to stay informed

<image src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/90/Wegwijzer_in_Wikidata%2C_Introductiecurus_Wikidata_-_Koninklijke_Bibliotheek%2C_6_juni_2023.pdf/page126-800px-Wegwijzer_in_Wikidata%2C_Introductiecurus_Wikidata_-_Koninklijke_Bibliotheek%2C_6_juni_2023.pdf.jpg?20230605132149" width="200" align="right"/>

* [Wikidata Weekly Summary](https://www.wikidata.org/wiki/Wikidata:Status_updates) (newsletter), e.g. [15 May 2023](https://www.wikidata.org/wiki/Wikidata:Status_updates/2023_05_15) 
* [Wikidata mailinglist](https://lists.wikimedia.org/postorius/lists/wikidata.lists.wikimedia.org/) + [archives](https://lists.wikimedia.org/hyperkitty/list/wikidata@lists.wikimedia.org) 	
* [Wikidata project chat](https://www.wikidata.org/wiki/Wikidata:Project_chat)
* [Wikidata De Kroeg](https://www.wikidata.org/wiki/Wikidata:De_kroeg) (Dutch discussions)  
* Wikidata @Telegram:
    - [General conversation about Wikidata](https://web.telegram.org/k/#-1224298920) and the [invite link](https://t.me/joinchat/AZriqUj5UajwQxn1aZ9WOg) 
    - [Wikidata Help](https://web.telegram.org/k/#@wikidatachat) and the [invite link](https://t.me/wikidatachat) 
    - [Other Wikidata Telegram channels](https://meta.wikimedia.org/wiki/Telegram#Wikidata) 
* [Wikidata @Twitter](https://twitter.com/wikidata)  
* [Wikidata @Facebook](https://www.facebook.com/Wikidata) + [Wikidata Community @Facebook](https://www.facebook.com/groups/WikidataCommunity) + [Wikidata.GLAM @Facebook](https://www.facebook.com/groups/Wikidata.GLAM) 

### Wikidata for research, science and cultural heritage

* *Unsorted articles*
  * [From Freebase to Wikidata: The Great Migration](https://dl.acm.org/doi/pdf/10.1145/2872427.2874809), Thomas Pellissier Tanon, Denny Vrandecic, Sebastian Schaffert, Thomas Steiner and Lydia Pintscher
  * [Wikidata from a Research Perspective - A Systematic Mapping Study of Wikidata](https://arxiv.org/pdf/1908.11153.pdf), Mariam Farda-Sarbas and Claudia Müller-Birn
  * [Queer Identities, Normative Databases: Challenges to Capturing Queerness On Wikidata](https://dl.acm.org/doi/pdf/10.1145/3579517), Katy Weathington and Jed R. Brubaker
  * [Investigating the potential of the semantic web for education: Exploring Wikidata as a learning platform](https://link.springer.com/article/10.1007/s10639-023-11664-1), Shani Evenstein Sigalov and Rafi Nachmias
  * [What we talk about when we talk about Wikidata quality: a literature survey](https://opensym.org/wp-content/uploads/2019/08/os19-paper-A17-piscopo.pdf), Alessandro Piscopo and Elena Simperl
* *Scientometrics / scholarly communication*
  * [Scholia](https://scholia.toolforge.org/) is a service that creates visual scholarly profiles for researchers, articles, organizations, topics, species, chemicals, etc using bibliographic and other information in Wikidata. 
  * Scholia example profiles: [Author: *Gerard van Breukelen*](https://scholia.toolforge.org/author/Q40107826) - [Article: *Disability-adjusted life years etc.*](https://scholia.toolforge.org/work/Q27860791) - [Journal: *Maastricht Journal of European and Comparative Law*](https://scholia.toolforge.org/venue/Q15760278) - [Organization: *Maastricht University*](https://scholia.toolforge.org/organization/Q1137652) - [Topic: *Obesity*](https://scholia.toolforge.org/topic/Q12174) - [Taxon: *Mosasaurus*](https://scholia.toolforge.org/taxon/Q312131) - [Chemical element: *Carbon*](https://scholia.toolforge.org/chemical-element/Q623)  
  * Scholia - further reading
    * [Scholia, Scientometrics and Wikidata](https://doi.org/10.1007/978-3-319-70407-4_36), Nielsen, F.Å., Mietchen, D., Willighagen, E. (2017). See also [https://arxiv.org/abs/1703.04222](https://arxiv.org/abs/1703.04222). 
    * [Wikidata:Scholia](https://www.wikidata.org/wiki/Wikidata:Scholia) and [Github:Scholia](https://github.com/WDscholia) 
* *Life and biomedical sciences*
  * [Wikidata: A platform for data integration and dissemination for the life sciences and beyond](https://doi.org/10.1101/031971 ), Elvira Mitraka, Andra Waagmeester, Sebastian Burgstaller-Muehlbacher, Lynn M. Schriml, Andrew I. Su and Benjamin M. Good (2015)
  * [Wikidata as a knowledge graph for the life sciences](http://dx.doi.org/10.7554/eLife.52614 ), Waagmeester et al. (2020), eLife. 9. 
  * [A protocol for adding knowledge to Wikidata: aligning resources on human coronaviruses](https://doi.org/10.1186/s12915-020-00940-y), Waagmeester, A., Willighagen, E.L., Su, A.I. et al., BMC Biol 19, 12 (2021). 
  * [Biological pathway abstractions: from two-dimensional drawings to multidimensional linked data](https://doi.org/10.26481/dis.20240116aw),  Waagmeester, A. S., Maastricht University (2024) - This doctoral thesis has 415 mentions of Wikidata!
  * [Wikidata and the bibliography of life](https://doi.org/10.7717/peerj.13712), Page, R.D.M., PeerJ 10:e13712 (2022) - See also https://vimeo.com/451179359
* *Astronomy*
  * [Identifying Planetary Names in Astronomy Papers: A Multi-Step Approach](https://doi.org/10.48550/arXiv.2312.08579), Shapurian, Golnaz, Michael J. Kurtz, and Alberto Accomazzi (2023). 
  * [Using Wikidata for an Observation Facility Vocabulary](https://ivoa.net/documents/Notes/ObsFacilityWikidata/20231115/NOTE-ObsFacilityWikidata-1.0-20231115.html), Baptiste Cecconi et al. Version 1.0, IVOA Note 2023-11-15
* *Mathematics*
  * [Mathematics in Wikidata?](https://oa.tib.eu/renate/bitstream/123456789/8963/1/paper-1-1-Mathematics.pdf), Philipp Scharpf, Moritz Schubotz and Bela Gipp
* *Language technology / Computational linguistics / AI / LLMs / NLP* 
  *  [Fine-tuned LLMs Know More, Hallucinate Less with Few-Shot Sequence-to-Sequence Semantic Parsing over Wikidata](https://arxiv.org/abs/2305.14202), Xu, Silei et al. (2023).
  * [Refining Wikidata Taxonomy using Large Language Models](https://arxiv.org/abs/2409.04056), Peng, Yiwen, Thomas Bonald and Mehwish Alam (2024) 
  * [User-friendly Comparison of Similarity Algorithms on Wikidata](https://arxiv.org/abs/2108.05410 ) Ilievski, Filip, Pedro A. Szekely, Gleb Satyukov and Amandeep Singh (2021) 
  * [Widaug. Data augmentation for named entity recognition using Wikidata](http://journal.sepln.org/sepln/ojs/ojs/index.php/pln/article/viewFile/6486/3893), Pablo Calleja, Alberto Sanchez and Oscar Corcho (2023)
  * [Improving Candidate Retrieval with Entity Profile Generation for Wikidata Entity Linking](https://arxiv.org/abs/2202.13404), Tuan Lai, Heng Ji and ChengXiang Zhai (2022)
* *GLAM / cultural heritage*
  * [50 cool new things you can now do with KB’s collection highlights](https://kbnlwikimedia.github.io/KBCollectionHighlights/stories/Cool%20new%20things%20you%20can%20now%20do%20with%20the%20KB's%20collection%20highlights/), a 5 part series on *Wikifying* the collection highlights of the KB national library of the Netherlands
* *Representation of (female) scientists*
  * [Edit Wikipedia and Wikidata to tell the stories of women and other underrepresented groups in physics](https://www.aps.org/initiatives/advocate-amplify/public-engagement/wiki-scientist/courses), American Physical Society
  * [Improve #WomenInSTEM Representation with Wikidata!](https://siarchives.si.edu/blog/improve-womeninstem-representation-wikidata), Smithsonian Institution Archives
* *More scientific articles related to Wikidata*
  * [Wikidata:Bibliography of Wikidata](https://www.wikidata.org/wiki/Wikidata:Bibliography_of_Wikidata) 
  * [Google Scholar](https://scholar.google.nl/scholar?q=wikidata&hl=nl&as_sdt=0,5&as_vis=1) on Wikidata
  * [Semantic Scholar](https://www.semanticscholar.org/search?&q=wikidata) on Wikidata, by field of study: [Art](https://www.semanticscholar.org/search?fos%5B0%5D=art&q=wikidata&sort=relevance) - [Biology](https://www.semanticscholar.org/search?fos%5B0%5D=biology&q=wikidata&sort=relevance) - [Computer Science](https://www.semanticscholar.org/search?fos%5B0%5D=computer-science&q=wikidata&sort=relevance) - [Education](https://www.semanticscholar.org/search?fos%5B0%5D=education&q=wikidata&sort=relevance) - [Environmental Science](https://www.semanticscholar.org/search?fos%5B0%5D=environmental-science&q=wikidata&sort=relevance) - [Geography](https://www.semanticscholar.org/search?fos%5B0%5D=geography&q=wikidata&sort=relevance) - [History](https://www.semanticscholar.org/search?fos%5B0%5D=history&q=wikidata&sort=relevance) - [Linguistics](https://www.semanticscholar.org/search?fos%5B0%5D=linguistics&q=wikidata&sort=relevance) - [Medicine](https://www.semanticscholar.org/search?fos%5B0%5D=medicine&q=wikidata&sort=relevance) - [Sociology](https://www.semanticscholar.org/search?fos%5B0%5D=sociology&q=wikidata&sort=relevance)
  * [Arxiv](https://arxiv.org/) on Wikidata
    * [Articles mentioning 'Wikidata'](https://arxiv.org/search/?query=wikidata&searchtype=all&abstracts=show)
    * [Articles with 'Wikidata' in the title](https://arxiv.org/search/?query=wikidata&searchtype=title&abstracts=show)
  * [Open Research Knowledge Graph (ORKG)](https://orkg.org/search/wikidata?types=&createdBy=) on Wikidata

## 10) Where to find help (passively and actively)

<image src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/90/Wegwijzer_in_Wikidata%2C_Introductiecurus_Wikidata_-_Koninklijke_Bibliotheek%2C_6_juni_2023.pdf/page132-800px-Wegwijzer_in_Wikidata%2C_Introductiecurus_Wikidata_-_Koninklijke_Bibliotheek%2C_6_juni_2023.pdf.jpg?20230605132149" width="200" align="right"/>

* [Wikidata documentation portal](https://www.wikidata.org/wiki/Help:Contents), the place where you can get help contributing to Wikidata.  
* [Wikidata Community portal](https://www.wikidata.org/wiki/Wikidata:Community_portal) 
* [Wikidata Professional Development Training Modules](https://dashboard.wikiedu.org/training/wikidata-professional), a set of modules covering the basics of contributing to Wikidata. See the [module about the Wikidata community](https://dashboard.wikiedu.org/training/wikidata-professional/wikidata-community).  
* Via Telegram, Mailinglists, Project chat, Twitter, Facebook: see [Section 9](#9-How-to-stay-informed) above
* [Live chat](https://web.libera.chat/?channel=#wikidata)
* Email : info@wikidata.org  
* [StackExchange](https://stackexchange.com/search?q=wikidata) (technical help)  
* Help by [User:OlafJanssen](https://www.wikidata.org/wiki/User:OlafJanssen). See also his [expert page](https://www.kb.nl/over-ons/experts/olaf-janssen) on kb.nl 

## 11) How to proceed?

<image src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/90/Wegwijzer_in_Wikidata%2C_Introductiecurus_Wikidata_-_Koninklijke_Bibliotheek%2C_6_juni_2023.pdf/page139-800px-Wegwijzer_in_Wikidata%2C_Introductiecurus_Wikidata_-_Koninklijke_Bibliotheek%2C_6_juni_2023.pdf.jpg?20230605132149" width="200" align="right"/>
 
* [Create an account](https://www.wikidata.org/wiki/Special:CreateAccount) on Wikidata 
* Get started with Wikidata yourself
* Check the other Wikimedia related courses of the KB 
    - [Wikidata & KB, an overview](https://github.com/KBNLwikimedia/Wikidata-KB-Overview), an overview of how Wikidata is used by/in/for both the linked open datasets (thesauri) and public domain heritage collections of the KB.
    - [OpenRefine-Wikidata Introduction Workshop](https://github.com/KBNLwikimedia/OpenRefine-Introduction-Workshop), a practical 90 minutes workshop (in Dutch) to learn how to work with OpenRefine and Wikidata at a basic level.
    - [Wikibase resources](https://github.com/KBNLwikimedia/Wikibase-resources), a collection of resources, overviews, links and knowlegde related to Wikibase, collected and curated by KB.
    - Wikidata & SPAQRL workshop (2024, to be announced)
* Questions? Looking for support or extra explanations? Contact Olaf Janssen, see above for his details

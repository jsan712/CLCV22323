# Weekly Response

**Data normalization** is turning non-simple domains (columns) into simple ones. In other words, normalization is taking unorganized data and breaking it down into smaller tables where the computer can retrieve data without knowing the hierarchical structure.

The goal of **First Normal** Form is to have all of the rows be unique and atomic. This means that each of the elements in each cell does not repeat and cannot be broken down any further.

The goal of **Second Normal** Form is the same as 1NF, but with the added stipulation that there is no partial dependency. This means that all attributes that do not make up a composite key should only depend on that primary key. 

The goal of **Third Normal** Form is the same as 2NF, with an additional measure stating that there are no transitive dependencies. This means that all fields must only be determinable by the primary or the composite key, not by any other keys.

# Digital Critiques

## Papyri.io
* Permanence and sustainability
  * Grade: B
  * Reasoning: Papyri.io does not have the same funding as other digital humanities sites. There is an explicit call to have individuals fund the project since there is no grant from the National Endowment for the Humanities or another large organization similar to it. There are partners and a list of donors who help fund, run, and contribute to the project, but with only $500,000 of the $2.5 million that the project needs to establish an endowment, this site is at risk of shutting down once the money runs out. There are elements that are said to be in development, but with no date of when that claim was made making it impossible to know if updates are frequent or recent. Texts have external links to GitHub to show the last edit on a specific text. Some edits are recent (although most are old) which shows there is work on the project, but without clear communication on the site about features, this does not bring the grade up to a B. The data can be downloaded in XML.

* Openness or restriction of their data
  * Grade: B
  * Reasoning: The work is licensed under a Creative Commons Attribution 3.0 License and the site does not charge a license fee. There is editorial history for each text and a way to edit documents, submit documents for publication, publish new documents, and collaborate with other users, but those privileges are locked behind an account. 

* Functionality of their interface and interaction with their data
  * Grade: C
  * Reasoning: There are a lot of advanced ways to search through the site, but nothing more. No maps or other visualizations, no extra information on the words in the text and many do not have a translation. 

* Connectivity across resources (under the principles of Linked Open Data)
  * Grade: A
  * Reasoning: There is linked data in RDF/XML, Turtle, N-Triples, JSON, and as a Graph Visualization. Papyri.io is available on the web with an open license to be open data. It is available as machine readable structured data with its option of downloadable XML files of their texts (which is non-proprietary), and uses open standards from W3C. There are URIs to other external sources for images, publications, provenance, archive, people, and places related to the text. Other external URIs lead to the sponsors of the project (The Duke Collaboratory for Classics Computing & the Institute for the Study of the Ancient World) There are internal URIs to direct users to more information about a specific metadata field within Papyri.io and information about the systems that they use to aggregate material.




## Perseus Digital Library
* Permanence and sustainability
  * Grade: A
  * Reasoning: The Perseus Project was proposed in 1985 and in 1987 it received massive funding to support the research the project was pursuing at the time. Since 2006, there have been many grants from a plethora of organizations, such as the National Endowment of the Humanities, the Department of Education, and the National Science Foundation to support the current research efforts of the project. There have also been a number of private individuals who have supported Perseus over the years. Currently, the site has a grant from the NEH “to focus on adding to translations available in Perseus” and to open up “new possibilities for connecting translation and source texts.” There is an XML download available for the text a user is looking at that is free to download, with the additional restriction that you offer Perseus any modifications you make. There have been frequent and recent updates to Perseus, updating existing translations, and work to create and expand Beyond Translation, which is a more powerful version of what Perseus is today. All of these factors lead me to believe that Perseus will be around for a long time and it will continue to evolve.

* Openness or restriction of their data
  * Grade: A
  * Reasoning: The work is licensed under a Creative Commons Attribution-ShareAlike 3.0 United States License, and there are no license fees. The text is also downloadable as an XML file “with the additional restriction that you offer Perseus any modifications you make. Perseus provides credit for all accepted changes, storing new additions in a versioning system.”

* Functionality of their interface and interaction with their data
  * Grade: A
  * Reasoning: While reading a chunk of a text (either by book or line), each word in the text has a separate page that, when clicked, displays the word, possible definitions (with the highest user voted definition highlighted in red), its part of speech, number, gender, and case, and other words that the selected word might be. The right hand side contains translation notes from multiple sources for the text listed on the side. There is also a vocabulary tool that shows the top 50% of words sorted by the weighted frequency, or all of the vocabulary for the text. The site allows you to search for a specific line in the text, or for a word within the current text or all of their texts in English, Greek, Latin, Old English, German, and Old Norse. You can search for all possible forms of a word, for all of the words, containing the exact phrase, containing at least one of the words, or without the words. The search will also return links to entries in language dictionaries and instructs you how to enter text in Greek. There is a references section that shows cross references to the current page such as “Anne Mahoney, Overview of Latin Syntax, Nouns, Adjectives, and Pronouns” for additional resources when looking at Latin Syntax and cross-references in general dictionaries to the current page.

* Connectivity across resources (under the principles of Linked Open Data)
  * Grade: A
  * Reasoning: Perseus is available on the web with an open license to be open data. It is available as machine readable structured data with its option of downloadable XML files of their texts (which is non-proprietary), and uses open standards from W3C, and includes URIs to other resources (although they are all internal).

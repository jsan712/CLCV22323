# Weekly Response paper -- Difference between variable, parameter, and argument
Downey defines variable, parameter, and argument in order to explain the differences between them and give the reader a deeper understanding of programming.

A **variable** is "a name that refers to a value" (Downey, 12). Variables are assigned in assignment statements and placed to the left of the '='. For example, ```main_character``` is a String variable with its value being "Harry Potter": ```main_character = "Harry Potter"```
    
A **parameter** is a variable that is used in a function definition. Parameters do not have a value assigned to them, but rather tell the program what type of variable, called an argument, to expect.

An **argument** is a value assigned to parameters. Arguments are assigned to parameters and are the concrete value(s) or reference(s) that is/are passed into the function, permanently filling the place of a parameter. In a way, one can think of a parameter as a hole and an argument as the peg that fits inside. An example of a parameter (foo) and arguement (whatever foo _really_ is) is as follows:

```
def my_fun(foo):
    print(foo)
```

Downey does an adequate job of explaining the difference between these three terms, but more explicit definitions of parameter and argument would be appreciated.

# Digital Critiques
## Critique of Pleiades
* permanence and sustainability
  * **Grade:** A
  * **Resoning:** The large amount of individual contributors, funding from the National Endowment of the Humanities, support from ISAW at NYU and AWMC at UNC Chapel Hill, a sizeable team of editors and reviewers, and recent updates to the project, I am confident that Pleiades is sustainable and permanent.
* openness or restriction of their data
   * **Grade:** A
   * **Resoning:** The website states, "All published content is accessible to everyone under open license." Additionally, there is a credits page to see who worked on Pleiades, pages to see the history, aims, and structure of the project, and the "Participate" page states that there is no intention to restrict their data.
* functionality of their interface and interaction with their data
    * **Grade:** A
    * **Resoning:** Clicking on the orange dots to see a short description of the ancient site and clicking on the site name to open standardized metadata (such as coordinates, other names the site possibly went by, references, how to cite the page, etc.) is intuitive. The search function also helps since it has other marked locations that are not Pleiades place resources, but these locations vary in how detailed their metadata is. The varied metadata is a result of lack of information of the ancient site, regardless of the contributor. Since Pleiades is not the only source to draw from, the non-standardized metadata on locations that are not Pleiades place resources is only a minor inconvience and not enough to bring this score down to a B. I did not encounter any broken links, bugs, or issues with the project website.
* connectivity across resources (under the principles of Linked Open Data)
    * **Grade:** A
    * **Resoning:** Pleiades offers alternate representations of their data in Atom, JSON, KML, RDF+XML, and Turtle. 

## Critique of ORBIS
* permanence and sustainability
  * **Grade:** B
  * **Resoning:** The support of a large institution like Stanford Univeristy and recent updates to the project demonstrate some permanence and sustainability, but the small team that created ORBIS and the fact that the team is _only_ comprised of historians and IT specialists at Stanford University, poses a risk to the long term sustainability of the project. While there are plans to expand the project in various paths, it is important to note that without a larger team, individual contributions, or extensive outside funding, the project is subject to termination at the whims of the university. 
* openness or restriction of their data
    * **Grade:** A
    * **Resoning:** No account is required to access the data or export the map. All of their research, from finding and marking sites to the algorithms used to calculate the different types of routes are listed in great detail in various points on the website.
* functionality of their interface and interaction with their data
    * **Grade:** A
    * **Resoning:** There are many tutorials on how to use each feature and the UI is intuitive. I did not encounter any broken links, bugs, or issues with the project website.
* connectivity across resources (under the principles of Linked Open Data)
    * **Grade:** C
    * **Resoning:** Not enough export options. No export options for detailed maps. Users are only able to export the map in vector format, without terrain, as an SVG file to edit in Adobe Illustrator or Inkscape.

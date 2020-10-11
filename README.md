# code-refactor

<h2>AKA: The Horiseon Code Refactor Exercise</h2>

<h2>Project Description</h2>

The purpose of this exercise was to update the 'Horiseon' webpage files to use HTML5 semantics and more efficicient CSS code without changing the appearance/functionality of the page. In order to allow for comparison, this repository contains two project folders.

The **original-code** folder contains the original index.html and css.style files with two main exceptions:

 * The image and css links in original-code/index.html have been changed to reflect new folder locations in the repository.
 
 * Comments have been added in original-code/style.css to identifiy and discuss inefficiencies in the code.

The **refacted-code** folder contains the my refacted code with minor semantic, content, and css changes. These changes include the following:

* Replacement of the 'div' tags with appropriate semantic tags.
* Use of alt="" to provide descriptions of images.
* Descriptive web page title created.
* Broken "Search Engine Optimization" nav link fixed.
* Elimination of superfluous lines of css code by correct use of css classes.
* Comments in CSS file describing changes.

<h2>A Takeaway...</h2>

One conclusion that can be drawn from this exercise is that semantic html elements allow for easier styling in CSS. By eliminating he non-descriptive 'div' element where possible, we increase our ability to make direct references to unique parent and child elements in our CSS rather than resorting to wanton class creation for every new section of styling -as was the case in the original-code folder. This in turn allows us to create fewer css styling classes which function truer to their purpose: to provide styling for multiple elements. 
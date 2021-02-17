# Code Refactor

<h2>AKA: The Horiseon Code Refactor Exercise</h2>

## Project Location

* [GitHub Repo](https://github.com/Gavin867/Code_Refactor)
* [Published Site](https://gavin867.github.io/Code_Refactor/)

## Project Description

The purpose of this exercise was to update the 'Horiseon' webpage files to use HTML5 semantics and more efficicient CSS code without changing the appearance/functionality of the page. This repository contains two elements.

For reference and comparison, the **original-code** folder contains the original code (via original-index.html and orginal-style.css files) with two main exceptions:

 * The image and css links in original-index.html have been changed to reflect new folder locations in the repository
 
 * Comments have been added in original-style.css to identifiy and discuss inefficiencies in the code

The **index.html** and **style.css** files in the root of this directory contain the refacted code which have minor semantic, content, and css changes from the original for better accessibility and cleanliness. These changes include the following:

* Replacement of the 'div' tags with appropriate semantic tags
* Use of alt="" to provide descriptions of images
* Descriptive web page title
* A broken "Search Engine Optimization" nav link fixed
* Elimination of superfluous lines of css code via semantic html tags and more efficient use of css classes
* Comments in CSS file describing changes

## A Takeaway...

One conclusion that can be drawn from this exercise is that semantic html elements allow for easier styling in CSS. By eliminating he non-descriptive 'div' elements where possible, we increase our ability to make direct references to more unique parent and child elements in our CSS rather than resorting to wanton class creation for every new section of styling, as was the case in the original-code folder. This in turn allows us to create fewer css styling classes which function truer to their intended purpose -to provide basline styling for multiple elements. 
# Code Refactor Starter Code
Link: [Deployed Horiseon Site](https://dalyd14.github.io/horiseon-code-refactor/)

## Purpose
This repository was weekly assignment 01. Our task was to take already established html and css
landing page code and refactor them for accessibility purposes.


## Acceptance Criteria
* [x] only semantic HTML elements present
* [x] elements in a logic structure independent of styling and positioning
* [x] alt attributes on all relevent images
* [x] heading tags in sequential order
* [x] consice descriptive title

	__*Plus*__
* Technical Acceptance
	* [x] all links function correctly
	* [x] CSS selectors follow semantic structure
	* [x] CSS file is properly commented
* Deployment
	* [x] application deployed at live URL
	* [x] loads with no errors
	* [x] GitHub Repo URL submitted
	* [x] GitHub Repo contains application code
* Application Quality
	* [x] application resembles screenshot (below)
* Repository Quality
	* [x] unique name
	* [x] repository follows best practices for file structure and naming
	* [x] best practices for class/id naming conventions, indentation, comments, etc.
	* [x] multiple commits with quality messages
	* [x] Quality README file


## Administrative Changes
1. Renamed repository name to "horiseon-code-refactor"
2. Changed file structure from having "Develop" as a parent folder to having the index.html and Assets folder in the main branch. I did this so GitHub Pages can access to index.html file in the main branch.

## Physical Changes
1. Changed the title from website to the company's name, Horiseon.
2. Added a link on the Horiseon logo to go "back" to the landing page. Also added an id for the Search Engine Optimization Section. All 4 links work correctly as of now.
3. Changed the divs with classes of "header" and "footer" to actual header and footer tags. I also made edits in the CSS file to reflect this change (deleted the preceding .). This helps the browser read the page more effectively.
4. Changed the three major div tags to section tags. Section tags help combine elements that contribute to a similar theme.
5. Added altattribute on all 7 pictures (the hero alt attribute can be found in the title attribute in the HTML). The 3 icons in the benefits section are not relevent, so they were given empty alt attributes so the browser ignores them.
6. Reorganized CSS file so the styles that apply to similar sections are grouped together and in order of importance and how they are displayed in the html
7. Changed some of the class names in the content section do they were more general. This allowed me to apply the same classes to multiple elements and remove redundancies
8. I was able to repeat step 7 for the benefits section as well


## Mock-Up Screenshot
![Horiseon Landing Page Screenshot](./assets/images/01-html-css-git-homework-demo.png)
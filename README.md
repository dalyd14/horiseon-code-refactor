# Code Refactor Starter Code


## Purpose
This repository was weekly assignment 01. Our task was to take already established html and css
landing page code and refactor them for accessibility purposes.


## Acceptance Criteria
* [ ] only semantic HTML elements present
* [ ] elements in a logic structure independent of styling and positioning
* [x] alt attributes on all relevent images
* [ ] heading tags in sequential order
* [x] consice descriptive title

	__*Plus*__
* Technical Acceptance
	* [x] all links function correctly
	* [ ] CSS selectors follow semantic structure
	* [ ] CSS file is properly commented
* Deployment
	* [ ] application deployed at live URL
	* [ ] loads with no errors
	* [ ] GitHub Repo URL submitted
	* [ ] GitHub Repo contains application code
* Application Quality
	* [ ] application resembles screenshot (below)
* Repository Quality
	* [ ] unique name
	* [ ] repository follows best practices for file structure and naming
	* [ ] best practices for class/id naming conventions, indentation, comments, etc.
	* [ ] multiple commits with quality messages
	* [ ] Quality README file


## Administrative Changes
1. Renamed repository name to "horiseon-code-refactor"
2. Changed file structure from having "Develop" as a parent folder to having the index.html and Assets folder in the main branch. I did this so GitHub Pages can access to index.html file in the main branch.

## Physical Changes
1. Changed the title from website to the company's name, Horiseon.
2. Added a link on the Horiseon logo to go "back" to the landing page. Also added an id for the Search Engine Optimization Section. All 4 links work correctly as of now.
3. Changed the divs with classes of "header" and "footer" to actual header and footer tags. I also made edits in the CSS file to reflect this change (deleted the preceding .). This helps the browser read the page more effectively.
4. Changed the three major div tags to section tags. Section tags help combine elements that contribute to a similar theme.
5. Added altattribute on all 7 pictures (the hero alt attribute can be found in the title attribute in the HTML). The 3 icons in the benefits section are not relevent, so they were given empty alt attributes so the browser ignores them


## Mock-Up Screenshot
![Horiseon Landing Page Screenshot](./assets/images/01-html-css-git-homework-demo.png)
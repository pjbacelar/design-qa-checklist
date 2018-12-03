## Design QA Before Handoff
Before handling the mockup specs to the front end developers, consider these points to avoid rework and design debts:

## Consistency
* [ ] Color Palette
	* [ ] Contrast
	* Make information visible and readable when mixing colors.
	* [ ] Style & Matching Rules
	* Check if it matches predefined rules on how to group and use the colors (subpalletes, gradients, transparent elements, etc.).
	* [ ] Impact
	* Ensure that the colors that draw more attention are on the right places. 

* [ ] Iconography
	* [ ] Alignment 
	* With other icons, text, etc.
	* [ ] Orientation
	* [ ] Weight 
	* Check if the visual weight matches other icons and UI elements.
	* [ ] Size
	* [ ] Style 
	* Stroke vs. Filled, Colorful vs. Monochromatic, Skeuomorphic vs. Flat, etc.

* [ ] Typography
	* [ ] Font family
	* [ ] Weight
	* [ ] Size
	* [ ] Legibility
	* [ ] Line Height
	* [ ] Line Breaks
	* [ ] Format 
	* E.g. Titles are all capitalized, warnings are all lowercase, etc.
	* [ ] Margins & White Space
	* [ ] Density

* [ ] Copy
	* [ ] Grammar & Syntax
	* [ ] Tone
	* E.g.: Formal language vs. Funny phrasing, Imperative mood vs. Subjunctive mood, etc.
	* [ ] Respect to Hierarchy 
	* Title, Subtitle, Body, etc.
	* [ ] Emphasis 
	* Highlight the obvious elements to ease the understanding but avoid too much highlighting.

* [ ] Graphics/Imagery
	* [ ] Style & Content
	* Search for other applied graphics to check if photos are preferable than illustrations, if those photos show people, inanimate objects or landscapes, etc.
	* [ ] Quality vs. File size
	* Try to find the right file size. If the image file is too small, it can be pixelated and if it's too heavy the loading time can be excruciating for the user as well.

## Interaction & Behavior
 
* [ ] Interactive Elements States
    * These are the most common states for web buttons, links, etc. but your UI can have more or less states depending on the function of a specific element.
    * [ ] Normal
    * [ ] Hover
    * [ ] Active
    * [ ] Disabled
    * [ ] Loading
    * [ ] Focused 

* [ ] Animations
    * [ ] Transitions
    * [ ] Loading States
    * If the UI is taking too long to render or is waiting for a slow server action to move forward, a loading state should be considerate to inform the user that the system has not froze.
 
* [ ] Interaction Type
* Check if the current interaction type is the best suitable for the element in case. E.g. Sometimes a hover can be more convenient than a click to open.
	* [ ] Click/Tap
	* [ ] Secondary Click (only desktop)
	* [ ] Hover (only desktop)
	* Convenient for previewing content 
	* [ ] Double Click/Tap
	* [ ] Click/Touch & Hold
	* [ ] Drag
	* Useful for rearranging content quickly
	* [ ] Vertical Scroll 
	* [ ] Horizontal Scroll (recommended only for mobile)
	* Good for grouping content into horizontal lists and reducing vertical space
	* [ ] Swipe (recommended only for mobile)
	* [ ] Pinch (recommended only for mobile)   

## Unusual States & Flows

* [ ] Placeholders
* Whenever a section or element that is supposed to be filled with information lacks any data at all, it's important to predict that and create a placeholder case.

* [ ] Warnings
	* There are a lot of possible error states & matching warnings for unexpected or prohibited behaviors. Below are the most common ones:
	* [ ] Wrong formatted data
	* E.g. Date fields that can't be in the future, Text that can't contain symbols, etc.
	* [ ] Blank required fields
	* [ ] Wrongly user uploaded data
	* E.g. Wrong file type, File too large, etc.
	* [ ] Data loading issues
	* E.g. Internet connection problems, Problems on the server side, etc.
 
 * [ ] Proper Feedback 
	* Always give the user instructions on how to solve the problem. If it's a forgotten password, provide a recovery link. If it's a server problem, inform a expected solving time for the user to wait or a way to contact the support team.

## Responsiveness 
* Those are the most common platforms, but remember to check all the targeted ones your software should be working on and add to the list. Make a quick recap on all the points before this one for each platform your software will be running on.
    * [ ] Mobile phones
    * [ ] Tablets
    * [ ] Old Desktops/Notebooks
    * [ ] HD Desktops/Notebooks
    * [ ] TVs
    * [ ] Wearables

## Problem Resolution
* [ ] Problem Solved (?)
* Before closing the specs and finishing the design phase, be sure to check if the solution you came up with matches the problem that was first encountered. It sounds silly, but sometimes in the midst of the creativity process designers get lost with aesthetical improvements and lose track of their initial objective.




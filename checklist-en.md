## 1. Setup Before Meeting:
* [ ] Ask developers to prepare a list of everything they did during the last sprint
* [ ] Schedule individual timeframes for each developer based on the amount of features that will be evaluated

## 2. Design QA Session:
For each feature evaluate the following aspects:
* [ ] Color Palette Consistency
* [ ] Contrast
* [ ] Typography
    * [ ] Font
    * [ ] Weight
    * [ ] Size
    * [ ] Legibility
* [ ] Button States
    * Those are the most common states for web buttons, but your UI can have more or less states depending on the function of this interactable element.
    * [ ] Normal
    * [ ] Hover
    * [ ] Active
    * [ ] Disabled
    * [ ] Loading
    * [ ] Focused 
* [ ] Iconography
    * [ ] Family/Style Consistency
         * Using flat icons alongside scheumorphic ones can hurt the general style & feel of the interface, mixing icon families should be done with care for consistency.
    * [ ] Alignment & Orientation
    * [ ] Size
* [ ] Placeholders
* [ ] Animations
    * [ ] Transitions
    * [ ] Loading States
         * If the UI is taking too long to render or is waiting for a slow server action to move forward, a loading state should be considerate to inform the user that the system has not froze.
* [ ] Graphics Resolution/Quality
    * [ ] Image Size
        * Try to find the right file size. If the image file is too small, it can be pixelated and if it's too heavy the loading time can be excruciating for the user as well.
* [ ] Responsiveness
    * E.g. Again those are the most common platforms for web applications, but remember to check all the platforms your software should be working with and add to this list.
    * [ ] Cellphones
    * [ ] Tablets
    * [ ] Old Desktops/Notebooks
    * [ ] HD Desktops/Notebooks

## 3. After the Meeting:
* [ ] Take note of all the errors and inconsistencies that were found during the QA session and classify them as:
    * [ ] Fixes and changes that the dev will take care of
    * [ ] Design debts that were found
    * A design debt can be a mockup or user flow that was not built during the design phase and the developer didn't implement or also a mockup that was misunderstood, lacked a detailed explanation and generated a wrong result.
* [ ] If you can't think of an obvious solution for a specific problem, add them to your research track and find the solution after the meeting.
  * Avoid doing mockup adjustments or researching during the meeting, because you'll be stealing the developer's time to do a task that is individual to the designer.
# meet-halfway Website

This project builds website for people, who want to find a location for meeting geographically distributed people.

When trying to bring together people from different locations, there is always a question where to meet. Travel distances might differ significantly and, as a result, the organisers might feel obliged to accommodate some people at expense of others.

This website is designed to help by calculating [centroid](https://en.wikipedia.org/wiki/Centroid) - in context of maps, it is the geographical average location for provided coordinates.

## Website URL

https://koleaby4.github.io/meet-halfway

## Customers' profile and needs

Our typical customer is a socially active person 15+ years old
who is planning to organise a meeting with family members, friends, colleagues of business counterparts.

The customer would have names and addresses of the meeting participants and would want to be able to:

1. add / remove participants
2. see their names and location on the maps
3. see central location (centroid) as soon as 2 or more participants are added
4. access formatted address of the central location (so it could be easily shared)
5. explore nearby places on the map around the central location
6. restore previously confirmed participants in case browsing session was interrupted

Depending on circumstances, our customers want to be able to comfortably use the website from both desktop and mobile devices.

## Our business goal

< To be added >

## User Stories

All user stories have been tracked using GitHub's [issues section](https://github.com/koleaby4/<ToBeAdded>),
which is a lightweight equivalent of [Jira](https://www.atlassian.com/software/jira), <br>
which is widely used for planning and tracking software development activities.

By default all tickets represent user stories.<br>
Example of a user story: [Build 'Testimonials' section for mobile view](https://github.com/koleaby4/<ToBeAdded>)

Only tickets with 'bug' label, represent defects in code, which have been found during testing.
Example of a bug: [Contacts section is misaligned in IE11](https://github.com/koleaby4/<ToBeAdded>)

Additional labels have been introduced to help categorising and filtering tasks:

1.  Non-functional requirements are marked [by NFR label](https://github.com/koleaby4/<ToBeAdded>)
2.  Accessibility stories are marked [by a11y label](https://github.com/koleaby4/<ToBeAdded>)

## Wireframes

Wireframes have been implemented using [balsamiq](https://balsamiq.com) <br>and attached to respective user stories.
In this way developers would know exactly what they should implement, which picking up respective stories.

Examples:

- [Desktop Contacts Section](https://github.com/koleaby4/<ToBeAdded>)
- [Mobile Projects Section](https://github.com/koleaby4/<ToBeAdded>)

## How we tested it

Functional tests have been carried out manually on regular basis using:

- Physical devices
  - Windows10 & Chrome desktop
  - Windows10 & IE11 desktop
  - Google Pixel 2 & Chrome mobile
- Virtual devices: Apple iPhone X via [SauceLabs](https://saucelabs.com)

Automated tests using [cypress](https://www.cypress.io) have been added to landing and services sections.
We also created a task to [add more automated tests](https://github.com/koleaby4/<ToBeAdded>) in the future.

Two accessibility scanners were used to validate website:

- [aXe](https://www.deque.com/axe)
- [Lighthouse](https://developers.google.com/web/tools/lighthouse/)

Finally, a series of peer reviews helped identifying additional issues such as:

- A number of orthographic mistakes
- Gaps in documentation
- ToDo - add an example of defect raised during peer review ([Issue 32](https://github.com/koleaby4/dom-designs/issues/32))

### Known issues

All known defects have been captured as GitHub issues and [marked by 'bug' label](https://github.com/koleaby4/<ToBeAdded>).<br>
Example: [ToDo: add a ticket here](https://github.com/<<ToBeAdded>>).

## How to run cypress tests

Prerequisites:

1.  Clone project's source codes
2.  Make sure you have [npm installed](https://www.npmjs.com/get-npm)

To execute tests:

1.  In terminal navigate to project folder
2.  Run `npm install`
3.  Run
    1. `npm run cypress:run` to execute all tests in headless mode
    2. or `npm run cypress:open` to open cypress UI and cherry-pick which tests to run

## How website was published

Website had been published into GitHub pages by following instructions provided in<br>
[Configuring a publishing source for GitHub Pages](https://help.github.com/en/articles/configuring-a-publishing-source-for-github-pages).

I truly believe it is a very clear set of instructions and trying to re-write them in my own words:

1.  Won't make them any better
2.  Will violate [KISS principles](https://en.wikipedia.org/wiki/KISS_principle)

## How to open it locally

1. Navigate to project repository: https://github.com/koleaby4/<ToBeAdded>
2. Follow [GitHub cloning instructions](https://help.github.com/en/articles/cloning-a-repository) to download or clone source files
3. Navigate to the project folder and open `index.html` in your web browser

## Validations

1. HTML validations:
   - [User story](https://github.com/koleaby4/<link to ticket ToBeAdded>)
   - [Full report](ToBeAdded)
2. CSS validations:
   - [User story](https://github.com/koleaby4/<link to ticket ToBeAdded>)
   - [Full report](ToBeAdded)

## Tools and technologies used

1.  IDE: [Visual Studio Code](https://code.visualstudio.com/)
2.  Web technologies:
    - [HTML](https://en.wikipedia.org/wiki/HTML5)
    - [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets#CSS_3)
    - [jQuery](ToBeAdde)
3.  Styling libraries and components:
    - [normalize.css](https://necolas.github.io/normalize.css)
    - [Bootstrap](https://getbootstrap.com)
    - [Bootswatch](https://bootswatch.com)
    - [Google fonts](https://fonts.google.com)
    - [Fontawesome](https://fontawesome.com)
    - [Ion Icons](https://ionicons.com)
    - [Sweet Alerts](https://sweetalert2.github.io)
4.  Source code versioning:
    - [Git](https://en.wikipedia.org/wiki/Git)
    - [GitHub](https://github.com)
5.  Validators:
    - [HTML validator](https://validator.w3.org/)
    - [CSS validator](http://jigsaw.w3.org/css-validator/)
6.  Testing tools:
    - [Chrome Dev Tools](https://developers.google.com/web/tools/chrome-devtools)
    - [aXe accessibility scanner](https://www.deque.com/axe)
    - [SauceLabs](https://saucelabs.com) for cross-platform & cross-browser compatibility
7.  Wireframes: [balsamiq](https://balsamiq.com)
8.  favicon generator: [favicon.io](https://favicon.io/favicon-generator)

## External resources / credits

1. Images: https://unsplash.com
2. Google Maps API [documentation](https://developers.google.com/maps/documentation/javascript)
3. [Situation-Complication-Resolution](https://speakingsherpa.com/how-to-tell-a-business-story-using-the-mckinsey-situation-complication-resolution-scr-framework/) presentation technique
4. Code snippets:
   - <toBeAadded>

## Acknowledgements

Special thank you to the people who guided and supported me during planning, execution and testing of this project:

- Anna Greaves
- Mario Aslau
- Sergio Rosas
- Simen Daehlin (mentor)

## Disclaimer

This project was created for educational purposes only.

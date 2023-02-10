# CEOForThePeople.Org

The website for the Coalition for Empowerment and Opportunity (CEO).

This README gives insight into how this was built and how we currently operate it, to help anyone transition into the project.

## Original Goals

* Quick turn-around -- only had a few days to get it done prior to an event
* "One-page" desired style - aimed to be a brochure site
* Sparse content - a link to an event, etc.
* Want it to look decent on desktop and mobile

## Approach

Given the above goals, we kept it simple:

* Used the Now UI Kit from CreativeTim, which I happen to have a PRO license for
* Used Pingendo, a great little app to put layouts together from ui kits like Now UI. It keeps the syntax from getting too messy, etc.
* Brought in the SASS of Now UI Kit, as well as the SASS of bootstrap on which it depends, so I can rebuild it as necessary and make changes in SASS.

## How we Build it

* The site itself is currently just an HTML page. We don't need to build it.
* The CSS sits in the `/sass` directory. We don't have an automated build for that, but I used the `Live Sass Compiler` VS Code Extension (id: `glenn2223.live-sass`) to allow me to recompile as I needed

## How we Deploy it

* Deploy previews are done via Netlify - great because it lets people comment on things live, which is helpful.
* The site itself is hosted via GitHub Pages, which we've configured with a custom domain.
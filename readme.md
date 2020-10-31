# WikiRye
An open source alternative to Wikiwand, designed with the goal of integration of all Wikimedia Foundation projects

This project uses the wikimedia api to procedurally generate a nicer looking alternative to the wikimedia default theme. This can be used to minimise the need for code injection extensions for styling which can often break the styling of wikimedia pages, and also minimises the need for projects such as wikiwand, which are closed source versions.

Written in vue, this project is intended as a learning tool for the author to use ui engines and APIs.

## Roadmap
**NB: all references to "vanilla wikimedia" refers to the default site that WikiRye has scraped data from.**

 - [ ] Create base interaction with Wikimedia API
 - [ ] Create base modules for every page
 - [ ] Routing
 - [ ] Custom CSS skin support
   - [ ] Integrate existing terminal color themes 
   - [ ] Create a SCSS variable compiler for those themes
   - [ ] Create inbuilt UI for switching themes and fonts based on [this post](https://stackoverflow.com/questions/46730904/user-switchable-custom-themes-with-vue-js)
 - [ ] Create usable UI
   - [ ] Add a sidebar for navigating long wikimedia articles
   - [ ] Add a "developer mode"
     - [ ] Show links on wikimedia to specific templates used to generate components on vanilla wikimedia installs e.g. an IMDb title on a page has a hover link to https://en.wikipedia.org/wiki/Template:IMDb_title
     - [ ] Info boxes have an "export JSON" feature for easy data extraction
   - [ ] Header containing:
     - [ ] a usable search box and an option to search with existing search engines
     - [ ] the site's logo
     - [ ] if logged in, the user's PFP and details
     - [ ] a redirect to edit the page on the "vanilla wikimedia" site
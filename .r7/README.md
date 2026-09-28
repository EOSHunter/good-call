# R7 repository context: GoodCall

A 2017 single-page GoodCall marketing prototype about education, careers, internet, credit, and moving. The page is a static front end; several sections contain placeholder text and links.

- `index.html`: page sections, slideshow, call-to-action links, and login modal markup.
- `assets/js/project.js`: initializes Foundation's modal and a Slick autoplay slideshow.
- `assets/scss/`: source styles; `assets/css/styles.css` is the compiled style used by the page.
- `assets/img/`: page graphics and logo. `assets/slick/` contains bundled carousel assets.
- `package.json`: jQuery, Slick Carousel, and Foundation 5 dependencies; `npm run sass` watches SCSS. No real test command is defined.

See [decisions](decisions.md) and [2017 changes](changes/2017-11.md). The current default branch is `master`; these notes describe the committed files, not a deployed service.

# Code Refactor Starter Code

Horiseon

Social marketing solutions

Patch notes:

* Index:
- Changed title of website to Horiseon

- Changed several div tags to to correct semantic tag. This includes <Header>, <Figure>, <Nav>, <Section>, <Aside>, and <Footer> tags.

- Fixed search engine optimization anchor link on the navigation bar that goes to the correct page.

- Added Alt attribute for all the images on the page with a basic description of what the image is about.

- Comments are placed in index file of changes

* CSS:

- Changed necessary selectors to correct tags

- Combined and removed redunant style elements. 
Ex(
combined
    .benefit-lead h3, .benefit-brand h3, .benefit-cost h3 {
        margin-bottom: 10px;
        text-align: center;
    }

removed
    .benefit-brand h3 {
        margin-bottom: 10px;
        text-align: center;
    }

    .benefit-cost h3 {
        margin-bottom: 10px;
        text-align: center;
    }
)

- Comments are placed in css file of changes.
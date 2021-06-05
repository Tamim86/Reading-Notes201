## Controlling images size via CSS

### Image size can be controled in CSS using the *heights*  property  just like any other element 

### div img{
###     height:400px;
###     width:900px;
### }

## Aligning images using CSS

### Float property => moves img elements left or right inide their container, allowing text to float arount them

### img.align-right {
###     float: right;
###     margin-left: 10px;
### }

## Centering Images in CSS
### By default, images are inline elements. This means that they flow within the surrounding text
### n order to center an image, it should be turned into a blocklevel element using the display property with a value of block
### img.align-center { 
### display: block; 
### margin: 0px auto;
### }

### The background-image property allows you to place an image behind any HTML element

### p {
### background-image: url("images/pattern.gif");}

## Repeat Images
### repeat => repeat image in both dimentions X & Y
### repeat -x => repeat image horizontally 
### repeat -y => repeat image vertically 
### no-repeat => not repeating the image
### Fixed => The background image stays in the same position on the page. 
### scroll => The background image moves up and down as the user scrolls up and down the page.

## Background-position: left top, left center, left bottom, center top, center center, center bottom, right top, right center, right bottom

# SEO: Search Engine Optimization
## SEO is the practice of trying to help your site appear nearer the top of search engine results when people look for the topics that your website cover
### SEO is often split into two areas: 
### on-page techniques =>The main component of this is looking at keywords that people are likely to enter into a search engine if they wanted to find your site, and then including these in the text and HTML code for your site in order to help the search engines know that your site covers these topics.
### off-page techniques => portant as on-page techniques. Search engines help determine how to rank your site by looking at the number of other sites that link to yours. They are particularly interested in sites whose content is related to yours. For example, if you were running a website that sold fish bait, then a link from a hairdresser is not likely to be considered as relevant as one from an angling community.
### Search engines also look at the words between the opening <a> tag and closing </a> tag in the link. If the text in the link contains keywords (rather than just click here or your website address) it may be considered more relevant


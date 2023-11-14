# Horiseon-code-refactor
This is a website for a digital marketing company called Horiseon specialising in SEO. The website HTML has been updated to use more semantic HTML elements to improve accessibility. Below I will explain how this was done. While learning about front-end coding, it is important for me to practice the things I've learnt, therefore I decided to see what I could improve with the knowledge I had.
Updating the HTML language by making it more semantic allows us to better understand the content of the website, it is also very important for SEO. Semantic HTML will help web crawlers to understand the website and therefore index it in a smarter way. 
## Header 
The top section of the website is now wrapped in a ```header``` element, which represents introductory content and typically contains a group of introductory or navigational aids.
The company logo "Horiseon" is rendered using the ```h1``` element. The word "seo" is given a separate ```span``` element with a class of "seo" for styling purposes.
The navigation links are placed within a ```nav``` (previously ```dev```) element, which signifies a set of navigation links for the current page.

## Main content 
The main content of the website is wrapped in a ```main``` element, which represents the main content of the document, what the page is really about.
Each section of the main content (like "Search Engine Optimization", "Online Reputation Management", and "Social Media Marketing") is marked with a ```section``` element, which indicates that the content within it is grouped under a thematic heading.
Each section starts with an ```h2``` element to provide a heading for the content and help with SEO. 
The images within each section are given an alt attribute, which describes the content of the image for screen readers and search engines.

## Aside
The section containing the company's services is wrapped in an ```aside``` element, which represents a portion of a document whose content is only indirectly related to the main content.
Each benefit is contained in a separate ```section``` element, which represents a standalone section of the content.
Each benefit is introduced with an ```h3``` element, providing a subheading for the content.

## Footer
The bottom section of the website is wrapped in a ```footer``` element, which represents a footer, which is the element that will go at the very end of the page and often contains social links and other generic information. 

## Changes 

The ```html``` element has a lang attribute set to "en-gb" to specify the language of the document as British English.
The ```meta``` element within the ```head``` section specifies the character encoding for the HTML document.
The ```link``` element within the ```head``` section references an external CSS file to style the website.
The website title is set to "Horiseon Website" using the ```title``` element within the ```head``` section.
All the ```dev``` elements have been changed for a more explanatory element, such as ```nav```, ```aside```, ```section```. 
The CSS has also been amended to align with DRY coding. 




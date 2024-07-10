# Advanced HTML


## Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

- Which guidelines to follow for HTML
- How to create the skeleton of an HTML5 page
- How to use semantic HTML tags to structure a web page
- Which use cases to use div vs span
- The semantic value’s of header, main, footer, article, nav, section, aside
- How to use headings (and why it’s important to follow the hierarchical order)
- How to make lists in HTML
- The differences between medias (SVG, GIF, PNG, JPG)
- How to structure data in a table
- How to integrate a video in a webpage
- How to integrate an audio file in a webpage
- How to embed external content
- How to correctly structure an HTML page

## Requirements
- A README.md file at the root of the folder of the project is mandatory
- Your code should be W3C compliant and validate with W3C-Validator
- Techium will be the name of the company we will use across our webpages.

# Tasks
## 0. Create your first webpage
Create your first HTML file 0-index.html with:

- Add the doctype on the first line (without any comment)
- After the doctype, open and close a html tag
- Add the language tag, specify English for ISO language code and add the direction tag (ltr or rtl) on the html tag.
- Open your file in your browser (the page should be blank)
- W3C won’t pass - you can ignore it

Repo:

- GitHub repository: holbertonschool-web_front_end
- Directory: html_advanced
- File: 0-index.html


## 1. Structure your webpage
Copy the content of 0-index.html into 1-index.html

Create the head and body sections

- inside the html tag, create the head and body tags (empty) in this order
- W3C won’t pass - you can ignore it

Repo:

- GitHub repository: holbertonschool-web_front_end
- Directory: html_advanced
- File: 1-index.html

## 2. The head - meta charset, viewport, title, description, favicons
Copy the content of 1-index.html into 2-index.html

## Meta charset:

- add a meta tag inside the head:
- add the charset attribute with the value utf-8

## Viewport:

- add a meta tag inside the head:
- add an attribute name on the tag and specify that it is the meta viewport
- add the key width with the value device-width
- add the key initial-scale with the value 1.0
- add the key viewport-fit with the value cover

## Title:

- add the title tag just after the meta viewport with value: Homepage - Techium

## Description:

- add a meta tag inside the head section
- add an attribute name on the tag and specify that is the meta description
- add another attribute called content
- add the following description: Techium is a digital agency

## Favicons:

- download the image above to use as a favicon
- Use the tool at https://realfavicongenerator.net/ to generate all the favicon formats
- take the favicon.ico and favicon.png and place these at the root of your project directory, so that it is siblings with your [0-9]+-index.html files.
- inside the head, create 2 link tags with these 3 attributes: rel, type, and href.
- the first link tag:
- rel: icon
- type: image/x-icon
- href: ./favicon.ico
- the second link tag:
- rel: icon
- type: image/png
- href: ./favicon.png

Repo:

- GitHub repository: holbertonschool-web_front_end
- Directory: html_advanced
- File: 2-index.html

# 3. Simple header, main, footer
Copy the content of 2-index.html into 3-index.html

## Header:

- create the header of your page between the open and close body tag
- put the text Header inside the header

## Main:

- create the main tag after the header tag
- put the text Main content inside your main tags

## Footer:

- create the footer tag after the main tag
- put the text Footer inside the footer tags

Repo:

- GitHub repository: holbertonschool-web_front_end
- Directory: html_advanced
- File: 3-index.html

# 4. Aside
Copy the contents of 3-index.html into article.html

- change the <title> to put: Article - Techium
- inside the main tags
- after the text, create the aside tags with text Aside

Repo:

- GitHub repository: holbertonschool-web_front_end
- Directory: html_advanced
- File: article.html

# 5. Section
Copy the content of 3-index.html into 5-index.html

- inside your <main> section
- remove the text in main, create these sections:
- create first section and put the text Hero section inside
- create second section and put the text Services section inside
- create third section and put the text Works section inside
- create fourth section and put the text About section inside
- create fifth section and put the text Latest news section inside
- create sixth section and put the text Testimonials section inside
- create seventh section and put the text Contact section inside
- Does not need to pass W3C

Repo:

- GitHub repository: holbertonschool-web_front_end
- Directory: html_advanced
- File: 5-index.html

# 6. Work, News, Testimonial articles
Copy the content of 5-index.html into 6-index.html

## Work articles:

- inside the section Works section
- add 3 article tags
- inside each article write Work # where the hashtag will be the ordered number (1, 2, or 3)

## News articles:

- inside the section Latest news section
- add 3 article tags
- inside each article write Article # where the hashtag will be the ordered number (1, 2, or 3)

## Testimonial articles:

- inside the section Testimonials section
- add 3 article tags
- inside each article write Testimonial # where the hashtag will be the ordered number (1, 2, or 3)
- W3C won’t pass - you can ignore it

Repo:

- GitHub repository: holbertonschool-web_front_end
- Directory: html_advanced
- File: 6-index.html
  

# 7. Navigation
Copy the content of 6-index.html into 7-index.html

- remove the Header text inside the <header>
- create the nav tag inside the header tag
- it should remain empty for now
- Does not need to pass W3C

Repo:

- GitHub repository: holbertonschool-web_front_end
- Directory: html_advanced
- File: 7-index.html
  

# 8. Level 1 headings
Copy the content of 7-index.html into 8-index.html

- create the level 1 heading inside your main before your sections
- put text Homepage in your heading tag
- Does not need to pass W3C

Repo:

- GitHub repository: holbertonschool-web_front_end
- Directory: html_advanced
- File: 8-index.html
  

# 9. Level 2 headings
Copy the content of 8-index.html into 9-index.html

- in the section tag with the the text Hero section, remove the text and create a level 2 heading with text We help you build your brand!
- in the section tag with the the text Services section, remove the text and create a level 2 heading with text Services
- in the section tag with the the text Works section, remove the text and create a level 2 heading with text Works
- in the section tag with the the text About section, remove the text and create a level 2 heading with text About Us
- in the section tag with the the text Latest news section, remove the text and create a level 2 heading with text Latest news
- in the section tag with the the text Testimonials section, remove the text and create a level 2 heading with text Testimonials
- in the section tag with the the text Contact section, remove the text and create a level 2 heading with text Contact
- W3C won’t pass - you can ignore it

Repo:

- GitHub repository: holbertonschool-web_front_end
- Directory: html_advanced
- File: 9-index.html
  

# 10. Level 3 headings
Copy the content of 9-index.html into 10-index.html

## Services headings:

- Inside the section containing the h2 heading Services, add these elements right after the h2:
- create a level 3 heading with text Design & Concept
- create a level 3 heading with text Digital Strategy
- create a level 3 heading with text Content Strategy
- create a level 3 heading with text UX Design
- create a level 3 heading with text Web Development
- create a level 3 heading with text Social Media

## Works headings:

- Inside the section containing the h2 heading Works:
- in the first article, replace the text with a level 3 heading with text Interior Design
- in the second article, replace the text with a level 3 heading with text Web Development
- in the third article, replace the text with a level 3 heading with text Personal Brand

## About Us headings:

- Inside the section containing the h2 heading About Us, after the h2 heading, create these elements in this order:
- a level 3 heading with text Who are we
- a level 3 heading with text Our culture
- a level 3 heading with text How we work

## Latest news headings:

- Inside the section containing the h2 heading Latest news:
- in the first article replace the text with a level 3 heading with text Hoc loco tenere se Triarius non potuit.
- in the second article replace the text with a level 3 heading with text Ut alios omittam, hunc appello, quem ille unum secutus est.
- in the third article replace the text with a level 3 heading with text Bestiarum vero nullum iudicium puto.
- W3C does not need to pass here

Repo:

- GitHub repository: holbertonschool-web_front_end
- Directory: html_advanced
- File: 10-index.html
  

# 11. styleguide
Copy the content of 3-index.html into 11-styleguide.html

- change the title to Styleguide - Techium
- remove the text from header, main, and footer
- create a new <section> inside your main tag
- create a header in this section
- in the header add a level 2 heading with text Headings
- after the header:
- add a level 1 heading with text Heading level 1
- add a level 2 heading with text Heading level 2
- add a level 3 heading with text Heading level 3
- add a level 4 heading with text Heading level 4
- add a level 5 heading with text Heading level 5
- add a level 6 heading with text Heading level 6

Repo:

- GitHub repository: holbertonschool-web_front_end
- Directory: html_advanced
- File: 11-styleguide.html
  

# 12. Paragraphs
Copy the content of 10-index.html into 12-index.html

About Us paragraphs:

- in the About Us section
- after the first h3 (who are we) create a paragraph with the text: Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsum, omnis expedita! Eum, praesentium cumque accusantium rem, sit quaerat est nisi ratione, deserunt ducimus quidem iste dicta quibusdam atque maxime cum!
- after the second h3 create a paragraph with the text: Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsum, omnis expedita! Eum, praesentium cumque accusantium rem, sit quaerat est nisi ratione, deserunt ducimus quidem iste dicta quibusdam atque maxime cum!
- after the third h3 create a paragraph with the text: Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsum, omnis expedita! Eum, praesentium cumque accusantium rem, sit quaerat est nisi ratione, deserunt ducimus quidem iste dicta quibusdam atque maxime cum!

## Latest news paragraphs:

- in the Latest news section
- in the first article
- create a paragraph with text Career before the heading
- create a paragraph with text Lorem ipsum dolor sit amet, consectetur adipiscing elit. Id Sextilius factum negabat. Quo tandem modo? At eum nihili facit; Quae contraria sunt his, malane? after the heading
- in the second article
- create a paragraph with text Digital Life before the heading
- create a paragraph with text Lorem ipsum dolor sit amet, consectetur adipiscing elit. Tum mihi Piso: Quid ergo? Tum ille: Ain tandem? Non autem hoc: igitur ne illud quidem. Sed quod proximum fuit non vidit. Nos commodius agimus. An nisi populari fama? after the heading
- in the third article
- create a paragraph with text Social before the heading
- create a paragraph with text Lorem ipsum dolor sit amet, consectetur adipiscing elit. Non igitur bene. Quid enim est a Chrysippo praetermissum in Stoicis? Pugnant Stoici cum Peripateticis. Prioris generis est docilitas, memoria; Apparet statim, quae sint officia, quae actiones. after the heading

## Contact paragraph:

- in the Contact section after the heading
- create a paragraph with the text: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Id Sextilius factum negabat. Quo tandem modo? At eum nihili facit; Quae contraria sunt his, malane?

## Additional paragraphs:

- below the level 2 Services heading add a paragraph with text We work with you
- below the level 2 Works heading add a paragraph with text Take a look in our portfolio
- below the level 2 About Us heading add a paragraph with text Everything about us
- below the level 2 Testimonials heading add a paragraph with text We are more than a digital company
- below the level 2 Contact heading add a paragraph with text We like to know new people

Does not need to pass W3C

Repo:

- GitHub repository: holbertonschool-web_front_end
- Directory: html_advanced
- File: 12-index.html
  

# 13. styleguide paragraphs
Copy the contents of 11-styleguide.html into 13-styleguide.html

- After the existing section containing Headings, create a new section in main
- in this section create a header
- Inside the header, create a level 2 heading with text Paragraph
- after the header add a level 2 heading with text Heading with a subtitle
- after the level 2 heading, add a paragraph with text This is my subtitle
- after the last paragraph, add another paragraph with text: Nunc lacinia ante nunc ac lobortis. Interdum adipiscing gravida odio porttitor sem non mi integer non faucibus ornare mi ut ante amet placerat aliquet. Volutpat eu sed ante lacinia sapien lorem accumsan varius montes viverra nibh in adipiscing blandit tempus accumsan.

Repo:

- GitHub repository: holbertonschool-web_front_end
- Directory: html_advanced
- File: 13-styleguide.html
  

# 14. Span
Copy the contents of 12-index.html into 14-index.html

In the very first <header>,

- before the nav, create a span with the text Techium
Does not need to pass W3C

Repo:

- GitHub repository: holbertonschool-web_front_end
- Directory: html_advanced
- File: 14-index.html
  

15. Div
Copy the contents of 14-index.html into 15-index.html

- Wrap the contents of the header element with a div
- Wrap the content of each section element within a div
- Finally, wrap the contents of the <footer> tag with a div
- W3C does not need to pass

Repo:

- GitHub repository: holbertonschool-web_front_end
- Directory: html_advanced
- File: 15-index.html
  

# 16. Structure your sections
Copy the contents of 15-index.html into 16-index.html

- in the div in the Services section
- create a header tag that wraps the h2 and the p
- create a div sibling to the header that wraps the rest of the content
- in the div in the Works section
- create a header tag that wraps the h2 and the p
- create a div sibling to the header that wraps the rest of the content
- in the div in the About Us section
- create a header tag that wraps the h2 and the p
- create a div sibling to the header that wraps the rest of the content
- in the div in the Latest news section
- create a header tag that wraps the h2
- create a div sibling to the header that wraps the rest of the content
- in the div in the Testimonials section
- create a header tag that wraps the h2 and the p
- create a div sibling to the header that wraps the rest of the content
- in the div in the Contact section
- create a header tag that wraps the h2 and the first p
- create a div sibling to the header that wraps the rest of the content
- W3C does not need to pass

Repo:

- GitHub repository: holbertonschool-web_front_end
- Directory: html_advanced
- File: 16-index.html
  

17. Comments
Copy the content of 16-index.html into 17-index.html

- before the header add a line break and a comment saying Header to help with scanning your code
- before the main add a line break and a comment saying Main to help with scanning your code
- before the footer add a line break and a comment saying Footer to help with scanning your code
- before the Hero section add a line break and a comment saying Hero section
- before the Services section add a line break and a comment saying Services section
- before the Works section add a line break and a comment saying Works section
- before the About Us section add a line break and a comment saying About Us section
- before the Latest news section add a line break and a comment saying Latest news section
- before the Testimonials section add a line break and a comment saying Testimonials section
- before the Contact section add a line break and a comment saying Contact section
- Does not need to pass W3C

Repo:

- GitHub repository: holbertonschool-web_front_end
- Directory: html_advanced
- File: 17-index.html
  

18. link your logo
Copy the content of 17-index.html into 18-index.html

- in the header, wrap the span with a link that redirects to the page at the root of your folder (/)
- wrap the link with a div
- W3C does not need to pass

Repo:

- GitHub repository: holbertonschool-web_front_end
- Directory: html_advanced
- File: 18-index.html
  

19. Create new pages
Copy the content of 18-index.html into about.html, latest_news.html and contact.html

- change the title of about.html to replace Homepage with About
- change the title of latest_news.html to replace Homepage with Latest news
- change the title of contact.html to replace Homepage with Contact
- Does not need to pass W3C

Repo:

- GitHub repository: holbertonschool-web_front_end
- Directory: html_advanced
- File: about.html, latest_news.html, contact.html
  

20. Add links
Copy the content of 18-index.html into 20-index.html

- in your nav tags
- create a link to / with the text Home
- create an anchor to services with the text Services
- create an anchor to works with the text Works
- create an anchor to about with the text About
- create an anchor to latest_news with the text Latest news
- create an anchor to testimonials with the text Testimonials
- create an anchor to contact with the text Contact
- For now, the anchor links will not work. We will make them work in the CSS project.

Does not need to pass W3C

Repo:

- GitHub repository: holbertonschool-web_front_end
- Directory: html_advanced
- File: 20-index.html




# HTML Comprehension Questions


## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [F] `<div><span>hello</div></span>`

b) [F]

```html
<ul>
<li>one</li>
</ol>
```

c) [F] `<ul></ul><img/><ol><li>one</li></ol>`


## Q2 - What is a screenreader and why should we care about them?

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_
A screenreader translates website information to speech, through a text-to-speech enginge, or braille, through a refreshable braille display, to the visually impaired.

https://www.nomensa.com/blog/2005/what-screen-reader


## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation

img to include the photos, maybe a section semantic tag to contain the photo section.

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
Either an ol or ul of a href="" tags. Add li for each a tag for bullet or numbered points.

c) You want to sell designer hats. You need to receive orders from the user.

img = product photo, div = to create card, h1 = name of product, h2 = name of designer, p = product copy, btn = purchase button, 

## Q4 - Can a button be a child of a button? Explain your reasoning

No, a button cannot be a child of a button. This is because button child elements are reserved for phrasing content, like text or img.




## Q5 - What is the most generic tag you can use?
div



## Q6 - What do the following achronyms stand for?

a) `a` - anchor element

b) `ol` - ordered list

c) `ul` - unordered list

d) `li` - list item

e) `tr` - table row

f) `th` - table head

g) `td` - table data


## Q7 - Usually, `td` elements are children of what kind of elements?
table


## Q8 - What is the difference between td and th?
th are cells that appear on top of the table and indicate column titles and have a small bottom padding. td are cells that appear within rows and have no padding between cells. 


## Q9 - Which tag makes the text appear bigger: h1 or h3?
h1


## Q10 - In which situation can you use self closing tags?
Certain tags allow self closing and dont follow a strict structure, like area or input, but for semantical purposes, you should always follow best practices with closing tags.


## Q11 - What is autofilling and why is it important?
Autofilling automates completion of filling form fields with pre-configured values. This is important for user experience because it minimizes cognitive overload.


## Q12 - Which attributes are always present in an img element?
src 


## Q13 - Which attribute is always present for an anchor tag?
href



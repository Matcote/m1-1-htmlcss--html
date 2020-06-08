# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [False] `<div><span>hello</div></span>`

b) [False]

```html
<ul>
<li>one</li>
</ol>
```

c) [False] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

A screenreader is a program that reads out the content of a web page to a user. Screenreaders are typically used by blind people who can not read the text on a page by themselves. We should care about them to make our site/page as accessible as possible for as many people as possible.

source: https://webaccess.berkeley.edu/ask-pecan/what-is-a-screen-reader

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation

<img />

b) You want to create a website that lists all the art gallery websites in your city and links to their website.

<ul><li><a></a></li></ul>

c) You want to sell designer hats. You need to receive orders from the user.

<form><input></input><form>

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning
A button can not be the child of a button. The child of a button can not be another clickable element. A button is clickable, and its child usually determines what the clickable button looks like (whether it is text, an image, etc..).

## Q5 - What is the most generic tag you can use?

<div>

## Q6 - What do the following achronyms stand for?

a) `a`

anchor

b) `ol`

ordered list

c) `ul`

unordered list

d) `li`

list item

e) `tr`

table row

f) `th`

table head

g) `td`

table data

## Q7 - Usually, `td` elements are children of what kind of elements?

<tr>

## Q8 - What is the difference between td and th?

they are the same except that th is used to indicate that that cell is the header of that column in the table. 

## Q9 - Which tag makes the text appear bigger: h1 or h3?

h1

## Q10 - In which situation can you use self closing tags?

when an element has no children (ex: img tags)

## Q11 - What is autofilling and why is it important?

autofilling is something many browsers can now do, where instead of filling in every input in a form, the browser can automatically fill the remaining inputs after the first one is filled based on the users past form submissions. This is important to take into account because many users love this feature and not having it on your web page is a pain in the users butt.

## Q12 - Which attributes are always present in an img element?

src and alt

## Q13 - Which attribute is always present for an anchor tag?

href
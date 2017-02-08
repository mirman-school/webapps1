# 2: Link it Up
Alright, time to move on from the Markdown training wheels. Time to make web content for real. This will require both HTML and CSS. First, we need to connect our HTML to our CSS. A special tag inside our `<head>` element will accomplish this.

## The `<link>` tag.
As [W3Schools](http://www.w3schools.com/tags/tag_link.asp) says, `<link>`s define a relationship between an HTML file and an external document. Mostly, we use this for CSS files.

### `<link>` Attributes
Any information that goes inside of an HTML tag is called an **attribute**. Attributes define behavior of an element. For `<link>` tags, we need three attributes:

1. `rel`
2. `type`
3. `href`

In more detail...

Attribute | Purpose | Value
--|--
`rel` | Defines the relationship of the linked file to the HTML | `stylesheet`
`type` | Defines what file format the link should be read | `text/css`
`href` | Defines the (relative) path to the file | `<something>.css`

## Primary Objective: Get CSS Functioning
Create a proper `<link>` tag, with appropriate attributes, to style `index.html`.

Inside the CSS, write style rules for `<h2>`, an ID of `foo`, and a class of `bar`.

(How do we define rules for ids and classes?)

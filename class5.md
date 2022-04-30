# Design Web Pages with CSS

# What is CSS?

If HTML is the skeleton of a website, CSS (which stands for Cascading Style sheets) is the skin. CSS is gives a website it's own style while the browser is just applying it's default - very basic - style.

# CSS Syntax

Being a rule-based language, in CSS you identify an element or group of elements on your website and apply a group of styles. This is defining the rules.

For example, if you wanted to change the color of text to green in every paragraph and make them bold, it would look like this:

> p {
    color: green;
    font-weight: bolder;
}/

Let's break this down:
* The first thing in a rule is a selector. It selects the HTML element you are going to style. For the example above, we are styling any `<p>` element.
* All the stylings in a rule need to surrounded by curly braces `{ }`.
* The styling comes in the form of **declaratiions**, which include a **property** and a **value**, respectively. As you can see, they are separated by a colon and a space and the declaration ends with a semi-colon.
* If you want to be more specific about what element(s) your style will affect, you can assign an 'id' or 'class' to an element (ex: `<p id="imp-graph">`; `<nav class="nav-bar2">`)/. Select the element to style by typing `#` or `.`, respectively, then the name (ex: `#imp-graph`; `.nav-bar2`)/.

# Three Ways to Insert CSS
1. External CSS - A style sheet saved with a .css extension. A reference to the external style sheet must be included in the HTML page inside the head section inside a `<link>` element (ex: `<link rel="stylesheet" href="styles.css">`)/.
2. Internal CSS - A style sheet inserted right onto the HTML page. It needs to be in the head section inside a `<style>` element/.
3. Inline CSS - A style used to apply a unique style to a single element. It is coded right into the opening tag (ex: `<h1 style="color:blue;text-align:center;">`)/. Inline style has the highest priority.
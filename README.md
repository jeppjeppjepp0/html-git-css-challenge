# HTML, Git, CSS challenge


## Technology Used 

| Technology Used         | Resource URL           | 
| ------------- |:-------------:| 
| HTML    | [https://developer.mozilla.org/en-US/docs/Web/HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) | 
| CSS     | [https://developer.mozilla.org/en-US/docs/Web/CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)      |   
| Git | [https://git-scm.com/](https://git-scm.com/)     |    

<hr/>

## Description 

[Visit the Deployed Site](https://jeppjeppjepp0.github.io/html-git-css-challenge/)

This challenge's goal is to modify a given codebase to meet accessibility standards by reading and understanding HTML and CSS files. The specific criteria are given below.

```md
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

<hr/>

## Table of Contents

* [Code Refactor Example](#code-refactor-example)
* [Learning Points](#learning-points)
* [Author Info](#author-info)

<hr/>

## Code Refactor Example

```html
<div class="header">
    <h1>Hori<span class="seo">seo</span>n</h1>
    <div>
        <ul>
            <li>
                <a href="#search-engine-optimization">Search Engine Optimization</a>
            </li>
            <li>
                <a href="#online-reputation-management">Online Reputation Management</a>
            </li>
            <li>
                <a href="#social-media-marketing">Social Media Marketing</a>
            </li>
        </ul>
    </div>
</div>
```

One of the bigger changes I made to the given code was to change the header class to the semantic html tag. These changes were also reflected in the style.css file.

```html
<header>
    <h1>Hori<span class="seo">seo</span>n</h1>
    <div>
        <!--links to navigate page (to content section)-->
        <ul>
            <li>
                <a href="#search-engine-optimization">Search Engine Optimization</a>
            </li>
            <li>
                <a href="#online-reputation-management">Online Reputation Management</a>
            </li>
            <li>
                <a href="#social-media-marketing">Social Media Marketing</a>
            </li>
        </ul>
    </div>
</header>

```



```css
.benefit-lead {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-brand {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}
```

Since all three of these classes applied the same commands, I rewrote them to all be contained within one class (seen below). This same process was applied to the sub-content class.

```css
.benefit-sub {
    margin-bottom: 32px;
    color: #ffffff;
}

```

<hr/>

## Learning Points 

This project helped test basic knowledge of HTML, CSS, and Git flow. 

The most important lessons learned in HTML from this challenge would be semantic HTML elements, and the application of classes and ID tags. These especially helped in relation to CSS since semantic elements, classes, and ID tags are all used to apply CSS styling. 

On the CSS side of things, the code became much more legible when each of the repetitive elements were collapsed into one. It also became much easier to understand the CSS when the elements were organized to match the order in which they appeared within the HTML file.

This project also helped solidify the Git workflow, including git add, git commit, and git push. 

<hr/>

## Author Info

```md
### Jedd Javier


* [Portfolio](N/A)
* [LinkedIn](https://www.linkedin.com/in/jedd-javier-4b323426b/)
* [Github](github.com/jeppjeppjepp0)
```
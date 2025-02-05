# INFO 1300(SP25) - Activity - Box Model Practice

In this activity we will practice using the box model and styling a navigation bar.

This is a practice activity; not for credit. Feel free to expand as inspired.

## Instructions 

- note the `styles` sub-folder and the `site.css` file inside
  - review these styling rules and observe what they do 
  
- lets style a nav bar by incrementally adding these rules:
            
            /* 1. remove the spacing */

            nav menu {
                  margin: 0;
                  padding: 0;
            }
            
            /* 2. remove the bullets from the list items */

            nav menu li {
                  list-style: none;
            }
            
            /* 3. make the links display as block; and add some spacing */

            nav menu li a {
                  display: block;
                  padding: 10px;
            }
            
            /* 4. add a hover effect */

            nav menu li a:hover {
                  background-color: red;
            }

- explore other properties
  

## Coding Resources

- **CSS Reference:** [MND CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
  - [MND Text Styling Guide](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Text_styling/Fundamentals)
  - [Colors by Name](https://developer.mozilla.org/en-US/docs/Web/CSS/named-color)
  - [Selectors](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/picture)
  
## VS Code and Development Server

- **To Code**: Open this repository as a Codespace on GitHub.
- **To View Site**: Start the web server by clicking "Go Live" in the bottom right-hand corner.
  - Once the web server has started, view the website in a web browser by clicking "Open in Browser".

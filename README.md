# CSS-Cheatsheet

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3d/CSS.3.svg/1200px-CSS.3.svg.png" alt="CSS Logo" width="200px">

## Selectors

| Selectors        | CSS Syntax                            |
| ---------------- |:-------------------------------------:|
| Universal        | ```* {} ```                           |
| ID               | ``` #ID {} ```                        |
| Class            | ``` .class {} ```                     |
| Type             | ``` h1, h2, h3 {} ```                 |
| Adjacent Sibling | ``` h1 + p {} ```                     |
| Child            | ``` ul > li {} ```                    |
| General Sibling  | ``` h1 ~ p {} ```                     |
| Descendant       | ``` p a {} ```                        |
| Atrribute        | ``` div[attribute="somevalue"] {} ``` |

## Pseudo Selectors & Elements

| Selectors                      | CSS Syntax                            |
| ------------------------------ |:-------------------------------------:|
| Mouse Over                     | ```a:hover {} ```                     |
| Active Link                    | ``` a:active {} ```                   |
| Focus                          | ``` input:focus {} ```                |
| Visited Link                   | ``` a:visited {} ```                  |
| Link                           | ``` .class:link {} ```                |
| checked Elements               | ``` input:checked {} ```              |
| Disabled                       | ``` input:disabled {} ```             |
| Enabled                        | ``` input:enabled {} ```              |
| Not a specified Element        | ``` :not(p) {} ```                    |
| First Line                     |  ``` p""first-line {} ```             |
| First Letter                   | ``` p::first-letter {} ```            |
| First Child                    | ``` p:first-child {} ```              |
| Last Child                     | ``` p:last-child {} ```               |
| Only Child                     | ``` p:only-child {} ```               |
| :nth-child                     | ``` p:nth-child() {} ```              |
| First Element of its parent    | ``` p:first-of-type ```               |
| Elements that have no children | ``` p:empty {} ```                    |
| Before Element                 | ``` .class::before {} ```             |
| After Element                  | ``` .class::after {} ```              |

## Position

| Selectors            | CSS Syntax                                                     |
| ---------------------|:--------------------------------------------------------------:|
| Position             | ```position: static, relative, absolute, fixed, sticky ```     |
| Properties           | ``` top, right, bottom, left ```                               |
| Float                | ``` float: left, right, none ```                               |
| Clear float          | ``` clear: none, left, right, both ```                         |
| Z index              | ``` z-index: 3,  auto,  inherit ```                            |


## Background

| Selectors             | CSS Syntax                                                                     |
| ----------------------|:------------------------------------------------------------------------------:|
| Background Image      | ```background-image: url() ```                                                 |
| Background Repeat     | ``` background-repeat: repeat-x, repeat-z, repeat, space, round, no-repeat ``` |
| Background Attachment | ``` background-attachment : scroll, fixed, local, inital, inherit ```          |
| Background Colour     | ``` background-color: #2AA9E0 ```                                              |
| Background Position   | ``` background-position: top, right, bottom, left, center ```                  |




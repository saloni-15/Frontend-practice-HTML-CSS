## ⭐Specificity of selectors

Element < .class < #id < inline-styling

## ⭐PSEUDOSELECTORS

A pseudo-class is used to define a special state of an element.

For example, it can be used to:

- Style an element when a user mouses over it
- Style visited and unvisited links differently
- Style an element when it gets focus

### Syntax-

```
selector:pseudo-class {
property: value;
}
```

### Types of pseudoselectors-

- :hover
- :active
- :first-child
- :nth-child
  etc...

## ⭐ADVANCED SELECTORS

- **Adjacent Sibling Selector**: It selects all the elements that are adjacent siblings of specified elements. It selects the second element if it immediately follows the first element.
  Syntax: It select ul tags which immediately follows the h4 tag.

```
h4+ul{
    border: 4px solid red;
}
```

- **General Sibling Selector**: It selects only the first element if it follows the first element and both children are of the same parent element. It is not necessary that the second element immediately follows the first element.
  Syntax: Changes to the span element content which follows paragraph tag and both have same parent tag.

```
p ~ span {
    color: red;
}
```

- **Direct Child Selector**: It selects any element matching the second element that is a direct child of an element matching the first element. The element matched by the second selector must be the immediate children of the elements matched by the first selector.
  Syntax:

```
p > div {
    background-color: DodgerBlue;
}
```

- **Decendant Selector**: It makes changes only to those elements which are inside the other element.
  Syntax: Select all the anchor tags which are inside ‘li’ element which are inside ‘ul’ element.

```
ul li a{
    color: red;
}
```

- **Attribute Selector**: It selects a particular type of inputs.
  Syntax:

```
input[type="checkbox"]{
    background:orange;
}
```

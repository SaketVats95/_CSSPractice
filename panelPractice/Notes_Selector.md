## CSS Selector :

### divide CSS selectors into five categories:

* Simple selectors (select elements based on name, id, class)
* Combinator selectors (select elements based on a specific relationship between them)
* Pseudo-class selectors (select elements based on a certain state)
* Pseudo-elements selectors (select and style a part of an element)
* Attribute selectors (select elements based on an attribute or attribute value)

### Group Selector Example:

```CSS
h1 {
  text-align: center;
  color: red;
}

h2 {
  text-align: center;
  color: red;
}

p {
  text-align: center;
  color: red;
}
```

* Can be written as 
  
```

h1, h2, p {
  text-align: center;
  color: red;
}
```

### BackGround

* background-color
* background-image
* background-repeat
* background-attachment
* background-position

BG Color with Opacity/Transparency

```div {
  background-color: green;
  opacity: 0.3;
}

When using the opacity property to add transparency to the background of an element, all of its child elements inherit the same transparency. This can make the text inside a fully transparent element hard to read.
```


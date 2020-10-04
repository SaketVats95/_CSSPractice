## Border Properties

The border-style property specifies what kind of border to display.

The following values are allowed:

* dotted - Defines a dotted border
* dashed - Defines a dashed border
* solid - Defines a solid border
* double - Defines a double border
* groove - Defines a 3D grooved border. The effect depends on the border-color value
* ridge - Defines a 3D ridged border. The effect depends on the border-color value
* inset - Defines a 3D inset border. The effect depends on the border-color value
* outset - Defines a 3D outset border. The effect depends on the border-color value
* none - Defines no border
* hidden - Defines a hidden border
     
    
The border-style property can have from one to four values (for the top border, right border, bottom border, and the left border).


### Rounded Border :
```
p {
  border: 2px solid red;
  border-radius: 5px;
}
```


border property is a **shorthand property** for the following individual border properties:
```
border-width
border-style (required)
border-color
p {
  border: 5px solid red;
}
```

### Padding Propeties:

```
padding property has four values:

padding: 25px 50px 75px 100px;
top padding is 25px
right padding is 50px
bottom padding is 75px
left padding is 100px
Example
Use the padding shorthand property with four values:

div {
  padding: 25px 50px 75px 100px;
}
```

### Outline Offset

The outline-offset property **adds space between an outline and the edge/border** of an element. The space between an element and its outline is transparent.


```
p {
  margin: 30px;
  border: 1px solid black;
  outline: 1px solid red;
  outline-offset: 15px;
}
```
## Box Model

```
Content - The content of the box, where text and images appear
Padding - Clears an area around the content. The padding is transparent
Border - A border that goes around the padding and content
Margin - Clears an area outside the border. The margin is transparent
```

```
div {
  width: 300px;
  border: 15px solid green;
  padding: 50px;
  margin: 20px;
}

Calculation :
320px (width)
+ 20px (left + right padding)
+ 10px (left + right border)
+ 0px (left + right margin)
= 350px
```
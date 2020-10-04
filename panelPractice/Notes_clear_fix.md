## The clear Property

The clear property specifies what elements can float beside the cleared element and on which side.

The clear property can have one of the following values:

none - Allows floating elements on both sides. This is default
left - No floating elements allowed on the left side
right- No floating elements allowed on the right side
both - No floating elements allowed on either the left or the right side
inherit - The element inherits the clear value of its parent
The most common way to use the clear property is after you have used a float property on an element.

When clearing floats, you should match the clear to the float: If an element is floated to the left, then you should clear to the left. Your floated element will continue to float, but the cleared element will appear below it on the web page.
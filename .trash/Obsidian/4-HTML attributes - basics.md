# HTML attributes are used to provide additional information about an element, define its properties, or configure an element's behavior in certain ways.

Attributes usually come in name/value pairs like `name="value"` and are always defined in the start tag of an HTML element. Here are some commonly used HTML attributes:

1. **class**: 
	This attribute is used to specify one or more class names for an element. The class attribute is mostly used to point to a class in a style sheet. But it can also be used by JavaScript to access and manipulate elements with the specific class name.
	
	Example:
```HTML
<div class="myClass">This is a text inside a div element.</div>
```

2. **id**: 
	The id attribute specifies a unique id for an HTML element. It is mostly used to point to a style in a style sheet, and by JavaScript to manipulate the element with the specific id.
	
	Example:
```HTML
<div id="myID">This is another text inside a div element.</div>
```

3. **style**: 
	The style attribute is used to add styles to an element, such as color, font, size, and more. It's a good practice to keep your CSS separate from HTML in an external style sheet, but this can be useful for small projects or testing.
	
	Example:
```HTML
<p style="color:blue;">This is a blue paragraph.</p>
```

4. **src**: 
	The src attribute is required for elements like `<img>`, `<script>`, and `<iframe>`. It specifies the source URL for an image, a script, or a frame.

	Example:
```HTML
<img src="image.jpg" alt="My Image">
```

5. **alt**: 
	The alt attribute provides an alternative description for an image. It's displayed if for some reason the image cannot be loaded and is also useful for accessibility purposes, as screen readers use this to describe images to visually impaired users.

	Example:
```html
<img src="image.jpg" alt="A description of the image">
```

6. **href**: The href attribute is used in anchor (`<a>`) tags to specify the URL of the page the link goes to. [[4.1 -HTML attributes - href]]

	Example:
```html
<a href="https://www.example.com">Visit Example.com</a>
```

7. **width** and **height**: These attributes are used to specify the width and height of elements like `<img>`, `<table>`, `<td>`, `<th>`, `<canvas>`, and `<iframe>`.

	Example:
```html
<img src="image.jpg" alt="My Image" width="500" height="600">
```
This is just the start—there are many more HTML attributes! Let me know if you have any questions about these or if you'd like to learn about others.

[[4.2-HTML attributes - tags - basics - action, method attributes]]
[[4.3-HTML attributes - 4 must have attributes - for in label, placeholder in input, value in input, required in input]]

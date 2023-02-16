# HTML Attributes 🔑
HTML attributes provide additional information about an HTML element, such as the element's 🔍 id, 🤝 `class`, and 💅 `style`. Attributes are specified using key-value pairs within the opening tag of an element.

The `id` Attribute 🔍
The 🔑 `id` attribute is used to uniquely identify an HTML element on a page. It is commonly used for linking to specific parts of a page, creating style rules that target a specific element, or for JavaScript manipulation. To set an `id` attribute, add the attribute to the opening tag of the element, followed by a unique identifier:

```html
<div id="my-element">
  This is my element! 👋
</div>
```
In this example, we've set the id attribute of a div element to "my-element". This identifier can then be used to target the element with CSS or JavaScript.

The `class` Attribute 🤝
The 🔑 `class` attribute is used to group elements together based on a shared characteristic. It is commonly used to apply styles to multiple elements at once or to target specific elements with JavaScript. To set a `class` attribute, add the attribute to the opening tag of the element, followed by a space-separated list of `class` names:

```html
<div class="my-class another-class">
  This is my element! 🤝
</div>
```
In this example, we've set the `class` attribute of a div element to "my-class" and "another-class". Multiple elements can share the same class name, allowing for easy styling or manipulation of related elements.

### The `style` Attribute 💅
The 🔑 `style` attribute is used to add inline styles to an HTML element. Inline styles are applied directly to the element and take precedence over external stylesheets and internal styles. To set a `style` attribute, add the attribute to the opening tag of the element, followed by one or more CSS property-value pairs:

```html
<div style="background-color: red; color: white;">
  This is my element! 💅
</div>
```
In this example, we've set the `style` attribute of a div element to add a red background color and white text color. While inline styles can be useful for quick and easy styling, it is generally recommended to use external stylesheets or internal styles for more complex styling needs.

### Other Common Attributes 📌
There are many other attributes that can be used to provide additional information about an HTML element, such as `title`, `alt`, and `href`. Here are a few examples:

`title`: provides additional information about an element, typically displayed as a tooltip when the user hovers over the element. 💬
```html
<img src="example.jpg" alt="A picture of an example" title="This is an example picture">
```
`alt`: specifies alternative text for an image if it cannot be displayed. 🖼️
```html
<img src="example.jpg" alt="A picture of an example">
```
`href`: specifies the URL of the page or file that the link goes to. 🔗

```html
<a href="https://www.example.com">Visit Example</a>
```
There are many more attributes available for different types of HTML elements. Encourage your students to explore and experiment with different attributes to see how they affect the behavior and appearance of their HTML elements. They can also check out attributes such as `data-`*, `src`, `width`, `height`, `target`, `name`, `type`, `value`
# MyFramework

![MyFramework Logo](https://i.ibb.co/DzS0ZRK/azada.png)

## What is MyFramework?

**MyFramework** is a lightweight HTML framework that introduces new custom tags such as `repeat` and `for` to simplify repetitive tasks and dynamic content creation in your HTML projects.

### Features
- **Custom Tags**:
  - `<repeat>`: Easily duplicate elements with varying data.
  - `<for>`: Simplify loops in HTML structure.
- Lightweight and easy to integrate.
- Enhances HTML's native functionality without a steep learning curve.

### Example Usage

```html
<repeat count="5">
  <p>Item: {{index}}</p>
</repeat>

<for each="item in items">
  <p>{{item.name}}</p>
</for>

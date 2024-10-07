# Top CSS Frontend Interview Questions and Answers

### 1. What is the difference between `inline`, `block`, and `inline-block` elements in CSS?

- **Inline**: Does not start on a new line, only takes up as much width as necessary, and you cannot set width and height.
- **Block**: Starts on a new line and takes up the full width of its container. You can set width and height.
- **Inline-block**: Like inline elements, but you can set width and height. It doesn’t force a new line but still respects block properties.

---

### 2. What is the CSS box model, and what are its elements?

The **CSS box model** defines how elements are displayed and the space they occupy. It consists of:

1. **Content**: The actual content of the element (text, images, etc.).
2. **Padding**: The space between the content and the border.
3. **Border**: A boundary surrounding the padding (optional).
4. **Margin**: The space outside the border, separating the element from others.

---

### 3. Explain the difference between `margin` and `padding` in CSS.

- **Margin**: The space **outside** the element’s border. It creates space between elements.
- **Padding**: The space **inside** the element’s border, between the content and the border.

---

### 4. What are pseudo-classes and pseudo-elements? Provide examples.

- **Pseudo-classes**: Used to define a special state of an element. Example: `:hover`, `:focus`.
  ```css
  a:hover {
    color: red;
  }
  ```
- **Pseudo-elements**: Used to style specific parts of an element. Example; `::before`, `::after`.
  ```css
  p::before {
    content: "Read this: ";
  }
  ```

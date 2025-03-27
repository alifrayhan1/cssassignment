## What are CSS Pseudo-Selectors?
Pseudo-selectors in CSS are special selectors that allow you to style elements based on their state, position, or other conditions that cannot be targeted using regular selectors. They are written using `:` or `::`.

---

## 5 Important Pseudo-Selectors:

### 1. `:hover`
This applies styles when the user hovers over an element.

**Example:**
```css
button:hover {
  background-color: blue;
  color: white;
}
```
When the mouse is over the button, the background will turn blue.

---

### 2. `:focus`
This applies styles when an input field or form element is focused.

**Example:**
```css
input:focus {
  border: 2px solid green;
}
```
When a user clicks on the input box, the border will turn green.

---

### 3. `:first-child`
This targets the first child element inside a parent element.

**Example:**
```css
p:first-child {
  font-weight: bold;
}
```
The first `<p>` tag will have bold text.

---

### 4. `:nth-child(n)`
This targets specific child elements based on their order.

**Example:**
```css
li:nth-child(odd) {
  background-color: lightgray;
}
```
Odd-numbered `<li>` elements (1st, 3rd, 5th, etc.) will have a light gray background.

---

### 5. `::before`
This adds content before an element.

**Example:**
```css
h1::before {
  content: "🔥 ";
}
```
A 🔥 emoji will appear before every `<h1>` element.

---

Apart from these, there are many other useful pseudo-selectors like `:last-child`, `:not()`, and `::after`, which are essential in web design.

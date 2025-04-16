# CSS Interview Questions and Answers

**1. What is the CSS box model?**

**Answer:** The CSS box model describes the rectangular boxes that are generated for elements in the document tree and laid out according to visual formatting model. It consists of:

* **Content:** The actual content of the element (text, images, etc.).
* **Padding:** The space around the content, inside the border.
* **Border:** A line that surrounds the padding and content.
* **Margin:** The space around the border, outside the element.

**2. What are the different ways to position elements in CSS?**

* `static`: The default positioning; elements are laid out in the normal flow of the document.
* `relative`: The element is positioned relative to its normal position. You can use `top`, `right`, `bottom`, and `left` to offset it.
* `absolute`: The element is removed from the normal document flow and positioned relative to its nearest positioned ancestor (or the initial containing block if no positioned ancestor exists).
* `fixed`: The element is removed from the normal document flow and positioned relative to the viewport. It stays in the same place even when the page is scrolled.
* `sticky`: The element behaves like `relative` within its normal flow, but becomes `fixed` when it reaches a specified offset from the viewport.

**3. What is the difference between `inline`, `block`, and `inline-block` display properties?**

* `inline`: Elements only take up the necessary width, flow horizontally, and respect left/right padding and margin, but not top/bottom padding and margin.
* `block`: Elements take up the full available width, start on a new line, and respect all padding and margin properties.
* `inline-block`: Elements flow horizontally like inline elements but respect all padding and margin properties like block elements.

**4. What is CSS specificity?**

**Answer:** Specificity is the algorithm that browsers use to determine which CSS rule is applied to an element.  It is essentially a system of weights that are applied to CSS selectors.  More specific selectors will override less specific selectors.

**5. What are CSS preprocessors?  Name a few.**

**Answer:** CSS preprocessors are scripting languages that extend the default capabilities of CSS.  They allow you to use variables, mixins, functions, and other features that aren't available in standard CSS.  The preprocessor code is then compiled into regular CSS.

**Examples:** `Sass`, `Less`, `Stylus`.

**6. What is the difference between `em` and `rem` units?**

**Answer:** Both are relative font-size units.

* `em`: Relative to the font-size of the element itself.
* `rem`: Relative to the font-size of the root element (the `<html>` element).

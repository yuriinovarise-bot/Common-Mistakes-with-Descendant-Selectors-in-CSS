Common Mistakes with Descendant Selectors in CSS
Description

When working with CSS selectors, spacing matters. A common beginner mistake is confusing:

p.eee – selects all <p> elements with class eee.

p .eee – selects all elements with class eee inside any <p> element.

Example
<!-- Selected by p.eee -->
<p class="eee">lorem ipsum</p>

<!-- Selected by p .eee -->
<p>lorem <span class="eee">ipsum</span></p>


p.eee targets <p> tags that have the class eee.

p .eee targets any element with class eee that is a descendant of a <p> tag.

Understanding this distinction is critical for applying styles correctly.

Tasks

Explain what the selector p.bbb selects, and write HTML code that matches it.

Explain what the selector p .bbb selects, and write HTML code that matches it.

Explain what the selector .eee p.bbb selects, and write HTML code that matches it.

Explain what the selector .eee p .bbb selects, and write HTML code that matches it.

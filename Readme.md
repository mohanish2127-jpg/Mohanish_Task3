# CSS Selectors Task

## Description
A demo page showing different ways to select and style elements in CSS —
element selectors, class selectors, id selectors, descendant selectors, and
nth-child selectors — without relying on Bootstrap or inline CSS.

## Files
- `index.html` – Page structure (headings, paragraphs, lists, links).
- `style.css` – All styling, linked via `<link rel="stylesheet" href="style.css">`.
- `Readme.md` – This documentation file.

## How Each Step Was Implemented
1. `index.html` and `style.css` created and linked in the `<head>`.
2. Body background color set with the `body` element selector.
3. Three heading tags (`h1`, `h2`, `h4`) all given `class="head"`.
4. `.head` class selector applies dark blue text to all three headings.
5. The `h2` also has `id="bglime"`; `#bglime` gives it a lime background.
6. The word `"head"` inside the `h2` is wrapped in a plain `<span>` (no
   class/id) and styled red using the descendant selector `h2 span`.
7. Three `<p>` tags with no id/class are styled white using the `p` element
   selector.
8. The second paragraph has `id="para"` and is styled green with `#para`.
9. In the third (second "plain") paragraph, the word `"paragraph"` is wrapped
   in a `<span>` (no class/id) and styled black + larger font using the
   descendant selector `p span`.
10. The two "here" links and the ordered list items are styled purely with
    `nth-child` selectors (`ul li:nth-child(1) a`, `ol li:nth-child(2)`, etc.)
    — no inline CSS, id, or class used on those elements.

## How to Run
Open `index.html` in any web browser. No build tools or server required.

## Author
Mohanish

# Bean There Cafe: Gestalt and Forms Demo

A small demo website for talking about Gestalt principles and how a basic accessible form is built.

## Files

- `index.html`: the page content
- `styles.css`: the page styles, including a "messy" version of the same page

## How it works

Use the bar at the top of the page to switch between a **Refined** and a **Messy** view of the same HTML. Turn on **Show Gestalt labels** to outline the areas that use each principle.

The contact form uses only HTML and CSS: linked labels, `fieldset` and `legend`, `required` and `type="email"` for browser validation, and error messages that CSS reveals with `:user-invalid`. Submitting a valid form just reloads the page, since there is no server.

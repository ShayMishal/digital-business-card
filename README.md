# Digital Business Card — Shay Mishal

A personal business card / landing page built for the Web Application Development
course. It presents who I am, what I work with, and how to reach me, with a
light/dark theme switch.

## Live site
https://shaymishal.github.io/digital-business-card/

## Built with
Just HTML and CSS — no JavaScript at all. The dark/light switch is done with two
hidden radio buttons and the CSS `:has()` selector on `:root`, which swaps the
CSS color variables. When no choice is made, the theme follows the operating
system through `prefers-color-scheme`.

## Structure
- index.html – the page markup (semantic: header, main, sections, footer)
- css/style.css – all of the styling (external file, nothing inline)
- assets/profile.jpg – profile photo

## Notes
The project section shows sample projects to demonstrate layout and content
structure; the contact details are real.

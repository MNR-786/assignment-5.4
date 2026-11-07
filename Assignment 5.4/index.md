# Assignment 5.4 - CSS Variables & Design Tokens

## Variables Defined in :root

- Colors: `--color-primary`, `--color-secondary`, `--color-background`, `--color-surface`, `--color-text`
- Spacing: `--space-small`, `--space-medium`, `--space-large`
- Font sizes: `--font-small`, `--font-medium`, `--font-large`, `--font-xlarge`

## Where the Variables Are Used

- Headings use the primary color and the font size variables.
- Cards use the surface color, the primary color for the border, and the spacing variables.
- Buttons use the primary and secondary colors and the spacing variables.

## Variable Change Test

I changed the value of `--color-primary` from `#1a3c6e` to `#8e1b3a`. The header, the footer, the headings, the card borders and the primary buttons all changed color at the same time, because they all use the same variable.

## Screenshots

Before the change:

![Before](before.png)

After the change:

![After](after.png)
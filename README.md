# Tailwind CSS @apply Directive Error: Misspelled or Missing Class

This repository demonstrates a common error when using Tailwind CSS's `@apply` directive: applying a misspelled or nonexistent class. The bug and its solution are detailed below.

## Bug
The `@apply` directive in Tailwind CSS is used to apply a class's styles directly. If the class name is misspelled or doesn't exist, the styles won't be applied, resulting in unexpected behavior.

## Solution
Ensure the class name used in `@apply` is spelled correctly and actually exists in your Tailwind CSS configuration or custom styles.

## How to Reproduce
1. Clone this repository.
2. Open `bug.css` to see the buggy code.
3. Notice that the button's background color is not blue as intended.
4. Refer to `bugSolution.css` for the corrected code.
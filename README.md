# CSS :nth-child Selector Issue with Nested Lists

This repository demonstrates a common issue encountered when using the `:nth-child` pseudo-class in CSS, specifically when dealing with nested lists. The problem arises from the way `:nth-child` calculates the index of list items in nested structures. It resets the count for each new nested list, resulting in unexpected styling.

The `bug.css` file shows the incorrect implementation which causes the issue. The correct implementation is shown in the `bugSolution.css` file. 
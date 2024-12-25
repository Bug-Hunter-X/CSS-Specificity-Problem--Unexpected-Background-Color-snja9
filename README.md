# CSS Specificity Bug

This repository demonstrates a common issue in CSS related to specificity. The goal is to style a paragraph element nested inside a container, but the expected style isn't applied due to specificity rules. The solution shows how to resolve this by employing more specific CSS selectors or overriding the specificity.

## Bug Report

The provided CSS code intends to style a paragraph element with a red background color inside a container that has a blue background.  The paragraph should have the red background, but due to a specificity issue, only the blue background is rendered.

## Solution

The solution uses a more specific selector to target the paragraph, ensuring the desired style is applied.
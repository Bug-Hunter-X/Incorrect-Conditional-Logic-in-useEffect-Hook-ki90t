# Incorrect Conditional Logic in useEffect Hook
This example demonstrates an uncommon bug in React where incorrect conditional logic within the `useEffect` hook leads to unexpected behavior.
The component updates the document title based on the counter value. However, the conditional logic only updates the title when the count is greater than 0. When the count resets to 0, the title remains unchanged, resulting in a missing title update.
The solution provides a corrected implementation that updates the document title regardless of the counter's value.
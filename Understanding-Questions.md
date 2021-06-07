# Understanding Questions:

1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.

- The user presses the 1 button.
- That triggers the handleAddOne event handler
- Which triggers the dispatch function in our reducer on our addOne function
- The addOne function returns the ADD_ONE case and inputs it into the reducer
- The reducer then returns our state object with the total increased by 1
- This value is then passed down to the TotalDisplay component, leading to....

- TotalDisplay shows the total plus 1.

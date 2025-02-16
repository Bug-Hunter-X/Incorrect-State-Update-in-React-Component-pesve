# Incorrect State Update in React Component

This repository demonstrates a common error in React applications involving incorrect state updates. The `bug.jsx` file showcases the problematic code where the component's state is directly assigned a new value instead of using the setter function from the `useState` hook. This results in the UI not reflecting changes in the state.

The `bugSolution.jsx` file provides the corrected version where the setter function is used correctly.  This example highlights the importance of using the setter function provided by the `useState` hook for updating the component's state effectively.
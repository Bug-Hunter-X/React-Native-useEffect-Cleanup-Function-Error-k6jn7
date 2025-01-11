# React Native useEffect Cleanup Function Error

This repository demonstrates a common error in React Native applications involving the `useEffect` hook's cleanup function. The issue arises when the cleanup function attempts to access or modify the component's state or props after the component has unmounted. This typically occurs when asynchronous operations within the `useEffect` hook outlast the component's lifecycle.

The `bug.js` file showcases the problematic code, while `bugSolution.js` provides a corrected version with explanations.
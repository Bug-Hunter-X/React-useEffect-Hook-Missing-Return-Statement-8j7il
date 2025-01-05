# React useEffect Hook Missing Return Statement

This repository demonstrates a common React bug related to the `useEffect` hook: forgetting to include a return statement for cleanup.  The example showcases a simple counter component.  The erroneous code lacks a return function in the `useEffect` hook. This omission prevents proper cleanup when the component unmounts, leading to potential memory leaks and unexpected behavior.

The solution demonstrates the correct usage of the `useEffect` hook, including the return statement that removes event listeners or performs other necessary cleanup tasks before the component is unmounted.
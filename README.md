# React useEffect Hook Bug

This repository demonstrates a common bug in React applications involving the `useEffect` hook.

## Bug Description

The provided code uses the `useEffect` hook without specifying dependencies.  This means the effect runs after every render, leading to an infinite loop and console spam.  

## Solution

The solution involves adding the appropriate dependencies array to the `useEffect` hook to control when the effect runs. 

## How to reproduce the bug:

1. Clone this repo.
2. Run `npm install`
3. Run `npm start`
4. Observe the continuous logging of 'Count' in the console and potential performance issues.

## How to fix the bug:

1. Replace the problematic code with the provided solution.
2. Rerun the application.
3. Observe the corrected behavior. 
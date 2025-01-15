# Next.js Invalid Hook Call Error

This repository demonstrates a common error in Next.js applications: the 'Invalid hook call' error.  This error typically occurs when using React Hooks outside of a functional component or in an unexpected context within the component's lifecycle.

## Bug Description

The provided `pages/index.js` attempts to use React Hooks (although none are explicitly shown in this simplified example) outside of a functional component, leading to the 'Invalid hook call' error.

## Solution

The solution involves ensuring that all React Hooks are called within functional components and adhering to the rules of Hooks usage.

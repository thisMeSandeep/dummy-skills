# React review checklist

1. Hooks are called only at the top level of a component, never inside conditions or loops.
2. Every `useEffect` has a correct dependency array.
3. Lists rendered with `.map` have a stable `key` that is not the array index.
4. Interactive elements are real buttons or links, not clickable `div` elements.
5. Images have `alt` text.
6. Objects and functions passed to memoized children are stable between renders.
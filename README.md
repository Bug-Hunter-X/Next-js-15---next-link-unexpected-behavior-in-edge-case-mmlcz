# Next.js 15 - next/link Unexpected Behavior

This repository demonstrates an uncommon issue encountered with the `next/link` component in Next.js 15.  The problem involves unexpected behavior when navigating to a nested route containing dynamic segments under specific conditions. The link might not redirect as expected or might trigger unexpected behavior in combination with other features. 

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Observe the navigation behavior of the `About Us` link.  It should exhibit the described unexpected behavior. 

## Solution

The solution might involve adjusting routing configurations or using alternative approaches for handling dynamic routes or implementing specific workarounds based on the identified issue. Refer to the `bugSolution.js` file for a possible solution.
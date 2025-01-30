# Next.js Link Component Issue

This repository demonstrates a common issue encountered when using the Next.js `Link` component:  the link doesn't navigate to the intended page despite seemingly correct code.

The `bug.js` file contains the problematic code. The solution is provided in `bugSolution.js`.

## Problem

The link in `bug.js` does not work as expected; clicking "About Us" does not navigate to the `/about` page.

## Solution

The solution in `bugSolution.js` addresses the likely cause of this issue (often a missing or incorrect `pages/about.js` file).
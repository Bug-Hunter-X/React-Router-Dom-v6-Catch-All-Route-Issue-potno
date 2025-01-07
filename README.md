# React Router Dom v6 Catch All Route Issue

This repository demonstrates a common issue encountered when using the catch-all route (`/*`) in React Router Dom v6. The catch-all route is intended to match any unmatched routes, but in certain scenarios, it fails to work as expected.  The issue arises from the order of routes and how they interact with each other, leading to unexpected rendering of pages and potentially other errors.

## Problem

The `/*` route, meant to be a fallback, is not catching routes that should fall under it, leading to incorrect page displays, or sometimes even unexpected errors. 

## Solution

The provided solution demonstrates the correct way to implement a catch-all route to prevent this issue.
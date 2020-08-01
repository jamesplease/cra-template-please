# Guide

This guide explains the features and changes I've made in this template.

### TypeScript

TypeScript is enabled by default with this template. Just create a file ending in
`.ts` or `.tsx` and you're off to the races.

### `focus-visible` Polyfill

`focus-visible` provides a better user experience when using custom focus styles,
but browser support is poor as of July 2020. This polyfill allows me to use it
today.

### Modern Normalize

A smaller CSS normalizer. What else is there to say?

### React Router + `query-history`

React Router for routing. `query-history` adds robust query params to it.

### Cursor styles

The cursor for non-editable text is set to `default`.

### `--weightedEase`

A useful curve for animations.

### Service Worker boilerplate

Service Workers are a great technology, but they don't come for free. Most
projects I create don't require Service Workers; therefore, that boilerplate
code is removed.

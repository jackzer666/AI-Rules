# Code Review Checklist

When reviewing code changes, check each item below:

## Comments
- [ ] Use `//` not `/* */`
- [ ] Space after `//`
- [ ] Comments on own line, above code
- [ ] No inline or end-of-line comments

## Imports
- [ ] No unused imports
- [ ] No duplicate imports

## Exports
- [ ] All exports at file bottom
- [ ] No inline exports (e.g., `export const`)

## Code Quality
- [ ] No `console.log` or `console.debug`
- [ ] No magic numbers or strings
- [ ] Use `===` and `!==`
- [ ] No `==` or `!=`

## Vue/Component
- [ ] No unused `ref`, `reactive`, etc.
- [ ] Props have proper defaults
- [ ] No excessive inline styles

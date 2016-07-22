# css-modules-talk
Think different, think components

## OOCSS, ACSS, BEM, SMACSS

## CSS in JS


## CSS Modules

### What they solve
- **Global Scope:** CSS Modules eliminate collisions in the global scope, they handle BEM for you.
- **Overqualified Selectors:** Because CSS modules live at the component level, there’s no need to write deeply nested selectors. Class names can be kept simple and relevant to the component.
- **Refactoring:** Refactoring is made simple, because we’re working at the component level, we can easily determine which styles apply to the component. For styles that use composition, we can quickly locate the other affected components.

> Are CSS Modules right for my project?  
  CSS Modules are not suitable for every project. A component based architecture is required (React, Angular 2), and aside from Rails, they only work with JavaScript applications. Furthermore, if you’re already using BEM, it may not make sense to switch to CSS Modules.

## Atomic CSS Modules

## Links
- http://clubmate.fi/oocss-acss-bem-smacss-what-are-they-what-should-i-use/
- https://www.sitepoint.com/atomic-oobemitscss/
- https://speakerdeck.com/hugogiraudel/local-styling-with-css-modules
- https://speakerdeck.com/fox/front-end-systems-at-scale
- http://www.universalmind.com/blog/css-modules%E2%80%8A-%E2%80%8Asolving-the-challenges-of-css-at-scale/
- http://glenmaddern.com/articles/css-modules

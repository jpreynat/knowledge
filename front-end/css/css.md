# [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)

## Notes

- ID's are unique.
  - Each element can have only one ID.
  - Each page can have only one element with that ID.
- Classes are NOT unique.
  - You can use the same class on multiple elements.
  - You can use multiple classes on the same element.
- [The DOM is just a tree of objects. CSS selects parts of that tree and applies attributes to those objects. It's all just code, it's just a shorthand for adding a bunch of attributes to a bunch of objects.](https://www.reddit.com/r/javascript/comments/9jpvon/do_you_even_need_a_css_framework/)
- [Always design your CSS format from the inside out](https://www.quora.com/What-is-the-best-way-to-prevent-divs-from-overlapping-I-have-3-divs-The-First-div-changes-its-size-and-overlaps-the-second-one-which-is-a-set-of-images)
  - format the elements within their container so that they look correct regardless of the size of the container.
  - similarly format those containers within their own containers
  - repeat until `<body>` is the containers
  - never use absolute widths (px, in, cm, etc.) for anything
- body tag takes up the whole width and height of the browser screen.

## Links

- [Pesticide Chrome Extension](https://chrome.google.com/webstore/detail/pesticide-for-chrome/bblbgcheenepgnnajgfpiicnbbdmmooh) - Invaluable for debugging CSS.
- [Understanding static and relative positioning](https://webplatform.github.io/docs/tutorials/static_and_relative_positioning/)
- [Code guide by @mdo](http://codeguide.co/)
- [CSS reference](https://cssreference.io/)
- [CSS Blocks](https://github.com/linkedin/css-blocks) - High performance, maintainable stylesheets.
- [Opticss](https://github.com/linkedin/opticss) - CSS Optimizer.
- [CSS Puns](https://saijogeorge.com/css-puns/)
- [Magic of CSS](https://adamschwartz.co/magic-of-css/)
- [Min](https://github.com/owenversteeg/min) - World's smallest (995 bytes) CSS framework.
- [Emotion](https://emotion.sh/) - Performant and flexible CSS-in-JS library.
- [Why We Use Styled Components at Decisiv](https://medium.com/@_alanbsmith/why-we-use-styled-components-at-decisiv-a8ac6e1507ac)
- [The case for CSS modules - Mark Dalgleish](https://www.youtube.com/watch?v=zR1lOuyQEt8)
- [Michael Chan - Inline Styles: themes, media queries, contexts, & when it's best to use CSS (2015)](https://www.youtube.com/watch?v=ERB1TJBn32c)
- [Understanding the CSS box model for inline elements](https://hacks.mozilla.org/2015/03/understanding-inline-box-model/)
- [astroturf](https://github.com/4Catalyzer/astroturf) - An "artificial" css-in-js for those that want it all.
- [Pesticide](https://github.com/mrmrs/pesticide) - Kill your CSS layout bugs.
- [Spectre](https://github.com/picturepan2/spectre) - Lightweight, Responsive and Modern CSS Framework.
- [Tachyons](https://github.com/tachyons-css/tachyons) - Functional CSS for humans.
- [CSS Animation 101](https://github.com/cssanimation/css-animation-101#readme)
- [Tailwind utility-first CSS framework](https://tailwindcss.com/docs/what-is-tailwind/)
- [CSStype](https://github.com/frenic/csstype) - Strict TypeScript and Flow types for style based on MDN data.
- [normalize.css](https://github.com/necolas/normalize.css) - Modern alternative to CSS resets.
- [Julia Muzafarova CSS Pens](https://codepen.io/miocene/)
- [CSS Modules](https://github.com/css-modules/css-modules) - Documentation about css-modules.
- [nano-css](https://github.com/streamich/nano-css) - CSS-in-JS library that you can actually use in production. Motto of nano-css is simple: create the smallest possible CSS-in-JS library and provide all features of any other library through addons.
- [Why I Write CSS in JavaScript (2019)](https://mxstbr.com/thoughts/css-in-js/)
- [Styled System](https://github.com/jxnblk/styled-system) - Responsive, theme-based style props for building design systems with React.
- [Rebass](https://github.com/rebassjs/rebass) - React primitive UI components built with styled-system..
- [TypeStyle](https://github.com/typestyle/typestyle) - Making CSS type safe.
- [The Three Tenets of Styled System (2019)](https://jxnblk.com/blog/the-three-tenets-of-styled-system/)
- [CSS Scan Chrome Extension](https://getcssscan.com/) - Instantly inspect and copy computed CSS.
- [DropCSS](https://github.com/leeoniya/dropcss) - Simple, thorough and fast unused-CSS cleaner.
- [CSS Standardization - The State of the Web with Jen Simmons (2019)](https://www.youtube.com/watch?v=TQ7NqpFMbFs)
- [Water.css](https://github.com/kognise/water.css) - Just-add-css collection of styles to make simple websites just a little nicer.
- [Loaders.css](https://github.com/ConnorAtherton/loaders.css) - Delightful and performance-focused pure css loading animations.
- [Artem Sapegin: Custom CSS is the Path to Inconsistent UI (2018)](https://www.youtube.com/watch?v=t5VTLwAias8)
- [Learn CSS Layout the pedantic way](http://book.mixu.net/css/)
- [CSSFX](https://cssfx.dev/) - Beautifully simple click-to-copy CSS effects.
- [CSS Working Group Editor Drafts](https://drafts.csswg.org/)
- [CSS Houdini Experiments](https://css-houdini.rocks/)
- [CSS-Only Chat](https://github.com/kkuchta/css-only-chat) - Truly monstrous async web chat using no JS whatsoever on the frontend.
- [Theme UI](https://github.com/system-ui/theme-ui) - Build consistent, themeable React UIs based on design system constraints and design tokens.
- [Nice comment on problems & solutions to writing CSS](https://github.com/tachyons-css/tachyons/issues/12#issuecomment-309565525)
- [tachyons tldr](https://tachyons-tldr.now.sh/#/classes)
- [A real-life journey into the opinionated world of 'utility-first' CSS (2018)](https://www.youtube.com/watch?v=2-q4asoHUqU)
- [CSS and Scalability (2016)](https://mrmrs.cc/writing/scalable-css/)
- [cssdb](https://cssdb.org/) - Comprehensive list of CSS features and their positions in the process of becoming implemented web standards.
- [Relearn CSS layout](https://every-layout.dev/) - How to better harness the built-in algorithms that power browsers and CSS. ([HN](https://news.ycombinator.com/item?id=20196061))

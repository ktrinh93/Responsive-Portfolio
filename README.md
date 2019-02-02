# Responsive-Portfolio

Redone version of Basic Porfolio (https://github.com/ktrinh93/Basic-Portfolio) but done with responsive formatting using media queries in the CSS document. In general, for medium or larger screen sizes, it displays the full content, but for smaller than medium/mobile screens, the content fills the width of the viewport for easier viewing.

Had some issues where appearance of the website looks somewhat jittery when switching between large and medium screen sizes/widths. Especially noticeable on the Portfolio page, because the "lg" viewport size (980px) has a very large right margin, the content of the website has an effectively thinner space compared to the "md" viewport size (786px). Unsure if this is an expected issue, but one nonetheless.

There is an issue where at larger viewport widths (> 1400px), the portrait on the About Me page clips out/below the content box. I was unable to figure out a way to make this scale smaller to match the height of the text at these larger viewport sizes.

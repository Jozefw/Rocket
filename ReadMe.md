1. SVG - inline SVG's in HTML looks horrible, IE 11 doesnt support CSS variables...so I decided to just change the fill directly in the SVG itself.

2. CSS - A larger task would have warrented a CSS preprocessor like LESS or SASS/SCSS.

3. Optimization - I would have added a Grunt task manager to minify, compress, and concatenate CSS, image, and Javascript files.

4. Grid System - Typically I would add Bootstrap V3, but the bloat of bootstrap and JQuery for this task seemed unreasonable.  I opted for FLEXBOX which has IE support in the manner in which it is utilized here. (See: https://caniuse.com/#feat=flexbox).

5. BEM Notation - I used a semblance of BEM notation in order to provide clarity in the HTMl without being verbose.

6. Spacing and Font Size Calculations - images were 2x the size of screen resolutions; spacing measurements were divided by 2.  Font sizes were then divided by 10 to yeild rems (html font-size = 62.5).  





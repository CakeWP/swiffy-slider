## [v1.2.0] - 03-12-2021

## Bugfixes

- None

## Changed
- Changed the use of <code>zoom</code> in css to <code>transform: scale()</code>
- Changed javascript to use <code>"</code> instead <code>'</code> consistently
- Changed all event listeners to be passive to increase performance even further

## Added

- Support for mouse drag option using the new swiffy-slider-extensions object
- Added swiffy-slider-extensions for adding features not needed for core releases. Can be accessed on <code>swiffyslider.extensions.*</code>
- Configure animation threshold for the intersection observer that sets <code>.slide-visible</code> when sliding. New attribute <code>data-slider-nav-animation-threshold</code>
- <code>swiffyslider.setVisibleSlides</code> can now be called with a threshold overwriting the default 0.3

## [v1.1.0] - 16-11-2021

## Bugfixes

- Configurator did not start autuplay when enabled
- Navigation in docs fixed

## Added

- Slide animation
- Javascript can now set visible-slide class using intersection observer
- Different animation styles in css

## Removed

- BREAKING slider-item-shadow has been removed since it uses ::after which disables touch sliding on mobile devices

## [v1.0.2] - 08-11-2021

- Fix z-index issue with nav and indicators (#1)

## [v1.0.1] - 08-11-2021

Welcome to the first release of Swiffy Slider.

This project utilizes what is available in modern browsers resulting in a super lightweight and fast slider, greatly reducing the javascript footprint and increase performance to meet todays standards.

**Slide any content made in markup**

- Navigate with Touch, Keyboard, trackpad, pen and Mouse - because it is just browser scrolling
- Setup is done in pure markup and css classes, no scripting required
- No js loading of slides, configuration or initialization
- Vanilla javascript, less than 1.3kb ~110 lines
- Very low overall footprint ~4.5kb in total (css+js gzip'ed)

**Swiffy Slider benefits**

* **Mobile first** :iphone:, responsive, scaleable and content resilient sliding. Ensuring painless mobile experience.
* **Lighthouse 100 points** :100: Using native browser features a unrivaled performance is ensured
* **SEO** :pencil:  is great as the slides and their content is in pure SLURP-readable markup
*  **Build designed pages** :art: any kind of markup can be slided giving perfect design freedom
* **Web Accessibility Guidelines (WCAG)** :trophy: make your website as accessible as needed since this is just markup

Thank you, give it a spin!
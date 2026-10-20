# Session: Lab1

ID: 26560030

Name: Bùi Thiệu Khiêm

Github: https://github.com/hickwhither/web-development-and-design-lab-0

## In-class excercise
https://hickwhither.github.io/web-development-and-design-lab-0

## Homework

### Flip card gallery
https://hickwhither.github.io/web-development-and-design-lab-0/1-flip-card-gallery
- `.flipcard` creates a 3D container with `perspective` (depth).
- `.flipcard-inner` holds both faces. `transform` keeps them in 3D space and animates rotation
-  `backface-visibility: hidden` hides reverse side of element
- `rotateY(180deg)` literally rotate

### Login / Sign-up card
https://hickwhither.github.io/web-development-and-design-lab-0/2-login-card
- `.container` is `display: flex` - creates two columns, `.left-panel` and `.right-panel` both `flex: 1` take equal space.
- `border-radius` rounds corner 
- `border-shadow` shadow

### Infinite Scrolling Marquee
https://hickwhither.github.io/web-development-and-design-lab-0/3-infinite-scrolling-marquee
- `@keyframes marquee-scroll` animates `translateX` from 0 to -50%. 
- `animation: marquee-scroll` 20s linear infinite; infinite loop
- `animation-play-state: paused` stop animation on hover

However there’s a noticable “cut” at the end of animation. (idk why)

# Animated Next Episode Button

## Overview

A simple HTML and CSS animation that creates a progress-bar effect on a "Next Episode" button. The gray overlay expands from left to right over 5 seconds.

## Features

- Pure HTML and CSS implementation.
- Left-to-right overlay animation.
- Customizable animation duration and colors.
- No JavaScript or external dependencies required.

## How It Works

- **Container:** Positions the overlay and button label.
- **Overlay:** Creates the animated gray layer.
- **Underlay:** Displays the "Next Episode" text.
- **Keyframes:** Animates the overlay width from `0px` to `202px`.
- **Duration:** Completes the animation in 5 seconds.

## Implementation

The animation uses CSS `@keyframes` to increase the overlay width over time.

```css
.overlay {
    position: absolute;
    top: 0;
    width: 0;
    height: 31px;
    background-color: gray;
    animation: linear 5s;
    border-radius: 2px;
}

@keyframes linear {
    from {
        width: 0;
    }
    to {
        width: 202px;
    }
}
```

## Customization

- Change the animation duration to control the speed.
- Modify the background color to customize the overlay.
- Adjust the width values to change the button size.

## Use Cases

- Video player interfaces.
- Automatic next-episode countdowns.
- Progress-style buttons.
- Media streaming UI prototypes.

## Author

**Sangwin Gawande**

Website: [https://sangw.in](https://sangw.in)

---

Cheers!!

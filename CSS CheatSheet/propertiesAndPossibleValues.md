# Complete List of CSS Properties and Their Possible Values

This document contains a list of CSS properties along with their possible values to assist in styling

---

## Table of Contents

1. [Box Model Properties](#box-model-properties)
2. [Typography Properties](#typography-properties)
3. [Background and Border Properties](#background-and-border-properties)
4. [Positioning and Display Properties](#positioning-and-display-properties)
5. [Flexbox Properties](#flexbox-properties)
6. [Grid Properties](#grid-properties)
7. [Animation and Transition Properties](#animation-and-transition-properties)
8. [Filter and Effects Properties](#filter-and-effects-properties)
9. [Other Miscellaneous Properties](#other-miscellaneous-properties)

---

## Box Model Properties

### `margin`
- Values: `auto`, `<length>` (e.g., `10px`), `<percentage>` (e.g., `10%`), `inherit`, `initial`, `unset`

### `padding`
- Values: `<length>`, `<percentage>`, `inherit`, `initial`, `unset`

### `border`
- Values: `<width> <style> <color>`
  - `width`: `<length>` (e.g., `1px`), `thin`, `medium`, `thick`
  - `style`: `none`, `solid`, `dashed`, `dotted`, `double`, `groove`, `ridge`, `inset`, `outset`
  - `color`: `<color>` (e.g., `red`, `#000`, `rgba(0, 0, 0, 0.5)`)

### `box-sizing`
- Values: `content-box`, `border-box`, `inherit`, `initial`, `unset`

### `width`
- Values: `<length>`, `<percentage>`, `auto`, `max-content`, `min-content`, `fit-content`, `inherit`, `initial`, `unset`

### `height`
- Values: Same as `width`

---

## Typography Properties

### `font-family`
- Values: `"<font-name>"`, `serif`, `sans-serif`, `monospace`, `cursive`, `fantasy`

### `font-size`
- Values: `<absolute-size>` (e.g., `small`, `medium`, `large`), `<relative-size>` (e.g., `larger`, `smaller`), `<length>` (e.g., `16px`), `<percentage>`

### `font-weight`
- Values: `normal`, `bold`, `lighter`, `bolder`, `<number>` (100–900)

### `line-height`
- Values: `normal`, `<number>` (e.g., `1.5`), `<length>`, `<percentage>`

### `text-align`
- Values: `left`, `right`, `center`, `justify`, `start`, `end`

### `text-decoration`
- Values: `none`, `underline`, `overline`, `line-through`, `blink`

### `letter-spacing`
- Values: `normal`, `<length>` (e.g., `2px`), `inherit`

### `word-spacing`
- Values: `normal`, `<length>`, `inherit`

---

## Background and Border Properties

### `background-color`
- Values: `<color>` (e.g., `#ffffff`, `rgba(255, 255, 255, 0.5)`), `transparent`, `inherit`

### `background-image`
- Values: `url('<image-path>')`, `none`, `linear-gradient()`, `radial-gradient()`

### `background-repeat`
- Values: `repeat`, `repeat-x`, `repeat-y`, `no-repeat`, `space`, `round`

### `background-size`
- Values: `auto`, `cover`, `contain`, `<length>`, `<percentage>`

### `border-radius`
- Values: `<length>` (e.g., `10px`), `<percentage>` (e.g., `50%`), `inherit`

### `border-color`
- Values: `<color>`, `transparent`, `inherit`

### `border-width`
- Values: `<length>` (e.g., `1px`), `thin`, `medium`, `thick`

---

## Positioning and Display Properties

### `position`
- Values: `static`, `relative`, `absolute`, `fixed`, `sticky`, `inherit`, `initial`, `unset`

### `display`
- Values: `block`, `inline`, `inline-block`, `flex`, `grid`, `none`, `inline-flex`, `inline-grid`, `inherit`, `initial`, `unset`

### `overflow`
- Values: `visible`, `hidden`, `scroll`, `auto`, `clip`

### `z-index`
- Values: `<integer>`, `auto`, `inherit`, `initial`, `unset`

### `visibility`
- Values: `visible`, `hidden`, `collapse`, `inherit`, `initial`, `unset`

---

## Flexbox Properties

### `justify-content`
- Values: `flex-start`, `flex-end`, `center`, `space-between`, `space-around`, `space-evenly`

### `align-items`
- Values: `stretch`, `flex-start`, `flex-end`, `center`, `baseline`

### `flex-direction`
- Values: `row`, `row-reverse`, `column`, `column-reverse`

### `flex-wrap`
- Values: `nowrap`, `wrap`, `wrap-reverse`

### `align-self`
- Values: `auto`, `stretch`, `flex-start`, `flex-end`, `center`, `baseline`

### `order`
- Values: `<integer>` (default is `0`)

---

## Grid Properties

### `grid-template-columns`
- Values: `none`, `<track-size>` (e.g., `100px`), `repeat()`, `minmax()`

### `grid-template-rows`
- Values: Same as `grid-template-columns`

### `grid-gap`
- Values: `<length>` (e.g., `10px`), `<percentage>`

### `align-content`
- Values: `stretch`, `center`, `flex-start`, `flex-end`, `space-between`, `space-around`

### `align-items`
- Values: `stretch`, `center`, `flex-start`, `flex-end`, `baseline`

### `grid-auto-flow`
- Values: `row`, `column`, `dense`

### `grid-column`
- Values: `<line> / <line>`, `span <number>`

---

## Animation and Transition Properties

### `animation`
- Values: `<name> <duration> <timing-function> <delay> <iteration-count> <direction>`

### `transition`
- Values: `<property> <duration> <timing-function> <delay>`

### `animation-timing-function`
- Values: `ease`, `linear`, `ease-in`, `ease-out`, `ease-in-out`, `step-start`, `step-end`

### `animation-fill-mode`
- Values: `none`, `forwards`, `backwards`, `both`

---

## Filter and Effects Properties

### `filter`
- Values: `none`, `blur()`, `brightness()`, `contrast()`, `drop-shadow()`, `grayscale()`, `hue-rotate()`, `invert()`, `opacity()`, `saturate()`, `sepia()`

### `box-shadow`
- Values: `none`, `<length> <length> <blur-radius> <spread-radius> <color>`

---

## Other Miscellaneous Properties

### `cursor`
- Values: `auto`, `default`, `pointer`, `text`, `wait`, `help`, `not-allowed`, `crosshair`, `move`, `grab`, `zoom-in`, `zoom-out`

### `opacity`
- Values: `<number>` (from `0` to `1`)

### `clip-path`
- Values: `none`, `circle()`, `ellipse()`, `polygon()`, `inset()`

### `content`
- Values: `normal`, `none`, `<string>`, `attr(<attribute>)`, `open-quote`, `close-quote`, `no-open-quote`, `no-close-quote`

---
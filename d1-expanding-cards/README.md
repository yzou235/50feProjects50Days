# Day 1: Expanding Cards

1. Build HTML Page.

   - Set panel class `class = "panel active"`
   - Use inline style to add background image to each panel
   - To get unsplash url: copy image address

2. Use Flexbox and CSS position to align everything.

   - parent container:
     - set flex display for container
     - set width
   - child panel:
     - adjust background size using two-value syntax `background-size: auto 100%`
     - set `background-position``
     - no repeat for `background-repeat`
     - set `height` in vh
     - `border-radius`, `color`, `cursor`
     - `flex: 0.5` (flex-growth 0.5 and flex-shrink: 1)
     - set `margin`
     - `position: relative` to set the position of h3 to absolute later
     - set `transition` for active
   - h3 heading in child panel:
     - `position: absolute` to set it to the bottom left corner
     - set `opacity: 0` make it only shown when active
   - format active panel
     - `flex: 5`

3. Use media query to adjust display on small screens.

   - don't show the last two panels when screen is small

4. Use JavaScript to realize expanding effect.

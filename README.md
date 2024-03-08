# 10min AutoLayout Challenge

<img src="./assets/screenshot.png">

Video demo: <https://twitter.com/teilweise/status/1295700159184154624>

Can you recreate this layout in 10min in SwiftUI?

Behavior when resizing the window:

- Only valid window sizes. You can't resize vertically and end up with tons of space. 20pt padding from window border to content, aka the default passing.
- If the window is wide enough, all buttons have the same width and space between the leftmost one and the Cancel/OK pair to the right.
- As the width of the window decreases, the text reflows and the buttons shrink.
- As the text reflows, it takes up more vertical space and increases the window height.
- As the buttons shrink, the "OK" and "Cancel" buttons reduce in width uniformly until their intrinsic content size (the text content) is reached as the minimum size.


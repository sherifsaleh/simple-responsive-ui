#General description
Implement HTML5/CSS3 solution for specified responsive UI design.
##Scope
* Solution must work in IE11+ and Chrome 41+
* Stylesheets must be written in SASS or LESS
* Any publicly available CSS library or framework can (but does not have to) be used
* Bonus points for using semantic HTML5 markup
##Requirements
Implement the following responsive layout:
* Body with pink background, body font size 5 times the default browser font size (16px @100% zoom)
* Left purple panel with vertically & horizontally centered 'X' char, 1.5 times wider than the body font size, tall as the browser window
* Top-right panel with 10 left-aligned 'X' chars, wrapping to the next line if the window is too narrow
* 4 panels with vertically & horizontally centered '1', '2', '3' and '4', 1.5 times taller than the body font size
  * Equally sized 2 panels per row in a narrow browser window (when 'X' chars in top-right panel fit on one line)
  * Equally sized 4 panels per row in a wide browser window (when 'X' chars in top-right panel do not fit on one line)

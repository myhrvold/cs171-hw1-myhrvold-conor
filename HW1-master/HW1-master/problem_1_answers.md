1.
The colspan="3" attribute creates 3 columns (Rank, State, Rate in this example).
http://www.w3schools.com/tags/att_th_colspan.asp


2.
See: https://dl.dropboxusercontent.com/u/14868427/q1part2_styles.png for CSS & HTML

The only HTML attribute for the header is align="center", which aligns the middle of text to the center of the screen, centering it.
http://www.w3schools.com/tags/tag_th.asp

CSS attributes (look at the Styles in Chrome Developer Tools) include:

padding in the header -- creates a 3 px space
http://www.w3schools.com/css/css_padding.asp

line-height in the body -- adjusts the height of the cell line http://www.w3schools.com/cssref/pr_dim_line-height.asp

margin of 0 in * (wildcard) -- does not add any margins around elements
http://www.w3schools.com/cSS/css_margin.asp

text-align in th -- aligns text for header elements
http://www.w3schools.com/cssref/pr_text_text-align.asp

font-weight in th -- sets font weight (like whether text is bold or not.)
http://www.w3schools.com/cssref/pr_font_weight.asp

display in th -- adjusts display parameter
http://www.w3schools.com/cssref/pr_class_display.asp

vertical-align in th -- aligns elements w/ respect to vertical axis
http://www.w3schools.com/cssref/pr_pos_vertical-align.asp


<b>3. DOM inspector vs. HTML source</b>

The DOM inspector shows you the page as it is actually rendered, with the DOM hierarchy and the results of JavaScript which brings interaction to the page.

The HTML source code shows you the how the page is created to make the resulting DOM hierarchy.

You want the source code to see how to make something (what you have to statically type as code to get a resulting dynamicism of the HTML page.)

You want the DOM inspector if you want to see the live properties of a feature resulting from the HTML code, such as what the effects on an element are from inheritance and other attributes which affect that element. (Since it's hard to visualize what will happen from just seeing the HTML code as it can be complex to work out.)

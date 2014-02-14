<b>1.</b> It needs labels; specifically, the rate and state labels we are about to add to give the visualization context. It’s useable  as is, but hard to interpret if you didn't create the graph yourself, or look through the source code.

<b>2.</b> The first group level is used to make an svg space to display the chart, under which everything else we will create resides in. A second is used to bind the data. The third is to add the bars (rects), while I create an additional (fourth) group for displaying text to give the bars context (Conor + text = Context.)

<b>3.</b> Potentially if you define the text before the bars then bars could go on top of the text. (In my case, it didn't make a differenc though because they were properly formatted on different areas along the x axis.) If you place the text after the rects are created, then the rects are lower in the hierarchy so the text would appear on top of the bars in the event of overlapping coordinates.


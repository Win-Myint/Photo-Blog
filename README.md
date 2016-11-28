# Photo-Blog 
Simple, good looking and responsive photo blog using HTML and CSS only! 

# Objective
- To have better understanding of CSS box model!

# My CSS Algorithm  
1. Set "image width" to 30% to display 3 images per row. (Note: body has 100%!) 
2. Use "float left" to get rid of unnessary white space between images. (Note: white space is added by default in HTML!) 
3. Set "margin" to 1.6% to align images equally. 
   -  I displayed 3 images per row and each image has taken 30% width, therefore 3 x 30 = 90% of available 100% width is in          used! 
   -  In order to algin 3 images equally, i only have 10% width can be used. So, i did some calculation
     1 image has 2 margins (margin left and margin right)
     3 images = 6 margins
     6 margins divided by 10% (available width) = 1.6% each

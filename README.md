# Beautiful-Beginnings
This is a webshop for baby clothes and other baby stuff.
First of all - I will explore the existing code and after that, I will follow the instructions in the info file. 


I find a couple mistakes in the HTML file.
# 1.I made a validation to the file. I used online validator and find some mistakes.  Every single image was without "alt" attribute. You know how important is this attribute for screen readers and accessibility at all.
2. I find mistake about input field “Search” . The  “for” attribute and “id” was different. The difference was only one letter (‘r’), but it is important, if we want to work well.
3. I find an appropriate class names as a “wysiwyg”. It’s meaningless. It will be a hard to maintain the file from other people. It’s bad practice!
4. In the footer, I found "img+text" surrounded by a paragraph. I talk about the copyright in the footer ( powered by: americaneagle.com and etc.  ). In my opinion, this is a bad idea. If you want to work separately with every single element - it's hard to do. It's a better choice to use a figure and figcaption. It's possible to use also "span" for the text.  


About the CSS document
1.I found a missing closе bracket that affected the layout of the footer. The problem was about the “NEWSLETTER FORM”. 
2. The second problem was about media queries. Some media queries were defined as min-width, others were defined as max-width. It's a little bit a confused. It's bad practice!


Recommendations about the UX/ UI.
UI / UX recommendations. The website looks good, but it looks like an old-fashioned website. There is no modern look. Also to the slider: I think will be a good idea to use some indicators, which tell to us how many slides we will see.

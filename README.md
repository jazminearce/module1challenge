# module1challenge

Module 1 Challenge - HTML CSS Git: Code Refactor

* * 

This project is to refactor the given project to be more accessible.

## Edits

I did some research on what websites should have to be more accessible to the public. One of the important factors was to ensure that there was enough of a contrast on the webpage so that someone who has an impaired vision could see read it well without seeing the colors.

The original website which looked like this:

![Headline & Main](original1.png)
![Info & Benefits](image-1.png)
![Infor & Benefits continued](image-2.png)

I used the website AudioEye https://www.audioeye.com/color-contrast-checker/ to test the contrast of how the website was initially designed and the ratio score was a low 5.0:1. As I was trying to find a similar darker color to the original, I realized 3 different colors were used for each section. To fix that, I switched the background color to be dark, so that the section is white and the text would be dark. On the AudioEye website, it scored a 13.9:1 ratio which is higher on the scale which is easier to read as well.

I specified the name of the title in the html so if the website has a screen reader, it will announce what exactly the website is instead of just reading out "website". I added an id selector for "search engine optimization" so that when selected at the navigation, it takes the user to the image and information of SEO, since selecting it before didn't take the user anywhere.

I increased the font-size and line-height for the paragraphs and headers to make it easier to read. I added vertical align to all images so that it can fit on different screen sizes.

Here is the final design:

![Headline & Main](edited1.png) 
![Info & Benefits](edited2.png) 
![Info & Benefits continued](edited3.png)

## License

[MIT]

Copyright (c) 2024 jazminearce
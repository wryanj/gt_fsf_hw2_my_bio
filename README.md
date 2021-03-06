# gt_fsf_hw2_my_bio
Bootsrap Utilization for a Responsive About, Contact, and Portfolio Page.

## Table of Contents

1.  [Deployed Applicatoin](#Deployed-Applicatoin)
2.  [Motivation](#Motivation)
3.  [Description](#Description)
4.  [Credits](#Credits)

## Deployed Applicatoin
[https://wryanj.github.io/gt_fsf_hw2_my_bio/]

## Motivation
I did this to learn more about bootsrap, and so that I could start to practice some of the things I am learning in general about layouts, css, and other fundamental web languages. 

## Description
This assignment provided us an opportunity to learn and utilize bootsrap to create responsive layouts for three static html pages. For me, this assignment was more challenging than the first. 

**Note** I used bootstrap 5 for this, which I then realized was still in beta as I got in. I had to add some of my own css to fix some issues, and after checking with a tutor they also believed some of what I was seeing may be a result of things in bs5 that are not worked out yet. There was also a lot less stack info on doing things in bs5, so I will be using bs4 for the next project.

I also leanred to make sure that whatever docs I use match the links I put in my project. I had used bs5 links and was using bs4 docs and that caused some confusion. There were some classes and such that had changed from bs4. 

I did not have time to play too much with the details of the styling, but I went with a different theme than the example images provided for the assignment. I went with a minimalistic theme and some black and white images to keep it crisp.

![image](https://user-images.githubusercontent.com/72420733/102654705-035b6b00-413f-11eb-8bd1-3fc4557274a7.png)

Whereas the bootsrap documentation was good, there were definitnly things I had to research on my own. I had some difficulty maintaining bottom and side margins at smaller viewport sizes, despite assignining the side margin classes to the elements I wanted to maintain side and bottom margin for (see below). I ended up using some of my own css to resolve the issue, and I did confirm despite the example images, that xs viewports should have no margins and conent should cover full screen width so I left as is for the 400px viewport width.

![image](https://user-images.githubusercontent.com/72420733/102654603-cdb68200-413e-11eb-8f7d-91c46a55a33f.png)

I also had some trouble getting the navbar links to justify to the right side of the page after they were uncollapsed at smaller viewports, but I am not sure if that is ok or not. I did not find any docs on this, aside from those explaining how to get the toggle button justified to the right (end):

![image](https://user-images.githubusercontent.com/72420733/102438027-8cf92480-3fe9-11eb-8bcd-837f9068f373.png)

In terms of utilizing the grid layout system with bootsrap, I was able to to this, but I will still have to learn if I did it in the best way. Generally on all pages, I created a header, a main container, and a footer. Within the main container I created a main row, and within that row two columns (one for content, one for white space). I then created subrows and columns, but never included actual content as the direct child of a row. For all rows, I included at least one column with col-md-12 class to put content in. I noted in many examples and reading, that most people seemed to do this and it helped ensure more consistent margins but I will have to learn more about why that is. 

![image](https://user-images.githubusercontent.com/72420733/102438076-a306e500-3fe9-11eb-88bf-41c59b1f80db.png)

This assignment tought me a lot about bootsrap, and continued to force me to get better at self-learning and organization (for example, just figuring out how I breakout and tackle tasks from scratch on a new development and then how I manage testing, and tracking of bugs or issues I find so I can get as many of them solved before the due date). I use a tool for now that I use in my professional job to do this, and will see how it works going forward. 

![image](https://user-images.githubusercontent.com/72420733/102438146-c29e0d80-3fe9-11eb-8ac9-39c4031ee70d.png)

**Note** I leanred that the auto-fill for file path in vs code does not always structure the same way. I had been using live server, and had no issues but then when I deployed to git pages, nothing was loading right from my repo. I found it was because my file paths were not doing the proper ../ to get back and into directories, so I updated them all and things worked. 

**Note** I also utilized an HTML validation service and was able to find some extra hyphens, and change semantics based on its reccomendations.


## Credits
I utilized bootstrap for most of the css and layout of the pages, and also utilized my classmates and instructors for some support on bug resolution.

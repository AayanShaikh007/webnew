# Website Devlog

Today I finalized the website. I lowk forgot that I needed to add devlogs so I guess this will need to be a really long devlog. I started making the website with the aim of making a minimalistic website that just 'gets the job done' without too many crazy animations. I also urgently needed a portfolio page where I could show off my projects and funnel traffic to my GitHub repos, because I heard portfolios are pretty important for internship applications.

## Framework Selection

I started by determining what framework to use. I looked at some websites from other Hack Clubbers and decided to use Astro because I could use it with various other frameworks and because it provides good performance. I have used Tailwind CSS a lot in the past as well, so I wanted to use that here too.

## Project Setup and Initial Development

Setting up the project didn't take too long. I think I had the whole thing setup in half an hour or so, which was a much better experience than working with React — I actually spent multiple hours debugging why React wouldn't build on my computer. I started with the main page, making some sample text and figuring out how to add side navigation bars and how to add navigation bars on mobile/small screens.

## Creating Core Pages and Components

I then moved onto making the other pages, like contact and resume. I realized that the code for navigation bars was pretty long and copy-pasting it was redundant, so I made them into Astro components that I could call in the various files after importing them from the appropriate file. I then added some more text, which surprisingly took me a good amount of time because I knew I would be putting this website on all my socials and it would be reflecting me in a way. Credit to Acon Lin's website for the commit version footer idea.

## Projects Page Development

Finally, I made the projects page, which started out as just a flex box with each project as a box. I progressed to add functionality for a popup box for each project and code that lets you click on an image to see it in larger size. I also looked into small things like hiding/changing the appearance of the scrollbar to make the experience more seamless. Adding information of the projects itself was a pretty tedious task, so I /might/ have had AI fetch summaries from the repos :|

## Finishing Touches

At the end, I added some finishing touches like animations to the text and the project boxes and tried to implement some code that would speed up the image loading time. I am currently looking into ways of adding a background animation to the page. 

---
layout: essay
type: essay
title: E6 Class Retrospective
# All dates must be YYYY-MM-DD format!
date: 2021-12-13
labels:
  - Wow
  - Assignment
---

1) Briefly describe your system (e.g. A store selling Pokemon game cards)

My system is HEAVENSCENT: a store selling fragrances.


2) Any notable shortcomings, bugs, problems, or additional features not implemented?

When navigating the product display pages, the console shows an uncaught syntax error for "<" in productdisplay.html line 245. The code at this location is a loop that determines whether the nav bar will show the link to Register based on the status of a cookie. The strange thing is that this code works perfectly fine as it should! However, I understand that errors showing in the console are grounds for points off; therefore, I tried to think of ways on how I could change the code without using HTML tags so that I could avoid this console error altogether. I ultimately couldn't, so this is my greatest shortcoming/regret about this assignment.
Other than that, I really wanted to succeed in many of the interesting extra credit opportunities for this asssignment such as combining carts between sessions and editing customer information, but I couldn't quite figure out how to do so on time.


3) Describe what you are most proud of about your system:

I'm pretty much proud of everything else. Much of the vision I had for my store, in terms of aesthetics, functionality, and architecture, really came into fruition. 


4) Describe what you are least happy with your system:

I am not happy about the off-centered store name in the top handle. I wanted to use the website layout of a template from w3schools, which has its own stylesheets, but the CSS from w3schools made it difficult for me to implement style changes quite like the way I wanted, such as using additional CSS to center the store name. I tried my best and truly tried a multitude of things but  couldn't fix this issue.


5) How was developing this assignment different than assignment #2?

The biggest difference is that I essentially started the assignment from scratch. Starting with the concept, I had to think of a new idea because I couldn't come up with sensible ways that I could possibly separate the product pages for my original idea of a sneaker store. Furthermore, the architecture required for Assignment 3 is significantly different from that of Assignment 2, so modifying what I had from Assignment 2 wouldn't really make sense for me. However, I did use/reference a lot of code I used from Assignment 2 (such as registration validation), so I technically didn't do everything from scratch.


6) When you ran into a problem, what did you do to address it?

If the problem was associated with a specific piece of code, I first tried to address the problem from a surface level. If that didn't work, I tried to think of different ways to write that piece of code so that I could fix the issue more systematically.


7) Describe what worked well in doing this assignment?

This assignment was different in that I referenced A LOT of code/information from outside resources. Fortunately, there was an ample amount of documentation on express sessions, how to implement security, using the node mailer, etc. so looking up how to do things on Google worked well for me for Assignment 3. 


8) Describe what did not work well in doing this assignment?

Again, I referenced a lot of code from the Internet for this assignment. Because I felt short on time, my first instinct was to copy the code and paste it into my file to see what happened, but I found that that wasn't the best method because I ended up spending a lot of time modifying that code to make it work into my assignment. The better method, as mentioned by Professor Port, is to study the reference and then adapt that into my code. It seems like it could possibly take longer, but it's really the opposite.


9) What did you learn from doing this assignment?

The process I underwent in order to construct my web application is extremely relevant to what is required of a professional in real life, specifically due to the usage of sessions and cookies which are used by businesses across the board. With that being said, I actually enjoyed doing this assignment, especially implementing certain functions like the shopping cart and login/logout, so I definitely want to consider this experience when thinking about what I could possibly do in the future (or maybe even just in my spare time).


10) If you could go back in time and do things differently, what would you change?

One of the most frustrating experiences was dealing with the issues of the w3schools template. While it did make a lot of things easier in terms of constructing the nav bar, I also felt like I couldn't implement my vision 100% the way I wanted to because of the w3schools stylesheet. (Looking back, I technically could've copied the stylesheet to my directory and modified it, but navigating the stylesheet was difficult because they used complicated styling methods, and attempting to fix that would've wasted time.) For Assignment 1 and 2, I didn't use a template and didn't face this kind of frustration, so I think next time I wouldn't use a template and try my best to construct things by myself to replicate what exists in a template.


11) Estimate the % of time you spent (a) thinking about how to do something, (b) writing code (but do not include testing, (c) testing and debugging

(a) 20%

(b) 30%

(c) 50%


12) Assign an estimated percentage on the amount each team member contributed to the assignment (including yourself) and explain briefly your rationale for the percentage breakdown. Be sure to include an overview of what specifically you and your partners contributed (e.g. “I worked on the security and my partner 1 worked on personalization”)

Not applicable--I worked by myself.
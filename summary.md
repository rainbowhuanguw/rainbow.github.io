1. What was the most challenging piece of this assignment?  Did you find it easy or challenging to work with HTML and CSS? 
Thinking about the content and design, i.e. what and how I want to highlight and present to the viewers. 
I found it surprisingly hard to work with HTML and CSS as they are static languages. I found myself unfamiliar with the syntax and had to look up desired fields online, which is time consuming. 

2. Decisions to make my website mobile friendly
I made use of the @media query to display blocks and fonts differently depending on the size of the screen.

example query code as follows. 
```
@media screen and (min-width: 768px) { /* for desktop */
    .box {
        width: 30%;
        height: 20%;
    }
    .box .text {
        font-size: 18px;
    }
}

@media screen and (max-width: 768px) { /* for mobile */
    .box {
        width: 100%;
        height: 50%;
    }
    .box .text {
        font-size: 20px;
    }
}
```

3. What did you take into account when you developed the design of your website? 
- Color scheme: grey, white, dark red. 
- Hovering actions: Most of the texts only got displayed when the user hovers over the corresponding project section, which helps to keep the page clean. 

4. Given more time and resources, what additional features would you add to your site in the future?
I would make my site more interactive by separating text into smaller chunks.
I would also like to add an extra page to showcase my hobbies to make it more personal. 
Probably adjust the font size and family accordingly. 


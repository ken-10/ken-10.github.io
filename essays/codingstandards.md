---
layout: essay
type: essay
title: Make Your Code Pretty
# All dates must be YYYY-MM-DD format!
date: 2019-02-09
labels:
  - Coding Standards
  - Software Engineering
---

## **First Impressions**
Remember the time when you didn't know how to code at all? Code looked pretty intimidating right? All these words, numbers, brackets, periods, and paranthesis everywhere spaced out and indented oddly but, after you learned the basics it wasn't so bad after all. Although, you know how to read code and all, at the end of the day, you got to admit, it's still ugly. But imagine it being uglier and how could it get uglier you ask? Well it gets ugly times two when you don't have any "coding standards." 

## **Coding Standards??**
A coding standard is when you set how many indents there should be, when a whitespace should be present between two words/letters, etc. Everyone has a perferred way of typing out their code, which is why I like to say that "handwritings" do exist in code. Let me explain. You've probably heard of someone saying, "You're handwriting is nice!" or "You're handwriting sucks!" Well this can easily be applied to the way one writes their code. If someone keeps line breaking unnecessarily and has too many indents in a line in an if statement:
```
if (code ==     ugly)

      {
                        checkstyle();}
```
many people will call you out for having a terribly formatted code. This is comparable to someone having unreadable handwriting. A code that does not conform with coding standards may still be read, but with difficulty. Readability is very important in software engineering because it is all about collaborating. In school, you may not need to look at one anothers' code for the majority of the time, but out in the real world, you will most likely be coding with other people on one project. So a fantastic way to prevent any ugly code is to have coding standards! These usually come in some checkstyle formatting file that you can easily activate to clean up your code or a red squiggly line appears under an area of your code when it doesn't look right and it tells you how to fix it. 

## **What I Use**
Being that I am currently learning Javascript, I started using this program called IntelliJ IDEA and it's very important that I install a coding standard configuration. I ended up using this config called: Eslint and I find it really useful because it gives you a green check mark to indicate that your code is up to the configurations standards. Also, it will underline code that needs to be repositioned, not used, syntax errors, etc. I've used other coding standard configurations and Eslint is just like any other checkstyle configuration out there. 

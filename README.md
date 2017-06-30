# 2-different-responsive-html-element
Making a responsive html, one with stretching, and the other with scaling

## Explanation
So this is something you should know when you're trying to make responsive html page. Basically this is somekind of hack that I developed some years ago to make html responsive (what I mean here very responsive)

I've seen that people has been struggling to achieve this, but I haven't seen the practical use of this (Unless by myself haha), but it seems that this kind of thing is not so well known. The stretches (normal) one might have been known for quite while as it's just basic, no need any hack. What I actually developed was the scaling thing.

## How it works
For the normal one, you're basically making elements that is relative to parent elements' height and width. The scaling one is a bit tricky, I used `padding-bottom: 100%` to make the height of the element keep the ratio.

### This is the scaled element (they're all elements from html, I used 0 images)
![scale](https://user-images.githubusercontent.com/4760947/27757199-e81d21dc-5e28-11e7-9fd4-45a56e4846d6.png)

### This is the stretched element (they're all elements from html, I used 0 images)
![stretch](https://user-images.githubusercontent.com/4760947/27757220-3035292e-5e29-11e7-9231-2e1f0a7e7127.png)

## How to check it
Just open those HTML files on your web browser, try to resize the window. Also try to zoom in and zoom out.

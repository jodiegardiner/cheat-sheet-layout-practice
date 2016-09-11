# Layout practice - Cheat Sheets
Simple cheatsheet links for all we have covered in Stream 1 by the end of the first week.


## What it does
Pulls together all the cheatsheets from across the slides into one responsive navigation bar. Also, I made my own html cheetsheat layout using content from one of the html cheatsheet links.

## Rationale
I wanted to practice the various techniques we learned in week 1 whilst also putting together something that I will personally find useful in the days and weeks to come.  Perhaps someone else will find it useful too.

I found that when I wanted to access the various cheatsheets, I had to jump back and forth between the slides to find the individual cheatsheets for a particular area of study.  Therefore, I wanted to point to the cheatsheets from one easily accessible location.

## Techniques
* First of all, I wanted to keep all of the styling information out of the HTML. Not only that but as I thought I would need at least 2 pages, this was the first time I have referenced an external stylesheet of my own creation.

* This is also the first time I encountered the TABLE tag but it seemed ideal for my purposes (displaying 2-column tabular data). I have since learned I could probably replicate it using the Definition List type.

* For all but the HTML cheatsheet, I have linked to the same urls we were given in the slides.  In html.html, I used the cheatsheets as content for my layout practice.

* I discovered the XMP tag which lets you display html tags as raw text without having to faff around too much.

* I found the background image first then used a colour picker tool to find a colour on it that I liked and went on to use as the background colour for the .box class.  This helped to create a continuity in aesthetics.

* I used the name anchor to put a "Return to top" link at the bottom of the layout so the user didn't get stranded at the bottom of the page with no easy way to get back.

## Responsiveness
The layout is very basic but the structure did breakdown into an ugly mess at smaller screen sizes.  Therefore, the navigation will switch to a flexbox column if the screen size is smaller than a tablet.

## Issues and obstacles

* There are still a couple of issues with overflowing data that I haven't managed to fix yet. This is mainly caused by content in the XMP tags which it is not able to wrap successfully using normal css wrapping properties.

* The flexbox navbar was repeated on two pages.  I wonder if there is a way to only have to write it once and reference it from the other page(s). In this case, I could obviously just copy and paste but I was thinking in terms of scalability to scores or hundreds of pages.

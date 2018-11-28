# FreeStylin
Collection of Styles used in Stylish. Mainly Focused around English translated Light/Web novels. Made for myself first. 

The TL:DR is that Light/Web novel websites suck. Huge whitespace, tiny fonts, minimum/maximum widths all over the shop, the expiriance is horrible. I don't know good design guidelines, I just know I dislike reading something on my large 1920x1080 monitor when the text area is under 800px wide. Huge sidebars, menues that follow you around like a lost puppy, built in chat, why the fuck would you even want that? I don't know css very well. I don't know web design either, or much of anything creative. I just know I'm angry that the webnovel reading expirience is so bad. 


The general gist of what im going for is as follows:

1: Remove anything not to do directly with the text of the Light/Webnovel, comments and navigation to the next chapter.
2: If a direct next-chapter button is avalible, remove any "next post" navigation. 
3: If the website enjoys changing styles around too much from chapter to chapter, remove it's ability to do so. Especially if it changes font size, weight, bolding and familly frequently. Simply targeting the entire shitty webpage is fine. 
4: Remove minimum widths whereever possible and expand the text area to fill almost the whole page using % based widths. I tend to create a few percent buffer around the left/right side of the page with a few % margin. Text too close to the edge of the screen can be difficult to read, but only allowing text right in the center also is bad as far as im concerned. As for minimum widths, zooming the page changes the effective resolution. For pages with small text and large minimum widths, zooming the page can create a scenario where you have to scroll left to right to read each line.
5:As at this point most of the page scales with zooming well, but inline images do not, so use vh and vw to scale the images to fit the viewport. Advice on the best size to pick would be good, for now I'll set it to 60% at most. 
6:I like aligning the images and heading text to the center of the page. Sometimes I am unsure how to do this without messing up the text on the page though.
7:There is several web/light novel websites that like adding random images in the middle of the chapter, to "Show" the user what the translator thinks the web novel is trying to show us. Others add embeds to youtube videos. I don't mind linking songs, but embeding things into the story space should really only be done to link actual sauce material. No random images of a town built in minecraft, I have an imagination and it works just fine thanks. No song at the start that gives away plot either. 


There is probably more I'm forgetting, but generally I just want to read. 

At the time of writing I'm still initially setting up the css. After some time I'll upload it to the applicable places including here. At that time I would love help in adding existing/new sites I missed, re-writing my shitty css hacks and anything else really. I would also like to decide what fonts should be selected if fonts are ovverwriten as well as other standardisation things. Although it might be going too far, I thought it might be nice to just completely override all web/light novel sites to turn them all into easy to read webpages that look pretty much the same.

# 100 Days Of Code - Log -Eduardo Febres

### Day 0: April 23rd, 2019
**Today's Progress**: I built a slick slider snippet from scratch to understand how it works and the classes it uses. I set up my 100-days-of-code repository.

**Thoughts**: I struggled a litlle to find out how to comment a markdown file.

**Link to work**: [Slick slider snippet]

### Day 1: April 24rd, 2019
**Today's Progress**: I placed the responsive slider and the responsive logo on the same container and they work toghether well. I still have to fix the vertical margins in medium sizes, and disable the slider in small sizes. I also have to synch an empty slide with a query that hides and shows the responsive logo background.

**Thoughts**: Even though I think my javascript knwoledge is near zero, I felt very confident customizing the responsive slider.

**Link to work**: [responsive logo + rough responsive slider content]

### Day 2: April 25st, 2019
**Today's Progress**: I struggled trying to manipulate with jquery the classes I used to make my logo responsive (using background image position and size and svg file) to make it appear and dissapear in synch with an empty slide of the slick slider. Didn't make any progress but learned some jquery sintax and workarounds. I didn't stop until I found this [solution to loop addClass and removeClass] with jquery. Hopefully I'll have my responsive slider + responsive logo header done by tomorrow.

### Day 3: April 26th, 2019
**Today's Progress**: I kept struggling to make a background image change in a loop, to achieve the responsive logo + responsive slider header. Didn't make it yet but already found a script (in pure java script, no library) to change a background image in a loop. I made the test with a svg  file and it worked. I think tomorrow I'll just have to synch the background image (with the responsive logo) and the slider and move on to the next challenge.

**Link to work**: [background image change in a loop with pure js]

### Day 4: April 27th, 2019
**Today's Progress**: Finally made it! Roughly but made it: I have a slick slider and a responsive logo on the same header. It was hard to synch the slider animation script and the toggle background image animation script, and I tried some others approaches (like covering the background responsive logo with a slide background color, or putting the responsive logo background-based on a slider container). None of them worked, so I try harder to synch the slider and the background image toggle, and finally made it. 

**Thoughts**: It's not even close a perfect solution. But I'm proud of how far have I go without learning more than really really basic javascript. I'll learn some more on the 100Days challenge, though, and I think that after this work everything will be easier there.

**Link to work**: [responsive slider + responsive logo header]

![responsive logo + slider gif](https://media.giphy.com/media/SVOOhH7Ed4BM1QCO9f/giphy.gif)

### Day 5: April 28th, 2019
**Today's progress**: Today I just adapted my current portfolio (build with #jekyll on #githubpages) to pass the Responsive Web Design Project on #freeCodeCamp. 

**Thoughs**: Some things were a little odd since I build it with a different approach.

### Day 6: April 29th, 2019
**Today's progress**: Today I kept bringing myself up to date with #freeCodeCamp projects (in order to get certifications), trying to work in real projects. I'm building a survey to add to my portfolio webpage, where costumers can quickly ask for an estimate.

### Day 7: May 2nd, 2019
**Today's progress**: For the last two days I couldn't help getting distracted by the turmoil in my country, Venezuela. Today I coded for more than three hours to recover some of the lost time. I've been optimizing my workflow, setting up a build machine with npm. I've been using two great tutorials by Site Point. I'm almost done with the build machine, and I hope to be working tomorrow on my Drupal theming.

**Thoughs**: I used to think that may be npm was too much of a tool for simple minifying, vendor prefixing and sass compiling jobs. However, I find it a very useful tool to organize your projects, no matter what their size is.

### Day 8: May 3rd, 2019
**Today's progress**: I finished muy build tool with npm, based on the [Site Point tutorial] and adding the postcss package. I also started to review some material about Drupal theming. And I found out that my own notes from more than a year really worked for me as a breadcrum. Ready to get deeply into the theming tomorrow.

**Thoughs**: I don't find how Gulp is useful if you can simply make a custom buildtool with npm. May be I'll find it useful when I'm more advances.

**Link to work**: [buildtool]

### Day 9: May 4rth, 2019
**Today's progress**: I started the setup of my Drupal theme and everything went well. However, when I was about to start mixing the twig files with my custom html, I decided to do it first with a test website. So I installed a new local Drupal site and took a w3 schools theme and made some adjustments, to make a Drupal theme from it.

**Thoughs**: Am I just procastinating? Sincerely I think that doing my first theming with a (more or less) complex real web site might not be the most productive path. I'll rather finish this photographer's template demo, before working directly with my digital humanities project.

### Day 10: May 5th, 2019
**Today's progress**: Theming is already going on. I spend some time seting up a custom build tool for the theme folder, from sass, to css, to css min, adding vendor prefixes and reflecting changes in real time. The fact that minifiers rewrites urls relative to the minified file location blew my mind a little .

**Thoughs**
My old notes have been of great help. It has made everything quite easier.

### Day 11: May 7th, 2019
**Today's progress**: Going ahead with Drupal theming. I've been working on the setup of the CMS as well, to have a nice working photographer's site Drupal template, with collections, tags and photo stories/series. I'm not making fast progress yet, because I'm still warming up and getting used to the file structure, relation between templates, debugging workflow, etcetera. Hope to have a very productive day tomorrow! (and start to commit so I can show some links).

**Thoughs**
I was trying to have a raw twig template and a html layout template (progressively mutating into twig), running at the same time on the templates folder. I think the only way is to open the raw twig template in the browser, never refresh, disable it, and inspect it as you replace the static html with twig scripts on the actual running-on-the-server file.

### Day 11: May 8th, 2019
**Today's progress**: More theming. Still getting used to the naming conventions, and to the clearing-cache routine. I messed it all up and had to start from scratch when I log out. I left the themed responsive menu working (although the small version is not dynamic yet) and finalized my day with a completely clear idea of the workflow and naming conventions.

**Thoughs**: May be learning Drush could be mi next challenge. Also, I think that I must define my profile as a junior full-stack developer, developing in Drupal, Jekyll, Prestashop and the front-end tools.

### Day 12: May 10th, 2019
**Today's progress**: After two intense paperwork-days, back to the one hour routine. In that time, today I just could make a little progress with theming, adding a pseudo-class to have one of the links (home) remaining on the top navbar when the rest of them ar not shown. I also made my work in progress template a more specific one (--front), not affecting the rest of the site while I work.

### Day 13: May 11th, 2019
**Today's progress**: Just to find out that I was theming the responsive navbar with a wrong approach: I was trying to duplicate the main navegation menu block, followingt the html template approach, wich repeats every menu Item and toggles hiding/showing one or another in different sizes. Tomorrow I'll make it work either with jquery or with a Drupal module.

### Day 14: May 15th, 2019
**Today's progress**: Installed a slimmenu in my Drupal site. Learned the workflow for snippets of jquery code in Drupal theming.

### Day 15: May 16th, 2019
**Today's progress**:  Tried to customize the slimmenu while theming but it's a terrible idea. Haha. After some struggling, I went back to customize it as a static template before using it with my Drupal site.  I'm making quite faster progress now, but it's late and I have to stop for today.

**Thoughs**:

* Does it worth to keep using clearfix hack? I did some research and found that it mostly doesn't worth it unless you have a wide audience in New Zeland (?). As a general rule, I wouldn't use snippets in the future if they are not made with modern styling (basically flexbox).
* Slimmenu is a great tool, although too hard to customize, and styled with the old fashioned clearfix approach. I'm considering a pull request, or may be fork it and upload a different version entirely made with flexbox.


### Day 16: May, 2019
**Today's progress**: I finally have cms responsive menu working!

### Day 17: May 27, 2019
**Today's progress**: Very productive day. I had the challenge to set up a cms based background parallax image that allows user to choose it and change it. Found this [beautiful module]. Had some trouble making it work (i missed one of the installation instruction steps, the one related with permissions), and it made me learn more about the relation between regions, config file and variables. 

**Toughs**: I've lost my streak, obviusly, but hopefully I'll get it back. Last week was a tough one.


[beautiful module]:https://tag1consulting.com/blog/background-image-new-drupal-8-module

[buildtool]:https://github.com/febr3s/dev_git/tree/master/buildtool

[responsive slider + responsive logo header]:https://github.com/febr3s/dev_git/tree/master/responsive-logo-sprite%2Bjs-slider

[background image change in a loop with pure js]:https://github.com/febr3s/dev_git/tree/master/responsive-logo-sprite-intermitente

[struggling with jquery and responsive logo + slider]:https://github.com/f3br3s/dev_git/blob/master/responsive-logo-sprite%2Bjs-slider/index.html

[solution to loop addClass and removeClass]:http://jsbin.com/oselux/1/edit?html,css,js,output

[responsive logo + rough responsive slider content]:https://github.com/f3br3s/dev_git/tree/master/responsive-logo-sprite%2Bjs-slider

[Slick slider snippet]: https://github.com/f3br3s/dev_git/tree/master/responsive-logo-sprite%2Bjs-slider

[//]: # (**Today's Progress**: Fixed CSS, worked on canvas functionality for the app.)

[//]: # (**Thoughts:** I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality.)

[//]: # (**Link to work:**)

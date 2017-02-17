---
layout: post
title: Waste In India
tags: [waste, visualization, India]
date: 2017-02-06 12:00:00
show-avatar: false
comments: true
css: /css/post.css
--- 

[comment]: <> (This is a comment)

<!-- STYLES -->
<link rel="stylesheet" type="text/css" href="/css/binbag/frame.css">

Our :tada: first :tada: Free Fifty project is with [Binbag](https://www.binbag.in/) :recycle:    
    
What they do | What we do  
----------------------------------------- | -----------------------------------------  
provide a simpler way to recycle in India  | data visualization of waste facilities

<div><br/></div>  

### Table of contents

- [What we want](#want)
- [How we build it](#build)
- [Next Steps](#nextsteps)
  
<div><br/></div>  
  
### What we want {#want}  
    
We want to build an interactive map which displays all waste facilities in India - including address, name and contacts.  
A similar map to this one is provided by [Wastebits](https://wastebits.com/) <i class="fa fa-arrow-down" aria-hidden="true"></i>
, which aims to serve the States.  


<iframe class="frame" src="https://wastebits.com/locator/results?keywords=Paper+Documents&location=California">
  <p>Your browser does not support iframes.</p>
</iframe>  

<div><br/></div>  
   
### How we build it {#build}  
  
Firstly we set up a map with facility listings to the left of it <i class="fa fa-arrow-down" aria-hidden="true"></i>.  
Feel free to click <i class="fa fa-hand-pointer-o" aria-hidden="true"></i> and explore.  

We use *[dummy data](https://freefifty.github.io/binbag/recyclers.csv)*. It details the locations of 10 bettary recycling stations near Balgalore, India.    
  
<iframe class="frame" src="https://freefifty.github.io/binbag/map.html">
  <p>Your browser does not support iframes.</p>
</iframe>  
  
Click this [link](https://freefifty.github.io/binbag/map.html){:target="_blank"} to explore better.  
  
The next step is to enable filtering: by type of accepted waste for recycling and /or/ city. This current examples shows all entries which are in 'Bangalore' and recyclye 'batteries'.   

<iframe class="frame" src="https://freefifty.github.io/binbag/map.html?type=battery&city=Bangalore">
  <p>Your browser does not support iframes.</p>
</iframe>  
  
View [this](https://freefifty.github.io/binbag/map.html?type=battery&amp;city=Bangalore){:target="_blank"} in a browser.  
  
After this we added an index search page, which looks like this:  
  
<iframe class="frame" src="https://freefifty.github.io/binbag/">
  <p>Your browser does not support iframes.</p>
</iframe>  
  
Click this [link](https://freefifty.github.io/binbag/){:target="_blank"} to explore better.  

This was made with [Mapbox](https://www.mapbox.com/){:target="_blank"}, [D3.js](https://d3js.org/){:target="_blank"} and [Jekyll](https://jekyllrb.com/){:target="_blank"}, and it feels like:    
  
+![](http://i.giphy.com/DqSw5gyRQ5yPC.gif) 

### Next Steps {#nextsteps}  
  
  <div><br/></div>  
  
1. Improve the looks and feel of visualization.  
2. Follow up with Binbag and report waste collection. 
  
<p class='author'>Author: Ekaterina Stambolieva</p>
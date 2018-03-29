# How-To-Change-Any-Link-Color-In-Blogger-Via-CSS-Easily

In this post you will learn How to Change Link Color in blogger template; Post title color, footer links, sidebar links, link from post body and many other beautiful link color effects.

Interestingly in recent months bunch of creative developers and designers across the world has jumped in and has served Blogger platform with loads of freaking awesome templates. So, today for blogspot users of various niches, list of beautiful templates with multiple of different useful features are available. But still, sometimes user want to make some little tweaks like to changes color schemes, background images, comments box, minor changes in layout and etc. Especially in old and default blogger templates doing modification more common.

There could be any reason to change link in blogger. For example; user wants to make links more visible and stands out from text stack or, want to make design more attractive to enhance users experience and click through rate also, etc.


# HOW TO CHANGE HYPERLINK COLOR IN BLOGGER DEFAULT TEMPLATE


It is much easy to change hyperlink color in blogger default templates because in these templates only a single color scheme is used for all links. To make changes in them go to Blogger > Template > Customise > Advance > Add CSS.

Now after that paste the following piece of code in Add CSS box.

a:link { color: #ff0000 !important; } 

a:visited { color: #0000ff !important; }  

a:hover { color: #38761d !important; }

a:active { color: #ff9900 !important; }    

And then tap on Apply to blog button to save changes.

In case you are not familiar with html color codes or facing any difficulties then you can simply replace color code (for example #ff0000) with the name of desired color. Checkout following piece of code to get an idea of what I'm saying,

a:link { color: red !important; }

a:visited { color: blue !important; }

a:hover { color: green !important; }

a:active { color: orange !important; }




# HOW TO CHANGE COLOR OF SPECIFIC HYPERLINK


n case you are interested to apply different color schemes on links within specfic sections forexample, Sidebar, any specific widget, footer links, post links, etc. then, you need to be little designer :P . The method is quite simple, you just need to mention the CLASS or an ID of that specific section before writing css code for link. For example, if I need to change the color of links only within blog post body (Bloggeristan) then I need to add following lines in Add CSS box.


.post-body a {
color: red !important;
}


To add hover effect you need add another line,

.post-body a:hover {
color: green !important;
}

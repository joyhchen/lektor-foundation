# lektor-foundation
Zurb Foundation 6 starter theme for Lektor. Preview here: http://w1.hewlohost.com/~joythewizard/

Hi, I've never worked with a static site generator before, so this is my first time working with Jinja2. Some parts of the site are currently hardcoded, but I'd like to move to get rid of those areas. Also, since this is my first time working with a static site generator, this project is a way for me to learn the ropes, meaning I'll fumble in some (if not many) areas. I'd love some help and I hope this project helps out anyone interested in Lektor. 

##Sass
This theme uses sass, but if you would rather use vanilla CSS, you can use the compiled foundation-sites.css file included and delete the sass components. 

##Temporary Grid Solution
I plan on creating a plugin, but for now you can add a grid to your page like this: 

Add to your html file: 

    <div class="row grid">
        <div class="large-4 columns">
            {{ this.column1 }}
        </div>
        <div class="large-4 columns">
            {{ this.column2 }}
        </div>
        <div class="large-4 columns">
            {{ this.column3 }}
        </div>
    </div>
    
To your ini file:

    [fields.column1]
    label = Column1
    type = markdown
    [fields.column2]
    label = Column2
    type = markdown
    [fields.column3]
    label = Column3
    type = markdown

You would have to adjust the large-4 class according to how many columns you have. This isn't the best way to create a grid but it works for now. Hopefully I can find the time to create a plugin where you can add rows and columns directly in the admin interface.

##Lektor
####What is Lektor? 
https://www.getlektor.com/docs/what/
####Installation
https://www.getlektor.com/docs/installation/
####Quickstart
https://www.getlektor.com/docs/quickstart/
####Lektor repo
https://github.com/lektor/lektor

##Zurb Foundation
####What is Zurb Foundation? 
Foundation is a front-end responsive framework. 
http://foundation.zurb.com/learn/about.html


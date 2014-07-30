## Unicorn.js, a <s>jQuery</s> plugin for sweet cyclic rainbow text!
### NOTE: This documentation is outdated, new docs coming soon

Carve hours from development time with **unicorn.js**! This revolutionary JQuery plug-in ***not only* applies rainbow colors** to elements' text, ***but also* animates these colors upon hover** in a direction of your choosing! No longer must you worry about rolling you own solution to this commonplace front-end task; just sit back, relax, and let unicorn.js take the wheel. 


<a href="http://codepen.io/presstep/full/HIGhc/">
Please try our demo:  ![image](https://f.cloud.github.com/assets/39191/2134420/40fec238-92e4-11e3-88c0-bc3129b4c651.png)
</a>

----------

> *"I truly feel that Unicorn.js is to become as commonplace as reset.css in web development. As its usage grows rampantly, I will undoubtedly be hailed as the Sir Isaac Newton of HTML Elements"*  <br> **-Todd**, *creator*

### Accolades

> *"I had given up jQuery completely. But then Unicorn.js brought me back. The sweet, pulsating rainbow of joy is a part of my daily routine now."* <br> **-[Paul Irish][1]**, front-end developer &amp; general badass

<blockquote><em>"[Todd feels] this is truly a harbinger of future web development."</em><br> <strong>-<a href="http://chriscoyier.net/">Chris Coyier</a></strong>, designer at <a href="http://codepen.io/">CodePen</a> & writer at <a href="http://css-tricks.com/">CSS-Tricks</a></blockquote>

<blockquote><em>"Unicorn.js is the next evolutionary step to make the web the magical realm of sparkly beings made of light and whip cream"</em><br> <strong>-<a href="http://v3.desandro.com/">David DeSandro</a></strong>, of Twitter and creator of <a href='http://masonry.desandro.com/'>Masonry</a></blockquote>

<blockquote><em>https://mtc.cdn.vine.co/r/videos/09F9F8244A1092892368543309824_26dca596279.0.4.15267178649808893943.mp4?versionId=AjyFG1dAUCOY3bX9DMtSItne.lVYwlAC</em><br> <strong>-<a href="http://davidwalsh.name/">David Walsh</a></strong>, MooTools brainchild and Mozilla dev</blockquote>

### All this functionality must come with a price, no?
In short, **NO**! After much soul-searching -- and rejections from [Code Canyon][3] -- I decided to release this web development panacea free of charge. ***You heard right, folks...* FREE!!!** 

### I'm sold, but how do get started with Unicorn.js?
*Lucky for you, implementation is simple.*

But you probably shouldn't...

<s>After including JQuery 1.7+</s>, simply download and include [**<strong>unicorn.js</strong>**][4]. For example, let's consider adding the following just before your closing `</body>` tag:

    <script src="path/to/unicorn/unicorn.js"></script>

With the brunt of the work done, simply add another script block below the preceding two:

    <script>
        Expecto.patronum('.unicorn', {
         	'duration': '.2',
         	'bowFlow':'ltr',
            'cursor':'pointer'
        });
    </script>

The dazzlingly dazzling `.patronum(strClassName, objOptions)` method will attach mouse event handlers to the selected elements. Now when hovered, the target element's text color animates, becoming an **irresistible swirling spectacle of cyclic rainbow splendor!!!**

### That's great, but what if I require a bit more versatility?

*You're in luck! Unicorn is a shining beacon for versatility in plugin authoring.*

**Options** *(outdated)*

<ol><li>Saturation<ul><li>changes the intensity of colours<li>accepts integer values between 1 and 100</li></ul></li><li>Light<ul><li>reflects the colours' brightness<li>accepts integer values between 1 and 100</li><li>defaults to 50, as values of 100 will produce solid white text</li></ul></li><li>Speed (ms)<ul><li>the length of one cycle<li>accepts integer values representing ms (1s = 1000ms)</li></ul></li><li>ltr<ul><li>specifies the direction of "<strong>bow-flow</strong>," standing for `left to right`<li>accepts Boolean value of true or false</li><li>defaults to false, so <strong>bow-flow</strong> is right to left</li></ul></li></ol>

Let's examine the following:

    <script>
    $(function() {
        $(".awesome_text").unicorn({
            "saturation":100,
            "light":60,
            "speed":50,
            "ltr":true
        });
    });
    </script>


Now, that's a beauty!

# What're you waiting for???
I think you've got it. <strong>Go, ahead... Get your bow-flow on.</strong>
<br>
<br>
 


  [1]: http://www.paulirish.com/
  [2]: http://chriscoyier.net/
  [3]: http://codecanyon.net/
  [4]: https://raw2.github.com/toddpress/Unicorn-js/master/unicorn.js

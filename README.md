![Miniscroll](http://miniscroll.rogerluizm.com.br/fb.jpg)

Miniscroll is a little library for touch and desktop scrollbar application. if you found bugs send it to rogerluizm@gmail.com or send to <a href="https://github.com/rogerluiz/Miniscroll-JS/issues?page=1&state=open">issue</a> page


### It adds miniscroll.js in its page:

<pre>
&lt;script src="miniscroll.js"&gt;&lt;/script&gt;
</pre>

***

HTML markup:

<pre>
&lt;div class="scroller"&gt;
     // text here
&lt;/div&gt;
</pre>

***

### CSS markup:
<pre>
.scroller {
     width: 400px;
     height: 300px;
     overflow: hidden;
}
</pre>

***

### inicialization:
<pre>
new Miniscroll(".scroller", {
     axis: "y",
     size: 10,
     sizethumb: "auto",
     thumbColor: "#0e5066",
     trackerColor: "#1a8bb2"
 });
</pre>

***

### add CSS end change the color of miniscroll thumb and tracker:
<pre>
.miniscroll-thumb {
     background-color: #0e5066 !important;
}

.miniscroll-tracker {
    background-color: #1a8bb2 !important;
}
</pre>

***

### CSS for a sigle scrollbar:
<pre>
&#35;miniscroll-target .miniscroll-thumb {
    background-color: #0e5066 !important;
}

&#35;miniscroll-target .miniscroll-tracker {
    background-color: #1a8bb2 !important;
}
</pre>

***

### Parameters:
**axis:**
_axle of scrollbar ex: "y" ou "x"_

**size:**
_the width of scrollbar ex: 10_

**sizethumb:**
_o tamanho do thumb ex: 100 ou "auto"_

**thumbColor:**
_the size of thumb ex: "#0e5066"_

**trackerColor:**
_color of fund of tracker ex: "#1a8bb2"_

**scrollbarSize:**
_size of scrollbar, you can set a size fix to scrollbar it ex: 300 this had left scrollbar with the height of 300px_

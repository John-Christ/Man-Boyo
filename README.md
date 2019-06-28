![Project Image](https://ia601408.us.archive.org/30/items/photoart1_20190627/WhatsApp%20Image%202019-05-11%20at%2002.40.24.jpeg)

# Welcome to Boyo Lifstyle.
---
## Below are display our latest videos and photos. Here is where you can checkout our latest releases
---
>Johnny Brozer - Fuck that shit!

brew install imagemagick
convert -delay 10 -loop 0 input*.png output.gif

_sass/call_me_what_you_like.scss
// Adds support for a video holder
// as per https://www.youtube.com/watch?v=boJewW5Mnxs

.myvideo {
position : relative;
display : block;
width : 30%;
min-width : 200px;
margin : auto;
height : auto;
}
.flex-video {
position : relative;
padding-bottom : 67.5%;
height : 0;
overflow : hidden;
}
.flex-video iframe, .flex-video object, .flex-video embed {
position : absolute;
top : 0;
left : 0;
width : 100%;
height : 100%;
}
<div class="myvideo">
   <video  style="display:block; width:100%; height:auto;" autoplay controls loop="loop">
       <source src="{{ site.baseurl }}/media/2016-10-24-add-video-to-github-README/visualise_params.mp4" type="video/mp4" />
       <source src="{{ site.baseurl }}/media/2016-10-24-add-video-to-github-README/visualise_params.ogv" type="video/ogg" />
       <source src="{{ site.baseurl }}/media/2016-10-24-add-video-to-github-README/visualise_params.webm"  type="video/webm"  />
   </video>
</div>

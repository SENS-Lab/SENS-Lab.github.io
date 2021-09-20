---
title: "SENS Lab - Home"
layout: homelay
excerpt: "SENS Lab at The Ohio State University."
sitemap: false
permalink: /
---

The Socio-Environmental Networks and Sustainability (SENS) Lab is a research group at the [School of Environment and Natural Resources](https://senr.osu.edu) at [The Ohio State University](https://www.osu.edu). We investigate how people interact with one another and with ecosystems, and how those interactions affect social and environmental outcomes.


<div markdown="0" id="carousel" class="carousel slide" data-ride="carousel" data-interval="4000" data-pause="hover" >
    <!-- Menu -->
    <ol class="carousel-indicators">
        <li data-target="#carousel" data-slide-to="0" class="active"></li>
        <li data-target="#carousel" data-slide-to="1"></li>
        <li data-target="#carousel" data-slide-to="2"></li>
        <li data-target="#carousel" data-slide-to="3"></li>
        <li data-target="#carousel" data-slide-to="4"></li>
        <li data-target="#carousel" data-slide-to="5"></li>
        <li data-target="#carousel" data-slide-to="6"></li>
    </ol>

    <!-- Items -->
    <div class="carousel-inner" markdown="0">
        <div class="item active">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/IMG_1151.JPG" alt="Slide 1" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/firemmodel.png.jpg" alt="Slide 2" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/lake.jpg" alt="Slide 3" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/firenet.jpg" alt="Slide 4" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/threemodenetwork.jpg" alt="Slide 5" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/WQCogMap.png" alt="Slide 6" />
        </div>       
         <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/firenet.jpg" alt="Slide 7" />
        </div>
    </div>
  <a class="left carousel-control" href="#carousel" role="button" data-slide="prev">
    <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="right carousel-control" href="#carousel" role="button" data-slide="next">
    <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>

Much of our work focuses on coupled human-natural systems, in which collective action among diverse stakeholder groups is often necessary to address environmental risk. Likewise, stakeholders must grapple with social and ecological dynamics that span multiple spatial/administrative scales. Our research is broadly organized around three core themes: 1) how diverse stakeholder groups conceptualize risk, individually and collectively, 2) how policy actors navigate complex risk mitigation governance systems, and 3) how governance systems self-organize to manage environmental risk (see [Research](research)).

<!-- 
**We are always looking for passionate new PhD students, Postdocs, and Master students to join us** [(more info)]({{ site.url }}{{ site.baseurl }}/opportunities) **!**
-->

<p id="twitterContainer" style="display: none; margin-left: auto; margin-right: auto;">
<a class="twitter-timeline" data-tweet-limit="3" data-width="1000" data-chrome="noscrollbar nofooter noborders" href="https://twitter.com/SENS_OSU">Tweets by Tech&People Lab @ ULisboa</a>
</p>

<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
<script>
function twitterStuff(){
  twttr.events.bind('rendered',function(){
    resizeTwitterIframe();
  });
}
function resizeTwitterIframe(){
  const vw = Math.max(document.documentElement.clientWidth, window.innerWidth || 0);
  const nodes = document.querySelectorAll('iframe.twitter-timeline');
  nodes.forEach(function(e,i,a){
    if(vw > 1023){ 
     const sectionTitle = e.contentDocument.getElementsByClassName('timeline-Header-title');
        if(sectionTitle.length){
          for (i = 0; i < sectionTitle.length; i++) {
            sectionTitle[i].style.fontWeight = "300";
            sectionTitle[i].style.fontSize = "12pt";
            sectionTitle[i].style.color = "#666666";
          }
      }
      const lis = e.contentDocument.getElementsByClassName('timeline-TweetList-tweet');
      if(lis.length){
          for (i = 0; i < lis.length; i++) {
            lis[i].style.width = "200px";
            lis[i].style.float = "left";
            lis[i].style.marginLeft = "0px";
            lis[i].style.marginRight = "10px";
            lis[i].style.borderTop = "1px solid white";
            lis[i].style.boxShadow = "0 4px 8px 0 rgba(0, 0, 0, 0.2)";
            lis[i].style.marginBottom = "15px";
          }
      }
      const text = e.contentDocument.getElementsByClassName('timeline-Tweet-text');
      if(text.length){
          for (i = 0; i < text.length; i++) {
            text[i].style.fontSize = "10pt";
            text[i].style.lineHeight = "18px";
            text[i].style.marginTop = "12px";
            text[i].style.marginBottom = "0px";
            text[i].style.marginLeft = "0px";
          }
      }
      const replyTag = e.contentDocument.getElementsByClassName('timeline-Tweet-inReplyTo');
      if(replyTag.length){
          for (i = 0; i < replyTag.length; i++) {
            replyTag[i].style.fontSize = "12px";
            replyTag[i].style.fontWeight = "300";
            replyTag[i].style.lineHeight = "16px";
            replyTag[i].style.marginTop = "6px";
            replyTag[i].style.marginBottom = "6px";
            replyTag[i].style.marginLeft = "0px";
            replyTag[i].style.paddingLeft = "0px";
          }
      }
      const authorName = e.contentDocument.getElementsByClassName('TweetAuthor-name');
      if(authorName.length){
          for (i = 0; i < authorName.length; i++) {
            authorName[i].style.fontSize = "12pt";
            authorName[i].style.lineHeight = "18px";
            authorName[i].style.fontWeight = "700";
            authorName[i].style.textOverflow = "ellipsis";
          }
      }
      const avatarDiv = e.contentDocument.getElementsByClassName('timeline-Tweet-author');
      if(avatarDiv.length){
          for (i = 0; i < avatarDiv.length; i++) {
            avatarDiv[i].style.paddingLeft = "45px";
          }
      }
      const avatar = e.contentDocument.getElementsByClassName('TweetAuthor-avatar');
      if(avatar.length){
          for (i = 0; i < avatar.length; i++) {
            avatar[i].style.width = "32px";
            avatar[i].style.height = "32px";
          }
      }
      const media = e.contentDocument.getElementsByClassName('timeline-Tweet-media');
      const hasMedia = media.length !== 0;
      if(media.length){
          for (i = 0; i < media.length; i++) {
            media[i].style.marginLeft = "0px";
            media[i].style.marginBottom = "0px";
          }
      }
      const metadata = e.contentDocument.getElementsByClassName('timeline-Tweet-metadata');
      if(metadata.length){
          for (i = 0; i < metadata.length; i++) {
            // metadata[i].style.position = "absolute";
            // metadata[i].style.bottom = "0";
            // metadata[i].style.direction = "rtl";
            metadata[i].style.display = 'none';
          }
      }
      document.getElementById('twitterContainer').style.display = "inline-block";
      const timelineBody = e.contentDocument.getElementsByClassName('timeline-Tweet');
      let biggerTweet = 0, parsedInt;
      let isRetweet = false;
      let isRetweetTheBigger = false;
      if(timelineBody.length){
          for (i = 0; i < timelineBody.length; i++) {
            for (var j = 0; j < timelineBody[i].childNodes.length; j++) {
                if(timelineBody[i].childNodes[j].className === 'timeline-Tweet-retweetCredit'){
                  isRetweet = true;
                  break;
                }
            }
            parsedInt = parseInt(window.getComputedStyle(timelineBody[i])["height"].replace("px",""));
            if(parsedInt > biggerTweet){
              biggerTweet = parsedInt;
              isRetweetTheBigger = isRetweet
            }
          }
          for (i = 0; i < timelineBody.length; i++) {
            if(isRetweetTheBigger)
              timelineBody[i].style.height = (46+biggerTweet)+"px";
            else
              if(!hasMedia)
                timelineBody[i].style.height = (8+biggerTweet)+"px";
              else
                timelineBody[i].style.height = (35+biggerTweet)+"px";
            timelineBody[i].style.padding = "16px";
          }
      }
    }else{
      document.getElementById('twitterContainer').style.display = "none";
    }
  });
}
document.onclick = function(e) {   //when the document body is clicked
  if (window.event) {
      e = event.srcElement;           //assign the element clicked to e (IE 6-8)
  }
  else {
      e = e.target;                   //assign the element clicked to e
  }
  if (e.className && e.className.indexOf('card') != -1) {
      //if the element has a class name, and that is 'someclass' then...
      window.open(e.id,"_self");
  }
}
var throttle = function(type, name, obj) {
    obj = obj || window;
    var running = false;
    var func = function() {
        if (running) { return; }
        running = true;
          requestAnimationFrame(function() {
            obj.dispatchEvent(new CustomEvent(name));
            running = false;
        });
    };
    obj.addEventListener(type, func);
};
/* init - you can init any event */
throttle("resize", "optimizedResize");
// handle event
window.addEventListener("optimizedResize", function() {
  const vw = Math.max(document.documentElement.clientWidth, window.innerWidth || 0);
  if(vw > 1023){
    if(document.getElementById('twitterContainer').style.display === 'none'){
      document.getElementById('twitterContainer').style.display = "inline-block";
      setTimeout(resizeTwitterIframe(), 100);
    }
  }else
    document.getElementById('twitterContainer').style.display = "none";
});
window.onload = function(e){
  twitterStuff();
}
</script>

We are grateful for funding from The Ohio State University, the Sustainability Institute, and the National Science Foundation.

<figure class="fourth">
  <img src="{{ site.url }}{{ site.baseurl }}/images/logopic/osucfaes_logo.png" style="width: 340px">
  <img src="{{ site.url }}{{ site.baseurl }}/images/logopic/silogo.png" style="width: 50px">
  <img src="{{ site.url }}{{ site.baseurl }}/images/logopic/nsf_logo.png" style="width: 110px">
</figure>

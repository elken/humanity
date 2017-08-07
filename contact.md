---
title: Contact
permalink: "/contact/"
bg: man.png
crawlertitle: How you can reach us
summary: How you can reach us
active: contact
layout: page
---

## Visit us!

<div id="googleMap" style="width:100%;height:400px;"></div>

<script>
function myMap() {
var mapProp= {
    center:new google.maps.LatLng(50.468161,-3.531531),
    zoom:20,
};
var map=new google.maps.Map(document.getElementById("googleMap"),mapProp);
}
</script>

<script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyCocy6_kZ4oaS0t1nrOMYsEZkbr6YcZPrU&callback=myMap"></script>
<br/>

| Monday | 10am-3pm |
| Tuesday | 10am-3pm |
| Wednesday | CLOSED |
| Thursday | 10am-3pm |
| Friday | 10am-2pm |
| Saturday | 10am-2pm |
| Sunday | CLOSED |

<h2>Call Us</h2>
<p>01803 297537</p>

<h2>Email us!</h2>

<a href="mailto:information@humanitytorbay.org.uk">For more information</a>
<br/>
<a href="mailto:{{site.email}}">To contact the owner of this site</a>

<h2>Reach out to us on social media!</h2>

<a class="twitter-timeline" data-lang="en" data-width="500" data-dnt="true" data-height="500" href="https://twitter.com/{{site.twitter_username}}">Tweets by {{site.twitter_username}}</a> <script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>
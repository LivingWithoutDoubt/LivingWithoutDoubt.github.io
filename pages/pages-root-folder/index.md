---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
#  <!-- image_fullwidth: header_unsplash_12.jpg -->
  image_fullwidth: FB_IMG_1454878233202.jpg
widget1:
  title: "Blog & Portfolio"
  url: '/blog/'
  image: header_roadmap_3.jpg
  text: ''
widget2:
  title: "Why You Rock"
  url: ''
  text: '<img src="https://s3.amazonaws.com/melinda-blog/images/FB_IMG_1454878233202.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Photo Gallery"
  url: '/photos/'
  image: widget-github-303x182.jpg
  text: 'Awesome pictures.'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
#callforaction:
#  url: https://tinyletter.com/feeling-responsive
#  text: Inform me about new updates and features ›
#  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

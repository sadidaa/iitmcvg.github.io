---
title: "Forums"
layout: single
permalink: "/forums/"
author_profile: true
---

Hello
{% raw %}
<iframe id="forum_embed"
  src="javascript:void(0)"
  scrolling="no"
  frameborder="0"
  width="100%"
  height="100%">
  Your browser doesn't support iFrames.
</iframe>
<script type="text/javascript">
  document.getElementById('forum_embed').src =
     'https://groups.google.com/forum/embed/?place=forum/cvgroup2013'
     + '&showsearch=true&showpopout=true&showtabs=false'
     + '&parenturl=' + encodeURIComponent(window.location.href);
</script>
{% endraw %}
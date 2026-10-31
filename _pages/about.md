---
layout: about
title: about
permalink: /
subtitle: <a href='https://www.inria.fr/'>Inria</a>

profile:
  align: right
  image: prof_pic_round.png # circular cut-out with transparent corners
  image_circular: true # crops the image to make it circular


selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # true  includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<style>
  /* One-page site: drop the "about" menu link and show the theme toggle on every screen size. */
  #navbar .nav-item, #navbar .navbar-toggler { display: none; }
  #navbar .navbar-nav { flex-direction: row; justify-content: flex-end; width: 100%; }

  /* Publication miniature on the left, details on the right. */
  @media (min-width: 576px) {
    .publications .abbr { flex: 0 0 33.33%; max-width: 33.33%; }
    .publications .abbr + div { flex: 0 0 66.67%; max-width: 66.67%; }
  }
</style>

<script>
  document.getElementById("navbarNav").classList.add("show");
</script>

I am an AI Research Engineer at Inria, within the [Multispeech](https://team.inria.fr/multispeech/home/) team. 
I am currently working on Audio-visual Fusion for Unsupervised Speech Enhancement. 
I did a master's in AI, Data Science and Machine Learning at Halmstad University (Sweden) and a master's in Electronics and Telecommunications at ENSIL (Limoges, France).

<h2 style="clear: both">publications</h2>

<div class="publications">

{% bibliography --group_by none %}

</div>

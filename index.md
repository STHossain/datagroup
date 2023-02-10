---
layout: default
title: Welcome
nav_order: 1
description: "Seminar page for our data science group"
permalink: /
has_toc: true
---



# Welcome to the online data science seminar page
{: .fs-9 }

{: .text-right }
<button class="btn js-toggle-dark-mode">Dark color mode</button>

<script>
const toggleDarkMode = document.querySelector('.js-toggle-dark-mode');

jtd.addEvent(toggleDarkMode, 'click', function(){
  if (jtd.getTheme() === 'dark') {
    jtd.setTheme('light');
    toggleDarkMode.textContent = 'Preview dark color scheme';
  } else {
    jtd.setTheme('dark');
    toggleDarkMode.textContent = 'Return to the light side';
  }
});
</script>


<img src="/docs/images/nets.jpg"  width="600" height="300" >



*Photo by [JJ Ying](https://unsplash.com/@jjying) on [Unsplash](https://unsplash.com/photos/8bghKxNU1j0)*



Thanks for dropping by, this is the webpage for our data science group. We are a group of entusiastic students / academics, coming from different backgrounds, mostly located in Bangladesh learning Statistics, Econometrics, Machine Learning, Programming, Data Science, R, Python, and ...... Once a week we sit online and talk about different things. You can join us if you are interested. This group does not have any official association with any university, and our seminars are completely free of cost. To see the discussion topics in detail you can check [Session Topics]({% link docs/Session_Topics.md %}) page. To join the group please check the page [Joining the seminar]({% link docs/Joining.md %}). 




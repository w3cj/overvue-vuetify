---
title: OverVue of Vuetify.js
revealOptions:
    transition: 'zoom'
---

<!-- .slide: data-background-video="https://cdn.flixel.com/flixel/v26zyfd6yf0r33s46vpe.tablet.mp4" data-background-video-loop="loop" data-background-video-muted -->

# O<img src="https://i.imgur.com/4sgyzVl.png" class="vue-logo" />er<img src="https://i.imgur.com/4sgyzVl.png" class="vue-logo" />ue
### of
# <img src="https://vuetifyjs.com/static/v-alt.svg" class="vue-logo fragment grow"/>uetify.js

with CJ

---

<!-- .slide: data-background-video="https://cdn.flixel.com/flixel/52vy4yxt8yw76d2u8dsm.tablet.mp4" data-background-video-loop="loop" data-background-video-muted -->

<div class="dark-bg fragment">
  Hello friends! <span class="emoji">👋</span>
  My name is <span class="red">CJ <span class="emoji">👽</span></span>.
</div>

<div class="dark-bg fragment">
  I am a <strong>Full Stack Developer <span class="emoji">🥞</span></strong>,
  <strong>Educator <span class="emoji">🏫</span></strong>, and
  <strong>Maker <span class="emoji">🛠</span>
  </strong> based in the <strong>Denver <span class="emoji">🏔</span></strong> area.
</div>

---

<!-- .slide: data-background-video="https://cdn.flixel.com/flixel/c8t92d7m4t5w4af4gmnc.hd.mp4" data-background-video-loop="loop" data-background-video-muted -->

<div class="dark-bg">
  I have worn many <span class="emoji">🎩</span>s in my career including <strong>Instructor <span class="emoji">👨‍🏫</span></strong>, <strong>Software Engineer <span class="emoji">🚂</span></strong>, <strong>QA Analyst <span class="emoji">🚨</span></strong>, <strong>System Administrator <span class="emoji">🔥</span></strong>, and <strong>Help Desk Consultant <span class="emoji">⛑</span></strong>.
</div>

---

<!-- .slide: data-background="http://galvanize-wp.s3.amazonaws.com/wp-content/uploads/2016/09/14143218/Platte-Oct-2015-4593-min.jpg"  -->

<div class="dark-bg">
  <h3>Lead Instructor, Principal Full Stack Developer</h3>
  <h2>at</h2>
  <img src="https://s3-us-west-2.amazonaws.com/galvanize.com-dev/galvanize-logo.svg" style="height:100px;width:auto;">
</div>

----

<!-- .slide: data-background="https://i.imgur.com/GhOQdqO.jpg"  -->

<div class="dark-bg fragment">
  <h2 class="fragment">Education Company</h2>
  <h2 class="fragment">Shared Work Space</h2>
  <h2 class="fragment">Meeting Space</h2>
</div>

---

<!-- .slide: data-background-video="https://cdn.flixel.com/flixel/ilek20y92dy1h38jx4j5.hd.mp4" data-background-video-loop="loop" data-background-video-muted -->

### I'm currently seeking my next adventure...

---

<!-- .slide: data-background-video="https://flixels.s3.amazonaws.com/flixel/8gg0il08d91lvga9gsme.tablet.mp4" data-background-video-loop="loop" data-background-video-muted -->

<a target="\_blank" href="https://makervan.life">
  <img src="http://i.imgur.com/OYZKTgl.png">
</a>

<div class="dark-bg">
  <h3>@makervanlife on instagram</h3>
</div>

---

### Coding Garden with CJ

YouTube.com/c/CodingGardenWithCJ

Live stream every Monday at 8:20PM 🗻 Mountain Time

<img src="https://i.ytimg.com/vi/pAHxtiQVL60/maxresdefault.jpg" style="max-width:35%">
<img src="https://i.ytimg.com/vi/6Dg6uDL1bes/maxresdefault.jpg" style="max-width:35%">
<img src="https://i.ytimg.com/vi/kChBiDhdSVA/maxresdefault.jpg" style="max-width:35%">
<img src="https://i.imgur.com/cwvKyKN.png" style="max-width:35%">

---

<!-- .slide: data-background="https://i.imgur.com/WPiNCVH.png"  -->

<div class="dark-bg">
  I am a co-organizer of the Den<img src="https://i.imgur.com/4sgyzVl.png" class="vue-logo-small" />er <img src="https://i.imgur.com/4sgyzVl.png" class="vue-logo-small" />ue Meetup
</div>

<div class="dark-bg fragment mt">
  If you're in the Den<img src="https://i.imgur.com/4sgyzVl.png" class="vue-logo-small" />er Area and working with <img src="https://i.imgur.com/4sgyzVl.png" class="vue-logo-small" />, I want to see you at the next meetup April 23rd!
</div>

<div class="dark-bg fragment mt">
  We are currently looking for food sponsors.
  We're always looking for full talk and lightning talk speakers.
</div>

---

<!-- .slide: data-background-video="https://cdn.flixel.com/flixel/bbqzgcm54sbewywlcl1d.hd.mp4" data-background-video-loop="loop" data-background-video-muted -->

<div class="dark-bg">
  <h2>Agenda</h2>
  <ul>
    <li>What is Vuetify.js?</li>
    <li>Why Vuetify.js?</li>
    <li>Install/Setup</li>
    <li>Theming</li>
    <li>Layout</li>
    <li>Grid</li>
    <li>UI Components</li>
  </ul>
</div>

---

<!-- .slide: data-background-video="https://cdn.flixel.com/flixel/de6w5hh1ijhzux3c3pah.tablet.mp4" data-background-video-loop="loop" data-background-video-muted -->

<div class="dark-bg">
  <h2>What is <img src="https://vuetifyjs.com/static/v-alt.svg" class="vue-logo"/>uetify.js?</h2>
</div>

---

#### [Material Design Guidelines](https://material.io/guidelines/) by Google

<video src="./videos/material-design-guidelines.mp4" autoplay loop></video>

---

#### Material Design Vue.js Component Library

```html
<v-app>
  <v-navigation-drawer app></v-navigation-drawer>
  <v-toolbar app></v-toolbar>
  <v-content>
    <v-container fluid>
      <router-view></router-view>
    </v-container>
  </v-content>
  <v-footer app></v-footer>
</v-app>
```

---

### Authored by John Leider

<img src="https://pbs.twimg.com/profile_images/978369970773086208/IL1Ytuzu_400x400.jpg" style="height:250px;width:auto;" />

https://github.com/johnleider/

https://twitter.com/zeroskillz

https://www.patreon.com/vuetify

---

<img src="https://i.imgur.com/yRDbQF8.png" style="height:600px;width:auto;" />

---

![](https://i.imgur.com/IiSlxhV.png)

[Github Star History](https://www.timqian.com/star-history/#vuetifyjs/vuetify)

---

# February 13th Vuetify v1.0 released

---

## Why <img src="https://vuetifyjs.com/static/v-alt.svg" class="vue-logo"/>uetify.js?

---

<img src="https://i.imgur.com/DMIX3mK.png" style="height:75px !important;width:auto !important;" />
<img src="https://i.imgur.com/PTHkkHr.png" style="height:75px !important;width:auto !important;" />
<img src="https://i.imgur.com/WxfuMLC.png" style="height:75px !important;width:auto !important;" />
<img src="https://i.imgur.com/8RsUpJu.png" style="height:75px !important;width:auto !important;" />
<img src="https://i.imgur.com/EJXZYqJ.png" style="height:75px !important;width:auto !important;" />
<img src="https://i.imgur.com/Ori4sXD.png" style="height:75px !important;width:auto !important;" />

---

#### Why <img src="https://vuetifyjs.com/static/v-alt.svg" class="vue-logo-small"/>uetify.js?

* Most every component you will ever need (more coming...)
* Semantic Naming
* Fantastic Documentation
* Extremely Easy to Get Started

---

# <a href="https://vuetifyjs.com/en/" target="blank_">TO THE DOCS</a>

---

# [Roadmap](https://vuetifyjs.com/en/getting-started/roadmap)

---

### Vue CLI Plugin

* vue-cli 3.0 plugin is being developed

```sh
vue create myApp
vue add vuetify
```

<video src="./videos/vue-cli-vuetify.mp4" autoplay loop></video>

---

### Community

* [Support Vuetify on Patreon](https://www.patreon.com/vuetify)
* [@vuetifyjs on twitter](https://twitter.com/vuetifyjs)
* [Discord: https://chat.vuetifyjs.com/](https://chat.vuetifyjs.com/)

---

<!-- .slide: data-background-video="https://media.giphy.com/media/3ohs7JG6cq7EWesFcQ/giphy.mp4" data-background-video-loop="loop" data-background-video-muted -->

<div class="dark-bg">
  <h2>Thank <img src="https://i.imgur.com/4sgyzVl.png" class="vue-logo" />ue!</h2>
  <p>cj@null.computer</p>
  <p>https://git.io/w3cj</p>
  <p>https://w3cj.now.sh</p>
</div>

---

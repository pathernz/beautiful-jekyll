---
layout: page
title: Getting Started
---

Getting started is *literally* as easy as 1-2-3 :smile:

Scroll down to see the steps involved, but here is a 40-second video just as a reference as you work through the steps. If you don't already have a [GitHub account](https://github.com/join), you'll need to sign up.

![Installation steps](assets/img/install-steps.gif)

<div class="gs-section-01" markdown="1">

### 1. Fork the Beautiful Jekyll repository 

Fork the [repository](https://github.com/daattali/beautiful-jekyll) 
by clicking the Fork button on the top right corner in GitHub.

</div>

<div class="gs-section-02" markdown="1">

  ### 2. Build your website in 3 steps
After you fork the repo, go to **Settings → Pages** in your new repository.  
Select the branch and folder (usually `master` with `/ (root)` for this template), then click **Save**.  
Your site will be built automatically. The URL will be:

</div>
<div class="gs-section-03" markdown="1">

### 3. Activate GitHub Pages
Once the build is finished, you’ll see a success notice with a link to your site.  
If it stalls, make a tiny edit (like updating `_config.yml`) or toggle the Pages folder to re-trigger the build.

</div>

<style>
/* Shared look: soft card, subtle shadow, rounded corners */
.gs-section-01,
.gs-section-02,
.gs-section-03 {
  background: #FFFFFF;
  border-radius: 14px;
  padding: 18px 20px;
  margin: 18px 0;
  box-shadow: 0 2px 10px rgba(0,0,0,0.06);
  border-left: 6px solid transparent;
}

/* Section-specific “ocean” accents */
.gs-section-01 { border-left-color: #4DD0E1; background: #F0FBFD; }  /* light aqua wash */
.gs-section-02 { border-left-color: #0288D1; background: #F4FAFF; }  /* pale ocean blue */
.gs-section-03 { border-left-color: #00796B; background: #F1FBF8; }  /* seafoam */

/* Typography within each section */
.gs-section-01 h3,
.gs-section-02 h3,
.gs-section-03 h3 {
  margin-top: 0;
  font-weight: 700;
  letter-spacing: 0.2px;
}

/* Ocean header hues */
.gs-section-01 h3 { color: #006064; } /* deep teal */
.gs-section-02 h3 { color: #0288D1; } /* ocean blue */
.gs-section-03 h3 { color: #00796B; } /* sea green */

/* Body text + links */
.gs-section-01 p,
.gs-section-02 p,
.gs-section-03 p,
.gs-section-01 li,
.gs-section-02 li,
.gs-section-03 li { line-height: 1.6; }

.gs-section-01 a,
.gs-section-02 a,
.gs-section-03 a { text-decoration: none; border-bottom: 1px dotted rgba(2,136,209,0.35); }

.gs-section-01 a:hover,
.gs-section-02 a:hover,
.gs-section-03 a:hover { border-bottom-color: rgba(2,136,209,0.7); }
</style>

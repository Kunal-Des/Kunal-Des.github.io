---
permalink: /
layout: splash
title: "Kunal Deshmukh"
excerpt: "Observational astronomer studying binary stars across the HRD"
header:
  overlay_image: splash-img.png
  overlay_filter: 0.3
  cta_url: "/home/"
  cta_label: "<i class=\"fa fa-plus\" aria-hidden=\"true\"></i>"
---


---
permalink: /
layout: splash
title: "Kunal Deshmukh"
excerpt: "Astronomy PhD Candidate, KU Leuven"
header:
  overlay_image: Tarantula-HST-ESO-Webb-LL.png
  overlay_filter: 0.5
  cta_url: "/home/"
  cta_label: "<i class=\"fa fa-plus\" aria-hidden=\"true\"></i>"
---

<style>
.page__hero--overlay {
  position: relative;
  min-height: 100vh;
  display: flex;
  align-items: center;
  transition: opacity 0.6s ease-in-out;
}
.page__hero--overlay.fade-out {
  opacity: 0;
}
.page__hero--overlay .wrapper {
  width: 100%;
  font-family: "Arial", sans-serif;
}
.page__hero--overlay .page__title {
  font-family: inherit;
  font-size: 3em;
}
.page__hero--overlay .page__lead {
  font-family: inherit;
  font-size: 1.3em;
}
.page__cta {
  position: absolute;
  bottom: 1.6in;
  left: 50%;
  transform: translateX(-50%);
  margin: 0;
}
.page__cta .btn {
  background: transparent;
  border: none;
  border-radius: 50%;
  width: 60px;
  height: 60px;
  font-size: 1.8em;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 0;
}
.page__cta .btn:hover {
  background: rgba(255, 255, 255, 0.15);
}
</style>

<script>
document.addEventListener('DOMContentLoaded', function () {
  var ctaLink = document.querySelector('.page__cta a');
  var hero = document.querySelector('.page__hero--overlay');
  if (ctaLink && hero) {
    ctaLink.addEventListener('click', function (e) {
      e.preventDefault();
      var target = this.getAttribute('href');
      hero.classList.add('fade-out');
      setTimeout(function () {
        window.location.href = target;
      }, 600);
    });
  }
});
</script>
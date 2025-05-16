---
date: '2023-06-25T09:53:42+02:00' # date in which the content is created - defaults to "today"
title: 'iTea - Intelligenter Tee-Assistent'
draft: false # set to "true" if you want to hide the content 
#link: "https://siegristlk.github.io/meine-website/de" # optional URL to link the logo to

params:
    button:
        icon: "icon-arrow-right"
        btnText: "Projektprotokoll öffnen"
        URL: "https://siegristlk.github.io/meine-website/reports/Report-Group8-ITea.pdf"
    image:
        src: "images/works/itea-poster.png"
        scale: 0.2

## The content is used for the description of the project
---

{{< rawhtml >}}
<div style="position: relative;">
  <iframe 
    id="storyframe"
    src="meine-website/reports/Report-Group8-ITea.pdf" 
    width="100%" 
    height="600px" 
    style="border: none;" 
    allowfullscreen 
    webkitallowfullscreen 
    mozallowfullscreen>
  </iframe>

  <button onclick="openFullscreen()" style="position: absolute; top: 10px; right: 10px; z-index: 10;">
    ⛶ Vollbild
  </button>
</div>

<script>
function openFullscreen() {
  const iframe = document.getElementById("storyframe");
  if (iframe.requestFullscreen) {
    iframe.requestFullscreen();
  } else if (iframe.webkitRequestFullscreen) {
    iframe.webkitRequestFullscreen();
  } else if (iframe.mozRequestFullScreen) {
    iframe.mozRequestFullScreen();
  } else if (iframe.msRequestFullscreen) {
    iframe.msRequestFullscreen();
  }
}
</script>
{{< /rawhtml >}}

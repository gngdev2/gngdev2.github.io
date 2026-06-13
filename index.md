---
title: gng
---

<!-- 1. Import sleek modern fonts from Google Fonts -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@200;300;400&family=JetBrains+Mono&display=swap" rel="stylesheet">

<style>
  body {
    font-family: 'Plus Jakarta Sans', sans-serif !important;
    font-weight: 300 !important; 
    background-color: #0d1117 !important; 
    color: #c9d1d9 !important;            
    letter-spacing: 0.01em; 
  }

    /* Hide the automatic hover link icons next to headings */
  .anchor {
    display: none !important;
  }
  
  h1:hover .anchor, 
  h2:hover .anchor, 
  h3:hover .anchor {
    display: none !important;
  }
  
  /* Removed the borders and lines here */
  h1, h2, h3, h4, h5, h6 {
    font-family: 'Plus Jakarta Sans', sans-serif !important;
    font-weight: 200 !important; 
    color: #f0f6fc !important;            
    letter-spacing: -0.02em; 
    border: none !important;             /* Completely removes the default line */
    border-bottom: 0 !important;         /* Double-ensures the bottom line is killed */
    padding-bottom: 0 !important;
    margin-bottom: 1rem !important;
  }
  
  a {
    color: #58a6ff !important;            
    text-decoration: none;
  }
  
  code, pre {
    font-family: 'JetBrains Mono', monospace !important;
    background-color: #161b22 !important;
    color: #ff7b72 !important;
    font-size: 0.9em !important;
  }
  
  /* Cleaned up the footer line as well */
  footer, .site-footer {
    color: #8b949e !important;
    border-top: none !important;         /* Removes the line above the footer */
    padding-top: 2rem !important;
  }
  
  /* Responsive Video Container */
  .video-container {
    text-align: center;
    width: 100%;
    max-width: 800px;        /* Dictates how large the video gets on big desktop screens */
    margin: 2rem auto;       /* Centers the container and gives it top/bottom breathing room */
  }

  .video-container iframe {
    width: 100% !important;  /* Forces the iframe to fill the container width */
    height: auto !important;
    aspect-ratio: 16 / 9;    /* Maintains perfect cinematic proportions on all screens */
    border-radius: 12px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.5);
  }
</style>

<h1 style="text-align: center;">gng: hello - hi</h1>

<h2 style="text-align: center;">Poly Otter</h2>

<div class="video-container">
  <iframe 
    src="https://www.youtube.com/embed/gSVaykTc9rY" 
    title="YouTube video player" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
    allowfullscreen>
  </iframe>
</div>

<div style="text-align: center;">
An isometric sea otter adventure
</div>

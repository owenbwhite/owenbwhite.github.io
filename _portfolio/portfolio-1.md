---
title: "NYC Coronavirus Map"
excerpt: "Real-time updates of NYC Health Data on the outbreak<br/><img src='/images/500x300.png'>"
collection: portfolio
---

I wish you and your family safety in these testing times. I wanted to better understand the situation in New York so I created this visualization. Broken down by area code you may see tests, confirmed cases, and other covid-19 metrics provided by <a href="https://github.com/nychealth/coronavirus-data">NYC Health Data</a>

<style type="text/css">
    html, body, #nyc-map {
      height: 100%;
    }
    body, #nyc-map {
      overflow: hidden;
      margin: 0;
    }
    #iframe-nyc {
      width: 100%;
      height: 100%;
      border: none;
    }
  </style>
  <div id="nyc-map">
    <div id="iframe-nyc" sandbox="allow-scripts" src="_portfolio/nycovid.html"></div>
  </div>
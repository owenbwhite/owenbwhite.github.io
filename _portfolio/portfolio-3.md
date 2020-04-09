---
title: "Billboard Hot 100 lyrical analysis over the decade"
excerpt: "Exploratory analysis of pop music chart's lyrical content.<br/><img src='/images/billboard.jpg'>"
collection: portfolio
---

An attempt to capture the lyrical motifs of pop music over time. We fetch our data from billboard, returning each chart, at one chart per week, a list of songs and their respective popularity ranking. Acquiring a set of total songs, we fetch lyrics using the <a href="">Genius API</a>. After acquiring the lyrics for the songs, we must process them and attempt to capture sentiment in each line.

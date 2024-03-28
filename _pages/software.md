---
permalink: /software/
title: "Software"
---

# Scientific Software

## QoMMMa

[QoMMMa](https://github.com/NeilMcFarlane-gh/QoMMMa) is an additive QM/MM package maintained within the Harvey group at KU Leuven. It uses Tinker for any MM-side calculations, and QM-side calculations can be performed with a variety of quantum chemistry codes including: Gaussian, ORCA, xTB, Jaguar, and Molpro. The source code is written in Fortran90, and Python3 is used as a scripting language to wrap the source code and generate job files for the QM and MM packages.

## LennardJones-GSM
[LennardJones-GSM](https://github.com/NeilMcFarlane-gh/LennardJones-GSM) is a work-in-progress computational chemistry code that generates reaction pathways for rearrangements of Lennard-Jones clusters of particles using the growing string method. It is written entirely in Python3.

# Other Software

## Loot-Island-Scoring
[Loot-Island-Scoring](https://github.com/NeilMcFarlane-gh/Loot-Island-Scoring) is a work-in-progress Python3 prototype app for scoring a board game. The board game is not so well-known and is called [*Loot Island*](https://boardgamegeek.com/boardgame/235512/loot-island). Unfortunately, the scoring system takes a long time to do by-hand, so this app aims to solve this. The long-term goals are to port the code to JavaScript once the prototype has been finalised and publish to the Android app store.

## Untappd-Scraper
[Untappd-Scraper](https://github.com/NeilMcFarlane-gh/Untappd-Scraper) is a very early-stage work-in-progress Python3 code for scraping the data on a user profile of the popular beer rating app [*Untappd*](https://untappd.com/). The code uses BeautifulSoup to scrape a given user's profile, and the long-term goals are that all the user data can be scraped from a profile, and a number of plots can be generated which show the user's preferences in beer.

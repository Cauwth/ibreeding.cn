---
title: IP4GS
summary: IP4GS, an interactive platform for genomic selection, offers a user-friendly interface for performing streamlined GS analysis involving the above-mentioned steps simply through point-and-click actions. 
tags:
- Tools
date: "2023-02-09"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point:

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url:
- icon: link
  icon_pack: fas
  name: more
  url: https://github.com/furan2019/IP4GSdata.git
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

authors: [""]

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

A shiny-based
application usually consists of two parts, a user-interface (UI) script
(IP4GS_UI.r for IP4GS) and a server script (IP4GS_server.r for
IP4GS). The UI script controls the layout of different panels andvisualization of results and bridges the user inputs and background functions. IP4GS utilized several packages to enrich and improvethe UI interactive experience, such as “DT” for dynamic tables,“plotly” for dynamic plots, “shinycssloaders” for loading animations, “shinybusy” for progress notification, and“shinyWidgets” for input of multiform parameters and dynamic
controls. HTML5 language and condition panels were also introduced to improve and optimize the layout of panels. The
server script plays an important role in shiny-based applications. All functions provided by IP4GS were achieved by server script,including data input, data preprocessing, and GS model building and evaluation. For real-time interaction, user-defined parameters and operations are passed to the server script, which then executes the corresponding functions and formats the outputs. Lastly, the server script returns the results to a specific location according to flags that can bridge the UI script and server script.

Please read the [tutorial](https://github.com/furan2019/IP4GSdata.git) for details!

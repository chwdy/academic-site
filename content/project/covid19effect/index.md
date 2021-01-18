---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Covid19 Effect Analysis"
summary: "Estimate the econimic effect on GDP On specific countries (Python)"
authors: [DiweiZhu]
tags: [Machine Learning,Data Engineering]
categories: []
date: 2021-01-15T15:45:00-05:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Covid19 Effect Analysis"
  focal_point: "smart"
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: "/project/covid19effect/Presentation.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Background: Given the Covid 19 positive cases number around the world ,we try to combine the economic, population, edcation data to predict the effect on GDP among selected country.  


Task performed:
- Grouping countries in to 3 groups based on there GDP per capita
- Trained linear regression model with historical GDP data 
- Trained linear regression model to find the relationship between economic effects and attributes of a country
- Predict and analyse the effect of 8 countries among 3 different income groups
- Visualized the groups and results   

